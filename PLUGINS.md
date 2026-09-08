# Install as plugin -- Free only

Product: **The Buyer Engagement Sales Engine**
Channel: **Free** (library + Fit Chat)
Plugin id: uyer-engagement-sales-engine-free
Display: Buyer Engagement Sales Engine -- Free
Version: **1.0.10-free.1**

This marketplace / plugin ships the **Free** surface only. The paid engine (Boot, _system skills, operating loop) is **not** included.

Repo: https://github.com/gregvanderlinde/buyer-engagement-sales-engine

---

## Claude Code

### Add marketplace from this repo

1. Clone or open this repository.
2. In Claude Code: add marketplace pointing at this repo (marketplace manifest: .claude-plugin/marketplace.json).
3. Install plugin: uyer-engagement-sales-engine-free.

### Or load a local clone

`ash
claude --plugin-dir /path/to/buyer-engagement-sales-engine
`

Skills (namespaced under the plugin):

- ese-free-orient -- what Free is / Golden Wedge overview
- ese-free-fit -- Fit Chat (buy / not-buy)
- ese-free-library -- browse library/ vocabulary and previews

---

## Grok Build

1. Add marketplace from this repo (manifest: .grok-plugin/marketplace.json).
2. Install the same plugin id: uyer-engagement-sales-engine-free.
3. Skills mirror Claude: orient, fit, library.

---

## Version table

| Surface | Version string | Notes |
| --- | --- | --- |
| Free plugin (Claude + Grok) | 1.0.10-free.1 | This repo / this marketplace |
| Paid package (separate) | v1.0.10-beta.3 | Not shipped here |

package_align in VERSION.txt ties Free plugin cut .1 to package 1.0.10.

---

## Explicit boundary

- **In:** Free library, HOW_WE_HELP, Fit Chat, Free skills above
- **Out:** paid engine, Boot, _system, send-gate operating loop, paid depth behind FREE PREVIEW ENDS HERE

Licence: MIT for this Free surface. Author: Greg van der Linde / gregvanderlinde@gmail.com