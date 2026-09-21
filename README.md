# Awesome Jev [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

What people built with Jev (TypeSafe System One). Showcase, not a tools directory.
Each line is a project and what Jev does inside it.

## Routing

- [Foreman](https://github.com/thruwire/foreman) — Jev on a Codex worker for semantic supervision on a factory floor
- [llama-index-jev](https://github.com/WiktorB2004/llama-index-jev) — LlamaIndex reranker + router with typed Jev scores/choices.
- [opencode-jev-orchestrator](https://github.com/aaronshaf/opencode-jev-orchestrator) — Sticky cheap model; Jev escalates hard turns to stronger subs.
- [agent-router](https://github.com/nidhi-singh02/agent-router) — Picks Cursor/Claude/Codex/OpenCode + effort, then launches.
- [todo-jev](https://github.com/maker-KK/todo-jev) — Task classifier + 3-tier routing engine powered by Jev.
- [tiershift](https://github.com/iamvatsalpatel/tiershift) — Every LLM call → cheapest capable model; Jev routes ~ms.
- [jev-router](https://github.com/rajdhakad9826/jev-router) — Cost-aware Choice: cheapest model that can handle the query.
- [JevRouter](https://github.com/BillionsBobby/JevRouter) — Routes models / tools / subagents with Jev Choice.
- [hono-jev-router](https://github.com/yusukebe/hono-jev-router) — Hono semantic router: HTTP requests routed by meaning via Jev.
- [pi-jev (Theo)](https://github.com/TheoOliveira/pi-jev) — Pi: semantic tool routing + typed System One decisions.
- [flue-jev-demo](https://github.com/matthewp/flue-jev-demo) — Flue agent routing with Jev through Cloudflare AI Gateway.
- [Jev-Auto-Router](https://github.com/miniLV/Jev-Auto-Router) — Codex per-call GPT model routing via Jev Choice.
- [jcm-router](https://github.com/adarshmishra07/jcm-router) — Local proxy: Jev picks Claude model + effort per message.
- [pi-jev-router](https://github.com/mejiasd3v/pi-jev-router) — Pi: Jev Choice routes model via Vercel AI Gateway.
- [jev-router (prismhq)](https://github.com/prismhq/jev-router) — LiteLLM proxy: Jev Choice picks which model runs next.
- [tax-doc-classifier](https://github.com/kyotofin/tax-doc-classifier) — Choice IRS form + page class; code acts only when confidence ≥0.95
- [Codriver](https://github.com/johnpozy/codriver) — per-turn Choice picks which fleet model fits this turn, then rewrites the outbound message
- [ReflexRoute](https://github.com/AIGNLAI/ReflexRoute) — zero-shot / few-shot Choice routes which model runs next
- [jev-router](https://github.com/gargpratyush/jev-router) — per-turn routes Claude Code / Codex to cheap vs strong model while keeping each CLI’s native session
- [SemDecide](https://github.com/sharziki/semdecide) — Jev as a Unix CLI: classify, score, filter, and guard in scripts and CI
- [Jev Codex Router](https://github.com/0xNatoshi/jev-codex-router) — Jev scores how hard each coding turn is, then picks a cheap vs stronger model
- [safer-with-jev](https://github.com/andrelandgraf/safer-with-jev) — Jev classifies the task, then routes it to Grok or GPT (was typesafe-on-neon)
- [Lahfir harness router](https://x.com/mdlahfir/status/2100314182201802811) — Jev routes Claude Code / Codex / Opencode tasks by intensity (Haiku vs Opus sub-agents vs external harness)

## Refund review

- (none in this batch)

## Realtime

- [jev-ultrafast](https://github.com/browser-use/jev-ultrafast) — each step Jev picks the operation and the element from DOM state; small LLM only types; flight search demo 7s / $0.0039; [demo](https://x.com/gregpr07/status/2100411066966749359)
- [tsai-civ2](https://github.com/phyous/tsai-civ2) — Civilization II in browser: live Jev action probabilities.
- [jev-triage (issues)](https://github.com/cephalization/jev-triage) — Issue triage across large repos with typed Jev judgments.
- [jev-chat-for-twitch](https://github.com/ethanplusai/jev-chat-for-twitch) — Chrome: filter live Twitch chat with Jev.
- [jev-block-android-ad](https://github.com/ufec/jev-block-android-ad) — Android: JevNoiseGate filters notifications/SMS by meaning.
- [jev-robotics-demo](https://github.com/FazalAAli/jev-robotics-demo) — MuJoCo robot arm: Jev vs Claude Opus decisions.
- [jev-reflex-autonomy-lab](https://github.com/khordoo/jev-reflex-autonomy-lab) — Multi-drone autonomy: Jev reflex decisions.
- [typesafe-jev-drone-demo](https://github.com/kxzk/typesafe-jev-drone-demo) — Three.js drone: live Jev navigation choices.
- [jev-paint](https://github.com/achimala/jev-paint) — Use Jev to make art (closed action choices).
- [jev-pong](https://github.com/ably-labs/jev-pong) — Pong: ball moves one step per Jev/LLM decision.
- [snake-jev](https://github.com/siroccomask/snake-jev) — Snake: parallel Jev assessments, one API call per tick.
- [tsai-sc](https://github.com/phyous/tsai-sc) — StarCraft shareware: Jev controls keyboard/mouse.
- [jev-plays-pokemon-red](https://github.com/valentynkit/jev-plays-pokemon-red) — PyBoy Pokemon: code owns route; Jev picks at branches ~100ms.
- [jev-plays-pokemon](https://github.com/milanboers/jev-plays-pokemon) — Pokemon Red: Jev picks actions.
- [jev-bfs](https://github.com/komikat/jev-bfs) — Wikipedia link races: Jev ranks next hop live.
- [jev-canvas](https://github.com/gaborishka/jev-canvas) — Voice + finger on tldraw; Jev decides draw intent.
- [jev-desktop](https://github.com/yikangy873-gif/jev-desktop) — Codex Computer Use: Jev selects the next UI action.
- [jev-for-chrome](https://github.com/chy4pro/jev-for-chrome) — Chrome: Jev drives the tab you’re looking at.
- [jev-agent-browser](https://github.com/forvela/jev-agent-browser) — Bounded browser agents: typed actions via Jev.
- [jev-browser](https://github.com/jkudish/jev-browser) — Browser use with Jev as the decision model.
- [fastbrowse](https://github.com/agent-labs-dev/fastbrowse) — Jev picks each on-page action; LLM reads/plans around it.
- [jev-skip](https://github.com/valentynkit/jev-skip) — Caption-time sponsor skip: probability per span → skip.
- [jev-triage](https://github.com/maraichr/jev-triage) — Choice case/desk + Score priority + Noul fraud/recall; code sets queue/SLA/next step
- [Jev-MongoDB](https://github.com/qiaohaojie/Jev-MongoDB) — Choice category + Score mood/urgency/safety on Change Streams; code writes back and pushes a board
- [youtube-sponsor-detection](https://github.com/trungdq88/youtube-sponsor-detection) — Choice over caption lines / Noul “spoken ad?”; code maps timestamps and skips
- [jev-voice-browser](https://github.com/moritzkremb/jev-voice-browser) — spoken partial transcripts → Jev picks intent/target (~250–350ms); Playwright acts; text spans copied verbatim
- [WebMCP × Jev bench](https://webmcp.com/benchmark) — Jev picks WebMCP tools; Mercury fills args; 49/49 at ~112×–245× lower model cost vs GPT-6 Astra computer use; [thread](https://x.com/0xidanlevin/status/2100937437325205568) · [WindTunnel](https://github.com/nekuda-ai/WindTunnel)
- [1v1 Jev](https://github.com/emrickgarrett/OneVOneJev) — Jev at about 9Hz picks move, aim, ADS, shoot, and jump
- [Playground](https://github.com/markjaquith/typesafe-ai-playground) — Jev experiments: PHI detect, comment review, live tone, job and industry classify
- [Prism](https://github.com/irfndi/prism-liquidity-agent) — Jev scores toxic flow, market stress, mean-reversion, and liquidity (shadow only, no live trades)
- [neo4jev](https://github.com/jexp/neo4jev) — Jev scores candidate graph edges, then beam-searches the likely path
- [jev-desktop](https://github.com/lahfir/agent-desktop) — Jev reads the Accessibility Tree and picks which control and which action
- [TypeSafe Mario](https://github.com/fhshaik/typesafe-mario) — Jev chooses NES controller macros from structured emulator state (Choice + Noul + Score); no screenshots
- [TypeSafe Computer Use](https://github.com/awlevin/typesafe-computer-use) — OCR reads the Mac screen; Jev picks the next UI action (~$0.0002/step); [demo thread](https://x.com/awlevin/status/2100262612428894676)
- [Kyle Jeong + Stagehand](https://x.com/kylejeong/status/2100622054945095934) — a11y tree as state; Jev picks the next browser action, Stagehand executes; ~$0.001/task, near-instant remote browser
- [jev-trader](https://github.com/jarrodwatts/jev-trader) — Jev watches the Kuru MON-USDC book and posts a post-only limit quote each Monad block (~300ms)
- [Sprite Fusion realtime levels](https://www.spritefusion.com/blog/generating-game-level-in-real-time-with-jev) — game state in; Jev Choices for next terrain slice (type/width/gap/height); code places blocks (~319–375ms, ~$0.00057/request)
- [jevpilot](https://github.com/standardagents/jevpilot) — Choice among sampled drive paths at ~1.5–4Hz in a Three.js driving sim
- [jev-drone](https://github.com/RomanSlack/jev-drone) — classical CV builds the scene; Jev picks maneuver / risk / lost-target at ~2.5Hz in MuJoCo
- [mobile-jev](https://github.com/droidrun/mobile-jev) — Jev chooses each Android UI action; Uber demo ~21s / 9 actions (to checkout, no purchase)

## Eval

- [Jev Review](https://github.com/devagrawal09/jev-review) — Jev pre-screens correctness, security, reliability, compatibility, and test risk before a heavier model
- [jev-architect](https://github.com/karanb192/jev-architect) — Find, design, and evaluate TypeSafe Jev decision loops.
- [jev-classifier](https://github.com/felpsdev/jev-classifier) — Local tool-routing classifier for coding agents + gateway.
- [pi-typesafe](https://github.com/DevMortimer/pi-typesafe) — Pi: batched evaluation tool + typed API for extensions.
- [jevvy](https://github.com/PanAchy/jevvy) — Jev-powered plugins for coding agents.
- [jevwire](https://github.com/Brainwires/jevwire) — MCP + DecisionModel library + escalate-only Claude hooks.
- [jev-use](https://github.com/shitianfang/jev-use) — Plugin: hand no-text-output steps to Jev judgments.
- [jev-skill-suggester](https://github.com/win4r/jev-skill-suggester) — Bounded installed-skill recommendations via Jev.
- [jev-spam-eval](https://github.com/bitnovus/jev-spam-eval) — Zero-shot spam filtering with Noul vs TF-IDF baselines.
- [mastra-jev-moderation](https://github.com/CodeAlive-AI/mastra-jev-moderation) — Input moderation for Mastra agents via Jev.
- [jev-auto-approve](https://github.com/metalbear-co/jev-auto-approve) — Jev PR auto-approver.
- [jev-sentinel](https://github.com/harshwasan/jev-sentinel) — Pi: Jev checks tool calls/outputs/replies (injection etc.).
- [jev-security-scan](https://github.com/win4r/jev-security-scan) — Review Skills/MCP code for suspicious behavior with Jev.
- [jev-review (Niaz)](https://github.com/NiazMorshed2007/jev-review) — Local-first continuous quality review MCP for coding agents.
- [perch](https://github.com/lakeday-org/perch) — Semantic code linting against configurable Jev questions.
- [abide](https://github.com/coldteadotai/abide) — Make coding agents abide by project rules (Jev-backed).
- [pi-quiet-ask](https://github.com/HyunjunJeon/pi-quiet-ask) — Pi quiet decision layer via TypeSafe Jev.
- [stanley-code](https://github.com/devagrawal09/stanley-code) — Bounded TypeSafe Jev workflows for coding agents.
- [limpet](https://github.com/noplan-inc/limpet) — Stop hook: plain-language rules so agents don’t stop too early.
- [wakegate](https://github.com/shitianfang/wakegate) — Ask Jev if a sleeping agent wakeup is worth a full LLM turn.
- [jev-belay](https://github.com/valentynkit/jev-belay) — Claude Code Stop hook: evidence check before trusting “done”.
- [diffjury](https://github.com/raihankhan-rk/diffjury) — PR risk router + code-review coach via Jev.
- [jev-logtriage](https://github.com/jyatesdotdev/jev-logtriage) — Choice whether a log batch is worth acting on; confidence gates.
- [is-malicious](https://github.com/luantak/is-malicious) — Scans source/CI files; Jev flags suspicious behavior.
- [hunch](https://github.com/Kelbie/hunch) — Semantic code review with plain-English rules + Jev.
- [jev-pref](https://github.com/doeixd/jev-pref) — Lints code changes against AGENTS.md prefs via Jev.
- [hermes-jev-approvals](https://github.com/anpicasso/hermes-jev-approvals) — Hermes smart command approvals reviewed by Jev.
- [jev-commit](https://github.com/valentynkit/jev-commit) — Pre-commit: one Jev call — message match staged diff?
- [jev-git](https://github.com/AkashPriyadarshii/jev-git) — Pre-commit / pre-push semantic reflex gate.
- [pi-verdict](https://github.com/jesset/pi-verdict) — Minimal Pi permission gate (auto-mode style).
- [jev-guard](https://github.com/leepokai/jev-guard) — Risk-scores every tool call → allow / ask / deny.
- [pi-jev](https://github.com/y0usaf/pi-jev) — Pi tool-call gate + jev_ask for typed calibrated answers.
- [pi-jev-permit](https://github.com/kurihada/pi-jev-permit) — Pi bash/write/edit calls: Noul permit gate before run
- [jevmod](https://github.com/ohernandezdev/jevmod) — multi-category Noul moderation (spam/scam/…) with thresholds you own
- [Paolo Rosson PR review](https://x.com/redp314/status/2100585126652481915) — paste a diff → one Jev/TypeSafe call → ~14 typed checks as probabilities → BLOCK / security review / nits / merge; ~$0.00007/PR
- [fx auto-review](https://x.com/fazxes/status/2100300097695232164) — Jev as the safety classifier for fx auto mode; ~5–18× faster and more accurate than GPT-5.6 Luna on their benchmark
- [pi-jev-auto-mode](https://github.com/jomatsu/pi-jev-auto-mode) — semantic allow/block on Pi bash/write/edit; fails closed when undecidable (~193–642ms)
- [pi-warden](https://github.com/DevMortimer/pi-warden) — scores write/edit vs project rules plus irreversible/off-task on tool calls; steers the Pi agent
- [Jev-Moderation-Bot](https://github.com/brainstormity/Jev-Moderation-Bot) — Choice LEGITIMATE|SPAM|SCAM_LINK plus Noul ban-now? per Discord message
- [triagedy](https://github.com/m0rphtail/triagedy) — per alert: disposition close|escalate|contain|investigate plus severity/FP/IR probabilities; Rust policy maps to action
- [privacy-facts](https://github.com/thenewpotato/privacy-facts) — ~14 privacy-policy questions as typed labels + confidence; picks supporting policy sections for excerpts
- [sokit](https://github.com/jodan-alberts/sokit) — control questions each turn (next_action / spam-route / draft-safety Noul); ConfidenceGate → act|confirm|escalate

## Writing check
- [Human Compiler](https://github.com/asfarsadewa/human-compiler) — Jev scores prose for information density, clarity, hostility, and corporate tells, then the compiler emits rustc-style diagnostics
- [Jev-X-Sentiment-Analysis](https://github.com/brainstormity/Jev-X-Sentiment-Analysis) — X posts: Jev sentiment / judgment labels.
- [slop-grader](https://github.com/lukstei/slop-grader) — Rule-based slop grader for text files powered by Jev.
- [pagegrade](https://github.com/kitze/pagegrade) — Choice/Score page sections for clarity, writing, SEO.
- [JevSlop](https://github.com/TKY-27/JevSlop) — Jev judges whether a note/article is AI slop.
- [taste-lint](https://github.com/mblode/taste-lint) — Catch AI slop before you ship.
- [snifftest](https://github.com/DanRWilloughby/snifftest) — Prose linter for AI writing tells (rules + optional Jev).
- [draftpulse](https://github.com/pekth/draftpulse) — Choice draft category + multi Score (hook/specificity/reply/share/dwell/slop); code weights into a label
- [script-judge](https://github.com/BriyanPatel/script-judge) — Choice approve / revise / reject on a pasted script (does not rewrite it)
- [Jevibe Check](https://github.com/sriganesh/jevibe-check) — Jev labels drafts and posts for warmth, constructiveness, tension, sarcasm, clarity, and intent

## Tools

Official SDK / skill / Gateway / docs: [jev.gallery/tools](https://jev-gallery.pinto-cost.workers.dev/tools)

- [typesafe-mcp](https://github.com/itsmostafa/typesafe-mcp) — Jev as Choice / Score / Noul inside Claude Code, Desktop, and Codex
- [jev_jsonschema](https://github.com/Kiln-AI/jev_jsonschema) — Run a JSON Schema through Jev API; get JSON judgments back.
- [jevkit](https://github.com/ariel-frischer/jevkit) — Rust CLI for typed decisions + offline lint before you pay.
- [jev-cli](https://github.com/tumf/jev-cli) — Small dependency-free CLI for TypeSafe Jev judgments.
- [decide-mcp](https://github.com/dakdevs/decide-mcp) — Configurable decision MCP with Jev + bias profile routing.
- [jevalyn](https://github.com/Ray-Hughes/jevalyn) — Rails-native wrapper around Jev System One API.
- [jev-dsh-decision](https://github.com/Devin-AXIS/jev-dsh-decision) — Structured decision plugin for agent harnesses.
- [ask-jev-skill](https://github.com/shantanugoel/ask-jev-skill) — Hermes/agent skill to ask TypeSafe Jev.
- [jev-workbench](https://github.com/molis-ai/jev-workbench) — Versioned judgment functions on Jev; call published versions.
- [jevcal](https://github.com/abhixhek/jevcal) — Calibrate/threshold/drift-check typed decision models.
- [jevocks](https://github.com/unicodeveloper/jevocks) — Everyday stocks status judgments with Jev.
- [jev-trade](https://github.com/aowang-ai/jev-trade) — Live Hyperliquid trader driven by Jev choices.
- [jev-cvss](https://github.com/Red5d/jev-cvss) — Fast CVSS scoring from vuln descriptions via Jev.
- [jev-web-analyzer](https://github.com/replynodes/jev-web-analyzer) — See what Jev thinks about a SaaS website.
- [jev-scout (MCP)](https://github.com/kierandotai/jev-scout) — MCP research: every query/result/page scored by Jev.
- [advocaat](https://github.com/pithings/advocaat) — Type-safe client for asking Jev questions about datasets.
- [jev-mcp (blakestone)](https://github.com/blakestone-x/jev-mcp) — MCP: classify/score/check/match/screen tools.
- [jev-mcp](https://github.com/burnigtm/jev-mcp) — MCP: put TypeSafe Jev on Cursor/Codex coding loop.
- [Jevbridge](https://github.com/tacticocc/Jevbridge) — ACP/MCP adapter: Jev beside coding/chat models.
- [grok-bot-jev](https://github.com/Bodila51/grok-bot-jev) — Grok Bot decision layer: usage gates + Jev skill templates.
- [hunch (Ruby)](https://github.com/carldaws/hunch) — Ruby/Rails probabilistic control flow via Jev likely?.
- [sqlite-jev](https://github.com/mgaitan/sqlite-jev) — Batched NL judgments for SQLite via Jev.
- [jevql](https://github.com/kylemclaren/jevql) — Semantic SQL for Postgres powered by Jev.
- [jegrep](https://github.com/can1357/jegrep) — Semantic grep: find code by describing what you want.
- [jgrep (keltokhy)](https://github.com/keltokhy/jgrep) — Filter lines by meaning with Jev (description as pattern).
- [jev-curate](https://github.com/AkashPriyadarshii/jev-curate) — High-throughput dataset sifter powered by Jev.
- [jev-cookbook](https://github.com/nexibeo/jev-cookbook) — Practical Jev recipes (triage etc.) on OpenRouter.
- [new-api-plugin-typesafe](https://github.com/FFatTiger/new-api-plugin-typesafe) — new-api plugin: native /v1/systemone Jev tasks.
- [jev-agent-skill](https://github.com/yuyang2230/jev-agent-skill) — Offload classify/screen/score/verify to Jev from agents.
- [jev-judgment](https://github.com/HyunjunJeon/jev-judgment) — Agent skill: closed coding judgments → TypeSafe Jev.
- [super-jev](https://github.com/Kevthetech143/super-jev) — Small decision-to-action harness for TypeSafe Jev.
- [pi-typesafe-jev](https://github.com/legacybridge-tech/pi-typesafe-jev) — Pi extension: five tools wrapping TypeSafe Jev judgments.
- [jev-engineering](https://github.com/eugeniughelbur/jev-engineering) — Decision layer for agents: hard rules then Jev call.
- [jev-mcp (BYK)](https://github.com/BYK/jev-mcp) — MCP: typed noul/choice/score judgments for agents.
- [jev-scout](https://github.com/AkashPriyadarshii/jev-scout) — Repo/crate scout: Jev relevance without hallucinated claims.
- [jev-seo](https://github.com/AkashPriyadarshii/jev-seo) — SEO/GEO CLI + MCP: Jev-backed ranking/judgments.
- [jev-social](https://github.com/socai-io/jev-social) — IG/TikTok/LinkedIn research: typed routing + evidence.
- [fast-dev-compaction](https://github.com/leonaaardob/fast-dev-compaction) — Codex plugin: Jev-guided context restoration around compaction.
- [pi-fast-jev-compaction](https://github.com/joelhooks/pi-fast-jev-compaction) — Pi: verbatim compaction keep/truncate/drop via Jev.
- [yoshi](https://github.com/compozy/yoshi) — Context-pruning proxy: Jev judges which history is still needed.
- [jev-pruner](https://github.com/tamaratran/jev-pruner) — Trim long Bash output with Jev before the model sees it.
- [jev.nvim](https://github.com/valentynkit/jev.nvim) — Neovim: Treesitter splits; Jev scores functions → quickfix.
- [jsort](https://github.com/keltokhy/jsort) — Sort lines by meaning via pairwise Jev comparisons.
- [jgrep](https://github.com/kyu1204/jgrep) — Semantic code search: what code does, not what it’s called.
- [jev-nlgrep](https://github.com/YehuiTang0316/jev-nlgrep) — Natural-language grep powered by Jev.
- [jev-semgrep](https://github.com/uehaj/jev-semgrep) — Semantic grep: Jev scores each line against a meaning.
- [jev-reranker (shinpr)](https://github.com/shinpr/jev-reranker) — Rerank/filter/compress JSON search hits with Jev.
- [jev-reranker](https://github.com/hotchpotch/jev-reranker) — RAG relevance filter/rerank with Jev probabilities.
- [citation-verifier](https://github.com/MarissaFamularo/citation-verifier) — Noul: does each cited paper support the citing sentence?
- [jev-axi](https://github.com/shiftynick/jev-axi) — CLI: pick / rate / check / rank / triage / guard.
- [docjev](https://github.com/jerryjliu/docjev) — Doc Q&A / retrieval judgments with Jev.
- [sift](https://github.com/bohutang/sift) — Chrome: label every X post (substance/humor/promo/junk/…).
- [typesafe-jev](https://github.com/gtaras7/typesafe-jev) — Screen a folder of CVs with typed Jev judgments + policy.
- [jev-rules](https://github.com/EliaAlberti/jev-rules) — one Noul per standing rule (“is this request about that?”); Claude Code only sees matching rules
- [pi-jev-skill-suggestion](https://github.com/iamdin/pi-jev-skill-suggestion) — Pi extension: strip skill listing; Jev gate + wide/narrow Choice → at most one skill (cookbook two-stage; fail open)
- [classifier.dev](https://classifier.dev/) ([repo](https://github.com/mrmps/classifier-dev)) — hosted zero-shot labels via Jev (fast=Jev; smart=unsure → reasoning model)
- [skillbox](https://github.com/kitze/skillbox) — self-hosted skills library (MCP); optional Jev recommends which skill fits the task
- [jev-shell-history](https://github.com/mrnugget/jev-shell-history) — zsh autosuggestions: Jev ranks which past command you are completing as you type
- [pg-jev](https://github.com/realZachi/pg-jev) — Postgres extension: filter/rank/classify rows with plain-language Jev conditions in SQL
- [unclutter](https://github.com/kitze/unclutter) — browser extension: Jev identifies page clutter/ads and hides them via reusable template rules
- [notra](https://github.com/usenotra/notra) — Choice sentiment plus rank/position classifiers for GEO / AI-visibility mentions
- [HA-Jev](https://github.com/AboveColin/HA-Jev) — Noul/Choice/Score on Home Assistant house state → sensors; Assist routes by confidence
- [jev-mcp](https://github.com/jkudish/jev-mcp) — Jev as MCP tools: verify claims, screen prompt injection, rank by meaning
- [Blink](https://github.com/ellipsis-dev/blink) — at each directory level Jev scores which files or folders matter, then sends more walkers there
- [Winnow](https://github.com/GhalebDweikat/winnow) — Jev judges which Read / Bash / Grep output is actually relevant before it enters Claude Code context
- [fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction) — Jev scores each tool call/result (keep / truncate / drop) for Claude Code compaction; [demo](https://x.com/tamarajtran/status/2100694549362553153)
- [SkillRanker](https://github.com/Dicklesworthstone/skillranker) — Jev ranks which agent skills fit the next step from live session context (Choice + Noul; abstention when none fit)
- [jevmeter](https://github.com/ChetasLua/jevmeter) — scores every transcript sentence for BS/spin/hype; ffmpeg burns a live meter into a 16:9 edit
- [typesafe-adblock](https://github.com/realZachi/typesafe-adblock) — code finds ad-shaped DOM nodes; Jev Noul per candidate “is this a paid ad?”; removes above threshold (BYOK Chrome ext)
- [jev-search](https://github.com/superagents-lab/jev-search) — Jev picks sources/time/query, then scores hit relevance; returns ranked links/snippets only; [live](https://jev.s1.dev)
- [typesafe-skill-router](https://github.com/DECRUX9812/typesafe-skill-router) — Jev names the one Hermes skill worth loading before the model call (~$0.001/turn); abstains if low fit
- [jev-agent-skill-router](https://github.com/GodsBoy/jev-agent-skill-router) — batched Choice over a skill catalogue → route / no_skill / review with need/ambiguity/fit Nouls
- [typesafe-mod](https://github.com/BeLazy167/typesafe-mod) — Claude Code hook — Jev ranks installed skills per prompt; can also score AskUserQuestion options in parallel
- [OpenRouter](https://openrouter.ai/typesafe-ai/jev) — Jev as a System One decision model on OpenRouter (beta); typed state + question → typed decision with probability; [announcement](https://x.com/openrouter/status/2100744709589316009)
- [LangChain + Jev harness](https://x.com/i/article/2100744524951932928) — TypeSafeClassifier / middleware: model routing and Auto Mode safety checks before tool calls; [post](https://x.com/sydneyrunkle/status/2100754364545761643)
- [jev-experiments](https://github.com/dabit3/jev-experiments) — latency-focused Jev demo suite (agent-assist, commit-sentry, shell-guard, dispatch, …): multi-question typed judgments in ~100ms
- [Six things with Jev](https://isaacflath.com/writing/six-things-i-tried-with-jev) — Isaac Flath: fact-check scripts, rank news, find PDF text, check citations, group review notes, eval agent-failure traces; [thread](https://x.com/isaac_flath/status/2100623016644223175)
- [cursor-clijev-compaction](https://github.com/kleosr/cursor-clijev-compaction) — same keepCall/keepResult nouls for Cursor CLI agent history; re-injects kept facts after native compact
- [Brainwires jev-mcp](https://github.com/Brainwires/jev-mcp) — MCP tools jev_rank / jev_verify / jev_next_step / jev_gate_action for chunk ranking, claim check, turn-done, and pre-destructive gates
- [Reflex](https://github.com/kshetrajna12/reflex) — in-browser WebGPU Qwen doing noul/choice/score with probabilities; [demo](https://kshetrajna12.github.io/reflex/) · [thread](https://x.com/kshetrajna/status/2100739853101195744)
- [json-render + Jev](https://github.com/vercel-labs/json-render) — Jev chooses catalog components / slots / action bindings; code assembles the UI spec (no free-form JSON); [docs](https://json-render.dev/docs/jev) · [demo](https://x.com/ctatedev/status/2101022101750571357)
- [WTF is Jev (9 builds)](https://x.com/i/article/2100772231462961152) — Matt Van Horn roundup of early builds (browser agent, compaction, fx, routing, RAG, games, email, batch eval, on-device); [thread](https://x.com/mvanhorn/status/2100788572316139655)
- [RAG chunk filter](https://x.com/kushbhuwalka/status/2100731050075050485) — per retrieved chunk, keep vs drop for precision (no author repo yet)
- [Minecraft realtime](https://x.com/wuyang_zhou/status/2100727660875808913) — Jev for fast realtime actions while a planner LLM plans (multi-zombie fight)
- [Email triage batch](https://www.youtube.com/watch?v=9oWxrsRo4d8) — batch inbox triage/classify/route (Vogel demo; ~1500 emails in batches of 100)
- [Every mini vibe check](https://every.to/also-true-for-humans/mini-vibe-check-typesafe-s-jev-judged-everything-i-ve-written-in-0-7-seconds) — 21 AI-writing checks × 37 docs → 777 judgments in under 0.7s (~$0.0025)
