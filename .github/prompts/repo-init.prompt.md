---
description: "Initialize repository with MCPs, documentation base, and workspace configuration"
argument-hint: "[repository name or 'current' for active workspace]"
agent: "agent"
---

# Repository Initialization Guide

I'll help you configure your repository environment for: **{repository}**

Complete each step below and I'll help you document everything in [.context/context/context.md](.context/context/context.md).

## Step 1: Select Dialogue Language
Which language(s) should be used for team communication and documentation?
- **English**: For international or multilingual teams
- **Français**: Pour les équipes francophones
- **Both**: Bilingual support
- **Other**: Specify your language(s)

**→ Answer and I'll save this to the context file.**

## Step 2: Configure Documentation Base
Where does your team store organizational knowledge and documentation?
- **Confluence**: Atlassian Confluence wiki (provide workspace URL)
- **Notion**: Notion workspace (provide workspace URL/ID)
- **Local**: GitHub, files, or local storage (describe location)

**→ Provide links/URLs and I'll document this.**

## Step 3: MCPs (Model Context Protocol) Configuration
What MCPs should be enabled for this repository?

For each MCP:
- Name (e.g., GitHub, Jira, Slack)
- Purpose (what it's used for)
- Configuration status (setup needed? already done?)
- Authentication details (if applicable)

**→ List the MCPs and I'll create a configuration inventory.**

## Step 4: Test and Verify MCPs
For each MCP configured:
- Can you successfully authenticate?
- Can you perform a basic operation? (e.g., fetch a GitHub repo, list Jira issues)
- Any setup quirks or troubleshooting needed?

**→ Provide test results and I'll document them.**

## Step 5: Document Repository Structure
Describe your repository's main directories:
- What's the purpose of each main folder?
- Where are entry points, configs, build files?
- Where are tests, CI/CD configs, documentation?

**→ Share the structure and I'll create a map.**

---

## Output

Once complete, I will generate/update:
- `.context/context/context.md` - Full repository context
- `.github/copilot-instructions.md` - VSCode instructions
- `CLAUDE.md` - Claude Code instructions

This context will be loaded automatically by both VSCode Copilot and Claude Code.
