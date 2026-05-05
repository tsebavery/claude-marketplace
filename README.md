# tsebavery-marketplace

Claude Code plugin marketplace by tsebavery — industrial automation and
workflow tooling.

## Installation

```bash
claude /plugin marketplace add tsebavery/claude-marketplace
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [device-recon](https://github.com/tsebavery/recon-plugin) | Industrial device reconnaissance toolkit — web UI crawling, protocol discovery, descriptor parsing, OT-safe security auditing |
| [readiness](https://github.com/tsebavery/project-readiness-plugin) | Portable Claude Code readiness assessment — inventories any repo, fetches current best practices live, produces an actionable upgrade plan |

### Install a plugin

```bash
claude /plugin install device-recon@tsebavery-marketplace
claude /plugin install readiness@tsebavery-marketplace
```

After installing `readiness`, run `/readiness:init` once per project to
bootstrap the per-project profile, then `/readiness:assess` to run the
assessment.
