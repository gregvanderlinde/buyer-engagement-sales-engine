---
name: bese-free-library
description: Browse Free library terms, preview entries, worksheets, paths. Use when learning vocabulary or opening library files. Routes selling moments to term/entry/worksheet packs.
---

# Free library browse

Help the user navigate library/ while they work -- learn as you go, not a homework course.

Resolve rule: `term:<id>` -> `library/terms/<id>.md`. Matching preview entry: `library/entries/<id>.md` when present.

## Map

- library/entries/ -- preview entries (teasers)
- library/terms/ -- term cards
- library/worksheets/ -- worksheet fronts (many are pointers; respect FREE PREVIEW ENDS HERE)
- library/paths/ -- guided paths
- library/GLOSSARY.md -- vocabulary index

## Gates

Respect **FREE PREVIEW ENDS HERE** lines. Do not invent or paste paid depth beyond the Free files in this repo.
Never tell a Free user to open `_system/templates/...` as if it exists here -- that is Run. Point to the Free worksheet front under `library/worksheets/` instead, and say the full form body is in Run.

## Situational router (advice -> assets)

When they describe a moment (or ask "what should I read"), serve **2-4** assets max. Open files; summarize in their words; offer related terms without dumping the library.

| If they say / mean | Serve first | Also | Worksheet front (optional) |
| --- | --- | --- | --- |
| What is this / where to start | `library/GLOSSARY.md` + `term:buyer-engagement` | `term:engage-not-pitch-and-prove` | -- |
| I pitch / feature-dump | `term:engage-not-pitch-and-prove` | `term:why-curiosity` + entry same ids if present | -- |
| First conversation / what to ask | `term:curiosity-conversation` | `term:engagement-questions`, `term:seed-dont-shame` | -- |
| Deals go quiet / no next step | `term:dont-give-without-getting` | `term:continuum`, `term:send-gate` | -- |
| Are we even a fit / qualify | `term:fit-six` | `term:why-walk-zero-fit`, `term:gap` | `library/worksheets/bid-or-no-bid-assessment.md` |
| Who decides / stuck with one contact | `term:power-map` | `term:why-multithread` | -- |
| Numbers / value / proof | `term:qualified-outcomes` | `term:why-ratios` | `library/worksheets/qualified-outcomes-form.md` |
| Forecast is a guess | `term:completeness` | `term:qualified-outcomes` | `library/worksheets/continuum-completeness.md` |
| Style / how to talk to them | `term:cprd` | `term:selling-to-buyers-cprd`, `term:knowing-yourself-cprd` | `library/worksheets/cprd-self-read.md` |
| Know myself / Edge / ICP | `term:edge`, `term:icp` | `term:discovery`, `term:seller-brief` | `library/worksheets/understand-yourself-self-assessment.md` |
| Know the customer / role | `term:know-thy-customer` | `term:ideal-buyer` | `library/worksheets/role-jd-read.md`, `buyer-profile.md` |
| Prospecting / pipeline fill | `term:prospecting` | `term:qualified-outcomes-prospecting` | warm/cold/referral script fronts |
| First 30 days / build a process | `library/paths/new-to-sales.md` | follow that path's Serve lines (Free-safe) | per path step |
| Want the engine / Boot / send gate live | Point to **UPGRADE.md** only | -- | -- |

After serving, one line footer style:
`Learn: term:<id> | term:<id> | term:<id>`

## Behavior

- Open the file they ask for; summarize in their words
- Prefer the router table when the ask is situational
- Keep Free vs paid clear: this surface is Free only
- Obey HOW_WE_HELP.md -- no proprietary rebuild help
