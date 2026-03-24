# Clave Marketplace

Plugin marketplace for the Clave desktop app.

## Structure

```
clave-marketplace/
├── .claude-plugin/marketplace.json   # Marketplace registry
└── plugins/
    └── workspace-builder/            # Plugin: workspace file builder
        ├── .claude-plugin/plugin.json
        └── skills/
            └── create-workspace/     # Skill: create .clave files
                └── SKILL.md
```

## Adding plugins

Each plugin lives in `plugins/<name>/` with a `.claude-plugin/plugin.json` and one or more skills in `skills/<skill-name>/SKILL.md`.

Register new plugins in `.claude-plugin/marketplace.json`.
