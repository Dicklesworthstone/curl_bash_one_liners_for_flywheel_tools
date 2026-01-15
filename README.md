<div align="center">

# Curl One-Liners for Flywheel Tools

[![GitHub](https://img.shields.io/badge/GitHub-Dicklesworthstone-181717?style=for-the-badge&logo=github)](https://github.com/Dicklesworthstone)
[![X](https://img.shields.io/badge/X-@doodlestein-000000?style=for-the-badge&logo=x)](https://x.com/doodlestein)
[![Discord](https://img.shields.io/badge/Discord-Flywheel_Hub-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://t.co/kGjc2TQptc)

</div>

> [!TIP]
> Hover over any code block and click the copy icon. All commands use non-interactive mode.

---

### 🤖 AI Orchestration

[ACFS](https://github.com/Dicklesworthstone/agentic_coding_flywheel_setup) · Full multi-agent setup
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/agentic_coding_flywheel_setup/main/install.sh?$(date +%s)" | bash -s -- --yes --mode vibe
```

[NTM](https://github.com/Dicklesworthstone/ntm) · Tmux session manager
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/ntm/main/install.sh?$(date +%s)" | bash -s -- --easy-mode
```

[Useful Tmux](https://github.com/Dicklesworthstone/useful_tmux_commands) · Shell functions
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/useful_tmux_commands/main/add_useful_tmux_commands_to_zshrc.sh?$(date +%s)" | bash -s -- --easy
```

[Brenner Bot](https://github.com/Dicklesworthstone/brenner_bot) · AI agent framework
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/brenner_bot/main/install.sh?$(date +%s)" | bash -s -- --easy-mode --verify
```

[Agent Flywheel Skills](https://github.com/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations) · Clawdbot skills
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations/main/install.sh?$(date +%s)" | bash -s -- --all
```

---

### 🧠 Memory & Search

[CASS](https://github.com/Dicklesworthstone/coding_agent_session_search) · Cross-agent search
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/coding_agent_session_search/main/install.sh?$(date +%s)" | bash -s -- --easy-mode --verify
```

[CASS Memory](https://github.com/Dicklesworthstone/cass_memory_system) · Procedural memory
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/cass_memory_system/main/install.sh?$(date +%s)" | bash -s -- --easy-mode --verify
```

[Beads Viewer](https://github.com/Dicklesworthstone/beads_viewer) · Dependency graph TUI
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/beads_viewer/main/install.sh?$(date +%s)" | bash
```

---

### 🛡️ Security

[DCG](https://github.com/Dicklesworthstone/destructive_command_guard) · Command guard
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/destructive_command_guard/master/install.sh?$(date +%s)" | bash -s -- --easy-mode
```

[SLB](https://github.com/Dicklesworthstone/slb) · Two-person rule
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/slb/main/scripts/install.sh?$(date +%s)" | bash
```

[ACIP](https://github.com/Dicklesworthstone/acip) · Prompt injection defense
```bash
curl -fsSL -H "Accept: application/vnd.github.raw" "https://api.github.com/repos/Dicklesworthstone/acip/contents/integrations/clawdbot/install.sh?ref=main&ts=$(date +%s)" | bash
```

---

### 🔧 Developer Tools

[XF](https://github.com/Dicklesworthstone/xf) · File operations CLI
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/xf/main/install.sh?$(date +%s)" | bash -s -- --easy-mode
```

[Source2Prompt](https://github.com/Dicklesworthstone/source_to_prompt_tui) · Code to LLM prompt
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/source_to_prompt_tui/main/install.sh?$(date +%s)" | bash
```

[Repo Updater](https://github.com/Dicklesworthstone/repo_updater) · Sync repos
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/repo_updater/main/install.sh?$(date +%s)" | bash
```

[SRPS](https://github.com/Dicklesworthstone/system_resource_protection_script) · Keep Linux responsive
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/system_resource_protection_script/main/install.sh?$(date +%s)" | bash
```

[CAAM](https://github.com/Dicklesworthstone/coding_agent_account_manager) · Agent auth manager
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/coding_agent_account_manager/main/install.sh?$(date +%s)" | bash
```

---

### ✨ Prompts & Skills

[jfp CLI](https://github.com/Dicklesworthstone/jeffreysprompts.com) · Search prompts
```bash
curl -fsSL "https://jeffreysprompts.com/install-cli.sh?$(date +%s)" | bash
```

[JeffreysPrompts Skills](https://github.com/Dicklesworthstone/jeffreysprompts.com) · Install all skills
```bash
curl -fsSL "https://jeffreysprompts.com/install.sh?$(date +%s)" | bash
```

---

### 🔬 Specialized

[MCP Agent Mail](https://github.com/Dicklesworthstone/mcp_agent_mail) · MCP server
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/mcp_agent_mail/main/scripts/install.sh?$(date +%s)" | bash -s -- --yes
```

[APR](https://github.com/Dicklesworthstone/automated_plan_reviser_pro) · Spec refinement
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/automated_plan_reviser_pro/main/install.sh?$(date +%s)" | bash
```

[Phage Explorer](https://github.com/Dicklesworthstone/phage_explorer) · Bacteriophage TUI
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/phage_explorer/main/install.sh?$(date +%s)" | bash -s -- --with-database
```

[GIIL](https://github.com/Dicklesworthstone/giil) · Cloud photo downloader
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/giil/main/install.sh?$(date +%s)" | bash
```

[Chat to File](https://github.com/Dicklesworthstone/chat_shared_conversation_to_file) · Export ChatGPT
```bash
curl -fsSL "https://raw.githubusercontent.com/Dicklesworthstone/chat_shared_conversation_to_file/main/install.sh?$(date +%s)" | bash
```

---

<details>
<summary>🌐 Website Previews</summary>

<br>

<div align="center">
<table>
<tr>
<td align="center"><a href="https://agent-flywheel.com/tldr"><img src="https://agent-flywheel.com/opengraph-image?895f31c767058372" alt="Agent Flywheel" width="400"></a><br><b>Agent Flywheel</b></td>
<td align="center"><a href="https://brennerbot.org"><img src="https://brennerbot.org/opengraph-image?a523997cd907b722" alt="Brenner Bot" width="400"></a><br><b>Brenner Bot</b></td>
</tr>
<tr>
<td align="center"><a href="https://jeffreysprompts.com"><img src="https://jeffreysprompts.com/opengraph-image?ea14d913901310ce" alt="Jeffrey's Prompts" width="400"></a><br><b>Jeffrey's Prompts</b></td>
<td align="center"><a href="https://jeffreyemanuel.com"><img src="https://jeffreyemanuel.com/opengraph-image?52ef97c0151f4368" alt="Jeffrey Emanuel" width="400"></a><br><b>Jeffrey Emanuel</b></td>
</tr>
</table>
</div>

</details>

<details>
<summary>🎴 Repository Cards</summary>

<br>

<div align="center">

<a href="https://github.com/Dicklesworthstone/agentic_coding_flywheel_setup"><img src="https://socialify.git.ci/Dicklesworthstone/agentic_coding_flywheel_setup/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="ACFS" width="600"></a>

<a href="https://github.com/Dicklesworthstone/ntm"><img src="https://socialify.git.ci/Dicklesworthstone/ntm/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="NTM" width="600"></a>

<a href="https://github.com/Dicklesworthstone/brenner_bot"><img src="https://socialify.git.ci/Dicklesworthstone/brenner_bot/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="Brenner Bot" width="600"></a>

<a href="https://github.com/Dicklesworthstone/coding_agent_session_search"><img src="https://socialify.git.ci/Dicklesworthstone/coding_agent_session_search/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="CASS" width="600"></a>

<a href="https://github.com/Dicklesworthstone/cass_memory_system"><img src="https://socialify.git.ci/Dicklesworthstone/cass_memory_system/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="CASS Memory" width="600"></a>

<a href="https://github.com/Dicklesworthstone/destructive_command_guard"><img src="https://socialify.git.ci/Dicklesworthstone/destructive_command_guard/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="DCG" width="600"></a>

<a href="https://github.com/Dicklesworthstone/xf"><img src="https://socialify.git.ci/Dicklesworthstone/xf/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="XF" width="600"></a>

<a href="https://github.com/Dicklesworthstone/jeffreysprompts.com"><img src="https://socialify.git.ci/Dicklesworthstone/jeffreysprompts.com/image?description=1&font=Inter&language=1&name=1&owner=1&pattern=Plus&theme=Dark" alt="JeffreysPrompts" width="600"></a>

</div>

</details>

---

<div align="center">
<sub><b>Made with <a href="https://claude.ai/code">Claude Code</a></b> · <a href="https://t.co/kGjc2TQptc">Discord</a></sub>
</div>
