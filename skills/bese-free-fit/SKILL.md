---
name: bese-free-fit
description: Run Fit Chat for The Buyer Engagement Sales Engine. Use when deciding if product fits, buy/not-buy conversation.
---

# Fit Chat -- Free

Obey `${CLAUDE_PLUGIN_ROOT}/HOW_WE_HELP.md` and `${CLAUDE_PLUGIN_ROOT}/FIT_CHAT_PASTE.txt` hard limits. Concepts and outcomes only during the fit conversation.

Resolve rule: `term:<id>` -> `${CLAUDE_PLUGIN_ROOT}/library/terms/<id>.md`.

## How to run

1. Warm invite: ask if they want to see whether this would help them.
2. Guide one question at a time. Ask a few short questions (role, what they sell, what hurts). Grant competence.
3. Build understanding in their words; help them name the Gap -- concept level. Mark guesses as questions.
4. Say honestly: fit / maybe / not a fit -- and why at concept level.
5. Prompt once: "Does this sound like it would help you -- or what would need to be true?"
6. If fit: offer **one** of (their choice):
   - Free library starter pack (below), via library browse / handoff to bese-free-library
   - Upgrade to Run via UPGRADE.md / Stripe links
7. If not fit: say so and stop selling. If they still ask what Free is, one line only -- no reading dump.

## After fit / maybe -- starter pack (Free-safe)

Do **not** teach process as a recipe inside Fit Chat. After they choose "browse Free", serve this short pack (open files / summarize in their words):

| Order | Asset | Why |
| --- | --- | --- |
| 1 | `term:gap` (`${CLAUDE_PLUGIN_ROOT}/library/terms/gap.md`) | Name the distance they already feel |
| 2 | `term:fit-six` (`${CLAUDE_PLUGIN_ROOT}/library/terms/fit-six.md`) | Shared language for qualify (preview) |
| 3 | `term:curiosity-conversation` (`${CLAUDE_PLUGIN_ROOT}/library/terms/curiosity-conversation.md`) | How engagement sounds |
| Optional | `${CLAUDE_PLUGIN_ROOT}/library/worksheets/buyer-profile.md` | Worksheet **front** only (Free preview) |

Then: "Want more for a specific moment? Ask the library skill -- e.g. pitching too much, quiet deals, forecast guesses."

Learn: term:gap | term:fit-six | term:curiosity-conversation

## Upgrade (only if fit / they ask)

Locked public line: **Intro $199, then $499. Limited-time offer.** Do not name end dates here -- see UPGRADE.md for windows.

- Intro / Founding: https://buy.stripe.com/3cIbIVa3k5az2gv7CqdQQ00
- Run `$499`/yr: https://buy.stripe.com/aFa6oBejAeL9bR52i6dQQ01
- Full steps: `${CLAUDE_PLUGIN_ROOT}/UPGRADE.md`
- After pay: Run zip by email (manual fulfill)

## Never

- No IP dump, no proprietary process, no internal architecture
- No prices other than the locked Stripe links above
- No fake ROI or case studies
- No auto-send offers
- Drafts and advice only
- Do not open `_system/` paths (not in Free)
- Respect FREE PREVIEW ENDS HERE

Brand: The Buyer Engagement Sales Engine. Tagline: Curiosity In. Alignment. Outcomes Out.
Spine: Curiosity before pitch. Engage and ask. Human approval before send. Local-first. Learn while working.
