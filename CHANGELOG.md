# Changelog

All notable changes to **Curl One-Liners for Flywheel Tools** are documented here.

This project has no tagged releases or GitHub Releases. Every entry corresponds to a commit on the `main` branch. Commit links point to the canonical GitHub commit view.

Repository: <https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools>

---

## Current state (HEAD: `cf86cdf`)

The repository contains 3 files and catalogs 21 tools across 6 categories.

| File | Purpose |
|:-----|:--------|
| `README.md` | 21 curl one-liners in minimal vertical-list format |
| `LICENSE` | MIT with OpenAI/Anthropic Rider |
| `gh_og_share_image.png` | 1280x640 social preview image |

---

## Timeline

### 2026-02-21

#### License updated to MIT with OpenAI/Anthropic Rider

[`cf86cdf`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/cf86cdf855cd857b4db336564c0c6c415c06e4d9)

Replaced the plain MIT license with **MIT + OpenAI/Anthropic Rider**. The rider restricts use by OpenAI, Anthropic, and their affiliates without express written permission from Jeffrey Emanuel. Defines "Restricted Parties" broadly (officers, directors, employees, contractors, agents, consultants, service providers, representatives), covers derivative works, and includes automatic termination, injunctive relief, and fee-shifting clauses.

#### Social preview image added

[`680e70b`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/680e70b50d12daf38356e0f18b4498d7ee978c98)

Added `gh_og_share_image.png` (54.5 KB, 1280x640) for consistent OpenGraph previews when sharing the repository URL on social media. Generated via the `gh-og-share-images` skill.

---

### 2026-01-21

#### Initial MIT license added

[`56d0277`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/56d027742c17dde0ad11b02b54de7267a62a7e65)

Standard MIT license added. Copyright (c) 2026 Jeffrey Emanuel. Later replaced by the rider version on 2026-02-21.

---

### 2026-01-17

#### README content and structure revision

[`2872450`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/287245047179fce96bc3a782708371ceffc1463b)

Two tools removed, Showcase section promoted to top-level visibility, and several layout refinements applied. Tool count went from 23 to 21.

**Tools removed:**
- **Useful Tmux** (`useful_tmux_commands`) -- removed from AI Orchestration (superseded by NTM).
- **JeffreysPrompts Skills** bulk installer -- removed from Prompts & Skills (redundant with jfp CLI).

**Layout changes:**
- Showcase section (Website Previews + Repository Cards) promoted from collapsible `<details>` blocks to always-visible `## Showcase` with subsections.
- Repository cards switched from single-column stacked images (600px) to 2-column HTML table grid (480px each).
- Website preview images widened from 400px to 420px with explicit `width="50%"` cell sizing.
- Added subtitle: "One-line installers for the Flywheel toolchain. Copy, paste, and go."
- Removed the footer "Made with Claude Code" branding.
- Removed full alphabetical reference table.

---

### 2026-01-15

Three commits on this date established the repository and iterated through layout approaches. The final layout (minimal vertical list) is the one that persists to the current HEAD.

#### Initial commit -- 23 tools, 6 categories

[`02b1972`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/02b1972d9f5f90e5b5165edccac6c192f9b0b3af)

Repository created with a single `README.md` containing 23 curl one-liners. All commands use non-interactive flags and `$(date +%s)` cache busters for fresh downloads. Presentation used markdown tables with three columns (Tool, One-Liner, Description).

#### Refactor to 2-column card grid

[`f9bd2fb`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/f9bd2fba235c9b0fa266619de5d9ff0731d89cb4)

Second layout iteration. Same 23 tools, different presentation. Replaced markdown tables with HTML `<table>` 2-column card grid using 50% width cells and `colspan="2"` for odd-count and long-URL items. Replaced verbose descriptions with 3-6 word taglines. Condensed alphabetical reference to 4-column layout. README grew from 315 to 502 lines.

#### Refactor to minimal vertical list (current format)

[`ef8b327`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/ef8b327aeaabc3fdfd7da362bdf1d6414ba8f626)

Third and final layout iteration. Replaced the card grid with a minimal vertical list: tool name + short description on one line, full-width fenced code block below. This enables GitHub's native hover-to-copy button without table cell width constraints. Moved website previews and repository cards into collapsible `<details>` sections. Removed badge row and category descriptions. README shrank from 502 to 206 lines.

---

## Tool catalog

### AI Orchestration

