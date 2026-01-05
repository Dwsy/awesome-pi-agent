[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# awesome-pi-agent

Concise, curated resources for extending and integrating the pi coding agent.

## Primary project

- pi (pi-mono) — Official coding agent, docs, and examples: https://github.com/badlogic/pi-mono/tree/main/packages/coding-agent/docs

---

## Getting Started & Docs

- Official coding-agent docs — Usage, CLI reference, SDK, RPC, sessions, and compaction. https://github.com/badlogic/pi-mono/tree/main/packages/coding-agent/docs
- Package README — High-level package README and development notes. https://github.com/badlogic/pi-mono/blob/main/packages/coding-agent/README.md

---

## Skills

- Community skills collection — pi-skills repository with example SKILL.md files and workflows. https://github.com/badlogic/pi-skills
- Anthropic skills — Example skills (document processing, web tools) useful as inspiration. https://github.com/anthropics/skills

---

## Hooks

- Hooks reference — Hook API, lifecycle events, and example hooks (permission gate, git checkpoint, status-line). https://github.com/badlogic/pi-mono/blob/main/packages/coding-agent/docs/hooks.md
- Community hooks & extensions — example collections and user hooks (memory-mode, plan-mode, filter-output). Examples:
  - https://github.com/hjanuschka/shitty-extensions
  - https://github.com/michalvavra/agents
  - https://github.com/LarsEckart/dotfiles

---

## Custom Tools

- Custom tools guide — Authoring guide for tools callable by the LLM: parameters, rendering, streaming, and session state. https://github.com/badlogic/pi-mono/blob/main/packages/coding-agent/docs/custom-tools.md

---

## Themes

- Theme guide — Theme schema, required color tokens, and examples for terminal themes. https://github.com/badlogic/pi-mono/blob/main/packages/coding-agent/docs/theme.md

---

## Providers & Integrations

- Web UI provider utilities — Provider dialogs, custom provider store, and model discovery utilities. https://github.com/badlogic/pi-mono/tree/main/packages/web-ui
- Model registry — Core model/provider registry and API-key resolution implementation. https://github.com/badlogic/pi-mono/blob/main/packages/coding-agent/src/core/model-registry.ts
- Pods / models examples — Example models.json for pods and local runners. https://github.com/badlogic/pi-mono/blob/main/packages/pods/src/models.json
- Integration examples and adapters:
  - ACP adapter: https://github.com/svkozak/pi-acp
  - Project config example: https://github.com/vtemian/pi-config

---

## Examples & Recipes

- Examples directory — Working examples for hooks, custom tools, SDK usage, and more. https://github.com/badlogic/pi-mono/tree/main/packages/coding-agent/examples
- Context & writeups — articles or notes referencing the agent. https://github.com/crossjam/mpr/blob/main/content/pi_coding_agent.md

---

## Community & Resources

- Search GitHub for additional hooks, tools, skills, and user extensions. Seeded repos above are good starting points.

---

## Submission Checklist

When adding a new resource, ensure the following:
- [ ] Tool is actively maintained (commits within last year)
- [ ] Has documentation / README
- [ ] Description is concise and explains value
- [ ] Link works and goes to correct resource
- [ ] Not a duplicate
- [ ] Alphabetically ordered within section

Please add only one-line entries (short description + link). Maintainers may re-order or trim entries during review.

---

## Contributing

Fork, create a topic branch, add your entry to the appropriate section in this README (one-line entry, alphabetical), and open a Pull Request using the PR template.

## CI

Link-checker workflow: .github/workflows/check-links.yml (runs on push and PRs)

---

## License

MIT — see LICENSE
