# design-scout

A Claude skill for research-first website design.

Websites designed from memory come out generic: centred hero, gradient blob, three feature cards. This skill makes Claude look at real design work before it designs anything, write down what it decided and why, and get your approval before it builds.

## What it does

1. **Intake.** Asks for the niche, the name, and what the business or product does. Offers a few optional questions (audience, feel, sites you like, brand assets).
2. **Scout.** Searches design galleries for real references, plus two or three direct competitors and one better-designed neighbouring niche.
3. **Brief.** Writes a `design-brief.md` with a concept, section-by-section layout, named fonts, a hex palette, a signature element and a "will not do" list.
4. **Checkpoint.** Shows you the direction and waits for a yes or changes.
5. **Build and check.** Builds to the brief, then runs a slop check and compares screenshots against the references.

It only cites pages it actually opened, and it never invents testimonials, logos or statistics.

## Sources it searches

| Lens | Sites |
|---|---|
| Live websites | Land-book, Lapa Ninja, One Page Love, SiteInspire, Awwwards, Recent |
| UI patterns | Mobbin, Refero, Collect UI |
| Visual mood | Dribbble, Behance, Layers, Muzli, Savee, Cosmos, Pinterest |
| Type and colour | Typewolf, Colors & Fonts |

Some of these block plain fetching or need a login for full results. The skill works best when Claude has web search and a browser tool; see `references/sources.md` for how each site is reached.

## Install

**Claude Code:** clone into your skills folder.

```bash
git clone https://github.com/Ikarunaa/design-scout.git ~/.claude/skills/design-scout
```

**Claude apps:** download `design-scout.skill` from this repo and add it under Settings → Capabilities → Skills.

## Use

Ask Claude to design or build a website, or run it by name:

```
/design-scout
```

## Files

- `SKILL.md`: the workflow
- `references/sources.md`: the 18 galleries, what each is for, how to search it
- `references/brief-template.md`: the design brief format
- `references/slop-check.md`: the checklist of generic-design tells
- `design-scout.skill`: the packaged skill
