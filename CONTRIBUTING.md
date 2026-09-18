# Contributing

Submit a public project that uses TypeSafe Jev for a concrete purpose, or a compatible reimplementation of the Jev API or decision schema. Source code must let a reviewer inspect the integration or reproduction. Describe what it does without unsupported speed, accuracy, quality, or safety claims.

## Add a project

Create `entries/owner--repository.json` with these fields:

```json
{
  "name": "Project name",
  "repository": "owner/repository",
  "description": "One factual sentence describing the project and its use of Jev.",
  "category": "search"
}
```

- Use exactly the repository's `owner/name`, without a URL, and lowercase the filename.
- Choose a category from `.github/jev-review.json`; `other` is reserved for uncertain model results.
- Source paths are optional: the Action tries to find the Jev integration automatically. If you know the relevant files, add `"evidence": ["src/client.ts"]` with up to six relative paths. You can omit this field or use `[]`.
- Every material claim in `description` should have an `evidence` path pointing at the file that proves it. Existence claims (for example a bundled GitHub Action) should name that file.
- If the review cannot find enough evidence, it will ask you to add source paths and flag the submission for maintainer review.
- Change 1–10 entry files in the PR, one file per project. Do not mix entry submissions with other changes. README is regenerated after merge.
- Run `npm run check` and `npm test` locally if possible.
- Disclose in the PR description whether you maintain or are affiliated with each project. For maintainer-discovered batches, link the discovery sources and state that this is not an author submission.

The reviewer is advisory. A model recommendation does not automatically merge or reject a PR. Missing files, unclear evidence, and incorrect categories can be fixed with another commit, which triggers another review. Review criteria and their thresholds are public and provisional.

For batches, each project receives an independent Jev review. The comment summarizes the batch and includes expandable per-project results. Only an all-recommended batch is recommended; one error fails the Action but preserves completed sibling reports. GitHub merges the entire PR: resolve, remove, or split unresolved entries before merging. Every new commit re-reviews the batch, so prefer batches of 5–10 projects.

## Review details

At a fixed public repository commit, Jev first selects up to six source files using the README, dependency manifests, and candidate filenames/sizes. This selection does not see source contents or optional evidence hints. The Action then reads the selected files plus any supplied evidence paths, and a separate Jev call judges concrete integration, description support, and usable setup instructions. A Choice question suggests the category. If discovery is insufficient, the review asks for paths instead of treating missing evidence as a rejection.

Files are sent whole, never truncated. The review accepts up to ten files and 48,000 file-content characters; a file that cannot fit is omitted with a visible warning requiring maintainer review. Individual file reads and the selection request also have resource limits. These are not exact model token counts, and exceeding provider limits fails visibly. No second retrieval round is implemented.

The comment reports the outcome, probabilities, evidence links, reviewed PR commit, model version, and policy hash. Missing evidence, an uncertain category, or a proposed-category mismatch requires maintainer review. The Action never merges a PR or edits the submission. PR runs retain a JSON report as a GitHub Actions artifact for 14 days; this is not a permanent review archive.

Single-project reports keep schema version 1. Batch reports use schema version 2 with a `reports` array containing each project's full result and entry path. Save reports before artifact expiry when a permanent review record is needed.

README, manifests, candidate paths, and selected source contents are sent to TypeSafe. Reports retain selection probabilities, selected/included paths, model, usage, and input hashes under `discovery`; top-level `usage` counts only the final review. Provider failures are reported as failures, not favorable reviews. The privileged workflow executes only trusted base-branch code and reads submitted files as data.


See [validation records](docs/reviews/README.md) for saved live reports.

## Maintenance

Policy, workflow, generated-output, and entry-removal changes belong in separate maintainer PRs. Entry removals require human review. Initial seed entries were maintained by hand; do not claim they passed live Jev review without a linked report.

## Local development

Use Node.js 22 or newer. Run `npm run check`, `npm test`, and `npm run build`; these checks do not need an API key.

The README is generated from `entries/`, `docs/introduction.md`, and `docs/footer.md`. Edit these sources and run `npm run build`. Links in the introduction and footer are relative to the generated root README. After a merge, GitHub Actions regenerates the README automatically.

## Enable Jev review

The repository owner must configure a dedicated `TYPESAFE_API_KEY` GitHub Actions secret. No key is included or shared with other projects. Until configured, the model review cannot complete; catalog validation remains usable.

```bash
gh secret set TYPESAFE_API_KEY --repo fatwang2/awesome-jev
```

The CLI prompts for the secret. Do not paste keys into PRs, Issues, or committed files. Re-run the review workflow after configuring the key, or update a submission PR.

To calibrate, collect a small human-labeled set containing genuine integrations, keyword false positives, weak evidence, incorrect descriptions, and ambiguous categories. Keep some cases out of threshold tuning and report false acceptance/rejection and category agreement on that held-out set. The action's local CLI can produce reports without publishing comments.
