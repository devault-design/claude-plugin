# Devault for Claude

Research real UI design while you work. Devault is a library of design references: screens from shipped
websites and mobile apps, complete user flows, marketing emails, year-by-year redesigns and original interface
concepts, plus a library of ready-made design systems.

This plugin connects Claude to Devault's MCP server and adds three skills that teach Claude to use it well.

## Install

In Claude Code:

```
/plugin install devault --marketplace devault-design/claude-plugin
```

On claude.ai, Claude Desktop and Cowork, install it from the plugin directory and connect Devault on the plugin's
Connectors tab.

## What you can ask

- "Find onboarding screens from fintech apps."
- "How do apps design paywalls? Give me the numbers and a few examples."
- "Get me a dark dashboard design system as Tailwind tokens."
- "Find a checkout screen from an e-commerce app, then screens that look like it."

## What it includes

| | |
|---|---|
| **MCP server** | `https://devault.design/api/mcp`: nine read-only tools to search screens, analyze a pattern across the library, look at a screen closely, find similar screens, see what the library holds for a company, and fetch design systems |
| **Skills** | `research-ui-patterns`, `apply-design-system`, `get-started` |

Design systems come in nine formats: DESIGN.md, Tailwind v4, CSS variables, shadcn/ui, W3C design tokens, Figma
variables, SwiftUI, Android XML and an image prompt.

## Requirements

A Devault account whose plan includes MCP access. The first time Claude calls a Devault tool you sign in to
Devault in your browser and approve the connection; you can revoke it at any time.

## Good to know

- Every tool only reads. Nothing here can change your Devault account.
- A search returns one page of results, and the number of images is limited per day.
- Screens are references for study and inspiration. The companies shown are not affiliated with Devault.

## Links

- Website: https://devault.design
- Support: https://devault.design/support
- Privacy: https://devault.design/privacy
- Terms: https://devault.design/terms

Devault is a product of HYDRANODE LTD.
