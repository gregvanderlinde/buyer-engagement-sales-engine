# Install as plugin -- Free only
## Version 1.0.10-free.5

Product: **The Buyer Engagement Sales Engine**
Channel: **Free** (library + Fit Chat)
Plugin id: `buyer-engagement-sales-engine-free`
Display: Buyer Engagement Sales Engine -- Free
Version: **1.0.10-free.5**

Repo: https://github.com/gregvanderlinde/buyer-engagement-sales-engine

This marketplace / plugin ships the **Free** surface only. The paid engine (Boot, `_system` skills, operating loop) is **not** included.

---

## Boundary: Free vs paid

| | Free (this repo / this plugin) | Paid (separate package) |
| --- | --- | --- |
| What | Library previews, HOW_WE_HELP, Fit Chat, three Free skills | Full engine: Boot, `_system`, send-gate operating loop, paid library depth |
| Install | Plugin / marketplace from this GitHub repo | Separate Run package (Stripe / fulfill when open) |
| Expect | Orient, Fit Chat, browse `library/` | Do **not** expect Boot or engine skills from Free |

---

## Claude Code -- click-by-click

### Path A -- from GitHub (preferred)

1. Open https://github.com/gregvanderlinde/buyer-engagement-sales-engine
2. Clone or Download ZIP; unzip to a durable folder (keep the folder; do not delete `.claude-plugin/`).
3. Open Claude Code in a terminal.
4. Add marketplace: `/plugin marketplace add` with the path or git URL to this repo (manifest at `.claude-plugin/marketplace.json`).
5. Install: `/plugin install buyer-engagement-sales-engine-free` (or via `/plugin` UI).
6. `/reload-plugins` if prompted.
7. Try `/buyer-engagement-sales-engine-free:bese-free-orient` then fit and library skills.

### Path B -- local test without marketplace

```bash
claude --plugin-dir /path/to/buyer-engagement-sales-engine
```

Replace `/path/to/buyer-engagement-sales-engine` with your durable clone folder.

---

## Grok Build -- click-by-click

1. Same clone of the GitHub repo (https://github.com/gregvanderlinde/buyer-engagement-sales-engine).
2. In Grok Build: open Marketplace / `/marketplace` or config marketplace sources.
3. Add this repo as marketplace (manifest: `.grok-plugin/marketplace.json`).
4. Install `buyer-engagement-sales-engine-free`.
5. Run skills: `bese-free-orient`, `bese-free-fit`, `bese-free-library`.

---

## Skills table

| Skill folder | What |
| --- | --- |
| `bese-free-orient` | What Free is / Golden Wedge |
| `bese-free-fit` | Fit Chat |
| `bese-free-library` | Browse `library/` |

On Claude Code, skills are namespaced under the plugin, e.g. `/buyer-engagement-sales-engine-free:bese-free-orient`.

---

## Version table

| Surface | Version string | Notes |
| --- | --- | --- |
| Free plugin (Claude + Grok) | **1.0.10-free.5** | This repo / this marketplace |
| Paid package (separate) | v1.0.10-beta.3 | Not shipped here |

`package_align` in VERSION.txt ties Free plugin cut `.2` to package `v1.0.10-beta.3`.

---

## Explicit boundary (in / out)

- **In:** Free library, HOW_WE_HELP, Fit Chat, Free skills above
- **Out:** paid engine, Boot, `_system`, send-gate operating loop, paid depth behind FREE PREVIEW ENDS HERE

---

## Not yet (honest)

Official Anthropic community directory submit / xAI marketplace PR -- separate Greg GO; this repo is installable as your own marketplace now.

---

Licence: MIT for this Free surface. Author: Greg van der Linde / gregvanderlinde@gmail.com
---

## Upgrade to Run (paid)

Free plugin does **not** include the engine. To buy Run:

See **[UPGRADE.md](UPGRADE.md)** -- Stripe links for Founding $199 (through 2026-09-18) and Run $499/yr.

After pay: manual zip fulfill by email. Free skills stay Free.
