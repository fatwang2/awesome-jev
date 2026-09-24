# Awesome Jev

Open-source projects built with [TypeSafe Jev](https://typesafe.ai), with submissions reviewed by Jev.

[Submit a project](CONTRIBUTING.md) · [How reviews work](#how-reviews-work) · [Jev Review Action](https://github.com/fatwang2/jev-review-action)

## Projects

163 projects.

### SDKs

- [advocaat](https://github.com/pithings/advocaat) — A small, type-safe client for asking AI questions about your data, powered by TypeSafe Jev\.
- [jev](https://github.com/dannote/jev) — TypeSafe Jev for OTP: reply to Jev from a GenServer and pattern match on its answer
- [jev-go](https://github.com/Gaurav-Gosain/jev-go) — Go client for TypeSafe's System One API and its model Jev: typed judgments and calibrated probabilities instead of generated text
- [jev-go](https://github.com/Stumble/jev-go) — An independent Go SDK for TypeSafe AI's Jev / System One API\.
- [jev-harness](https://github.com/AntonioCoppe/jev-harness) — A small TypeScript library that turns TypeSafe Jev answers into actions you can ship\.
- [jev-tree](https://github.com/reachjalil/jev-tree) — Recursive Jev choice over a taxonomy\. Select from more than 255 options without breaking TypeSafe Jev's choice cap\.
- [jevclient](https://github.com/AboveColin/jevclient) — Async Python client for TypeSafe Jev\. Typed questions in, probabilities and choices out, no prose to parse\.
- [req\_llm](https://github.com/agentjido/req_llm) — A Req- and Finch-backed Elixir package that standardizes LLM API calls across providers, including a TypeSafe Jev provider with typed evaluation support\.
- [swift-typesafe](https://github.com/ainame/swift-typesafe) — Swift 6\.4 SDK for TypeSafe AI, following the Python SDK's 0\.6\.0 API\.
- [TypeLLM](https://github.com/TypeLLM/TypeLLM) — TypeLLM brings the same typed-decision interface as TypeSafe Jev to the open-source autoregressive models you already run—without a proprietary model API, model retraining, structured-output library, or manual KV-tensor management\.
- [TypeSafe JavaScript SDK](https://github.com/typesafe-ai/typesafe-sdk-js) — Official JavaScript and TypeScript client for TypeSafe's typed decision API, with question builders and typed responses\.
- [TypeSafe Python SDK](https://github.com/typesafe-ai/typesafe-sdk-python) — Official Python client for TypeSafe's typed decision API, with synchronous and asynchronous clients\.
- [typesafe\_sdk](https://github.com/nshkrdotcom/typesafe_sdk) — typesafe\_sdk is the Elixir SDK for TypeSafe AI and its first System One model, Jev\.
- [typesafe\_sdk\_ex](https://github.com/vinnie357/typesafe_sdk_ex) — Typesafe AI SDK in Elixir using Req
- [typesafe-ai](https://github.com/Twister915/typesafe-ai) — typesafe-ai brings TypeSafe's System One evaluation API into Rust as small, typed judgments that fit inside ordinary application code\.
- [typesafe-ai-rs](https://github.com/gilljon/typesafe-ai-rs) — An independent Rust client for the TypeSafe AI System One API, maintained at gilljon/typesafe-ai-rs\.
- [typesafe-rs](https://github.com/AbdelStark/typesafe-rs) — Evaluate a state against named questions \(noul, choice, score\) and get one typed answer per question\.
- [typesafe-sdk](https://github.com/joshmn/typesafe-sdk) — A Ruby client for the TypeSafe System One API\.
- [typesafe-sdk-go](https://github.com/Tangerg/typesafe-sdk-go) — Go SDK for the TypeSafe AI API — typed questions in, probability distributions out\.
- [typesafe-sdk-php](https://github.com/Butochnikov/typesafe-sdk-php) — PHP client for the TypeSafe AI System One API\.
- [typesafeai-dotnet-sdk](https://github.com/saibimajdi/typesafeai-dotnet-sdk) — Community \.NET SDK for the TypeSafe AI System One API — typed noul, choice, and score questions with structured, confidence-scored answers\. Not affiliated with TypeSafe AI\.
- [zio-typesafe-ai](https://github.com/jamesward/zio-typesafe-ai) — A Scala 3 / ZIO library for TypeSafe AI's Jev / System One API — a "System One model" that answers typed, atomic questions about a piece of state instead of generating text\.

### Integration

- [ask-jev-skill](https://github.com/shantanugoel/ask-jev-skill) — Hermes skill: call TypeSafe Jev \(jev-latest\) as a typed tiebreaker\.
- [cursor-clijev-compaction](https://github.com/kleosr/cursor-clijev-compaction) — TypeSafe Jev-scored context recovery for Cursor CLI \(agent\)\. Capture tool I/O, score keep/drop, re-inject after native compact\.
- [dsh-jev-tools](https://github.com/HorusJiang/dsh-jev-tools) — DeepSeek Harness plugin that runs three automatic Jev judgments on the live session — pruning oversized tool output to the segments relevant to the request, screening fetched pages for instructions aimed at the model, and picking which skill fits the next step — and adds jev\_ask and a jev\_gate completion check that escalates every unclear answer\.
- [fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction) — Claude Code plugin that replaces the compaction summary with Jev decisions: every tool call and result is scored in one fast request, stale ones are dropped or truncated, everything kept stays verbatim\.
- [GPTCache](https://github.com/zilliztech/GPTCache) — Semantic cache with a Jev evaluator that uses Noul judgments to check whether a cached response can serve an incoming request\.
- [ha-conversation-jev](https://github.com/luxus/ha-conversation-jev) — Home Assistant custom conversation agent: Jev \(TypeSafe System One, jev-latest\) classifies an utterance, then either calls a light service \(v0 fast path\) or hands off to the SpaceXAI Grok conversation agent\.
- [hermes-jev](https://github.com/keeltrace/hermes-jev) — It is built for narrow, typed judgments that should not require the main generative model to improvise an answer: routing, ranking, verification, multi-question assessment, tool gating, and context-value decisions\.
- [hono-jev-router](https://github.com/yusukebe/hono-jev-router) — Hono router that uses TypeSafe Jev to match HTTP requests against natural-language route descriptions\.
- [jcm-router](https://github.com/adarshmishra07/jcm-router) — A local proxy that sits between Claude Code and the Anthropic API and picks the model and effort level per message, using TypeSafe's Jev classifier\.
- [Jev for Home Assistant](https://github.com/AboveColin/HA-Jev) — Home Assistant integration that turns Jev answers into sensors, adds four automation actions returning a probability, a choice with its distribution or a score, and provides a conversation agent for Assist that maps a spoken command onto Home Assistant's built-in intents\.
- [Jev MCP](https://github.com/jkudish/jev-mcp) — MCP server that uses TypeSafe Jev for claim verification, content screening, and semantic candidate ranking\.
- [jev-agent-skill-router](https://github.com/GodsBoy/jev-agent-skill-router) — Typed, confidence-aware agent skill routing with TypeSafe Jev\.
- [jev-browser](https://github.com/Ying-Kai-Liao/jev-browser) — Browser automation where an LLM plans and Jev \(Typesafe System One\) decides\. Library, CLI and MCP server\.
- [jev-ego](https://github.com/romaluev/jev-ego) — TypeScript browser agent for ego lite — Jev Ultrafast's indexed action space, without Chrome, Playwright, or Browser Harness\.
- [jev-guard](https://github.com/ClemensSchartmueller/jev-guard) — jev-guard intercepts tool calls \(shell executions, file writes, patch applications, file reads, and directory inspections\) before execution, performs sub-millisecond local boundary and sensitive file checks, and utilizes TypeSafe AI's System One \(Jev\) model to evaluate blast radius, reversibility, and destructive potential\.
- [jev-mcp](https://github.com/blakestone-x/jev-mcp) — MCP server for TypeSafe Jev: typed classify, score, check, match and screen for any agent, with confidence on every answer
- [jev-resilience](https://github.com/Vicente-MD/jev-resilience) — Non-blocking Spring Boot Starter for Spring WebFlux that implements a Semantic Circuit Breaker to detect silent HTTP 200 failures using TypeSafe Jev\.
- [jev-router](https://github.com/gargpratyush/jev-router) — Automatic per-turn model routing for Claude Code and OpenAI Codex\.
- [jev-router](https://github.com/prismhq/jev-router) — Open-source LLM router that uses TypeSafe's Jev to pick a model, on top of LiteLLM
- [jev-shell-history](https://github.com/mrnugget/jev-shell-history) — Fish-style zsh history autosuggestions ranked by Jev \(TypeSafe\)
- [jev-starter](https://github.com/hamakyo/jev-starter) — Typed, policy-driven decision workflows on top of TypeSafe AI Jev: confidence routing, fallbacks, evaluation, and RAG patterns for TypeScript apps\.
- [jev-use](https://github.com/shitianfang/jev-use) — Claude Code, Codex, and pi plugin exposing jev\_judge and jev\_gate MCP tools with a routing skill and a PreToolUse command gate; a typed escalation contract returns writing and unsure steps to the LLM\.
- [Jevbridge](https://github.com/tacticocc/Jevbridge) — ACP and MCP adapter that bridges TypeSafe Jev with any LLM — computer use and typed decisions alongside Codex, Claude, Grok, and OpenCode\.
- [jevlogs](https://github.com/reachjalil/jevlogs) — Open-source Jev log triage for OpenTelemetry\. Score the signal before expensive LLM analysis\.
- [laravel-typesafe-jev](https://github.com/Butochnikov/laravel-typesafe-jev) — Unofficial Laravel integration for TypeSafe Jev AI with typed responses, async requests, scoped dependency injection, and testing fakes\.
- [llama-index-jev](https://github.com/WiktorB2004/llama-index-jev) — Drop-in LlamaIndex reranker and router powered by TypeSafe Jev: typed Score / Choice answers, cheap compared to LLM-as-judge — not a Cohere or FlagEmbedding cross-encoder\.
- [Milvus Model](https://github.com/milvus-io/milvus-model) — Python reranker adapter that sends candidate documents as Jev Noul questions in one request, then sorts the returned scores and preserves original document indices\.
- [omp-jev-compaction](https://github.com/jerryfane/omp-jev-compaction) — omp plugin that uses Jev to score tool-call and tool-result relevance, preserves kept conversation text verbatim, and parks elided output in readable files\.
- [pg\_typesafe](https://github.com/giuliosmall/pg_typesafe) — PostgreSQL extension that calls TypeSafe Jev from SQL for Choice, Noul, and Score, including batched detect and classify\.
- [pi-jev](https://github.com/y0usaf/pi-jev) — TypeSafe Jev as a decision layer for the Pi coding agent: a measured tool-call gate plus jev\_ask for typed, calibrated answers
- [pi-jev-router](https://github.com/mejiasd3v/pi-jev-router) — Let TypeSafe's Jev choose a model and reasoning effort for Pi, then keep both fixed for the session\.
- [pi-typesafe](https://github.com/DevMortimer/pi-typesafe) — TypeSafe decisions for Pi: batched evaluation tool, terminal playground, and typed API for extension authors
- [ruby\_llm-typesafe](https://github.com/kieranklaassen/ruby_llm-typesafe) — TypeSafe structured-output provider for RubyLLM 2
- [sqlite3-jev](https://github.com/mattn/sqlite3-jev) — SQLite extension that calls TypeSafe Jev — a decision-only model that returns typed answers \(yes/no probability, choice, score\) instead of text — straight from SQL\.
- [tripwire](https://github.com/noelzappy/tripwire) — Judge every LLM response before the user sees it\. AI SDK middleware and OpenAI-compatible proxy\.
- [Typesafe MCP](https://github.com/itsmostafa/typesafe-mcp) — MCP server that exposes TypeSafe Jev structured evaluations to coding agents and desktop clients\.
- [typesafe-ai-rails](https://github.com/GenieRobot/typesafe-ai-rails) — Community Rails integration for TypeSafe AI's System One API, built on the community typesafe-sdk Ruby gem\.
- [typesafe-jev-workflow](https://github.com/GiesN/typesafe-jev-workflow) — A small async LangGraph workflow that sends a mocked email to TypeSafe's Jev model, receives a typed Choice \(invoice or general\), and routes to a demo handler\.

### Developer tools

- [agentic-harness-cli](https://github.com/powerpuff-kitty/agentic-harness-cli) — The decisions command family implements the offline deterministic boundary for the provider-neutral Decision Kernel contract pinned from the canonical repository\.
- [bicameral](https://github.com/AbdelStark/bicameral) — Hybrid coding harness: System 2 writes, System 1 \(Jev\) runs reflexes\.
- [blink](https://github.com/ellipsis-dev/blink) — Search a codebase with Jev using an ensemble of walkers that walk the file system to find a file\.
- [commit-miner](https://github.com/devanshbatham/commit-miner) — Classify Git commit diffs and messages with Jev\. Bug fixes, security fixes/CWEs, and change types\.
- [diffjury](https://github.com/raihankhan-rk/diffjury) — One click fetches the PR dossier \(title, body, diff, contributors\) and runs a TypeSafe Jev systemOne judgment — risk bars, noul probabilities, and a verdict\.
- [every](https://github.com/sufianetaouil/every) — Ask a yes/no question of every function in a codebase\. Ranked answers in seconds, for cents\. Grep whose pattern is a question, powered by TypeSafe Jev\.
- [foreman](https://github.com/thruwire/foreman) — A Codex worker does the software engineering while Foreman independently assesses whether the implementation is complete, requirements are satisfied, tests are sufficient, verification is needed, or human input is required\.
- [Jev Codex Router](https://github.com/0xNatoshi/jev-codex-router) — Codex proxy that uses TypeSafe Jev judgments to route coding turns to different models\.
- [Jev Review](https://github.com/devagrawal09/jev-review) — Code-review workflow that uses TypeSafe Jev structured judgments to assess changes and codebases, with a local results dashboard\.
- [Jev Review Action](https://github.com/fatwang2/jev-review-action) — Configurable GitHub Action using Jev to review directory submissions and classify pull requests, with evidence links and template-generated comments\.
- [jev-axi](https://github.com/shiftynick/jev-axi) — Command-line interface that sends typed questions to TypeSafe Jev so coding agents can gate shell commands before they run, classifying routine commands locally before any request is made\.
- [jev-belay](https://github.com/valentynkit/jev-belay) — Claude Code Stop hook that checks the transcript for evidence before trusting a "done" claim, spending one four-question Jev call only when files changed with no passing check since, and failing open on every error path\.
- [jev-code](https://github.com/devagrawal09/jev-code) — jev-code is a command-line toolkit that coding agents can delegate judgment-heavy work to\.
- [jev-commit](https://github.com/valentynkit/jev-commit) — Pre-commit hook where one Jev call judges whether the commit message matches the staged diff, flags debug leftovers and unmentioned work, and blocks only when it detects a credential\.
- [jev-curate](https://github.com/AkashPriyadarshii/jev-curate) — Synthetic dataset sifter that streams JSONL and Parquet rows through TypeSafe Jev Noul checks to disk\.
- [jev-git](https://github.com/AkashPriyadarshii/jev-git) — Sub-second Git pre-commit and pre-push reflex gate that screens staged diffs for secrets and destructive commands using TypeSafe Jev\.
- [jev-pref](https://github.com/doeixd/jev-pref) — CLI that turns project preferences from agent instruction files into jev-pref\.json rules and uses TypeSafe Jev to review code hunks, staged files, or pull requests against them, returning findings to coding agents\.
- [jev-review](https://github.com/NiazMorshed2007/jev-review) — Local-first MCP plugin for continuous software-quality review by AI coding agents, powered by Jev\.
- [jev-scout](https://github.com/AkashPriyadarshii/jev-scout) — Zero-hallucination open-source repo and crate scout powered by TypeSafe AI Jev System One scoring\.
- [jev-seo](https://github.com/AkashPriyadarshii/jev-seo) — Zero-cost, agent-first SEO &amp; Generative Engine Optimization \(GEO\) search radar CLI suite and MCP server powered by DuckDuckGo and TypeSafe Jev System One\.
- [jev-superpowers](https://github.com/AkashPriyadarshii/jev-superpowers) — Systematic software development framework for AI coding agents upgraded with TypeSafe Jev System One typed decisions, zero-hallucination package vetting, and completion gates\.
- [jev\.nvim](https://github.com/valentynkit/jev.nvim) — Neovim plugin that splits the buffer into functions with Treesitter, scores each against a plain-language question with Jev, and ranks answers by probability in the quickfix window\.
- [jevkit](https://github.com/ariel-frischer/jevkit) — jevkit is a Rust CLI for TypeSafe Jev that validates Choice, Score, and Noul question sets with 13 offline lint rules before sending the request to the /api/alpha/decisions endpoint and prints the parsed answers as JSON\.
- [Jevonian](https://github.com/xinyao27/jevonian) — Local OpenAI- and Anthropic-compatible proxy that asks one Jev call to pick both the model route and the thinking level for jevonian/auto, after deterministic code has filtered candidates by protocol, context window, effort floor, and spent quota windows, and after pinning a real model ID or requesting jevonian/&lt;route&gt; skips Jev entirely\.
- [JevSeek](https://github.com/morcoan/JevSeek) — Desktop and CLI coding agent that uses Jev to select the next tool from user intent and recorded execution results\.
- [Leanest](https://github.com/baronunread/leanest) — Local-first test selector that uses TypeSafe Jev semantic judgments to decide which tests are safe to skip for a given code change, dropping straight into CI via its bundled GitHub Action\.
- [pi-jev-auto-mode](https://github.com/jomatsu/pi-jev-auto-mode) — Jev \(TypeSafe System One\) backed auto mode for the Pi coding agent: semantically auto-approves bash, write, and edit tool calls and fails closed when a decision cannot be made\.
- [pi-warden](https://github.com/DevMortimer/pi-warden) — Guardrails for Pi built on pi-typesafe that steer the agent instead of interrupting you: Jev judges irreversible and off-task tool calls, detects stuck loops, checks unverified done claims, flags slop
- [progressgate](https://github.com/AshutoshVJTI/progressgate) — It's a small deterministic policy sitting on top of TypeSafe Jev semantic judgments — Jev reads the trajectory, code decides what to do about it\.
- [SemDecide](https://github.com/sharziki/semdecide) — CLI that uses TypeSafe Jev for semantic predicates, classification, scoring, and filtering in Unix pipelines\.
- [slop-grader](https://github.com/lukstei/slop-grader) — Rule-based CLI and agent skill that grades text and markdown files against custom rulesets using TypeSafe Jev, guiding an AI agent to auto-fix violations\.
- [Supercov](https://github.com/supercorp-ai/supercov) — Code quality and coverage CLI for coding agents that uses TypeSafe Jev to assess source-code quality\.
- [TypeSafe AI Playground](https://github.com/markjaquith/typesafe-ai-playground) — Rust CLI with TypeSafe Jev experiments for PHI detection, code-comment review, tone analysis, and classification\.
- [Winnow](https://github.com/GhalebDweikat/winnow) — Claude Code tool-output filter that uses TypeSafe Jev to judge which blocks are relevant to the current task\.

### Search

- [hev reranker](https://github.com/hev/reranker) — Python library using Jev Noul judgments to score candidate documents for query relevance, then sort or filter the results\.
- [Jev Search](https://github.com/superagents-lab/jev-search) — Web search using Jev to choose sources, time ranges and query candidates, then rank Search1API results by relevance\.
- [jgrep](https://github.com/keltokhy/jgrep) — Filters text, structured records, functions, and diff hunks against plain-English descriptions using Jev Noul judgments\.
- [jgrep](https://github.com/kyu1204/jgrep) — Semantic grep CLI that asks Jev one Noul per code chunk, git diff hunk or CSV row \(16 per request\) and prints grep-style file:line hits, with English-sentence lint rules for CI and an interactive init\.
- [jselect](https://github.com/keltokhy/jselect) — Selects source-linked evidence within a token budget using Jev Noul relevance judgments and local diversity-aware selection\.
- [jsort](https://github.com/keltokhy/jsort) — Ranks text along a plain-English criterion using pairwise Jev Noul comparisons and a locally fitted Bradley-Terry scale\.
- [MemSearch](https://github.com/zilliztech/memsearch) — Markdown memory retrieval for coding agents with an optional Jev reranker that scores retrieved chunks using Noul questions\.
- [neo4jev](https://github.com/jexp/neo4jev) — Neo4j graph navigation demo that uses TypeSafe Jev to select relationships and check goals during beam search\.
- [Search with Jev and Milvus](https://github.com/milvus-io/bootcamp) — Runnable search tutorials using Gemini embeddings, Milvus retrieval, and Jev judgments for reranking, filtering, stopping, routing, cache reuse, curation, guardrails, and evaluation\.
- [Vector Graph RAG](https://github.com/zilliztech/vector-graph-rag) — Multi-hop retrieval with an optional Jev reranker that scores candidate relations using Noul judgments and selects them with a configurable threshold\.

### Applications

- [cua](https://github.com/aryaminus/cua) — Computer-use automation where an LLM discovers a UI flow once and it replays deterministically with no model in the loop; Jev answers the continue/stuck decision when discovery stops making progress\.
- [human-compiler](https://github.com/asfarsadewa/human-compiler) — A compiler for human language\. Paste text, get diagnostics\. Measured by TypeSafe Jev\.
- [Jev Cookbook](https://github.com/nexibeo/jev-cookbook) — Runnable Node recipes that call Jev through OpenRouter's Decisions endpoint for classification jobs such as support-ticket routing, with confidence thresholds and human-review routing kept in code\.
- [Jev for Chrome](https://github.com/chy4pro/jev-for-chrome) — Unofficial Chrome extension port of Jev Ultrafast in which Jev selects the browser operation and DOM target each step and a separate text model supplies typed text\.
- [Jev Mac Voice](https://github.com/brudarko/jev-mac-voice) — Electron app for English voice control of macOS through OpenAI Realtime and a native Swift Accessibility bridge, with an optional browser command where TypeSafe Jev Choice, Noul, and Score questions pick the action, target, and completion check for Playwright to execute after policy and approval\.
- [Jev Social](https://github.com/socai-io/jev-social) — Local Instagram and TikTok research app where TypeSafe Jev selects bounded socai CLI operations from observed state and deterministic code validates confidence before browser execution\.
- [Jev Trade](https://github.com/aowang-ai/jev-trade) — Live Hyperliquid desk: each tick Jev answers Choice questions for long/short, open/close/hold, and leverage; application code quotes or sends no order\. Documents a dry-run path; a live key sends real orders\.
- [Jev Ultrafast](https://github.com/browser-use/jev-ultrafast) — Python browser agent using Jev to select operations and DOM targets, with a separate text model for typing\.
- [Jev Web Analyzer](https://github.com/replynodes/jev-web-analyzer) — Analyzes a public SaaS landing page as clean Markdown and asks Jev ten bounded Choice questions about what a first-time visitor is likely to understand\.
- [jev-audio-beeper](https://github.com/santos-sanz/jev-audio-beeper) — Private TypeScript proof of concept: identify Spanish profanity with Jev's typed probabilistic decisions and replace the matching word intervals with a beep without changing the audio duration\.
- [jev-skip](https://github.com/valentynkit/jev-skip) — Browser extension that reads the YouTube caption track and paints a per-segment sponsor probability on the seek bar before the intro ends, with no crowd database, reporting 77% of SponsorBlock's sponsor seconds caught over 23 videos at $0\.0008 a video\.
- [jev-trader](https://github.com/jarrodwatts/jev-trader) — A TypeSafe Jev model watches the Kuru MON-USDC order book and answers buy or sell every \~300 ms\.
- [Jev-Trades](https://github.com/zadescoxp/Jev-Trades) — A Next\.js dashboard for live crypto market data and TypeSafe-powered paper trading\.
- [jev-voice-browser](https://github.com/moritzkremb/jev-voice-browser) — Control a real browser by voice\. Jev \(TypeSafe System One\) decides intent \+ target in \~300 ms per spoken word; Playwright acts — often before you finish the sentence\.
- [jevmeter](https://github.com/ChetasLua/jevmeter) — Put a live Jev \(TypeSafe\) meter on any video: every sentence scored, rendered as a 16:9 edit
- [jlink](https://github.com/keltokhy/jlink) — Links records under a plain-English match rule using Jev Noul pair judgments, with local candidate blocking and match resolution\.
- [mobile-jev](https://github.com/droidrun/mobile-jev) — A standalone mobile agent for Mobilerun, powered by TypeSafe's Jev and the Mobilerun API\.
- [typesafe-adblock](https://github.com/realZachi/typesafe-adblock) — 🧹 Fun project: a Chrome extension that asks a tiny AI decision model \(TypeSafe Jev\) "is this DOM element an ad?" and pops it off the page\. BYOK, no backend, not a real ad blocker\.
- [typesafe-ai-playground](https://github.com/BunsDev/typesafe-ai-playground) — A community playground for TypeSafe AI's Jev: edit classification experiments, compare A/B inputs, route conversations, extract document fields, inspect code-policy decisions, and explore games and simulations built around typed model outputs\.
- [typesafe-computer-use](https://github.com/awlevin/typesafe-computer-use) — macOS computer-use tool using Jev to choose actions from OCR and accessibility state, with a separate model for free-text writing\.
- [typesafe-jev](https://github.com/gtaras7/typesafe-jev) — A local screening workbench for a folder of CVs, built on TypeSafe's Jev model\.
- [UI Generator Instinct Jev](https://github.com/joevidev/ui-generator-instinct-jev) — A demo app where the user describes a UI case in free text and Jev \(TypeSafe's System One model\) answers typed Choice/Noul/Score questions to pick and configure a real shadcn/ui component or page block, never generating code or copy\.
- [unclutter](https://github.com/kitze/unclutter) — Jev classifies nonessential page elements through Vercel AI Gateway or TypeSafe AI directly; the extension stores and reapplies local hiding rules by page template\.

### Games

- [jev-askable-arm](https://github.com/TarunTomar122/jev-askable-arm) — Zero-shot English goals on a sim Franka\. Jev chains hardcoded primitives\.
- [jev-doom-agent](https://github.com/lukaske/jev-doom-agent) — A TypeSafe Jev Choice decision—or an explicitly labeled deterministic offline policy—selects a tactical macro; the local motor controller turns that macro into Doom controls\.
- [jev-drone](https://github.com/RomanSlack/jev-drone) — Camera-only autonomous drone in MuJoCo with a small judgment model \(TypeSafe Jev\) in the loop at 2\.5Hz
- [jev-gomoku](https://github.com/mizchi/jev-gomoku) — TypeSafe AI の System One モデル Jev を MoonBit から触るためのプレイグラウンド。 Jev は「文字列ではなく型付きの確率判断を返す」意思決定専用モデルです\(unstructured state in, typed probabilistic decisions out\)。
- [jev-got](https://github.com/phureewat29/jev-got) — Each turn a story model writes the next scene, and then TypeSafe's Jev reads that scene back and answers five questions about it: where Jon now stands, what kind of scene it was, how much danger he is in, what should play under it, and whether the prose stayed inside the fiction\.
- [jev-little-airways](https://github.com/lbotinelly/jev-little-airways) — A show-and-tell capability study for Jev, TypeSafe's System One decision model\.
- [jev-plays-pokemon-red](https://github.com/valentynkit/jev-plays-pokemon-red) — Pokemon Red on PyBoy where deterministic code owns the route and arithmetic, Jev picks only at branches, and every battle turn's faint prediction is scored by Brier against RAM state\.
- [JevsBistro](https://github.com/andrewsilber/JevsBistro) — Deterministic 3D restaurant simulator that replays the same dinner service to compare rule-based, camera-assisted, and Jev-planned waiters, logging each decision's state, options, confidence, and latency\.
- [PlayJev](https://github.com/OmniJev/PlayJev) — Qwen3\.5-0\.8B-Base fine-tuned on frames labelled by ten per-game search programs to play ten browser games from 448 px screenshots, reading a probability over each game's option list off one forward pass instead of generating text, and serving the Jev /v1/systemone request and response schema\.
- [snake-jev](https://github.com/siroccomask/snake-jev) — A desktop Snake experiment powered by Jev / System One\.
- [Soupbase](https://github.com/spoonnotfound/soupbase) — A lateral-thinking puzzle game where Jev Choice judgments answer player questions and assess proposed solutions, while application code requires supported facts, a coherent explanation, and sufficient confidence before marking a puzzle solved\.
- [tsai-civ2](https://github.com/phyous/tsai-civ2) — An original Civilization II browser harness for TypeSafe Jev, with live decision probabilities and a Roman-themed spectator display\.
- [tsai-sc](https://github.com/phyous/tsai-sc) — A TypeSafe System One harness for Strongarm, the first combat mission in the original StarCraft shareware campaign, with a game recording and Jev's actual action probabilities\.
- [typesafe-mario](https://github.com/fhshaik/typesafe-mario) — An experimental controller that lets TypeSafe's Jev model directly choose NES controller inputs for the original Super Mario Bros\.
- [typesafe-snake](https://github.com/sorrycc/typesafe-snake) — Snake auto-played by TypeSafe's Jev model: one System One choice per tick, legal moves and facts generated in code

### Research

- [assay-001](https://github.com/jourdanlabs/assay-001) — ASSAY-001: independent, pre-registered verification of TypeSafe Jev's calibration and type-safety claims\. Split verdict, published in full\.
- [decider](https://github.com/Mapika/decider) — It is an open reproduction of the "System One" model class \(TypeSafe AI's Jev\), built on Qwen/Qwen3\.5-2B-Base\.
- [DeepSearcher search-stopping evaluation](https://github.com/zilliztech/deep-searcher) — Standalone experiment comparing Jev and a generative model as search-stopping policies, with a replay workflow and recorded evaluation results\.
- [jev-agent-failure-benchmark](https://github.com/TokenTrim/jev-agent-failure-benchmark) — This benchmarks Jev \(Typesafe\.ai\) on the text subset of Who&amp;When Pro, an agent-failure-attribution benchmark: given a failed multi-agent run, predict the responsible agent, the decisive step, and the error type\.
- [jev-dspy-lab](https://github.com/jmanhype/jev-dspy-lab) — Reproducible calibration, confidence-gating, latency, and modeled-cost benchmarks for Jev / TypeSafe System One decisions used in DSPy workflows\.
- [jev-eval-agent](https://github.com/vinilana/jev-eval-agent) — The repository exists to answer one question: how many steps does the agent need to finish the same task when the LLM picks the tool itself vs\. when Jev \(TypeSafe's classifier\) picks it?
- [jev-phishing-bench](https://github.com/anisselbd/jev-phishing-bench) — Public, reproducible comparison of Jev \(TypeSafe AI's System One model, launched 15 September 2026\) against a classic LLM on one security decision: should an email agent click the link in this email?
- [jev-rerank-bench](https://github.com/anessbelbati/jev-rerank-bench) — Can a decision model beat dedicated rerankers? TypeSafe Jev vs Cohere Rerank 4 vs ZeroEntropy zerank-2 vs a chat-model baseline: 14 datasets, every raw API response, bootstrap ranges on every gap\.
- [jev-search-rerank-eval](https://github.com/zhuyansen/jev-search-rerank-eval) — Does a TypeSafe Jev rerank beat embedding search? Graded relevance eval \(9,831 pairs, 164 zh/en queries\) over the Agent Skills Hub catalog, with the judge-circularity bias measured\.
- [jev-sec-bench](https://github.com/Gaurav-Gosain/jev-sec-bench) — Blind security benchmarks for Jev, TypeSafe's System One model: prompt injection and vulnerable code detection, built on jev-go
- [jev-secret-detection](https://github.com/teyhouse/jev-secret-detection) — Measures how well TypeSafe's Jev model spots real secret credentials in file snippets\.
- [jev-spam-eval](https://github.com/bitnovus/jev-spam-eval) — This repository explores how far TypeSafe's pretrained Jev model can go through zero-shot classification and context enrichment\.
- [jevcal](https://github.com/abhixhek/jevcal) — Stop guessing confidence thresholds\. jevcal measures a typed decision model on your data, picks the threshold that meets your accuracy target, tells you how much traffic still needs an LLM, and fails CI when a model update quietly breaks it\.
- [jevfire](https://github.com/kikoncuo/jevfire) — JEVfire assigns typed variables from finite choices, batching independent fields through vLLM for parallel execution and reuse of their shared instruction/context prefix when the engine cache permits it\.
- [jevmlx](https://github.com/bnsd55/jevmlx) — Asking an LLM for JSON means parsing what it wrote and retrying until it parses\. jevmlx takes a schema of booleans, enums, and multi-selects, scores every allowed answer for every field in one forward pass, and assembles the JSON itself — valid by construction, every field with a probability\.
- [Laya](https://github.com/NandhaKishorM/laya) — A multilingual, non-autoregressive System 1 decision engine with Jev-like typed choice, score, and noul decisions, language-aware checkpoint routing, and reproducible comparisons against Jev\.
- [LitJev](https://github.com/zhengxuyu/litjev) — Open reproduction of Jev's decision layer on Qwen models that serves the Jev /v1/systemone request and response schema \(choice, score, noul\) from a local Hugging Face checkpoint by reading option logits instead of generating text, with an MMLU-Pro direct-answer benchmark\.
- [openjev](https://github.com/razorback16/openjev) — Open, Jev-compatible System One decision server on DiffusionGemma
- [openjev-sglang](https://github.com/ekzhang/openjev-sglang) — A server implementing the TypeSafe/Jev HTTP API with Qwen3\.6-35B-A3B on SGLang\.
- [smoking-extraction-benchmark](https://github.com/vclic/smoking-extraction-benchmark) — Synthetic smoking-history extraction benchmark comparing TypeSafe Jev and OpenAI structured outputs, with reproducible accuracy, cost, and latency results\.
- [typesafe-ai-benchmark](https://github.com/iammrduncan/typesafe-ai-benchmark) — This benchmark runs Qwen 3\.8 27B on Cerebras and TypeSafe Jev side by side across seven synthetic workloads, with a separate local Needle 3 evaluation on the same contracts\.

## Submit a project

Add up to ten project entries in a PR using the [contribution guide](CONTRIBUTING.md). Each project is reviewed independently. Source paths are optional—the reviewer looks for integration code automatically. You can also [ask for help submitting](https://github.com/fatwang2/awesome-jev/issues/new?template=submission.yml).

## How reviews work

[Jev Review Action](https://github.com/fatwang2/jev-review-action) checks source evidence, reviews the project description and setup instructions, and suggests a category. Jev supplies typed judgments; code renders the comment. Maintainers decide what gets merged.

See the [review policy](.github/jev-review.json) and [validation records](docs/reviews/README.md).

## About

An independent project by [fatwang2](https://github.com/fatwang2), not affiliated with TypeSafe. Inclusion is not a certification. [MIT licensed](LICENSE); listed projects retain their own licenses.
