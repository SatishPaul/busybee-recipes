# BusyBee Recipes

Installable, governed AI recipes for professional-services firms, Tax, Audit, Advisory, and IT Consulting, built on the Microsoft stack (Copilot, Copilot Studio, Azure AI Foundry, Power Platform, Purview, Fabric).

Each recipe generalizes a proven AI workflow into a governed pattern a firm can run, and ships with a copy-paste prompt, an optional Copilot Cowork skill, and a Power Platform solution spec. Every recipe is companion to a "Built in the Hive" article.

This repository is the **source of recipe assets**. It is designed to be imported by the BusyBee marketplace app and browsed directly on GitHub.

> Not affiliated with Microsoft. Microsoft 365 Copilot and Dynamics 365 are trademarks of Microsoft Corporation. Recipes are technology playbooks, not professional (tax, audit, legal) advice.

## How to use a recipe

Each recipe folder under `recipes/<line>/<slug>/` contains:

- **README.md** — business value, what it does, prerequisites, step-by-step, expected output, cost tier.
- **prompt.md** — a runnable, guard-railed copy-paste prompt for Copilot / Copilot Cowork.
- **recipe.yaml** — metadata (surface, plugins, scope, mode, cost tier, license).
- **skill/** — optional installable Cowork skill (drop into `Documents/Cowork/skills/`).
- **power-platform/** — Dataverse tables, flows, and Copilot Studio agent specs.
- **screenshots/** — output previews.

See [`install/how-to-install-a-skill.md`](install/how-to-install-a-skill.md) and [`install/how-to-import-a-solution.md`](install/how-to-import-a-solution.md).

## Catalog

| # | Recipe | Line | Assets | Cost |
|---|--------|------|--------|------|
| 1 | [Regulatory Morning Brief](recipes/tax/regulatory-morning-brief/) | Tax | prompt, skill, Power BI | Medium |
| 2 | [R&D Credit Documentation Engine](recipes/tax/rd-credit-ai-engine/) | Tax | prompt, skill, Power Platform | High |

More recipes are published as their companion articles ship.

## License

Apache License 2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE).
