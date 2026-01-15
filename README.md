# my-crazy-skills

Collection of AI skills tracked as git submodules. Categories live under `skills/` and reflect the current organization.

## Layout

- `skills/learning/`
  - `33-js-concepts` - JavaScript concepts guide with curated resources
- `skills/frontend/`
  - `ui-ux-pro-max-skill` - UI/UX engineering skill pack
- `skills/creative/`
  - `skill-prompt-generator` - multi-domain AI image prompt generator
- `skills/research/`
  - `ipsw-skill` - Apple firmware RE tooling
  - `notebooklm-skill` - NotebookLM source-grounded Q&A
- `skills/tooling/`
  - `agent-skills` - agent skill collection
  - `claude-code-templates` - Claude Code templates/tools
  - `mcp-progressive-agentskill` - progressive MCP access
  - `skills` - Anthropic skill examples/spec
- `skills/workflows/`
  - `planning-with-files` - file-based planning workflow
  - `superpowers` - structured coding-agent workflow
- `skills/platforms/`
  - `clawdhub` - skill registry
  - `marketplace` - AI Skillstore marketplace
- `skills/publishing/`
  - `x-article-publisher-skill` - publish Markdown to X Articles
- `skills/general/`
  - `claude-skills` - Claude skills collection

## Getting started

Clone with submodules:

```bash
git clone --recurse-submodules <repo_url>
```

If you already cloned:

```bash
git submodule update --init --recursive
```

## Add a skill

```bash
git submodule add <repository_url> skills/<category>/<skill_name>
```

Example:

```bash
git submodule add https://github.com/example/playwright-skill skills/frontend/playwright
```

## Updates

Submodules are automatically updated daily via GitHub Actions.
