# Curated Stars

Per-repo index of everything starred on [NovaLux12](https://github.com/NovaLux12?tab=stars), generated from the GitHub API and grouped by what each cluster is for.

**How this list works.** Reps get starred here so they are easy to raise in conversation later. The list is
curated in one direction only: things get *added* when they're interesting, and get *removed* when they've
been reviewed and found wanting. Low local adoption is expected and is not a defect — an adoption number
describes one deployment, not the worth of anything on the list. Nothing here is removed merely for being
unused.

**Activity state** is computed from the last commit to the default branch, not `pushed_at`, which is
inflated by branch pushes. That distinction matters: nine of these repos differ by more than 30 days
between the two measures.

**Regenerating.** The index is generated, not hand-maintained, so it does not rot between updates. The
generator lives outside this repo; the last regeneration is recorded in the header date.

---

_Generated 2026-10-06 from live GitHub API (172 repos). This is a **reference shelf**: repos get starred here so they're easy to raise in conversation later. Low local adoption is expected and is not a defect — a low adoption number describes the deployment, not the worth of anything on the list. What gets removed is anything reviewed and found wanting, not anything merely unused.

Regenerate: `python3 scripts/gh/build-star-index.py`  
Activity state uses the last commit to the **default branch**, not `pushed_at`, which is inflated by branch pushes.


## Legend

- **State** — `active` <30d · `cooling` 30–180d · `stale` 180–365d · `dormant` >365d
- **local** — confirmed installed/running in the live deployment (npm global, docker image, cron, or binary on PATH)
- **no licence** — flagged; prototype rather than usable tool


## Summary

| 172 repos | active 134 | cooling 21 | dormant 2 | stale 15 | local 29 | no-licence 7 |


## Worth asking about

Not a prune list — these are the ones with something to say when raised in conversation.

- **[thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)** — 97,064★ · Apache-2.0 · active · Persistent cross-session context. Storage model and forgetting/compression policy are the interesting read for the memory pipeline.
- **[headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom)** — 74,517★ · Apache-2.0 · active · Compresses tool output and RAG chunks before they hit the LLM (claims 20–95% reduction). Directly relevant to how we run.
- **[HKUDS/nanobot](https://github.com/HKUDS/nanobot)** — 48,826★ · MIT · active · Lightweight self-hosted agent framework with MCP + memory. Closest thing to our own stack worth studying.
- **[Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm)** — 66,759★ · MIT · active · Local-first RAG/agent platform. Good reference for self-hosting UX: compose file, swappable vector store, multi-workspace.
- **[backblaze-labs/b2-mcp](https://github.com/backblaze-labs/b2-mcp)** — 41★ · MIT · active · Official B2 MCP server — pairs with the backup stack we already run.
- **[github/spec-kit](https://github.com/github/spec-kit)** — 140,402★ · MIT · active · Spec-driven development toolkit. Useful as a process reference.


> **Archived:** [hishamhm/htop](https://github.com/hishamhm/htop) — 5,890★, last push 2020-11-17. Keep or drop at the curator's discretion.

> **No licence:** [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) — 797★. No explicit grant to use, modify or redistribute.

> **No licence:** [SafeAI-Lab-X/ClawKeeper](https://github.com/SafeAI-Lab-X/ClawKeeper) — 1,024★. No explicit grant to use, modify or redistribute.

> **No licence:** [CortexReach/memory-lancedb-pro](https://github.com/CortexReach/memory-lancedb-pro) — 4,452★. No explicit grant to use, modify or redistribute.

> **No licence:** [reflectt/agent-team-kit](https://github.com/reflectt/agent-team-kit) — 3★. No explicit grant to use, modify or redistribute.

> **No licence:** [reflectt/agent-autonomy-kit](https://github.com/reflectt/agent-autonomy-kit) — 6★. No explicit grant to use, modify or redistribute.

> **No licence:** [reflectt/agent-bridge-kit](https://github.com/reflectt/agent-bridge-kit) — 2★. No explicit grant to use, modify or redistribute.

> **No licence:** [reflectt/agent-memory-kit](https://github.com/reflectt/agent-memory-kit) — 5★. No explicit grant to use, modify or redistribute.

## OpenClaw ecosystem (29)

- **[openclaw/openclaw](https://github.com/openclaw/openclaw)** — 391,506★ · 1,721 watchers · MIT · active · starred 2026-06-21 · local  
  The AI that really does things. Any OS. Any Platform. The lobster way. 🦞
- **[VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills)** — 52,973★ · 315 watchers · MIT · active · starred 2026-06-22  
  The awesome collection of OpenClaw skills. 5,400+ skills filtered and categorized from the official OpenClaw Skills Regi
- **[HKUDS/nanobot](https://github.com/HKUDS/nanobot)** — 48,826★ · 219 watchers · MIT · active · starred 2026-08-08  
  Ultra-lightweight, open-source, self-hosted personal AI agent framework in Python with WebUI, tools, memory, MCP, multi-
- **[nanocoai/nanoclaw](https://github.com/nanocoai/nanoclaw)** — 30,881★ · 133 watchers · MIT · active · starred 2026-06-22  
  A lightweight alternative to OpenClaw that runs in containers for security. Connects to WhatsApp, Telegram, Slack, Disco
- **[openclaw/clawhub](https://github.com/openclaw/clawhub)** — 9,489★ · 64 watchers · MIT · active · starred 2026-06-22 · local  
  Skill + Plugin Registry for OpenClaw
- **[HKUDS/ClawWork](https://github.com/HKUDS/ClawWork)** — 8,551★ · 81 watchers · MIT · stale · starred 2026-06-22  
  "ClawWork: OpenClaw as Your AI Coworker - 💰 $15K earned in 11 Hours"
- **[ValueCell-ai/ClawX](https://github.com/ValueCell-ai/ClawX)** — 7,612★ · 49 watchers · MIT · active · starred 2026-06-22  
  ClawX is a desktop app that provides a graphical interface for OpenClaw AI agents. It turns CLI-based AI orchestration i
- **[openclaw/Peekaboo](https://github.com/openclaw/Peekaboo)** — 5,254★ · 17 watchers · MIT · active · starred 2026-06-22  
  Peekaboo is a macOS CLI & optional MCP server that enables AI agents to capture screenshots of applications, or the enti
- **[openclaw/mcporter](https://github.com/openclaw/mcporter)** — 5,050★ · 23 watchers · MIT · active · starred 2026-06-22 · local  
  Call MCPs via TypeScript, masquerading as simple TypeScript API. Or package them as cli.
- **[Martian-Engineering/lossless-claw](https://github.com/Martian-Engineering/lossless-claw)** — 4,901★ · 28 watchers · MIT · active · starred 2026-06-22  
  Lossless Claw — LCM (Lossless Context Management) plugin for OpenClaw
- **[mergisi/awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents)** — 3,994★ · 41 watchers · MIT · cooling · starred 2026-08-08  
  162 production-ready AI agent templates for OpenClaw. SOUL.md configs across 19 categories. Submit yours!
- **[openclaw/acpx](https://github.com/openclaw/acpx)** — 3,318★ · 19 watchers · MIT · active · starred 2026-06-22  
  Headless CLI client for stateful Agent Client Protocol (ACP) sessions
- **[DingTalk-Real-AI/dingtalk-openclaw-connector](https://github.com/DingTalk-Real-AI/dingtalk-openclaw-connector)** — 2,131★ · 11 watchers · MIT · cooling · starred 2026-06-22  
  Official OpenClaw DingTalk channel plugin \| 钉钉官方 OpenClaw 插件
- **[openclaw/imsg](https://github.com/openclaw/imsg)** — 1,353★ · 11 watchers · MIT · active · starred 2026-06-22  
  CLI for Apple's Messages.app so your agent can send and receive text messages/iMessages.
- **[openclaw/lobster](https://github.com/openclaw/lobster)** — 1,269★ · 19 watchers · MIT · active · starred 2026-06-22  
  Lobster is a Openclaw-native workflow shell: a typed, local-first “macro engine” that turns skills/tools into composable
- **[openclaw/agent-skills](https://github.com/openclaw/agent-skills)** — 1,102★ · 3 watchers · MIT · active · starred 2026-06-22  
  Useful skills for agents and claws.
- **[SafeAI-Lab-X/ClawKeeper](https://github.com/SafeAI-Lab-X/ClawKeeper)** — 1,024★ · 19 watchers · none · cooling · starred 2026-06-22 · no licence  
  ClawKeeper: Comprehensive Safety Protection for OpenClaw Agents Through Skills, Plugins, and Watchers (aka The Norton fo
- **[crabwise-ai/crabwalk](https://github.com/crabwise-ai/crabwalk)** — 874★ · 10 watchers · MIT · cooling · starred 2026-08-08  
  🦀 Crabwalk 🦀 Real-time companion monitor for OpenClaw agents.
- **[supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory)** — 797★ · 1 watchers · none · active · starred 2026-08-08 · no licence  
  OpenClaw Supermemory lets to have long-term memory and recall for your openclaw agent.
- **[alvinreal/awesome-openclaw](https://github.com/alvinreal/awesome-openclaw)** — 739★ · 6 watchers · CC0-1.0 · active · starred 2026-06-22  
  A curated list of the best OpenClaw resources: official projects, skills, plugins, dashboards, deployment tooling, memor
- **[comet-ml/opik-openclaw](https://github.com/comet-ml/opik-openclaw)** — 724★ · 8 watchers · Apache-2.0 · active · starred 2026-06-22  
  🦞 Official plugin for OpenClaw that exports agent traces to Opik. See and monitor agent behaviour, cost, tokens, errors
- **[win4r/openclaw-a2a-gateway](https://github.com/win4r/openclaw-a2a-gateway)** — 552★ · 4 watchers · MIT · cooling · starred 2026-06-22  
  OpenClaw plugin implementing the A2A (Agent-to-Agent) protocol v0.3.0 — bidirectional agent communication gateway
- **[mudrii/openclaw-dashboard](https://github.com/mudrii/openclaw-dashboard)** — 457★ · 4 watchers · MIT · active · starred 2026-06-21  
  A beautiful, zero-dependency command center for OpenClaw AI agents
- **[Signet-AI/signetai](https://github.com/Signet-AI/signetai)** — 303★ · 3 watchers · NOASSERTION · active · starred 2026-06-25  
  Sync and store memories, shared identity files (AGENTS.md, CLAUDE.md), session transcripts, institutional knowledge, and
- **[openclaw/crabfleet](https://github.com/openclaw/crabfleet)** — 238★ · 2 watchers · MIT · active · starred 2026-06-22  
  Mission control for agent runs.
- **[openclaw/shellbench](https://github.com/openclaw/shellbench)** — 141★ · 2 watchers · MIT · active · starred 2026-06-22  
  The agent benchmark that scores the full stack — harness, config, and model — not just the LLM. Trace-based scoring, rel
- **[Vorim-AI-Labs/vorim-openclaw-skill](https://github.com/Vorim-AI-Labs/vorim-openclaw-skill)** — 33★ · 0 watchers · MIT · cooling · starred 2026-06-25  
  Official OpenClaw Skill for Vorim AI — cryptographic identity, scoped permissions, and tamper-evident audit trails for O
- **[reflectt/agent-team-kit](https://github.com/reflectt/agent-team-kit)** — 3★ · 0 watchers · none · stale · starred 2026-06-22 · no licence  
  OpenClaw skill: Multi-agent team coordination with roles, intake, and backlog management
- **[reflectt/agent-bridge-kit](https://github.com/reflectt/agent-bridge-kit)** — 2★ · 0 watchers · none · stale · starred 2026-06-22 · no licence  
  Cross-platform presence for AI agents — post to Moltbook, read from forAgents.dev, aggregate feeds

## CLI & shell tooling (26)

- **[oven-sh/bun](https://github.com/oven-sh/bun)** — 96,140★ · 626 watchers · NOASSERTION · active · starred 2026-06-22 · local  
  Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one
- **[junegunn/fzf](https://github.com/junegunn/fzf)** — 83,404★ · 451 watchers · MIT · active · starred 2026-06-22 · local  
  :cherry_blossom: A command-line fuzzy finder
- **[jesseduffield/lazygit](https://github.com/jesseduffield/lazygit)** — 82,934★ · 338 watchers · MIT · active · starred 2026-06-22  
  simple terminal UI for git commands
- **[BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep)** — 68,886★ · 318 watchers · Unlicense · cooling · starred 2026-06-22  
  ripgrep recursively searches directories for a regex pattern while respecting your gitignore
- **[tldr-pages/tldr](https://github.com/tldr-pages/tldr)** — 63,830★ · 414 watchers · NOASSERTION · active · starred 2026-06-22  
  Collaborative cheatsheets for console commands 📚.
- **[ghostty-org/ghostty](https://github.com/ghostty-org/ghostty)** — 61,904★ · 219 watchers · MIT · active · starred 2026-06-22  
  👻 Ghostty is a fast, feature-rich, and cross-platform terminal emulator that uses platform-native UI and GPU acceleratio
- **[sharkdp/bat](https://github.com/sharkdp/bat)** — 60,690★ · 249 watchers · Apache-2.0 · active · starred 2026-06-22 · local  
  A cat(1) clone with wings.
- **[starship/starship](https://github.com/starship/starship)** — 60,172★ · 203 watchers · ISC · active · starred 2026-06-22  
  ☄🌌️  The minimal, blazing-fast, and infinitely customizable prompt for any shell!
- **[cli/cli](https://github.com/cli/cli)** — 46,559★ · 1,139 watchers · MIT · active · starred 2026-07-06 · local  
  GitHub’s official command line tool
- **[charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea)** — 45,305★ · 152 watchers · MIT · active · starred 2026-06-22  
  A powerful little TUI framework 🏗
- **[koalaman/shellcheck](https://github.com/koalaman/shellcheck)** — 40,140★ · 408 watchers · GPL-3.0 · active · starred 2026-06-22  
  ShellCheck, a static analysis tool for shell scripts
- **[ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide)** — 39,915★ · 81 watchers · MIT · active · starred 2026-06-22 · local  
  A smarter cd command. Supports all major shells.
- **[httpie/cli](https://github.com/httpie/cli)** — 38,734★ · 116 watchers · BSD-3-Clause · dormant · starred 2026-06-22 · local  
  🥧 HTTPie CLI  — modern, user-friendly command-line HTTP client for the API era. JSON support, colors, sessions, download
- **[pnpm/pnpm](https://github.com/pnpm/pnpm)** — 36,752★ · 164 watchers · MIT · active · starred 2026-06-22  
  Fast, disk space efficient package manager
- **[jdx/mise](https://github.com/jdx/mise)** — 34,656★ · 51 watchers · MIT · active · starred 2026-06-22  
  dev tools, env vars, task runner
- **[dandavison/delta](https://github.com/dandavison/delta)** — 32,429★ · 115 watchers · MIT · stale · starred 2026-06-22 · local  
  A syntax-highlighting pager for git, diff, grep, rg --json, and blame output
- **[atuinsh/atuin](https://github.com/atuinsh/atuin)** — 31,912★ · 80 watchers · MIT · active · starred 2026-06-22  
  ✨ Making your shell magical
- **[charmbracelet/glow](https://github.com/charmbracelet/glow)** — 27,596★ · 89 watchers · MIT · active · starred 2026-06-22 · local  
  Render markdown on the CLI, with pizzazz! 💅🏻
- **[eza-community/eza](https://github.com/eza-community/eza)** — 23,486★ · 40 watchers · EUPL-1.2 · cooling · starred 2026-06-22  
  A modern alternative to ls
- **[mobile-shell/mosh](https://github.com/mobile-shell/mosh)** — 14,548★ · 207 watchers · GPL-3.0 · stale · starred 2026-06-22  
  Mobile Shell
- **[charmbracelet/lipgloss](https://github.com/charmbracelet/lipgloss)** — 11,900★ · 42 watchers · MIT · active · starred 2026-06-22  
  Style definitions for nice terminal layouts 👄
- **[gokcehan/lf](https://github.com/gokcehan/lf)** — 9,535★ · 66 watchers · MIT · active · starred 2026-06-22 · local  
  Terminal file manager
- **[mvdan/sh](https://github.com/mvdan/sh)** — 9,113★ · 62 watchers · BSD-3-Clause · active · starred 2026-06-22 · local  
  A shell parser, formatter, and interpreter with bash and zsh support; includes shfmt
- **[MinishLab/semble](https://github.com/MinishLab/semble)** — 6,182★ · 18 watchers · MIT · active · starred 2026-08-02  
  Fast and Accurate Code Search for Agents. Uses 99% fewer tokens than grep+read
- **[hishamhm/htop](https://github.com/hishamhm/htop)** — 5,890★ · 3 watchers · GPL-2.0 · dormant · starred 2026-06-22 · **archived** · local  
  htop is an interactive text-mode process viewer for Unix systems. It aims to be a better 'top'.
- **[pluk-inc/markdown-preview](https://github.com/pluk-inc/markdown-preview)** — 2,447★ · 5 watchers · MIT · active · starred 2026-08-08  
  A simple Markdown viewer for reading .md files

## Agent frameworks & SDKs (21)

- **[Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** — 187,666★ · 1,540 watchers · NOASSERTION · active · starred 2026-06-22  
  AutoGPT is the vision of accessible AI for everyone, to use and to build on. Our mission is to provide the tools, so tha
- **[huggingface/transformers](https://github.com/huggingface/transformers)** — 166,998★ · 1,236 watchers · Apache-2.0 · active · starred 2026-06-22  
  🤗 Transformers: the model-definition framework for state-of-the-art machine learning models in text, vision, audio, and
- **[langchain-ai/langchain](https://github.com/langchain-ai/langchain)** — 147,496★ · 923 watchers · MIT · active · starred 2026-06-22  
  The agent engineering platform.
- **[OpenHands/OpenHands](https://github.com/OpenHands/OpenHands)** — 90,117★ · 495 watchers · MIT · active · starred 2026-06-22  
  🙌 OpenHands: AI-Driven Development
- **[headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom)** — 74,517★ · 218 watchers · Apache-2.0 · active · starred 2026-08-02  
  Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 20% fewer tokens for coding agents, 60-95%
- **[openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)** — 68,517★ · 465 watchers · Apache-2.0 · active · starred 2026-06-22  
  A coding agent for open models like Kimi K3 and GLM 5.3
- **[microsoft/autogen](https://github.com/microsoft/autogen)** — 61,271★ · 531 watchers · CC-BY-4.0 · stale · starred 2026-06-22  
  A programming framework for agentic AI
- **[crewAIInc/crewAI](https://github.com/crewAIInc/crewAI)** — 59,398★ · 398 watchers · MIT · active · starred 2026-06-22  
  Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers
- **[Aider-AI/aider](https://github.com/Aider-AI/aider)** — 49,398★ · 271 watchers · Apache-2.0 · cooling · starred 2026-06-22  
  aider is AI pair programming in your terminal
- **[sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills)** — 47,295★ · 325 watchers · MIT · active · starred 2026-08-02  
  AAS Core is the local, agent-first control plane for complete catalog discovery, agent-owned selection, stack validation
- **[stanfordnlp/dspy](https://github.com/stanfordnlp/dspy)** — 38,522★ · 218 watchers · MIT · active · starred 2026-06-22  
  DSPy: The framework for programming—not prompting—language models
- **[OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files)** — 27,308★ · 118 watchers · MIT · active · starred 2026-08-08  
  Persistent file-based planning for AI coding agents and long-running tasks. Crash-proof markdown plans, session recovery
- **[deepset-ai/haystack](https://github.com/deepset-ai/haystack)** — 26,684★ · 166 watchers · Apache-2.0 · active · starred 2026-06-22  
  Open-source AI orchestration framework for building context-engineered, production-ready LLM applications. Design modula
- **[SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent)** — 20,495★ · 112 watchers · MIT · cooling · starred 2026-06-22  
  SWE-agent takes a GitHub issue and tries to automatically fix it, using your LM of choice. It can also be employed for o
- **[pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai)** — 20,449★ · 123 watchers · MIT · active · starred 2026-06-22  
  How Python does AI. Agents, realtime voice, image generation, embeddings. Every model, every interface, typed end to end
- **[567-labs/instructor](https://github.com/567-labs/instructor)** — 13,981★ · 55 watchers · MIT · active · starred 2026-06-22  
  structured outputs for llms
- **[openchamber/openchamber](https://github.com/openchamber/openchamber)** — 11,210★ · 46 watchers · MIT · active · starred 2026-08-08  
  Agentic Development Environment based on OpenCode AI agent
- **[Enderfga/claw-orchestrator](https://github.com/Enderfga/claw-orchestrator)** — 586★ · 5 watchers · MIT · active · starred 2026-06-22  
  Run Claude Code, Codex, Antigravity, Cursor Agent and OpenCode as one runtime — persistent sessions, multi-agent council
- **[reflectt/agent-autonomy-kit](https://github.com/reflectt/agent-autonomy-kit)** — 6★ · 0 watchers · none · stale · starred 2026-06-22 · no licence  
  🚀 Stop waiting for prompts. Proactive work system for AI agents.
- **[reflectt/agent-identity-kit](https://github.com/reflectt/agent-identity-kit)** — 2★ · 0 watchers · MIT · stale · starred 2026-06-22  
  🪪 A portable identity standard for AI agents. agent.json tells the world about agents.
- **[reflectt/agent-production-kit](https://github.com/reflectt/agent-production-kit)** — 1★ · 0 watchers · MIT · stale · starred 2026-06-22  
  Governance-first framework for deploying AI agents to production. Policy engine, audit logging, identity system, and bou

## Other / uncategorised (19)

- **[yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp)** — 195,959★ · 958 watchers · Unlicense · active · starred 2026-06-22  
  A feature-rich command-line audio/video downloader
- **[github/spec-kit](https://github.com/github/spec-kit)** — 140,402★ · 717 watchers · MIT · active · starred 2026-08-13  
  💫 Toolkit to help you get started with SDD or any other process!
- **[nodejs/node](https://github.com/nodejs/node)** — 122,406★ · 3,017 watchers · NOASSERTION · active · starred 2026-06-22 · local  
  Node.js JavaScript runtime ✨🐢🚀✨
- **[PowerShell/PowerShell](https://github.com/PowerShell/PowerShell)** — 55,612★ · 1,454 watchers · MIT · active · starred 2026-08-16  
  PowerShell for every system!
- **[run-llama/llama_index](https://github.com/run-llama/llama_index)** — 52,422★ · 289 watchers · MIT · active · starred 2026-06-22  
  LlamaIndex is the document processing platform for AI
- **[tmux/tmux](https://github.com/tmux/tmux)** — 49,802★ · 489 watchers · ISC · active · starred 2026-06-22 · local  
  tmux source code
- **[sharkdp/fd](https://github.com/sharkdp/fd)** — 44,651★ · 155 watchers · Apache-2.0 · active · starred 2026-06-22 · local  
  A simple, fast and user-friendly alternative to 'find'
- **[langchain-ai/langgraph](https://github.com/langchain-ai/langgraph)** — 42,787★ · 189 watchers · MIT · active · starred 2026-06-22  
  Build resilient agents.
- **[jqlang/jq](https://github.com/jqlang/jq)** — 35,748★ · 357 watchers · NOASSERTION · active · starred 2026-06-22 · local  
  Command-line JSON processor
- **[MODSetter/SurfSense](https://github.com/MODSetter/SurfSense)** — 16,324★ · 90 watchers · NOASSERTION · active · starred 2026-08-08  
  Air gapped, privacy focused open source NotebookLM alternative. Join our Discord: https://discord.gg/ejRNvftDp9
- **[direnv/direnv](https://github.com/direnv/direnv)** — 15,492★ · 84 watchers · MIT · active · starred 2026-06-22  
  unclutter your .profile
- **[primer/octicons](https://github.com/primer/octicons)** — 8,765★ · 148 watchers · MIT · active · starred 2026-09-22  
  A scalable set of icons handcrafted with ❤️ by GitHub
- **[bookorbit/bookorbit](https://github.com/bookorbit/bookorbit)** — 5,230★ · 18 watchers · AGPL-3.0 · active · starred 2026-08-22  
  BookOrbit: Your Reading Space
- **[stevesolun/ctx](https://github.com/stevesolun/ctx)** — 588★ · 6 watchers · MIT · cooling · starred 2026-08-02  
  CTX Fit finds the cheapest AI coding setup that reliably works on your repository, then applies the winner as a reviewab
- **[frozenpepper/deepseek-and-destroy](https://github.com/frozenpepper/deepseek-and-destroy)** — 152★ · 1 watchers · MIT · cooling · starred 2026-08-05  
  —
- **[domien-f/carelink-bridge](https://github.com/domien-f/carelink-bridge)** — 24★ · 3 watchers · MIT · cooling · starred 2026-07-18  
  Bridge that sends Medtronic CareLink pump and CGM data to Nightscout by simulating the CareLink mobile app's OAuth2 auth
- **[Carme99/PresenceJam-Desktop](https://github.com/Carme99/PresenceJam-Desktop)** — 2★ · 0 watchers · MIT · active · starred 2026-10-06  
  Windows desktop app syncing Spotify now-playing to Microsoft Teams status messages via Graph API (Tauri 2 + Svelte 5)
- **[NovaLux12/carelink-bridge](https://github.com/NovaLux12/carelink-bridge)** — 2★ · 0 watchers · MIT · active · starred 2026-07-21  
  Community fork of domien-f/carelink-bridge — sends Medtronic CareLink pump + CGM data to Nightscout via OAuth2 mobile-ap
- **[NovaLux12/gh-digest](https://github.com/NovaLux12/gh-digest)** — 2★ · 0 watchers · MIT · active · starred 2026-07-06  
  🔍 gh-digest — summarise GitHub account activity across repos. Single static binary, zero runtime deps.

## Agent memory / recall (15)

- **[thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)** — 97,064★ · 307 watchers · Apache-2.0 · active · starred 2026-08-02  
  Persistent Context Across Sessions for Every Agent –  Captures everything your agent does during sessions, compresses it
- **[vllm-project/vllm](https://github.com/vllm-project/vllm)** — 93,284★ · 599 watchers · Apache-2.0 · active · starred 2026-06-22  
  A high-throughput and memory-efficient inference and serving engine for LLMs
- **[mem0ai/mem0](https://github.com/mem0ai/mem0)** — 66,671★ · 255 watchers · Apache-2.0 · active · starred 2026-06-22  
  The Memory Layer for AI Agents - Drop-in memory infrastructure for AI agents and apps. Context that persists. Built for
- **[vectorize-io/hindsight](https://github.com/vectorize-io/hindsight)** — 46,277★ · 94 watchers · MIT · active · starred 2026-08-02 · local  
  Hindsight: Agent Memory That Learns
- **[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** — 45,897★ · 183 watchers · MIT · active · starred 2026-08-02  
  High-performance code intelligence MCP server. Indexes codebases into a persistent knowledge graph — average repo in mil
- **[volcengine/OpenViking](https://github.com/volcengine/OpenViking)** — 39,305★ · 112 watchers · AGPL-3.0 · active · starred 2026-06-22  
  Self-evolving Context Database for AI Agents. Unify Agent Memory, Knowledge RAG and Skills.
- **[rohitg00/agentmemory](https://github.com/rohitg00/agentmemory)** — 29,182★ · 88 watchers · Apache-2.0 · active · starred 2026-08-08  
  #1 Persistent memory for AI coding agents based on real-world benchmarks
- **[gastownhall/beads](https://github.com/gastownhall/beads)** — 27,678★ · 94 watchers · MIT · active · starred 2026-08-08  
  Beads - A memory upgrade for your coding agent
- **[letta-ai/letta](https://github.com/letta-ai/letta)** — 25,049★ · 141 watchers · Apache-2.0 · active · starred 2026-06-22  
  Platform for stateful agents: AI with advanced memory that can learn and self-improve over time.
- **[Gentleman-Programming/engram](https://github.com/Gentleman-Programming/engram)** — 7,061★ · 37 watchers · MIT · active · starred 2026-08-08  
  Persistent memory system for AI coding agents. Agent-agnostic Go binary with SQLite + FTS5, MCP server, HTTP API, CLI, a
- **[CortexReach/memory-lancedb-pro](https://github.com/CortexReach/memory-lancedb-pro)** — 4,452★ · 16 watchers · none · active · starred 2026-06-22 · no licence  
  Enhanced LanceDB memory plugin for OpenClaw — Hybrid Retrieval (Vector + BM25), Cross-Encoder Rerank, Multi-Scope Isolat
- **[Goldentrii/AgentRecall-X](https://github.com/Goldentrii/AgentRecall-X)** — 371★ · 2 watchers · MIT · active · starred 2026-08-02  
  Correction-first persistent memory for AI agents. MCP server + SDK + CLI. Compounds across sessions.
- **[gavdalf/total-recall](https://github.com/gavdalf/total-recall)** — 274★ · 9 watchers · MIT · stale · starred 2026-08-08  
  Total Recall — Autonomous Agent Memory. The only memory system that watches on its own. Five-layer observational memory
- **[edwin-hao-ai/Awareness-Local](https://github.com/edwin-hao-ai/Awareness-Local)** — 199★ · 3 watchers · MIT · cooling · starred 2026-08-08  
  Local-first AI agent memory — one command, works offline, no account needed. Give your Claude Code, Cursor, Windsurf, Op
- **[reflectt/agent-memory-kit](https://github.com/reflectt/agent-memory-kit)** — 5★ · 0 watchers · none · stale · starred 2026-06-22 · no licence  
  🧠 3-layer memory system for AI agents. Stop forgetting how to do things.

## Runtimes & languages (12)

- **[microsoft/markitdown](https://github.com/microsoft/markitdown)** — 188,844★ · 591 watchers · MIT · active · starred 2026-09-07  
  Python tool for converting files and office documents to Markdown.
- **[rust-lang/rust](https://github.com/rust-lang/rust)** — 119,648★ · 1,549 watchers · Apache-2.0 · active · starred 2026-06-22  
  Empowering everyone to build reliable and efficient software.
- **[denoland/deno](https://github.com/denoland/deno)** — 108,684★ · 1,425 watchers · MIT · active · starred 2026-06-22  
  A modern runtime for JavaScript and TypeScript.
- **[astral-sh/uv](https://github.com/astral-sh/uv)** — 90,445★ · 186 watchers · Apache-2.0 · active · starred 2026-06-22 · local  
  An extremely fast Python package and project manager, written in Rust.
- **[python/cpython](https://github.com/python/cpython)** — 77,541★ · 1,652 watchers · NOASSERTION · active · starred 2026-06-22  
  The Python programming language
- **[openai/openai-python](https://github.com/openai/openai-python)** — 31,754★ · 400 watchers · Apache-2.0 · active · starred 2026-06-22  
  The official Python library for the OpenAI API
- **[AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi)** — 22,975★ · 84 watchers · Apache-2.0 · active · starred 2026-07-12  
  ⚡️A native, local-first alternative to Logitech Options+, written in Rust 🦀 — remap buttons, DPI, and SmartShift over HI
- **[bootandy/dust](https://github.com/bootandy/dust)** — 12,478★ · 39 watchers · Apache-2.0 · active · starred 2026-06-22  
  A more intuitive version of du in rust
- **[janet-lang/janet](https://github.com/janet-lang/janet)** — 4,440★ · 62 watchers · MIT · active · starred 2026-07-06  
  A dynamic language and bytecode vm
- **[anthropics/anthropic-sdk-python](https://github.com/anthropics/anthropic-sdk-python)** — 3,951★ · 182 watchers · MIT · active · starred 2026-06-22  
  —
- **[pypa/packaging](https://github.com/pypa/packaging)** — 752★ · 26 watchers · NOASSERTION · active · starred 2026-07-06  
  Core utilities for Python packages
- **[1mrnewton/cutlass](https://github.com/1mrnewton/cutlass)** — 58★ · 1 watchers · Apache-2.0 · cooling · starred 2026-07-09  
  An open-source Rust video editor where you edit by describing what you want.

## Local LLM + inference (9)

- **[ollama/ollama](https://github.com/ollama/ollama)** — 182,379★ · 1,019 watchers · MIT · active · starred 2026-06-22  
  Get up and running with Kimi, GLM, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma and other models.
- **[ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp)** — 130,491★ · 845 watchers · MIT · active · starred 2026-06-22  
  LLM inference in C/C++
- **[Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm)** — 66,759★ · 415 watchers · MIT · active · starred 2026-08-02  
  Stop renting your intelligence. Own it with AnythingLLM. Everything you need for a powerful local-first agent experience
- **[ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp)** — 54,173★ · 412 watchers · MIT · active · starred 2026-06-22  
  Port of OpenAI's Whisper model in C/C++
- **[JustVugg/colibri](https://github.com/JustVugg/colibri)** — 39,983★ · 322 watchers · Apache-2.0 · active · starred 2026-07-12  
  Run frontier MoE models on hardware you already own — pure C, zero deps, experts streamed from disk. Tiny engine, immens
- **[langfuse/langfuse](https://github.com/langfuse/langfuse)** — 35,440★ · 114 watchers · NOASSERTION · active · starred 2026-06-22  
  🪢 Open source agent evals & observability: Trace, evaluate, and improve LLM applications with one open platform.
- **[drumih/turbo-fieldfare](https://github.com/drumih/turbo-fieldfare)** — 6,866★ · 39 watchers · Apache-2.0 · active · starred 2026-08-07  
  Gemma 4 26B-A4B inference in ~2 GB of RAM on any M-series MacBook
- **[withcatai/node-llama-cpp](https://github.com/withcatai/node-llama-cpp)** — 2,186★ · 22 watchers · MIT · active · starred 2026-06-22 · local  
  Run AI models locally on your machine with node.js bindings for llama.cpp. Enforce a JSON schema on the model output on
- **[FuJacob/cotabby](https://github.com/FuJacob/cotabby)** — 1,060★ · 8 watchers · AGPL-3.0 · active · starred 2026-07-12  
  Cotabby is local AI autocomplete for your entire Mac. Open source. On device. Everywhere you type.

## Self-hosting + infra (9)

- **[immich-app/immich](https://github.com/immich-app/immich)** — 115,678★ · 360 watchers · AGPL-3.0 · active · starred 2026-07-27 · local  
  High performance self-hosted photo and video management solution.
- **[khoj-ai/khoj](https://github.com/khoj-ai/khoj)** — 37,576★ · 181 watchers · AGPL-3.0 · cooling · starred 2026-08-02  
  Your AI second brain. Self-hostable. Get answers from the web or your docs. Build custom agents, schedule automations, d
- **[tailscale/tailscale](https://github.com/tailscale/tailscale)** — 37,196★ · 242 watchers · BSD-3-Clause · active · starred 2026-07-27 · local  
  The easiest, most secure way to use WireGuard and 2FA.
- **[TabbyML/tabby](https://github.com/TabbyML/tabby)** — 33,901★ · 187 watchers · NOASSERTION · cooling · starred 2026-08-02  
  Self-hosted AI coding assistant
- **[valkey-io/valkey](https://github.com/valkey-io/valkey)** — 27,383★ · 137 watchers · BSD-3-Clause · active · starred 2026-07-06 · local  
  A flexible distributed key-value database that is optimized for caching and other realtime workloads.
- **[cloudflare/cloudflared](https://github.com/cloudflare/cloudflared)** — 16,043★ · 141 watchers · Apache-2.0 · active · starred 2026-07-27 · local  
  Cloudflare Tunnel client
- **[cloudflare/moltworker](https://github.com/cloudflare/moltworker)** — 9,950★ · 51 watchers · Apache-2.0 · stale · starred 2026-06-22  
  Run OpenClaw, (formerly Moltbot, formerly Clawdbot) on Cloudflare Workers
- **[jedisct1/dsvpn](https://github.com/jedisct1/dsvpn)** — 5,816★ · 110 watchers · MIT · active · starred 2026-07-06  
  A Dead Simple VPN.
- **[Control-D-Inc/ctrld](https://github.com/Control-D-Inc/ctrld)** — 900★ · 26 watchers · MIT · stale · starred 2026-07-20 · local  
  A highly configurable, multi-protocol DNS forwarding proxy

## MCP + agent protocol (8)

- **[microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp)** — 37,874★ · 152 watchers · Apache-2.0 · active · starred 2026-08-08  
  Playwright MCP server
- **[github/github-mcp-server](https://github.com/github/github-mcp-server)** — 33,407★ · 403 watchers · MIT · active · starred 2026-08-08  
  GitHub's official MCP Server
- **[PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp)** — 27,988★ · 124 watchers · Apache-2.0 · active · starred 2026-08-08  
  🚀 The fast, Pythonic way to build MCP servers and clients.
- **[googleapis/mcp-toolbox](https://github.com/googleapis/mcp-toolbox)** — 16,602★ · 94 watchers · Apache-2.0 · active · starred 2026-08-08  
  MCP Toolbox for Databases is an open source MCP server for databases.
- **[zilliztech/claude-context](https://github.com/zilliztech/claude-context)** — 12,589★ · 59 watchers · MIT · cooling · starred 2026-08-02  
  Code search MCP for Claude Code. Make entire codebase the context for any coding agent.
- **[Tencent/AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard)** — 6,764★ · 49 watchers · Apache-2.0 · active · starred 2026-06-22  
  A full-stack AI Red Teaming platform securing AI ecosystems via Agent Scan, Skills Scan, MCP scan, AI Infra scan and LLM
- **[backblaze-labs/b2-mcp](https://github.com/backblaze-labs/b2-mcp)** — 41★ · 1 watchers · MIT · active · starred 2026-09-10  
  MCP server for Backblaze B2 Cloud Storage: a focused, safe 40-tool surface (17 native B2 SDK, 19 S3 data-plane, 4 analyt
- **[apius-tech/Palo-MCP](https://github.com/apius-tech/Palo-MCP)** — 28★ · 3 watchers · MIT · active · starred 2026-07-13  
  PanOS MCP Server

## Adobe-alternative suite (6)

- **[storytold/photocraft](https://github.com/storytold/photocraft)** — 4,749★ · 18 watchers · Apache-2.0 · active · starred 2026-10-06  
  An open-source, clean-room reimplementation of Adobe Photoshop in pure Rust
- **[storytold/filmcraft](https://github.com/storytold/filmcraft)** — 1,243★ · 8 watchers · Apache-2.0 · active · starred 2026-10-06  
  An open-source, clean-room reimplementation of Adobe Premiere Pro built in pure Rust.
- **[storytold/lightcraft](https://github.com/storytold/lightcraft)** — 916★ · 6 watchers · Apache-2.0 · active · starred 2026-10-06  
  An open-source, clean-room reimplementation of Adobe Lightroom in pure Rust.
- **[storytold/printcraft](https://github.com/storytold/printcraft)** — 842★ · 3 watchers · Apache-2.0 · active · starred 2026-10-06  
  An open-source, clean-room reimplementation of Adobe Acrobat built in pure Rust
- **[storytold/vectorcraft](https://github.com/storytold/vectorcraft)** — 813★ · 6 watchers · Apache-2.0 · active · starred 2026-10-06  
  An open-source, clean-room reimplementation of Adobe Illustrator, built in pure Rust.
- **[storytold/effectcraft](https://github.com/storytold/effectcraft)** — 673★ · 7 watchers · Apache-2.0 · active · starred 2026-10-06  
  —

## Coding agents / harnesses (6)

- **[deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness)** — 244,547★ · 1,048 watchers · MIT · active · starred 2026-08-16  
  DeepSeek Harness: Everything is a Plugin.
- **[nexu-io/open-design](https://github.com/nexu-io/open-design)** — 99,697★ · 302 watchers · Apache-2.0 · active · starred 2026-08-02  
  🎨 Best DeepSeek Harness Design Plugin. The open-source Claude Design alternative. 🖥️ Local-first desktop app. 🖼️ Your co
- **[code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent)** — 69,843★ · 237 watchers · NOASSERTION · active · starred 2026-08-08  
  OmO: Just type "mass ulw" keyword with your prompt. Now you are the master of graph engineering.
- **[can1357/oh-my-pi](https://github.com/can1357/oh-my-pi)** — 34,472★ · 97 watchers · MIT · active · starred 2026-06-24  
  ⌥ Coding agent with the IDE wired in. Built by Stencil Labs.
- **[Kilo-Org/kilocode](https://github.com/Kilo-Org/kilocode)** — 27,509★ · 116 watchers · MIT · active · starred 2026-08-08  
  Kilo is the all-in-one agentic engineering platform. Build, ship, and iterate faster with the most popular open source c
- **[different-ai/openwork](https://github.com/different-ai/openwork)** — 23,911★ · 91 watchers · NOASSERTION · active · starred 2026-08-08  
  The open-source alternative to Claude Cowork (powered by opencode)

## Observability & ops (5)

- **[koala73/worldmonitor](https://github.com/koala73/worldmonitor)** — 87,898★ · 500 watchers · AGPL-3.0 · active · starred 2026-07-26 · local  
  Real-time global intelligence dashboard. AI-powered news aggregation, geopolitical monitoring, and infrastructure tracki
- **[sharkdp/hyperfine](https://github.com/sharkdp/hyperfine)** — 28,952★ · 109 watchers · Apache-2.0 · active · starred 2026-06-22  
  A command-line benchmarking tool
- **[Arize-ai/phoenix](https://github.com/Arize-ai/phoenix)** — 11,732★ · 61 watchers · NOASSERTION · active · starred 2026-06-22  
  AI Observability & Evaluation
- **[nightscout/cgm-remote-monitor](https://github.com/nightscout/cgm-remote-monitor)** — 2,836★ · 290 watchers · AGPL-3.0 · cooling · starred 2026-07-27  
  nightscout web monitor
- **[reflectt/agent-observability-kit](https://github.com/reflectt/agent-observability-kit)** — 2★ · 0 watchers · NOASSERTION · stale · starred 2026-06-22  
  Framework-agnostic observability for AI agents. Visual debugging like LangGraph Studio, but works with ANY framework.

## Web / browser / scraping (4)

- **[firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)** — 189,143★ · 485 watchers · AGPL-3.0 · active · starred 2026-08-10 · local  
  Supercharge your AI agents with data from the web and beyond. Building the library for superintelligence. 🔥
- **[browser-use/browser-use](https://github.com/browser-use/browser-use)** — 117,269★ · 476 watchers · MIT · active · starred 2026-06-22  
  Agents that use the browser.
- **[vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser)** — 43,567★ · 108 watchers · Apache-2.0 · active · starred 2026-07-26 · local  
  Browser automation CLI for AI agents
- **[0xMassi/webclaw](https://github.com/0xMassi/webclaw)** — 2,368★ · 11 watchers · AGPL-3.0 · active · starred 2026-08-02  
  Fast, local-first web content extraction for LLMs. Scrape, crawl, extract structured data — all from Rust. CLI, REST API

## Skills / prompt libraries (3)

- **[awesome-opencode/awesome-opencode](https://github.com/awesome-opencode/awesome-opencode)** — 10,499★ · 78 watchers · CC0-1.0 · cooling · starred 2026-08-08  
  A curated list of awesome plugins, themes, agents, projects, and resources for https://opencode.ai
- **[clawsouls/soulspec](https://github.com/clawsouls/soulspec)** — 22★ · 0 watchers · Apache-2.0 · cooling · starred 2026-06-25  
  The open standard for AI agent personas. One file. Persistent identity.
- **[reflectt/tdce-toolkit](https://github.com/reflectt/tdce-toolkit)** — 1★ · 0 watchers · MIT · stale · starred 2026-06-22  
  Test-Driven Context Engineering (TDCE) Toolkit: framework-agnostic tests for agent prompts/context
