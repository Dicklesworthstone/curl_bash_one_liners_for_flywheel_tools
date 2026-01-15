<div align="center">

# Quick Curl Bash One-Liners for My Tools

[![GitHub](https://img.shields.io/badge/GitHub-Dicklesworthstone-181717?style=for-the-badge&logo=github)](https://github.com/Dicklesworthstone)
[![X (Twitter)](https://img.shields.io/badge/X-@doodlestein-000000?style=for-the-badge&logo=x)](https://x.com/doodlestein)
[![Discord](https://img.shields.io/badge/Discord-Flywheel_Hub-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://t.co/kGjc2TQptc)

<br>

![Tools](https://img.shields.io/badge/Tools-23-blue?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20macOS-lightgrey?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**One-liner installation commands for the Agent Flywheel ecosystem.**<br>
All commands use non-interactive modes and include cache busters for fresh downloads.

[AI Orchestration](#-ai-agent-orchestration) · [Memory & Search](#-memory--search) · [Security](#-security--safety) · [Dev Tools](#-developer-tools) · [Prompts](#-prompts--skills) · [Specialized](#-specialized-tools)

</div>

---

> [!TIP]
> **New to the ecosystem?** Start with [ACFS](#acfs) to install everything at once, or pick individual tools below.

---

## 🤖 AI Agent Orchestration

Tools for spawning, managing, and coordinating multiple AI coding agents.

| Tool | One-Liner | Description |
|:-----|:----------|:------------|
| <a id="acfs"></a>**[ACFS](https://github.com/Dicklesworthstone/agentic_coding_flywheel_setup)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/agentic_coding_flywheel_setup/main/install.sh?$(date +%s)" \| bash -s -- --yes --mode vibe` | Sets up 30+ tools for multi-agent AI coding workflows including three AI coding agents and all dependencies. |
| **[NTM](https://github.com/Dicklesworthstone/ntm)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/ntm/main/install.sh?$(date +%s)" \| bash -s -- --easy-mode` | Powerful tmux session management for orchestrating multiple AI coding agents across tiled panes with command palette. |
| **[Useful Tmux](https://github.com/Dicklesworthstone/useful_tmux_commands)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/useful_tmux_commands/main/add_useful_tmux_commands_to_zshrc.sh?$(date +%s)" \| bash -s -- --easy` | Tmux session management toolkit with shell functions for orchestrating AI coding agents, spawning sessions, and broadcasting prompts. |
| **[Brenner Bot](https://github.com/Dicklesworthstone/brenner_bot)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/brenner_bot/main/install.sh?$(date +%s)" \| bash -s -- --easy-mode --verify` | AI coding agent framework with easy-mode installation providing minimal prompts and sensible defaults. |
| **[Agent Flywheel Skills](https://github.com/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations/main/install.sh?$(date +%s)" \| bash -s -- --all` | Installs all Clawdbot skills for workflow automation, cloud tools, and development utilities in one command. |

---

## 🧠 Memory & Search

Persistent memory and cross-agent session search capabilities.

| Tool | One-Liner | Description |
|:-----|:----------|:------------|
| **[CASS](https://github.com/Dicklesworthstone/coding_agent_session_search)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/coding_agent_session_search/main/install.sh?$(date +%s)" \| bash -s -- --easy-mode --verify` | TUI for searching unified history across multiple coding agents (Claude Code, Codex, Gemini, etc.) with semantic search. |
| **[CASS Memory](https://github.com/Dicklesworthstone/cass_memory_system)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/cass_memory_system/main/install.sh?$(date +%s)" \| bash -s -- --easy-mode --verify` | Procedural memory system that transforms scattered AI agent sessions into persistent, cross-agent memory with confidence-tracked rules. |
| **[Beads Viewer](https://github.com/Dicklesworthstone/beads_viewer)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/beads_viewer/main/install.sh?$(date +%s)" \| bash` | Interactive TUI for viewing and navigating project dependency graphs and task management data from Beads tracker format. |

---

## 🛡️ Security & Safety

Protection against prompt injection, destructive commands, and unsafe operations.

| Tool | One-Liner | Description |
|:-----|:----------|:------------|
| **[DCG](https://github.com/Dicklesworthstone/destructive_command_guard)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/destructive_command_guard/master/install.sh?$(date +%s)" \| bash -s -- --easy-mode` | Security hook that blocks dangerous commands before execution, auto-configures Claude Code hooks and PATH. |
| **[ACIP](https://github.com/Dicklesworthstone/acip)** | `curl -fsSL -H "Accept: application/vnd.github.raw" "https://api.github.com/repos/Dicklesworthstone/acip/contents/integrations/clawdbot/install.sh?ref=main&ts=$(date +%s)" \| bash` | Installs cognitive defenses against prompt injection attacks for Clawdbot, establishing trust boundaries and protection against attack patterns. |
| **[SLB](https://github.com/Dicklesworthstone/slb)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/slb/main/scripts/install.sh?$(date +%s)" \| bash` | Two-person rule CLI for running potentially destructive commands from AI coding agents, requiring peer review before execution. |

---

## 🔧 Developer Tools

Utilities for file operations, code formatting, system management, and repo sync.

| Tool | One-Liner | Description |
|:-----|:----------|:------------|
| **[XF](https://github.com/Dicklesworthstone/xf)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/xf/main/install.sh?$(date +%s)" \| bash -s -- --easy-mode` | Comprehensive CLI for file operations and transformations with automatic configuration and sensible defaults. |
| **[Source2Prompt](https://github.com/Dicklesworthstone/source_to_prompt_tui)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/source_to_prompt_tui/main/install.sh?$(date +%s)" \| bash` | Terminal UI for combining source code files into LLM-ready prompts with real-time token counting and structured XML output. |
| **[Repo Updater](https://github.com/Dicklesworthstone/repo_updater)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/repo_updater/main/install.sh?$(date +%s)" \| bash` | Keeps multiple GitHub repositories in sync - clone missing repos, pull updates, detect conflicts with actionable resolution commands. |
| **[SRPS](https://github.com/Dicklesworthstone/system_resource_protection_script)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/system_resource_protection_script/main/install.sh?$(date +%s)" \| bash` | Keeps Linux dev boxes responsive under load with priority tuning, sysctl tweaks, and a polished TUI monitor. |
| **[CAAM](https://github.com/Dicklesworthstone/coding_agent_account_manager)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/coding_agent_account_manager/main/install.sh?$(date +%s)" \| bash` | Manages authentication across multiple AI coding agents with automatic platform detection and setup. |

---

## ✨ Prompts & Skills

Curated prompt libraries and Claude Code skill installers.

| Tool | One-Liner | Description |
|:-----|:----------|:------------|
| **[jfp CLI](https://github.com/Dicklesworthstone/jeffreysprompts.com)** | `curl -fsSL "https://jeffreysprompts.com/install-cli.sh?$(date +%s)" \| bash` | Agent-optimized CLI for discovering, searching, and installing curated AI coding prompts as Claude Code skills. |
| **[JeffreysPrompts Skills](https://github.com/Dicklesworthstone/jeffreysprompts.com)** | `curl -fsSL "https://jeffreysprompts.com/install.sh?$(date +%s)" \| bash` | Bulk installs all JeffreysPrompts prompts directly as Claude Code skills to your local skills directory. |

---

## 🔬 Specialized Tools

Domain-specific utilities and integrations.

| Tool | One-Liner | Description |
|:-----|:----------|:------------|
| **[MCP Agent Mail](https://github.com/Dicklesworthstone/mcp_agent_mail)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/mcp_agent_mail/main/scripts/install.sh?$(date +%s)" \| bash -s -- --yes` | Sets up MCP Agent Mail server with auto-detection of coding agent integrations, starts HTTP server, and installs Beads tools. |
| **[APR](https://github.com/Dicklesworthstone/automated_plan_reviser_pro)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/automated_plan_reviser_pro/main/install.sh?$(date +%s)" \| bash` | Automates iterative specification refinement using GPT Pro Extended Reasoning with background processing and session management. |
| **[Phage Explorer](https://github.com/Dicklesworthstone/phage_explorer)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/phage_explorer/main/install.sh?$(date +%s)" \| bash -s -- --with-database` | TUI for browsing, visualizing, and analyzing bacteriophage genetic data with color-coded sequences and 3D structure viewing. |
| **[GIIL](https://github.com/Dicklesworthstone/giil)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/giil/main/install.sh?$(date +%s)" \| bash` | Downloads full-resolution images from cloud photo shares (iCloud, Dropbox, Google Photos, Google Drive) via browser automation. |
| **[Chat to File](https://github.com/Dicklesworthstone/chat_shared_conversation_to_file)** | `curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/chat_shared_conversation_to_file/main/install.sh?$(date +%s)" \| bash` | Exports shared ChatGPT conversations to local files with automatic platform detection and dependency installation. |

---

<details>
<summary><b>📋 Full Alphabetical List</b></summary>

<br>

| # | Tool | Category |
|:-:|:-----|:---------|
| 1 | [ACFS](https://github.com/Dicklesworthstone/agentic_coding_flywheel_setup) | AI Orchestration |
| 2 | [ACIP](https://github.com/Dicklesworthstone/acip) | Security |
| 3 | [Agent Flywheel Skills](https://github.com/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations) | AI Orchestration |
| 4 | [APR](https://github.com/Dicklesworthstone/automated_plan_reviser_pro) | Specialized |
| 5 | [Beads Viewer](https://github.com/Dicklesworthstone/beads_viewer) | Memory & Search |
| 6 | [Brenner Bot](https://github.com/Dicklesworthstone/brenner_bot) | AI Orchestration |
| 7 | [CAAM](https://github.com/Dicklesworthstone/coding_agent_account_manager) | Developer Tools |
| 8 | [CASS](https://github.com/Dicklesworthstone/coding_agent_session_search) | Memory & Search |
| 9 | [CASS Memory](https://github.com/Dicklesworthstone/cass_memory_system) | Memory & Search |
| 10 | [Chat to File](https://github.com/Dicklesworthstone/chat_shared_conversation_to_file) | Specialized |
| 11 | [DCG](https://github.com/Dicklesworthstone/destructive_command_guard) | Security |
| 12 | [GIIL](https://github.com/Dicklesworthstone/giil) | Specialized |
| 13 | [jfp CLI](https://github.com/Dicklesworthstone/jeffreysprompts.com) | Prompts & Skills |
| 14 | [JeffreysPrompts Skills](https://github.com/Dicklesworthstone/jeffreysprompts.com) | Prompts & Skills |
| 15 | [MCP Agent Mail](https://github.com/Dicklesworthstone/mcp_agent_mail) | Specialized |
| 16 | [NTM](https://github.com/Dicklesworthstone/ntm) | AI Orchestration |
| 17 | [Phage Explorer](https://github.com/Dicklesworthstone/phage_explorer) | Specialized |
| 18 | [Repo Updater](https://github.com/Dicklesworthstone/repo_updater) | Developer Tools |
| 19 | [SLB](https://github.com/Dicklesworthstone/slb) | Security |
| 20 | [Source2Prompt](https://github.com/Dicklesworthstone/source_to_prompt_tui) | Developer Tools |
| 21 | [SRPS](https://github.com/Dicklesworthstone/system_resource_protection_script) | Developer Tools |
| 22 | [Useful Tmux](https://github.com/Dicklesworthstone/useful_tmux_commands) | AI Orchestration |
| 23 | [XF](https://github.com/Dicklesworthstone/xf) | Developer Tools |

</details>

---

## 🌐 Website Previews

<div align="center">

<table>
<tr>
<td align="center" width="50%">
<a href="https://agent-flywheel.com/tldr">
<img src="https://agent-flywheel.com/opengraph-image?895f31c767058372" alt="Agent Flywheel" width="400">
</a>
<br>
<b>Agent Flywheel</b>
</td>
<td align="center" width="50%">
<a href="https://brennerbot.org">
<img src="https://brennerbot.org/opengraph-image?a523997cd907b722" alt="Brenner Bot" width="400">
</a>
<br>
<b>Brenner Bot</b>
</td>
</tr>
<tr>
<td align="center" width="50%">
<a href="https://jeffreysprompts.com">
<img src="https://jeffreysprompts.com/opengraph-image?ea14d913901310ce" alt="Jeffrey's Prompts" width="400">
</a>
<br>
<b>Jeffrey's Prompts</b>
</td>
<td align="center" width="50%">
<a href="https://jeffreyemanuel.com">
<img src="https://jeffreyemanuel.com/opengraph-image?52ef97c0151f4368" alt="Jeffrey Emanuel" width="400">
</a>
<br>
<b>Jeffrey Emanuel</b>
</td>
</tr>
</table>

</div>

---

<details>
<summary><b>🎴 Repository Preview Cards</b></summary>

<br>

<div align="center">

#### AI Agent Orchestration

<a href="https://github.com/Dicklesworthstone/agentic_coding_flywheel_setup">
<img src="https://socialify.git.ci/Dicklesworthstone/agentic_coding_flywheel_setup/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="ACFS" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/ntm">
<img src="https://socialify.git.ci/Dicklesworthstone/ntm/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="NTM" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/useful_tmux_commands">
<img src="https://socialify.git.ci/Dicklesworthstone/useful_tmux_commands/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="Useful Tmux" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/brenner_bot">
<img src="https://socialify.git.ci/Dicklesworthstone/brenner_bot/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="Brenner Bot" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations">
<img src="https://socialify.git.ci/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="Agent Flywheel Skills" width="600">
</a>

---

#### Memory & Search

<a href="https://github.com/Dicklesworthstone/coding_agent_session_search">
<img src="https://socialify.git.ci/Dicklesworthstone/coding_agent_session_search/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="CASS" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/cass_memory_system">
<img src="https://socialify.git.ci/Dicklesworthstone/cass_memory_system/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="CASS Memory" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/beads_viewer">
<img src="https://socialify.git.ci/Dicklesworthstone/beads_viewer/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="Beads Viewer" width="600">
</a>

---

#### Security & Safety

<a href="https://github.com/Dicklesworthstone/destructive_command_guard">
<img src="https://socialify.git.ci/Dicklesworthstone/destructive_command_guard/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="DCG" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/acip">
<img src="https://socialify.git.ci/Dicklesworthstone/acip/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="ACIP" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/slb">
<img src="https://socialify.git.ci/Dicklesworthstone/slb/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="SLB" width="600">
</a>

---

#### Developer Tools

<a href="https://github.com/Dicklesworthstone/xf">
<img src="https://socialify.git.ci/Dicklesworthstone/xf/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="XF" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/source_to_prompt_tui">
<img src="https://socialify.git.ci/Dicklesworthstone/source_to_prompt_tui/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="Source2Prompt" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/repo_updater">
<img src="https://socialify.git.ci/Dicklesworthstone/repo_updater/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="Repo Updater" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/system_resource_protection_script">
<img src="https://socialify.git.ci/Dicklesworthstone/system_resource_protection_script/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="SRPS" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/coding_agent_account_manager">
<img src="https://socialify.git.ci/Dicklesworthstone/coding_agent_account_manager/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="CAAM" width="600">
</a>

---

#### Prompts & Skills

<a href="https://github.com/Dicklesworthstone/jeffreysprompts.com">
<img src="https://socialify.git.ci/Dicklesworthstone/jeffreysprompts.com/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="JeffreysPrompts" width="600">
</a>

---

#### Specialized Tools

<a href="https://github.com/Dicklesworthstone/mcp_agent_mail">
<img src="https://socialify.git.ci/Dicklesworthstone/mcp_agent_mail/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="MCP Agent Mail" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/automated_plan_reviser_pro">
<img src="https://socialify.git.ci/Dicklesworthstone/automated_plan_reviser_pro/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="APR" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/phage_explorer">
<img src="https://socialify.git.ci/Dicklesworthstone/phage_explorer/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="Phage Explorer" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/giil">
<img src="https://socialify.git.ci/Dicklesworthstone/giil/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="GIIL" width="600">
</a>

<a href="https://github.com/Dicklesworthstone/chat_shared_conversation_to_file">
<img src="https://socialify.git.ci/Dicklesworthstone/chat_shared_conversation_to_file/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="Chat to File" width="600">
</a>

</div>

</details>

---

<div align="center">

<sub>

**Made with [Claude Code](https://claude.ai/code)** · [Join the Flywheel Hub Discord](https://t.co/kGjc2TQptc)

</sub>

</div>
