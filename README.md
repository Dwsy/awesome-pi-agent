# awesome-pi-agent

A curated "awesome" list of add-ons, extensions, examples, and resources for the pi coding agent (pi-mono / https://github.com/badlogic/pi-mono).

This repository collects community-built and official resources for extending and integrating pi: themes, hooks, skills, custom tools, models/providers, example projects, tutorials, and related tooling.

If you'd like me to create this repository on GitHub and push the initial commit, I will ask for explicit approval before performing any git push.

---

## Quick links

- Project: https://github.com/badlogic/pi-mono
- Docs (primary): https://github.com/badlogic/pi-mono/tree/main/packages/coding-agent/docs
- Examples: https://github.com/badlogic/pi-mono/tree/main/packages/coding-agent/examples

---

## Categories

The list below is organized using categories picked from the official docs and examples. Each category contains suggested sub-items to curate.

- Getting started
  - Installers & standalone binaries
  - Quick start snippets (auth.json, settings.json)
  - Tips for Windows (Git Bash / WSL)

- Official docs & references
  - README, SDK docs, RPC docs, CLI reference
  - Theme schema and examples
  - Hooks and custom tools API docs
  - Session & compaction docs

- Examples & recipes
  - Example hooks (permission gate, git checkpoint, snake, status-line)
  - Example custom tools (todo, question tool, subagent)
  - Example skills (brave-search, pdf-processing, transcription)
  - Recipes: common workflows (code review, refactor, generate tests)

- Hooks
  - Permission gates (safe-command prompts)
  - Path protection hooks (.env, node_modules)
  - Git checkpointing / stash hooks
  - CI/webhook triggers and file watchers
  - Status-line / TUI examples

- Custom Tools
  - Interactive tools (select/input/editor) examples
  - Stateful tools (todo lists, connection managers)
  - External service integrations (APIs, DB query tools)
  - Tools with custom TUI rendering

- Skills
  - PDF/document processing
  - Browser automation and CDP workflows
  - Search + scraping skills (Brave Search, web extraction)
  - Google APIs (Drive, Calendar, Gmail)
  - Transcription & audio processing

- Themes
  - Built-in dark & light themes
  - Community themes (showcases)
  - Theme authoring guide & schema

- Models & Providers
  - Custom providers (Ollama, vLLM, LM Studio) examples
  - Provider configuration snippets (models.json)
  - OAuth notes (GitHub Copilot, Google providers)

- Commands & Templates
  - Slash commands (.pi/commands/*.md) templates
  - AGENTS.md and SYSTEM.md templates for projects
  - settings.json snippets and recommended defaults

- SDK & Programmatic usage
  - SDK examples (createAgentSession, in-memory SessionManager)
  - RPC mode examples and integration tips
  - HTML export and session interoperability

- Integrations & Tools
  - VS Code tips (Copilot model issues, terminal contrast)
  - Docker/Devcontainer recipes for isolated runs
  - CI examples: validating themes, hooks, or skills in CI
  - Useful CLI tools: gh, jq, bat, rg

- Security & Safety
  - Hook patterns for blocking dangerous commands
  - Sandboxing recommendations (run pi in containers)
  - Best practices for storing API keys and OAuth tokens

- Community & Repositories
  - pi-skills repo
  - Anthropic/official skills repos
  - Notable community custom tools, hooks, and skills

- Tutorials & Blog posts
  - Author blog posts and rationales linked from docs
  - Step-by-step guides for building hooks, tools, skills, and themes

---

## Contributing

Contributions are welcome. Suggested workflow:

1. Fork the repository
2. Create a topic branch (do not commit to main)
3. Add your resource with a short description and a link
4. Open a Pull Request with a clear title and category

Please follow repository conventions when adding entries: include a one-line description, a link, and (optionally) tags like `hook`, `tool`, `skill`, `theme`, `example`.

Note: I will not push to any remote without explicit approval. If you'd like me to push the initial repository and open a PR on your behalf, reply "yes, push to GitHub" and provide the target GitHub repo URL (or let me create github.com/<your-username>/awesome-pi-agent).

---

## LICENSE

MIT — see LICENSE file.
