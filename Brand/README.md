# The Oracles — Brand

This folder is the source of truth for how The Oracles presents itself. It is read by humans **and** by Claude, so every teammate gets the same brand applied to their work automatically.

## What's in here

- `_machine-readable/brand.json` — token spec (colors, type, components, platform sizes). Update here first; everything else derives from it.
- `the-oracles-brand/SKILL.md` — the installable Claude skill. Once installed, Claude pulls these rules into any task for The Oracles.
- `02_Templates/Social Media/` — finished social asset templates (X, IG, YT, LI, FB).
- *(coming next)* `01_Foundation/`, `03_Components/`, `04_Photo+Video/`, `Guidelines.pdf`

**Rule:** *All* brand-related assets (logos, templates, mockups, exports, guidelines, marketing collateral) live under this folder. Do not create sibling brand folders at the workspace root.

## For teammates: install the skill (one time, ~2 minutes)

1. Open Cowork on your Mac.
2. In chat: `Install the the-oracles-brand skill from OneDrive: The Oracles / Brand / the-oracles-brand`
3. Cowork will copy `SKILL.md` into your local skills directory.
4. Test it: ask Claude to "draft an Instagram caption for our next release." It should hit the right tone and reference the wordmark and accent rule.

If your Cowork doesn't have the OneDrive connector set up, ask RobotAdmin — they'll walk you through it once.

## For teammates: how to use it

Just work normally. The skill loads automatically when:
- You mention The Oracles, theoracles.studio, BTS/MMXXVI
- You ask for social posts, decks, captions, thumbnails, donor copy, or layout reviews

You don't have to type "use the brand skill" — that's the whole point.

## Three sample prompts to try first

1. *"Draft three caption variants for an Instagram BTS reel of our last shoot."*
2. *"Design an Instagram story announcing a new episode — paper version and dark version."*
3. *"Review this slide layout for brand fit"* (drop in an image).

## When to update brand.json

Almost never on your own. The Filmmaker owns the brand; RobotAdmin transcribes. If you think something should change, open a thread — don't edit `brand.json` directly. The skill won't pick up edits until they're approved and pushed back to OneDrive.

Cadence: quarterly retro. What did Claude get wrong? What new patterns emerged? Update once, push, done.

## Governance — the boring part that keeps this working

- **Owner**: The Filmmaker
- **Scribe**: RobotAdmin
- **Approvals required for**: new color tokens, new fonts, any wordmark proportion or color change
- **Changelog**: keep a `CHANGELOG.md` in this folder. Date + one-line "why" per change.
- **Audit**: once a quarter, run the `design:design-system` skill against the live site and recent outputs. Flag drift.

## Companion skills already installed in Cowork

These pair with `the-oracles-brand` and are worth knowing about:

- `design:design-critique` — "review this design"
- `design:ux-copy` — "what should this button say"
- `design:accessibility-review` — "audit this for a11y"
- `design:design-handoff` — "generate dev specs from this mockup"
- `design:design-system` — quarterly audit

Use them. They already speak the same language as `the-oracles-brand`.
