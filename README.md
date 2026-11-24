# Devault for Claude

Research real UI design while you work. [Devault](https://devault.design) is a library of design references
(screens from shipped websites and mobile apps, complete user flows, marketing emails, year-by-year redesigns and
original interface concepts) and of ready-made design systems. This repository holds Devault's plugin for Claude.

## Install

In Claude Code:

```
/plugin install devault --marketplace devault-design/claude-plugin
```

Or add the marketplace first, then install:

```
/plugin marketplace add devault-design/claude-plugin
/plugin install devault@devault
```

On claude.ai, Claude Desktop and Cowork, install Devault from the plugin directory, then connect it on the plugin's
Connectors tab.

The first time Claude calls a Devault tool you sign in to Devault in your browser and approve the connection. You
need a Devault account whose plan includes MCP access.

## What's inside

- [`plugins/devault`](plugins/devault): the plugin. It connects Claude to Devault's MCP server at
  `https://devault.design/api/mcp` (nine read-only tools) and adds three skills: `research-ui-patterns`,
  `apply-design-system` and `get-started`.

See the [plugin's README](plugins/devault/README.md) for what you can ask.

## Links

Website: https://devault.design · Support: https://devault.design/support · Privacy: https://devault.design/privacy ·
Terms: https://devault.design/terms

Devault is a product of HYDRANODE LTD. See [LICENSE](LICENSE).
