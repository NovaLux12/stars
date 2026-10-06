# Curated Stars

<p align="center">
  <img src="./hero.jpg" alt="A dense bright core of points with scattered satellite clusters and one warm amber cluster standing apart" width="100%">
</p>

**A labelled shelf for 172 starred repos.**

> A star is a bookmark with no label. This repo is the label.

Repos land here when they're interesting and leave when they've been reviewed and found wanting. Running them was never the point - [it's a shelf](#the-shelf), and a low adoption number says something about the machine, not about the list.

[What's worth asking about](#worth-asking-about) - [The shelf](#the-shelf) - [Flags](#flags) - [Full record](nova-stars-index.md) (descriptions, watchers, star dates, all 172).

---

## Where things stand

**172** repos - **134** active - **21** cooling - **15** stale - **29** in use - **7** unlicensed - **1** archived

> [!NOTE]
> **Active** means a commit to the default branch in the last 30 days - deliberately not `pushed_at`, which branch pushes inflate. Nine of these repos differ by over a month between the two measures.

## Worth asking about

**[`thedotmack/claude-mem`](https://github.com/thedotmack/claude-mem)** - 97k* - Apache-2.0 - active  
Persistent cross-session context. Its storage model and forgetting/compression policy are the interesting read for the memory pipeline.

**[`headroomlabs-ai/headroom`](https://github.com/headroomlabs-ai/headroom)** - 75k* - Apache-2.0 - active  
Compresses tool output and RAG chunks before they hit the model. Claims 20-95% reduction; the claim is the thing worth testing.

**[`HKUDS/nanobot`](https://github.com/HKUDS/nanobot)** - 49k* - MIT - active  
Lightweight self-hosted agent framework with MCP and memory. Closest thing on this list to the stack this account actually runs.

**[`backblaze-labs/b2-mcp`](https://github.com/backblaze-labs/b2-mcp)** - 41* - MIT - active  
Official B2 MCP server - pairs with the backup stack already in use here.

**[`github/spec-kit`](https://github.com/github/spec-kit)** - 140k* - MIT - active  
Spec-driven development toolkit. Useful as a process reference.

**[`vectorize-io/hindsight`](https://github.com/vectorize-io/hindsight)** - 46k* - MIT - active  
The memory service actually in use here. Worth watching as a dependency rather than as a comparison.

## Flags

**1 archived** - starred, not used.
- [`hishamhm/htop`](https://github.com/hishamhm/htop) - 5k*, last push 2020-11-17

**7 with no licence** - no explicit grant to use, modify or redistribute, so they are prototypes rather than tools.
- [`supermemoryai/openclaw-supermemory`](https://github.com/supermemoryai/openclaw-supermemory) - 797*
- [`SafeAI-Lab-X/ClawKeeper`](https://github.com/SafeAI-Lab-X/ClawKeeper) - 1k*
- [`CortexReach/memory-lancedb-pro`](https://github.com/CortexReach/memory-lancedb-pro) - 4k*
- [`reflectt/agent-team-kit`](https://github.com/reflectt/agent-team-kit) - 3*
- [`reflectt/agent-autonomy-kit`](https://github.com/reflectt/agent-autonomy-kit) - 6*
- [`reflectt/agent-bridge-kit`](https://github.com/reflectt/agent-bridge-kit) - 2*
- [`reflectt/agent-memory-kit`](https://github.com/reflectt/agent-memory-kit) - 5*

## The shelf

Everything else, grouped by what it's for. Open a group to see it.

```
OpenClaw ecosystem ............████████████████████████████ 29
CLI & shell tooling ...........█████████████████████████ 26
Agent frameworks & SDKs .......████████████████████ 21
Other .........................██████████████████ 19
Agent memory / recall .........██████████████ 15
Runtimes & languages ..........████████████ 12
Local LLM + inference .........█████████ 9
Self-hosting + infra ..........█████████ 9
MCP + agent protocol ..........████████ 8
Adobe-alternative suite .......██████ 6
Coding agents / harnesses .....██████ 6
Observability & ops ...........█████ 5
Web / browser / scraping ......████ 4
Skills / prompt libraries .....███ 3
```

<details>
<summary><b>OpenClaw ecosystem</b> - 29</summary>

- [`openclaw/openclaw`](https://github.com/openclaw/openclaw) - 392k* | MIT | active - `in use` - The AI that really does things. Any OS. Any Platform. The lobster way
- [`VoltAgent/awesome-openclaw-skills`](https://github.com/VoltAgent/awesome-openclaw-skills) - 53k* | MIT | active - The awesome collection of OpenClaw skills. 5,400+ skills filtered and categorized from the
- [`HKUDS/nanobot`](https://github.com/HKUDS/nanobot) - 49k* | MIT | active - Ultra-lightweight, open-source, self-hosted personal AI agent framework in Python with
- [`nanocoai/nanoclaw`](https://github.com/nanocoai/nanoclaw) - 31k* | MIT | active - A lightweight alternative to OpenClaw that runs in containers for security. Connects to
- [`openclaw/clawhub`](https://github.com/openclaw/clawhub) - 9k* | MIT | active - `in use` - Skill + Plugin Registry for OpenClaw
- [`HKUDS/ClawWork`](https://github.com/HKUDS/ClawWork) - 8k* | MIT | stale - ClawWork: OpenClaw as Your AI Coworker - $15K earned in 11 Hours"
- [`ValueCell-ai/ClawX`](https://github.com/ValueCell-ai/ClawX) - 7k* | MIT | active - ClawX is a desktop app that provides a graphical interface for OpenClaw AI agents. It turns
- [`openclaw/Peekaboo`](https://github.com/openclaw/Peekaboo) - 5k* | MIT | active - Peekaboo is a macOS CLI & optional MCP server that enables AI agents to capture screenshots
- [`openclaw/mcporter`](https://github.com/openclaw/mcporter) - 5k* | MIT | active - `in use` - Call MCPs via TypeScript, masquerading as simple TypeScript API. Or package them as cli
- [`Martian-Engineering/lossless-claw`](https://github.com/Martian-Engineering/lossless-claw) - 4k* | MIT | active - Lossless Claw — LCM (Lossless Context Management) plugin for OpenClaw
- [`mergisi/awesome-openclaw-agents`](https://github.com/mergisi/awesome-openclaw-agents) - 3k* | MIT | cooling - 162 production-ready AI agent templates for OpenClaw. SOUL.md configs across 19 categories
- [`openclaw/acpx`](https://github.com/openclaw/acpx) - 3k* | MIT | active - Headless CLI client for stateful Agent Client Protocol (ACP) sessions
- [`DingTalk-Real-AI/dingtalk-openclaw-connector`](https://github.com/DingTalk-Real-AI/dingtalk-openclaw-connector) - 2k* | MIT | cooling - Official OpenClaw DingTalk channel plugin - 钉钉官方 OpenClaw 插件
- [`openclaw/imsg`](https://github.com/openclaw/imsg) - 1k* | MIT | active - CLI for Apple's Messages.app so your agent can send and receive text messages/iMessages
- [`openclaw/lobster`](https://github.com/openclaw/lobster) - 1k* | MIT | active - Lobster is a Openclaw-native workflow shell: a typed, local-first “macro engine” that turns
- [`openclaw/agent-skills`](https://github.com/openclaw/agent-skills) - 1k* | MIT | active - Useful skills for agents and claws
- [`SafeAI-Lab-X/ClawKeeper`](https://github.com/SafeAI-Lab-X/ClawKeeper) - 1k* | none | cooling - `no licence` - ClawKeeper: Comprehensive Safety Protection for OpenClaw Agents Through Skills, Plugins,
- [`crabwise-ai/crabwalk`](https://github.com/crabwise-ai/crabwalk) - 874* | MIT | cooling - Crabwalk Real-time companion monitor for OpenClaw agents
- [`supermemoryai/openclaw-supermemory`](https://github.com/supermemoryai/openclaw-supermemory) - 797* | none | active - `no licence` - OpenClaw Supermemory lets to have long-term memory and recall for your openclaw agent
- [`alvinreal/awesome-openclaw`](https://github.com/alvinreal/awesome-openclaw) - 739* | CC0-1.0 | active - A curated list of the best OpenClaw resources: official projects, skills, plugins,
- [`comet-ml/opik-openclaw`](https://github.com/comet-ml/opik-openclaw) - 724* | Apache-2.0 | active - Official plugin for OpenClaw that exports agent traces to Opik. See and monitor agent
- [`win4r/openclaw-a2a-gateway`](https://github.com/win4r/openclaw-a2a-gateway) - 552* | MIT | cooling - OpenClaw plugin implementing the A2A (Agent-to-Agent) protocol v0.3.0 — bidirectional agent
- [`mudrii/openclaw-dashboard`](https://github.com/mudrii/openclaw-dashboard) - 457* | MIT | active - A beautiful, zero-dependency command center for OpenClaw AI agents
- [`Signet-AI/signetai`](https://github.com/Signet-AI/signetai) - 303* | NOASSERTION | active - Sync and store memories, shared identity files (AGENTS.md, CLAUDE.md), session transcripts,
- [`openclaw/crabfleet`](https://github.com/openclaw/crabfleet) - 238* | MIT | active - Mission control for agent runs
- [`openclaw/shellbench`](https://github.com/openclaw/shellbench) - 141* | MIT | active - The agent benchmark that scores the full stack — harness, config, and model — not just the
- [`Vorim-AI-Labs/vorim-openclaw-skill`](https://github.com/Vorim-AI-Labs/vorim-openclaw-skill) - 33* | MIT | cooling - Official OpenClaw Skill for Vorim AI — cryptographic identity, scoped permissions, and
- [`reflectt/agent-team-kit`](https://github.com/reflectt/agent-team-kit) - 3* | none | stale - `no licence` - OpenClaw skill: Multi-agent team coordination with roles, intake, and backlog management
- [`reflectt/agent-bridge-kit`](https://github.com/reflectt/agent-bridge-kit) - 2* | none | stale - `no licence` - Cross-platform presence for AI agents — post to Moltbook, read from forAgents.dev,

</details>

<details>
<summary><b>CLI & shell tooling</b> - 26</summary>

- [`oven-sh/bun`](https://github.com/oven-sh/bun) - 96k* | NOASSERTION | active - `in use` - Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one
- [`junegunn/fzf`](https://github.com/junegunn/fzf) - 83k* | MIT | active - `in use` - A command-line fuzzy finder
- [`jesseduffield/lazygit`](https://github.com/jesseduffield/lazygit) - 83k* | MIT | active - simple terminal UI for git commands
- [`BurntSushi/ripgrep`](https://github.com/BurntSushi/ripgrep) - 69k* | Unlicense | cooling - ripgrep recursively searches directories for a regex pattern while respecting your gitignore
- [`tldr-pages/tldr`](https://github.com/tldr-pages/tldr) - 64k* | NOASSERTION | active - Collaborative cheatsheets for console commands
- [`ghostty-org/ghostty`](https://github.com/ghostty-org/ghostty) - 62k* | MIT | active - Ghostty is a fast, feature-rich, and cross-platform terminal emulator that uses
- [`sharkdp/bat`](https://github.com/sharkdp/bat) - 61k* | Apache-2.0 | active - `in use` - A cat(1) clone with wings
- [`starship/starship`](https://github.com/starship/starship) - 60k* | ISC | active - The minimal, blazing-fast, and infinitely customizable prompt for any shell!
- [`cli/cli`](https://github.com/cli/cli) - 47k* | MIT | active - `in use` - GitHub’s official command line tool
- [`charmbracelet/bubbletea`](https://github.com/charmbracelet/bubbletea) - 45k* | MIT | active - A powerful little TUI framework
- [`koalaman/shellcheck`](https://github.com/koalaman/shellcheck) - 40k* | GPL-3.0 | active - ShellCheck, a static analysis tool for shell scripts
- [`ajeetdsouza/zoxide`](https://github.com/ajeetdsouza/zoxide) - 40k* | MIT | active - `in use` - A smarter cd command. Supports all major shells
- [`httpie/cli`](https://github.com/httpie/cli) - 39k* | BSD-3-Clause | dormant - `in use` - HTTPie CLI — modern, user-friendly command-line HTTP client for the API era. JSON support,
- [`pnpm/pnpm`](https://github.com/pnpm/pnpm) - 37k* | MIT | active - Fast, disk space efficient package manager
- [`jdx/mise`](https://github.com/jdx/mise) - 35k* | MIT | active - dev tools, env vars, task runner
- [`dandavison/delta`](https://github.com/dandavison/delta) - 32k* | MIT | stale - `in use` - A syntax-highlighting pager for git, diff, grep, rg --json, and blame output
- [`atuinsh/atuin`](https://github.com/atuinsh/atuin) - 32k* | MIT | active - Making your shell magical
- [`charmbracelet/glow`](https://github.com/charmbracelet/glow) - 28k* | MIT | active - `in use` - Render markdown on the CLI, with pizzazz!
- [`eza-community/eza`](https://github.com/eza-community/eza) - 23k* | EUPL-1.2 | cooling - A modern alternative to ls
- [`mobile-shell/mosh`](https://github.com/mobile-shell/mosh) - 15k* | GPL-3.0 | stale - Mobile Shell
- [`charmbracelet/lipgloss`](https://github.com/charmbracelet/lipgloss) - 12k* | MIT | active - Style definitions for nice terminal layouts
- [`gokcehan/lf`](https://github.com/gokcehan/lf) - 9k* | MIT | active - `in use` - Terminal file manager
- [`mvdan/sh`](https://github.com/mvdan/sh) - 9k* | BSD-3-Clause | active - `in use` - A shell parser, formatter, and interpreter with bash and zsh support; includes shfmt
- [`MinishLab/semble`](https://github.com/MinishLab/semble) - 6k* | MIT | active - Fast and Accurate Code Search for Agents. Uses 99% fewer tokens than grep+read
- [`hishamhm/htop`](https://github.com/hishamhm/htop) - 5k* | GPL-2.0 | dormant - `archived` `in use` - htop is an interactive text-mode process viewer for Unix systems. It aims to be a better 'top'
- [`pluk-inc/markdown-preview`](https://github.com/pluk-inc/markdown-preview) - 2k* | MIT | active - A simple Markdown viewer for reading .md files

</details>

<details>
<summary><b>Agent frameworks & SDKs</b> - 21</summary>

- [`Significant-Gravitas/AutoGPT`](https://github.com/Significant-Gravitas/AutoGPT) - 188k* | NOASSERTION | active - AutoGPT is the vision of accessible AI for everyone, to use and to build on. Our mission is
- [`huggingface/transformers`](https://github.com/huggingface/transformers) - 167k* | Apache-2.0 | active - Transformers: the model-definition framework for state-of-the-art machine learning models
- [`langchain-ai/langchain`](https://github.com/langchain-ai/langchain) - 147k* | MIT | active - The agent engineering platform
- [`OpenHands/OpenHands`](https://github.com/OpenHands/OpenHands) - 90k* | MIT | active - OpenHands: AI-Driven Development
- [`headroomlabs-ai/headroom`](https://github.com/headroomlabs-ai/headroom) - 75k* | Apache-2.0 | active - Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 20% fewer
- [`openinterpreter/openinterpreter`](https://github.com/openinterpreter/openinterpreter) - 69k* | Apache-2.0 | active - A coding agent for open models like Kimi K3 and GLM 5.3
- [`microsoft/autogen`](https://github.com/microsoft/autogen) - 61k* | CC-BY-4.0 | stale - A programming framework for agentic AI
- [`crewAIInc/crewAI`](https://github.com/crewAIInc/crewAI) - 59k* | MIT | active - Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative
- [`Aider-AI/aider`](https://github.com/Aider-AI/aider) - 49k* | Apache-2.0 | cooling - aider is AI pair programming in your terminal
- [`sickn33/agentic-awesome-skills`](https://github.com/sickn33/agentic-awesome-skills) - 47k* | MIT | active - AAS Core is the local, agent-first control plane for complete catalog discovery,
- [`stanfordnlp/dspy`](https://github.com/stanfordnlp/dspy) - 39k* | MIT | active - DSPy: The framework for programming—not prompting—language models
- [`OthmanAdi/planning-with-files`](https://github.com/OthmanAdi/planning-with-files) - 27k* | MIT | active - Persistent file-based planning for AI coding agents and long-running tasks. Crash-proof
- [`deepset-ai/haystack`](https://github.com/deepset-ai/haystack) - 27k* | Apache-2.0 | active - Open-source AI orchestration framework for building context-engineered, production-ready
- [`SWE-agent/SWE-agent`](https://github.com/SWE-agent/SWE-agent) - 20k* | MIT | cooling - SWE-agent takes a GitHub issue and tries to automatically fix it, using your LM of choice
- [`pydantic/pydantic-ai`](https://github.com/pydantic/pydantic-ai) - 20k* | MIT | active - How Python does AI. Agents, realtime voice, image generation, embeddings. Every model,
- [`567-labs/instructor`](https://github.com/567-labs/instructor) - 14k* | MIT | active - structured outputs for llms
- [`openchamber/openchamber`](https://github.com/openchamber/openchamber) - 11k* | MIT | active - Agentic Development Environment based on OpenCode AI agent
- [`Enderfga/claw-orchestrator`](https://github.com/Enderfga/claw-orchestrator) - 586* | MIT | active - Run Claude Code, Codex, Antigravity, Cursor Agent and OpenCode as one runtime — persistent
- [`reflectt/agent-autonomy-kit`](https://github.com/reflectt/agent-autonomy-kit) - 6* | none | stale - `no licence` - Stop waiting for prompts. Proactive work system for AI agents
- [`reflectt/agent-identity-kit`](https://github.com/reflectt/agent-identity-kit) - 2* | MIT | stale - A portable identity standard for AI agents. agent.json tells the world about agents
- [`reflectt/agent-production-kit`](https://github.com/reflectt/agent-production-kit) - 1* | MIT | stale - Governance-first framework for deploying AI agents to production. Policy engine, audit

</details>

<details>
<summary><b>Other</b> - 19</summary>

- [`yt-dlp/yt-dlp`](https://github.com/yt-dlp/yt-dlp) - 196k* | Unlicense | active - A feature-rich command-line audio/video downloader
- [`github/spec-kit`](https://github.com/github/spec-kit) - 140k* | MIT | active - Toolkit to help you get started with SDD or any other process!
- [`nodejs/node`](https://github.com/nodejs/node) - 122k* | NOASSERTION | active - `in use` - Node.js JavaScript runtime
- [`PowerShell/PowerShell`](https://github.com/PowerShell/PowerShell) - 56k* | MIT | active - PowerShell for every system!
- [`run-llama/llama_index`](https://github.com/run-llama/llama_index) - 52k* | MIT | active - LlamaIndex is the document processing platform for AI
- [`tmux/tmux`](https://github.com/tmux/tmux) - 50k* | ISC | active - `in use` - tmux source code
- [`sharkdp/fd`](https://github.com/sharkdp/fd) - 45k* | Apache-2.0 | active - `in use` - A simple, fast and user-friendly alternative to 'find'
- [`langchain-ai/langgraph`](https://github.com/langchain-ai/langgraph) - 43k* | MIT | active - Build resilient agents
- [`jqlang/jq`](https://github.com/jqlang/jq) - 36k* | NOASSERTION | active - `in use` - Command-line JSON processor
- [`MODSetter/SurfSense`](https://github.com/MODSetter/SurfSense) - 16k* | NOASSERTION | active - Air gapped, privacy focused open source NotebookLM alternative. Join our Discord:
- [`direnv/direnv`](https://github.com/direnv/direnv) - 15k* | MIT | active - unclutter your .profile
- [`primer/octicons`](https://github.com/primer/octicons) - 8k* | MIT | active - A scalable set of icons handcrafted with by GitHub
- [`bookorbit/bookorbit`](https://github.com/bookorbit/bookorbit) - 5k* | AGPL-3.0 | active - BookOrbit: Your Reading Space
- [`stevesolun/ctx`](https://github.com/stevesolun/ctx) - 588* | MIT | cooling - CTX Fit finds the cheapest AI coding setup that reliably works on your repository, then
- [`frozenpepper/deepseek-and-destroy`](https://github.com/frozenpepper/deepseek-and-destroy) - 152* | MIT | cooling
- [`domien-f/carelink-bridge`](https://github.com/domien-f/carelink-bridge) - 24* | MIT | cooling - Bridge that sends Medtronic CareLink pump and CGM data to Nightscout by simulating the
- [`Carme99/PresenceJam-Desktop`](https://github.com/Carme99/PresenceJam-Desktop) - 2* | MIT | active - Windows desktop app syncing Spotify now-playing to Microsoft Teams status messages via
- [`NovaLux12/carelink-bridge`](https://github.com/NovaLux12/carelink-bridge) - 2* | MIT | active - Community fork of domien-f/carelink-bridge — sends Medtronic CareLink pump + CGM data to
- [`NovaLux12/gh-digest`](https://github.com/NovaLux12/gh-digest) - 2* | MIT | active - gh-digest — summarise GitHub account activity across repos. Single static binary, zero

</details>

<details>
<summary><b>Agent memory / recall</b> - 15</summary>

- [`thedotmack/claude-mem`](https://github.com/thedotmack/claude-mem) - 97k* | Apache-2.0 | active - Persistent Context Across Sessions for Every Agent – Captures everything your agent does
- [`vllm-project/vllm`](https://github.com/vllm-project/vllm) - 93k* | Apache-2.0 | active - A high-throughput and memory-efficient inference and serving engine for LLMs
- [`mem0ai/mem0`](https://github.com/mem0ai/mem0) - 67k* | Apache-2.0 | active - The Memory Layer for AI Agents - Drop-in memory infrastructure for AI agents and apps
- [`vectorize-io/hindsight`](https://github.com/vectorize-io/hindsight) - 46k* | MIT | active - `in use` - Hindsight: Agent Memory That Learns
- [`DeusData/codebase-memory-mcp`](https://github.com/DeusData/codebase-memory-mcp) - 46k* | MIT | active - High-performance code intelligence MCP server. Indexes codebases into a persistent
- [`volcengine/OpenViking`](https://github.com/volcengine/OpenViking) - 39k* | AGPL-3.0 | active - Self-evolving Context Database for AI Agents. Unify Agent Memory, Knowledge RAG and Skills
- [`rohitg00/agentmemory`](https://github.com/rohitg00/agentmemory) - 29k* | Apache-2.0 | active - 1 Persistent memory for AI coding agents based on real-world benchmarks
- [`gastownhall/beads`](https://github.com/gastownhall/beads) - 28k* | MIT | active - Beads - A memory upgrade for your coding agent
- [`letta-ai/letta`](https://github.com/letta-ai/letta) - 25k* | Apache-2.0 | active - Platform for stateful agents: AI with advanced memory that can learn and self-improve over
- [`Gentleman-Programming/engram`](https://github.com/Gentleman-Programming/engram) - 7k* | MIT | active - Persistent memory system for AI coding agents. Agent-agnostic Go binary with SQLite + FTS5,
- [`CortexReach/memory-lancedb-pro`](https://github.com/CortexReach/memory-lancedb-pro) - 4k* | none | active - `no licence` - Enhanced LanceDB memory plugin for OpenClaw — Hybrid Retrieval (Vector + BM25),
- [`Goldentrii/AgentRecall-X`](https://github.com/Goldentrii/AgentRecall-X) - 371* | MIT | active - Correction-first persistent memory for AI agents. MCP server + SDK + CLI. Compounds across
- [`gavdalf/total-recall`](https://github.com/gavdalf/total-recall) - 274* | MIT | stale - Total Recall — Autonomous Agent Memory. The only memory system that watches on its own
- [`edwin-hao-ai/Awareness-Local`](https://github.com/edwin-hao-ai/Awareness-Local) - 199* | MIT | cooling - Local-first AI agent memory — one command, works offline, no account needed. Give your
- [`reflectt/agent-memory-kit`](https://github.com/reflectt/agent-memory-kit) - 5* | none | stale - `no licence` - 3-layer memory system for AI agents. Stop forgetting how to do things

</details>

<details>
<summary><b>Runtimes & languages</b> - 12</summary>

- [`microsoft/markitdown`](https://github.com/microsoft/markitdown) - 189k* | MIT | active - Python tool for converting files and office documents to Markdown
- [`rust-lang/rust`](https://github.com/rust-lang/rust) - 120k* | Apache-2.0 | active - Empowering everyone to build reliable and efficient software
- [`denoland/deno`](https://github.com/denoland/deno) - 109k* | MIT | active - A modern runtime for JavaScript and TypeScript
- [`astral-sh/uv`](https://github.com/astral-sh/uv) - 90k* | Apache-2.0 | active - `in use` - An extremely fast Python package and project manager, written in Rust
- [`python/cpython`](https://github.com/python/cpython) - 78k* | NOASSERTION | active - The Python programming language
- [`openai/openai-python`](https://github.com/openai/openai-python) - 32k* | Apache-2.0 | active - The official Python library for the OpenAI API
- [`AprilNEA/OpenLogi`](https://github.com/AprilNEA/OpenLogi) - 23k* | Apache-2.0 | active - A native, local-first alternative to Logitech Options+, written in Rust — remap buttons,
- [`bootandy/dust`](https://github.com/bootandy/dust) - 12k* | Apache-2.0 | active - A more intuitive version of du in rust
- [`janet-lang/janet`](https://github.com/janet-lang/janet) - 4k* | MIT | active - A dynamic language and bytecode vm
- [`anthropics/anthropic-sdk-python`](https://github.com/anthropics/anthropic-sdk-python) - 3k* | MIT | active
- [`pypa/packaging`](https://github.com/pypa/packaging) - 752* | NOASSERTION | active - Core utilities for Python packages
- [`1mrnewton/cutlass`](https://github.com/1mrnewton/cutlass) - 58* | Apache-2.0 | cooling - An open-source Rust video editor where you edit by describing what you want

</details>

<details>
<summary><b>Local LLM + inference</b> - 9</summary>

- [`ollama/ollama`](https://github.com/ollama/ollama) - 182k* | MIT | active - Get up and running with Kimi, GLM, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma and other models
- [`ggml-org/llama.cpp`](https://github.com/ggml-org/llama.cpp) - 130k* | MIT | active - LLM inference in C/C++
- [`Mintplex-Labs/anything-llm`](https://github.com/Mintplex-Labs/anything-llm) - 67k* | MIT | active - Stop renting your intelligence. Own it with AnythingLLM. Everything you need for a powerful
- [`ggml-org/whisper.cpp`](https://github.com/ggml-org/whisper.cpp) - 54k* | MIT | active - Port of OpenAI's Whisper model in C/C++
- [`JustVugg/colibri`](https://github.com/JustVugg/colibri) - 40k* | Apache-2.0 | active - Run frontier MoE models on hardware you already own — pure C, zero deps, experts streamed
- [`langfuse/langfuse`](https://github.com/langfuse/langfuse) - 35k* | NOASSERTION | active - Open source agent evals & observability: Trace, evaluate, and improve LLM applications with
- [`drumih/turbo-fieldfare`](https://github.com/drumih/turbo-fieldfare) - 6k* | Apache-2.0 | active - Gemma 4 26B-A4B inference in ~2 GB of RAM on any M-series MacBook
- [`withcatai/node-llama-cpp`](https://github.com/withcatai/node-llama-cpp) - 2k* | MIT | active - `in use` - Run AI models locally on your machine with node.js bindings for llama.cpp. Enforce a JSON
- [`FuJacob/cotabby`](https://github.com/FuJacob/cotabby) - 1k* | AGPL-3.0 | active - Cotabby is local AI autocomplete for your entire Mac. Open source. On device. Everywhere

</details>

<details>
<summary><b>Self-hosting + infra</b> - 9</summary>

- [`immich-app/immich`](https://github.com/immich-app/immich) - 116k* | AGPL-3.0 | active - `in use` - High performance self-hosted photo and video management solution
- [`khoj-ai/khoj`](https://github.com/khoj-ai/khoj) - 38k* | AGPL-3.0 | cooling - Your AI second brain. Self-hostable. Get answers from the web or your docs. Build custom
- [`tailscale/tailscale`](https://github.com/tailscale/tailscale) - 37k* | BSD-3-Clause | active - `in use` - The easiest, most secure way to use WireGuard and 2FA
- [`TabbyML/tabby`](https://github.com/TabbyML/tabby) - 34k* | NOASSERTION | cooling - Self-hosted AI coding assistant
- [`valkey-io/valkey`](https://github.com/valkey-io/valkey) - 27k* | BSD-3-Clause | active - `in use` - A flexible distributed key-value database that is optimized for caching and other realtime
- [`cloudflare/cloudflared`](https://github.com/cloudflare/cloudflared) - 16k* | Apache-2.0 | active - `in use` - Cloudflare Tunnel client
- [`cloudflare/moltworker`](https://github.com/cloudflare/moltworker) - 9k* | Apache-2.0 | stale - Run OpenClaw, (formerly Moltbot, formerly Clawdbot) on Cloudflare Workers
- [`jedisct1/dsvpn`](https://github.com/jedisct1/dsvpn) - 5k* | MIT | active - A Dead Simple VPN
- [`Control-D-Inc/ctrld`](https://github.com/Control-D-Inc/ctrld) - 900* | MIT | stale - `in use` - A highly configurable, multi-protocol DNS forwarding proxy

</details>

<details>
<summary><b>MCP + agent protocol</b> - 8</summary>

- [`microsoft/playwright-mcp`](https://github.com/microsoft/playwright-mcp) - 38k* | Apache-2.0 | active - Playwright MCP server
- [`github/github-mcp-server`](https://github.com/github/github-mcp-server) - 33k* | MIT | active - GitHub's official MCP Server
- [`PrefectHQ/fastmcp`](https://github.com/PrefectHQ/fastmcp) - 28k* | Apache-2.0 | active - The fast, Pythonic way to build MCP servers and clients
- [`googleapis/mcp-toolbox`](https://github.com/googleapis/mcp-toolbox) - 17k* | Apache-2.0 | active - MCP Toolbox for Databases is an open source MCP server for databases
- [`zilliztech/claude-context`](https://github.com/zilliztech/claude-context) - 13k* | MIT | cooling - Code search MCP for Claude Code. Make entire codebase the context for any coding agent
- [`Tencent/AI-Infra-Guard`](https://github.com/Tencent/AI-Infra-Guard) - 6k* | Apache-2.0 | active - A full-stack AI Red Teaming platform securing AI ecosystems via Agent Scan, Skills Scan,
- [`backblaze-labs/b2-mcp`](https://github.com/backblaze-labs/b2-mcp) - 41* | MIT | active - MCP server for Backblaze B2 Cloud Storage: a focused, safe 40-tool surface (17 native B2
- [`apius-tech/Palo-MCP`](https://github.com/apius-tech/Palo-MCP) - 28* | MIT | active - PanOS MCP Server

</details>

<details>
<summary><b>Adobe-alternative suite</b> - 6</summary>

- [`storytold/photocraft`](https://github.com/storytold/photocraft) - 4k* | Apache-2.0 | active - An open-source, clean-room reimplementation of Adobe Photoshop in pure Rust
- [`storytold/filmcraft`](https://github.com/storytold/filmcraft) - 1k* | Apache-2.0 | active - An open-source, clean-room reimplementation of Adobe Premiere Pro built in pure Rust
- [`storytold/lightcraft`](https://github.com/storytold/lightcraft) - 916* | Apache-2.0 | active - An open-source, clean-room reimplementation of Adobe Lightroom in pure Rust
- [`storytold/printcraft`](https://github.com/storytold/printcraft) - 842* | Apache-2.0 | active - An open-source, clean-room reimplementation of Adobe Acrobat built in pure Rust
- [`storytold/vectorcraft`](https://github.com/storytold/vectorcraft) - 813* | Apache-2.0 | active - An open-source, clean-room reimplementation of Adobe Illustrator, built in pure Rust
- [`storytold/effectcraft`](https://github.com/storytold/effectcraft) - 673* | Apache-2.0 | active

</details>

<details>
<summary><b>Coding agents / harnesses</b> - 6</summary>

- [`deepseek-ai/deepseek-harness`](https://github.com/deepseek-ai/deepseek-harness) - 245k* | MIT | active - DeepSeek Harness: Everything is a Plugin
- [`nexu-io/open-design`](https://github.com/nexu-io/open-design) - 100k* | Apache-2.0 | active - Best DeepSeek Harness Design Plugin. The open-source Claude Design alternative. Local-first
- [`code-yeongyu/oh-my-openagent`](https://github.com/code-yeongyu/oh-my-openagent) - 70k* | NOASSERTION | active - OmO: Just type "mass ulw" keyword with your prompt. Now you are the master of graph
- [`can1357/oh-my-pi`](https://github.com/can1357/oh-my-pi) - 34k* | MIT | active - Coding agent with the IDE wired in. Built by Stencil Labs
- [`Kilo-Org/kilocode`](https://github.com/Kilo-Org/kilocode) - 28k* | MIT | active - Kilo is the all-in-one agentic engineering platform. Build, ship, and iterate faster with
- [`different-ai/openwork`](https://github.com/different-ai/openwork) - 24k* | NOASSERTION | active - The open-source alternative to Claude Cowork (powered by opencode)

</details>

<details>
<summary><b>Observability & ops</b> - 5</summary>

- [`koala73/worldmonitor`](https://github.com/koala73/worldmonitor) - 88k* | AGPL-3.0 | active - `in use` - Real-time global intelligence dashboard. AI-powered news aggregation, geopolitical
- [`sharkdp/hyperfine`](https://github.com/sharkdp/hyperfine) - 29k* | Apache-2.0 | active - A command-line benchmarking tool
- [`Arize-ai/phoenix`](https://github.com/Arize-ai/phoenix) - 12k* | NOASSERTION | active - AI Observability & Evaluation
- [`nightscout/cgm-remote-monitor`](https://github.com/nightscout/cgm-remote-monitor) - 2k* | AGPL-3.0 | cooling - nightscout web monitor
- [`reflectt/agent-observability-kit`](https://github.com/reflectt/agent-observability-kit) - 2* | NOASSERTION | stale - Framework-agnostic observability for AI agents. Visual debugging like LangGraph Studio, but

</details>

<details>
<summary><b>Web / browser / scraping</b> - 4</summary>

- [`firecrawl/firecrawl`](https://github.com/firecrawl/firecrawl) - 189k* | AGPL-3.0 | active - `in use` - Supercharge your AI agents with data from the web and beyond. Building the library for
- [`browser-use/browser-use`](https://github.com/browser-use/browser-use) - 117k* | MIT | active - Agents that use the browser
- [`vercel-labs/agent-browser`](https://github.com/vercel-labs/agent-browser) - 44k* | Apache-2.0 | active - `in use` - Browser automation CLI for AI agents
- [`0xMassi/webclaw`](https://github.com/0xMassi/webclaw) - 2k* | AGPL-3.0 | active - Fast, local-first web content extraction for LLMs. Scrape, crawl, extract structured data —

</details>

<details>
<summary><b>Skills / prompt libraries</b> - 3</summary>

- [`awesome-opencode/awesome-opencode`](https://github.com/awesome-opencode/awesome-opencode) - 10k* | CC0-1.0 | cooling - A curated list of awesome plugins, themes, agents, projects, and resources for
- [`clawsouls/soulspec`](https://github.com/clawsouls/soulspec) - 22* | Apache-2.0 | cooling - The open standard for AI agent personas. One file. Persistent identity
- [`reflectt/tdce-toolkit`](https://github.com/reflectt/tdce-toolkit) - 1* | MIT | stale - Test-Driven Context Engineering (TDCE) Toolkit: framework-agnostic tests for agent

</details>

---

_Generated 2026-10-06 from the GitHub API. Regenerate rather than hand-editing - the next run overwrites the edit._

