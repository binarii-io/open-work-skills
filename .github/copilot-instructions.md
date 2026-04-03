---
name: "open-work-skills Project Context"
description: "Repository guidelines, context initialization workflows, and organizational knowledge"
---

# open-work-skills Agent Instructions

You are assisting with the **open-work-skills** project - a system for discovering, documenting, and sharing organizational context and repository setup knowledge.

## Project Overview

This repository contains tools and workflows for:
- **repo-init**: Setting up repositories with MCPs, documentation bases, and infrastructure
- **context-init**: Discovering and documenting organizational structure, tools, processes, and people
- **Skills & Prompts**: Reusable onboarding and discovery workflows

**See [.context/context/context.md](.context/context/context.md) for detailed context and setup status.**

## Key Workflows

### 1. Repository Initialization (`/repo-init`)
Help users configure their repository with:
- **Dialogue Language Selection** - English, Français, or other
- **Documentation Base** - Confluence, Notion, or Local storage
- **MCPs Configuration** - Model Context Protocol integrations
- **Repository Structure** - Document key directories and files
- **Connection Testing** - Verify MCPs work correctly

### 2. Organizational Context (`/context-init`)
Guide users in discovering organizational context:
- **Organizational Structure** - Teams, stakeholders, hierarchies
- **Tools & Technology** - Tech stack and integrations
- **Processes & Workflows** - Key workflows and decision points
- **People & Responsibilities** - Team members and experts
- **Documentation & Knowledge** - Where information is stored

## Available Skills & Prompts

| File | Purpose |
|------|---------|
| [`.github/prompts/repo-init.prompt.md`](.github/prompts/repo-init.prompt.md) | Prompt for repository initialization |
| [`.github/prompts/context-init.prompt.md`](.github/prompts/context-init.prompt.md) | Prompt for organizational context discovery |
| [`skills/context-init/SKILL.md`](skills/context-init/SKILL.md) | Skill for context-init discovery |
| [`onboarding/vscode.md`](onboarding/vscode.md) | VSCode onboarding guide |

## Instructions

### When Helping with Repository Setup
1. First, ask which language the team prefers (English/Français)
2. Help identify the documentation base (Confluence/Notion/Local)
3. Guide MCP configuration and testing
4. Document the repository structure

### When Helping with Organizational Context
1. Guide discovery of organizational structure
2. Map tools and technology stack
3. Document key processes and workflows
4. Identify important people and knowledge holders
5. Create knowledge transfer documentation

### Best Practices
- Use conversations to extract patterns and conventions
- Reference existing documentation when available
- Suggest improvements to onboarding processes
- Encourage team validation of discovered context
- Store complex context in `.context/context/context.md`

## Organization Preferences

- **Team Language**: Bilingual (Français/English)
- **Documentation Style**: Markdown
- **Context Storage**: `.context/context/context.md`
- **Customizations**: Follow VS Code customization best practices

## Standing Rules

### Documentation — `docs/` folder (non-negotiable)
A `docs/` folder **always** exists at the root of this repository and is the working directory for all documentation:
- **If Local base**: `docs/` is the final documentation destination
- **If Confluence/Notion**: `docs/` is the local staging area — documents are written here first, then pushed to the online platform

Always reference and write documentation to `docs/` by default.

## Related Resources

- [Customization Documentation](.github/copilot-instructions.md)
- [Repository Context](.context/context/context.md)
- [Onboarding Guide](onboarding/vscode.md)
- [Skills Directory](skills/)
