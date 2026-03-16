# Claude Code Plugins

A Claude Code plugin marketplace by [Lalit Maganti](https://github.com/LalitMaganti).

## Installation

```bash
claude plugin marketplace add LalitMaganti/claude-code-plugin
```

Then install a specific plugin:

```bash
claude plugin install syntaqlite@lalitmaganti-plugins
```

## Available plugins

| Plugin | Description |
|--------|-------------|
| [`syntaqlite`](https://github.com/LalitMaganti/syntaqlite/tree/main/integrations/claude-code) | SQLite SQL language server — diagnostics, formatting, completions, and semantic tokens |

## Adding a new plugin

1. Host the plugin anywhere (e.g. `integrations/claude-code/` in a project repo, or a standalone repo)
2. Add an entry to `.claude-plugin/marketplace.json` with a `github` or `git` source pointing to it

## License

Apache 2.0.
