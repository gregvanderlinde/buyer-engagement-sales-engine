# FreeWire v2 -- 1.0.10-free.7 (2026-09-10 PT)

Defect + doc-drift fixes from the live-install test (Docs_Working 5075 v2). No content/method change; no product-scope change.

- **Path fix (the real defect):** all bundled-file references in the three skills (bese-free-orient, bese-free-fit, bese-free-library) now resolve via `${CLAUDE_PLUGIN_ROOT}/...` instead of bare relative paths. Bare paths resolved against the user's cwd, so `bese-free-library` intermittently failed to find its own `library/` and reported content missing. This was the highest-value fix.
- **End dates removed:** dropped "through 2026-09-18" from bese-free-orient, bese-free-fit, FIT_CHAT_PASTE.txt, UPGRADE.md, and PLUGINS.md. Founding is now "limited-time offer" only -- matches HOW_WE_HELP.md ("do not name end dates"). Resolves the rule the skills were violating on every upgrade prompt.
- **Typo:** `$275$350` -> `$275-$350` in library/entries/does-coaching-deal-size-affect-interactions.md and its preview_html mirror.
- **Version table refreshed:** free.6 -> free.7 across plugin.json + marketplace.json (Claude + Grok), VERSION.txt, PLUGINS.md; paid-package cross-ref corrected beta.3 -> beta.5 (VERSION.txt was already beta.5).

Not submitted to any directory (separate Greg GO). Grok-marketplace add-your-own-source route still unconfirmed (5075 section 5).
