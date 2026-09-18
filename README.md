# Awesome Jev

What people built with Jev (TypeSafe System One). Showcase, not a tools directory.
Each line is a project and what Jev does inside it.

License: [CC0-1.0](LICENSE) (list copy only; linked projects keep their own licenses).

Source for the community batch: [X @0xlogicrw](https://x.com/0xlogicrw/status/2100478725393686556).

## Routing

- [Foreman](https://github.com/thruwire/foreman) — Jev on a Codex worker for semantic supervision on a factory floor
- [SemDecide](https://github.com/sharziki/semdecide) — Jev as a Unix CLI: classify, score, filter, and guard in scripts and CI
- [Jev Codex Router](https://github.com/0xNatoshi/jev-codex-router) — Jev scores how hard each coding turn is, then picks a cheap vs stronger model
- [safer-with-jev](https://github.com/andrelandgraf/safer-with-jev) — Jev classifies the task, then routes it to Grok or GPT (was typesafe-on-neon)
- [Lahfir harness router](https://x.com/mdlahfir/status/2100314182201802811) — Jev routes Claude Code / Codex / Opencode tasks by intensity (Haiku vs Opus sub-agents vs external harness)

## Refund review

- (none in this batch)

## Realtime

- [jev-ultrafast](https://github.com/browser-use/jev-ultrafast) — each step Jev picks the operation and the element from DOM state; small LLM only types; flight search demo 7s / $0.0039; [demo](https://x.com/gregpr07/status/2100411066966749359)
- [1v1 Jev](https://github.com/emrickgarrett/OneVOneJev) — Jev at about 9Hz picks move, aim, ADS, shoot, and jump
- [Playground](https://github.com/markjaquith/typesafe-ai-playground) — Jev experiments: PHI detect, comment review, live tone, job and industry classify
- [Prism](https://github.com/irfndi/prism-liquidity-agent) — Jev scores toxic flow, market stress, mean-reversion, and liquidity (shadow only, no live trades)
- [neo4jev](https://github.com/jexp/neo4jev) — Jev scores candidate graph edges, then beam-searches the likely path
- [jev-desktop](https://github.com/lahfir/agent-desktop) — Jev reads the Accessibility Tree and picks which control and which action
- [TypeSafe Mario](https://github.com/fhshaik/typesafe-mario) — Jev chooses NES controller macros from structured emulator state (Choice + Noul + Score); no screenshots
- [TypeSafe Computer Use](https://github.com/awlevin/typesafe-computer-use) — OCR reads the Mac screen; Jev picks the next UI action (~$0.0002/step); [demo thread](https://x.com/awlevin/status/2100262612428894676)
- [Kyle Jeong + Stagehand](https://x.com/kylejeong/status/2100622054945095934) — a11y tree as state; Jev picks the next browser action, Stagehand executes; ~$0.001/task, near-instant remote browser
- [jev-trader](https://github.com/jarrodwatts/jev-trader) — Jev watches the Kuru MON-USDC book and posts a post-only limit quote each Monad block (~300ms)
- [jev-drone](https://github.com/RomanSlack/jev-drone) — classical CV builds the scene; Jev picks maneuver / risk / lost-target at ~2.5Hz in MuJoCo
- [mobile-jev](https://github.com/droidrun/mobile-jev) — Jev chooses each Android UI action; Uber demo ~21s / 9 actions (to checkout, no purchase)

## Eval

- [Jev Review](https://github.com/devagrawal09/jev-review) — Jev pre-screens correctness, security, reliability, compatibility, and test risk before a heavier model
- [Paolo Rosson PR review](https://x.com/redp314/status/2100585126652481915) — paste a diff → one Jev/TypeSafe call → ~14 typed checks as probabilities → BLOCK / security review / nits / merge; ~$0.00007/PR
- [fx auto-review](https://x.com/fazxes/status/2100300097695232164) — Jev as the safety classifier for fx auto mode; ~5–18× faster and more accurate than GPT-5.6 Luna on their benchmark
- [pi-jev-auto-mode](https://github.com/jomatsu/pi-jev-auto-mode) — semantic allow/block on Pi bash/write/edit; fails closed when undecidable (~193–642ms)
- [jev-claude](https://github.com/takezou621/jev-claude) — Stop-hook asks if work is actually done → block & continue if not; optional bash triage

## Writing check
- [Human Compiler](https://github.com/asfarsadewa/human-compiler) — Jev scores prose for information density, clarity, hostility, and corporate tells, then the compiler emits rustc-style diagnostics
- [Jevibe Check](https://github.com/sriganesh/jevibe-check) — Jev labels drafts and posts for warmth, constructiveness, tension, sarcasm, clarity, and intent

## Tools

Official SDK / skill / Gateway / docs: [jev.gallery/tools](https://jev-gallery.pinto-cost.workers.dev/tools)

- [typesafe-mcp](https://github.com/itsmostafa/typesafe-mcp) — Jev as Choice / Score / Noul inside Claude Code, Desktop, and Codex
- [jev-mcp](https://github.com/jkudish/jev-mcp) — Jev as MCP tools: verify claims, screen prompt injection, rank by meaning
- [Blink](https://github.com/ellipsis-dev/blink) — at each directory level Jev scores which files or folders matter, then sends more walkers there
- [Winnow](https://github.com/GhalebDweikat/winnow) — Jev judges which Read / Bash / Grep output is actually relevant before it enters Claude Code context
- [fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction) — Jev scores each tool call/result (keep / truncate / drop) for Claude Code compaction; [demo](https://x.com/tamarajtran/status/2100694549362553153)
- [SkillRanker](https://github.com/Dicklesworthstone/skillranker) — Jev ranks which agent skills fit the next step from live session context (Choice + Noul; abstention when none fit)
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
- [WTF is Jev (9 builds)](https://x.com/i/article/2100772231462961152) — Matt Van Horn roundup of early builds (browser agent, compaction, fx, routing, RAG, games, email, batch eval, on-device); [thread](https://x.com/mvanhorn/status/2100788572316139655)
- [What people are wiring Jev into](https://x.com/i/article/2100863012357742592) — curator roundup by scene (routing, realtime, gates, batch eval, compaction, skills); [thread](https://x.com/oxwen11/status/2100863547009798235)
- [RAG chunk filter](https://x.com/kushbhuwalka/status/2100731050075050485) — per retrieved chunk, keep vs drop for precision (no author repo yet)
- [Minecraft realtime](https://x.com/wuyang_zhou/status/2100727660875808913) — Jev for fast realtime actions while a planner LLM plans (multi-zombie fight)
- [Email triage batch](https://www.youtube.com/watch?v=9oWxrsRo4d8) — batch inbox triage/classify/route (Vogel demo; ~1500 emails in batches of 100)
- [Every mini vibe check](https://every.to/also-true-for-humans/mini-vibe-check-typesafe-s-jev-judged-everything-i-ve-written-in-0-7-seconds) — 21 AI-writing checks × 37 docs → 777 judgments in under 0.7s (~$0.0025)
