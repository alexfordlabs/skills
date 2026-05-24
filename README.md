<!--
Author: Alexander Ford <alex@alexfordlabs.com>
Repository: https://github.com/alexfordlabs/skills
License: MIT
-->

# Alex Ford Labs — Claude Code plugins

The public [Claude Code](https://docs.claude.com/en/docs/claude-code) plugin marketplace for **Alex Ford Labs**. A growing collection of design-first developer tooling.

## Add the marketplace

```
/plugin marketplace add alexfordlabs/skills
```

Then browse and install:

```
/plugin
```

Each plugin installs under the `@alexfordlabs` namespace (e.g. `project-architect@alexfordlabs`).

## Plugins

| Plugin | What it does |
|---|---|
| **[project-architect](https://github.com/alexfordlabs/project-architect)** | Bootstraps any project end-to-end through an interactive, design-first workflow — research-augmented questioning, ADR-tracked decisions, parallel design-doc generation, a quality-gate auditor, and project-local `CLAUDE.md` + `.claude/` configuration. |
| **[reverse-engineer](https://github.com/alexfordlabs/reverse-engineer)** | The companion pointed the other way: recovers a design from a foreign/brownfield project (inventory → dependency map → live current-version research → inferred requirements → reviewable `RECOVERED_DESIGN.md`) and hands it back to project-architect through a shared state contract. |

The two interoperate: reverse-engineer recovers an existing codebase into the same flat decisions keyspace project-architect bootstraps into, so you can analyze, then continue building, with one shared state model.

## Releases

Plugins are versioned independently in their own repositories; this marketplace resolves each to its latest published release. See each plugin repo's `CHANGELOG.md` for history.

---

*Maintained by [Alex Ford Labs](https://github.com/alexfordlabs). MIT licensed.*