| Tool | Status | Install flags |
|:-----|:-------|:--------------|
| [ACFS](https://github.com/Dicklesworthstone/agentic_coding_flywheel_setup) | Present since initial commit | `--yes --mode vibe` |
| [NTM](https://github.com/Dicklesworthstone/ntm) | Present since initial commit | `--easy-mode` |
| [Brenner Bot](https://github.com/Dicklesworthstone/brenner_bot) | Present since initial commit | `--easy-mode --verify` |
| [Agent Flywheel Skills](https://github.com/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations) | Present since initial commit | `--all` |
| ~~Useful Tmux~~ | Removed in [`2872450`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/287245047179fce96bc3a782708371ceffc1463b) (2026-01-17) | `--easy` |

### Memory & Search

| Tool | Status | Install flags |
|:-----|:-------|:--------------|
| [CASS](https://github.com/Dicklesworthstone/coding_agent_session_search) | Present since initial commit | `--easy-mode --verify` |
| [CASS Memory](https://github.com/Dicklesworthstone/cass_memory_system) | Present since initial commit | `--easy-mode --verify` |
| [Beads Viewer](https://github.com/Dicklesworthstone/beads_viewer) | Present since initial commit | (none) |

### Security

| Tool | Status | Install flags |
|:-----|:-------|:--------------|
| [DCG](https://github.com/Dicklesworthstone/destructive_command_guard) | Present since initial commit | `--easy-mode` |
| [SLB](https://github.com/Dicklesworthstone/slb) | Present since initial commit | (none) |
| [ACIP](https://github.com/Dicklesworthstone/acip) | Present since initial commit | Uses GitHub API raw content endpoint |

### Developer Tools

| Tool | Status | Install flags |
|:-----|:-------|:--------------|
| [XF](https://github.com/Dicklesworthstone/xf) | Present since initial commit | `--easy-mode` |
| [Source2Prompt](https://github.com/Dicklesworthstone/source_to_prompt_tui) | Present since initial commit | (none) |
| [Repo Updater](https://github.com/Dicklesworthstone/repo_updater) | Present since initial commit | (none) |
| [SRPS](https://github.com/Dicklesworthstone/system_resource_protection_script) | Present since initial commit | (none) |
| [CAAM](https://github.com/Dicklesworthstone/coding_agent_account_manager) | Present since initial commit | (none) |

### Prompts & Skills

| Tool | Status | Install flags |
|:-----|:-------|:--------------|
| [jfp CLI](https://github.com/Dicklesworthstone/jeffreysprompts.com) | Present since initial commit | (none) |
| ~~JeffreysPrompts Skills~~ | Removed in [`2872450`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/287245047179fce96bc3a782708371ceffc1463b) (2026-01-17) | (none) |

### Specialized

| Tool | Status | Install flags |
|:-----|:-------|:--------------|
| [MCP Agent Mail](https://github.com/Dicklesworthstone/mcp_agent_mail) | Present since initial commit | `--yes` |
| [APR](https://github.com/Dicklesworthstone/automated_plan_reviser_pro) | Present since initial commit | (none) |
| [Phage Explorer](https://github.com/Dicklesworthstone/phage_explorer) | Present since initial commit | `--with-database` |
| [GIIL](https://github.com/Dicklesworthstone/giil) | Present since initial commit | (none) |
| [Chat to File](https://github.com/Dicklesworthstone/chat_shared_conversation_to_file) | Present since initial commit | (none) |

---

## Presentation assets

| Asset | Added | Commit |
|:------|:------|:-------|
| Website OG previews (agent-flywheel.com, brennerbot.org, jeffreysprompts.com, jeffreyemanuel.com) | 2026-01-15 | [`02b1972`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/02b1972d9f5f90e5b5165edccac6c192f9b0b3af) |
| Socialify repository cards (ACFS, NTM, Brenner Bot, CASS, CASS Memory, DCG, XF, JeffreysPrompts) | 2026-01-15 | [`02b1972`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/02b1972d9f5f90e5b5165edccac6c192f9b0b3af) |
| GitHub badges (profile, X/Twitter, Discord) | 2026-01-15 | [`02b1972`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/02b1972d9f5f90e5b5165edccac6c192f9b0b3af) |
| Social preview image (`gh_og_share_image.png`) | 2026-02-21 | [`680e70b`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/680e70b50d12daf38356e0f18b4498d7ee978c98) |

---

## Licensing history

| Date | License | Commit |
|:-----|:--------|:-------|
| 2026-01-15 to 2026-01-20 | No license file | -- |
| 2026-01-21 | MIT (standard) | [`56d0277`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/56d027742c17dde0ad11b02b54de7267a62a7e65) |
| 2026-02-21 to present | MIT with OpenAI/Anthropic Rider | [`cf86cdf`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/cf86cdf855cd857b4db336564c0c6c415c06e4d9) |

---

## Layout evolution

The README layout went through four revisions:

| # | Date | Commit | Format | Lines | Tools |
|:-:|:-----|:-------|:-------|------:|------:|
| 1 | 2026-01-15 | [`02b1972`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/02b1972d9f5f90e5b5165edccac6c192f9b0b3af) | Markdown tables (Tool / One-Liner / Description) | 315 | 23 |
| 2 | 2026-01-15 | [`f9bd2fb`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/f9bd2fba235c9b0fa266619de5d9ff0731d89cb4) | HTML 2-column card grid with taglines | 502 | 23 |
| 3 | 2026-01-15 | [`ef8b327`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/ef8b327aeaabc3fdfd7da362bdf1d6414ba8f626) | Minimal vertical list with full-width code blocks | 206 | 23 |
| 4 | 2026-01-17 | [`2872450`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/287245047179fce96bc3a782708371ceffc1463b) | Same format, 2 tools removed, Showcase promoted | 195 | 21 |

---

## Complete commit log

| Date | Hash | Summary |
|:-----|:-----|:--------|
| 2026-01-15 | [`02b1972`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/02b1972d9f5f90e5b5165edccac6c192f9b0b3af) | Initial commit: 23 tools in 6 categories |
| 2026-01-15 | [`f9bd2fb`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/f9bd2fba235c9b0fa266619de5d9ff0731d89cb4) | Refactor to 2-column card grid layout |
| 2026-01-15 | [`ef8b327`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/ef8b327aeaabc3fdfd7da362bdf1d6414ba8f626) | Minimal vertical list with full-width code blocks |
| 2026-01-17 | [`2872450`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/287245047179fce96bc3a782708371ceffc1463b) | Update README layout and links |
| 2026-01-21 | [`56d0277`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/56d027742c17dde0ad11b02b54de7267a62a7e65) | Add MIT License |
| 2026-02-21 | [`680e70b`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/680e70b50d12daf38356e0f18b4498d7ee978c98) | Add GitHub social preview image |
| 2026-02-21 | [`cf86cdf`](https://github.com/Dicklesworthstone/curl_bash_one_liners_for_flywheel_tools/commit/cf86cdf855cd857b4db336564c0c6c415c06e4d9) | Update license to MIT with OpenAI/Anthropic Rider |
