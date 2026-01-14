# Skills Organization

This directory contains AI skills organized by category. Each skill is added as a git submodule to ensure they stay up-to-date with their respective upstream repositories.

## Directory Structure

- `coding/`: Skills related to software development, refactoring, and language-specific patterns.
- `frontend/`: Skills for UI/UX engineering, CSS/styling, and component development.
- `research/`: Skills for deep analysis, information gathering, and documentation reading.
- `devops/`: Skills for CI/CD, deployment, and infrastructure management.
- `general/`: General-purpose skills that don't fit into a specific category.

## Adding a New Skill

To add a new skill, use the following command:

```bash
git submodule add <repository_url> skills/<category>/<skill_name>
```

Example:
```bash
git submodule add https://github.com/example/playwright-skill skills/frontend/playwright
```

## Automatic Updates

Submodules are automatically updated daily via GitHub Actions.
