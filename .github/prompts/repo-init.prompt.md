---
description: "Initialize repository with MCPs, documentation base, and workspace configuration"
argument-hint: "[repository name or 'current' for active workspace]"
agent: "agent"
---

# Repository Initialization Guide

I'll help you set up and configure your repository environment for: **{repository}**

## What We'll Cover

### 1. **Dialogue Language**
What language should be used for team interactions and documentation?
- **English**: For international or multilingual teams
- **Français**: Pour les équipes francophones
- **Other**: Specify preferred language(s)

This setting helps customize communication and documentation generation.

### 3. **Documentation Base Selection**
Where does your team store organizational knowledge and documentation?
- **Confluence**: Atlassian Confluence wiki
- **Notion**: Notion workspace
- **Local**: Documentation stored locally (GitHub, files, etc.)

Identify URLs, spaces, or paths where team docs live.

### 2. **MCPs (Model Context Protocol) Configuration**
What MCPs should be enabled for this repository?
- Identify which MCPs are needed (e.g., GitHub, Slack, Jira integrations)
- Note configuration details (API keys, workspace IDs, endpoints)
- Document which MCPs are used by which team members or workflows

### 4. **Test and Verify MCPs**
For each MCP configured:
- Test the connection and authentication
- Verify basic operations work (e.g., can fetch issues from Jira, can read GitHub repos)
- Document any setup quirks or troubleshooting steps

### 5. **Repository Structure Documentation**
Map the repo layout:
- Purpose of main folders (`src/`, `docs/`, `config/`, etc.)
- Key files and their roles (entry points, config files, etc.)
- Build/deployment paths
- Where to find tests, CI/CD configs, etc.

## Output Format

Create a Markdown document that includes:
- **Dialogue Language**: Selected language(s) for team communication and agents
- **Documentation Base**: Links and access instructions for each platform
- **MCPs Inventory**: Table listing each MCP, its purpose, configuration status, and test results
- **Repository Map**: Directory structure with descriptions
- **Connection Checklist**: Quick reference for verifying everything works

## Next Steps

After repo initialization:
- Share MCP configs with team and validate access
- Run context-init to document organizational context
- Create runbooks for common tasks using the MCPs
- Set up automation workflows leveraging the configured MCPs
