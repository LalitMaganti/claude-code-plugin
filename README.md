# syntaqlite — Claude Code Plugins

Claude Code plugin marketplace for the [syntaqlite](https://github.com/LalitMaganti/syntaqlite) project.

## Installation

```bash
claude plugin marketplace add LalitMaganti/claude-code-plugin
```

## Available plugins

| Plugin | Description |
|--------|-------------|
| `syntaqlite` | SQLite SQL language server — diagnostics, formatting, completions, and semantic tokens |

## Adding a new plugin

1. Create the plugin in the main repo under `integrations/<name>/`
2. Add an entry to `.claude-plugin/marketplace.json` pointing to it

## License

Apache 2.0.
