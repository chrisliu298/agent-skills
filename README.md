# Agent Skills

Skills I use with [Claude Code](https://docs.anthropic.com/en/docs/claude-code) and [Codex](https://openai.com/index/introducing-codex/).

## Published Skills

Skills I have built and maintain as open-source repos:

| Skill | Source | Description |
|-------|--------|-------------|
| autoresearch | [chrisliu298/autoresearch](https://github.com/chrisliu298/autoresearch) | Autonomous experiment loop faithful to Karpathy's autoresearch |
| citation-assistant | [chrisliu298/citation-assistant](https://github.com/chrisliu298/citation-assistant) | Add verified citations to academic LaTeX documents |
| deslop | [chrisliu298/deslop](https://github.com/chrisliu298/deslop) | Remove AI-generated slop from code changes |
| interviewer | [chrisliu298/interviewer](https://github.com/chrisliu298/interviewer) | Mock technical interviews for AI/ML |
| last-call | [chrisliu298/last-call](https://github.com/chrisliu298/last-call) | Session-end quality review of all changes |
| lbreview | [chrisliu298/lbreview](https://github.com/chrisliu298/lbreview) | Thorough code review of changes against main |
| nanorepl | [chrisliu298/nanorepl](https://github.com/chrisliu298/nanorepl) | Minimal reimplementations following Karpathy's nano philosophy |
| note-gen | [chrisliu298/note-gen](https://github.com/chrisliu298/note-gen) | Generate Obsidian notes from source materials |
| prism | [chrisliu298/prism](https://github.com/chrisliu298/prism) | Multi-perspective review through parallel agent deliberation |
| prompt-engineer | [chrisliu298/prompt-engineer](https://github.com/chrisliu298/prompt-engineer) | Write and refine prompts for Claude or GPT/Codex |
| recall | [chrisliu298/recall](https://github.com/chrisliu298/recall) | Search past sessions and Obsidian notes for context |
| relay | [chrisliu298/relay](https://github.com/chrisliu298/relay) | Bidirectional cross-agent relay between Claude Code and Codex |
| vault-linker | [chrisliu298/vault-linker](https://github.com/chrisliu298/vault-linker) | Build wikilink connections across Obsidian vaults |

## Community Skills

Public skills by others that I found useful and installed:

| Skill | Source | Description |
|-------|--------|-------------|
| defuddle | [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) | Extract clean markdown from web pages via CLI |
| humanizer | [blader/humanizer](https://github.com/blader/humanizer) | Remove AI-generated writing patterns |
| obsidian-cli | [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) | Interact with Obsidian vaults via CLI |
| pdf | [anthropics/skills](https://github.com/anthropics/skills), [openai/skills](https://github.com/openai/skills) | PDF manipulation: extract, create, merge, split, fill forms |
| skill-creator | [anthropics/skills](https://github.com/anthropics/skills) | Guide for creating new skills |

## Workflow Skills

Local skills for workflow acceleration. These aren't published as standalone repos.

| Skill | Description |
|-------|-------------|
| atomic-push | Atomic commits and push to remote |
| publish-skill | Publish local skill to standalone public GitHub repo |
| push | Single-commit push to remote |
| session-recovery | Recover sessions after directory rename/move |
| sync-upstream | Sync forked repo with upstream remote |
| update-readme | Update or create README.md for repos |

## Install

Clone a skill into your agent's skills directory:

```bash
# Claude Code
git clone https://github.com/chrisliu298/<skill>.git ~/.claude/skills/<skill>

# Codex
git clone https://github.com/chrisliu298/<skill>.git ~/.codex/skills/<skill>
```
