---
name: design-scout
description: Research-first website design. Before designing or building any website, landing page, homepage, portfolio, store or marketing page, scout real design references on Dribbble, Behance, Awwwards, Land-book, Lapa Ninja, One Page Love, SiteInspire, Mobbin, Refero, Typewolf, Colors & Fonts and similar galleries, turn them into a written design brief (layout, type, colour, signature element), get the user's sign-off, then build to that brief. Use this whenever the user asks to design, build, create, redesign or "make" a website or landing page, asks for design inspiration, references or a moodboard for a site, or complains that a design looks generic, templated, AI-made or like slop, even if they never say the word "inspiration".
---

# Design Scout

Websites designed from memory come out as the average of every website: centred hero, gradient blob, three feature cards, a font nobody chose. Good designers avoid this by looking at real work before they draw anything. This skill makes that the default: look first, decide on purpose, then build.

The flow is five steps. Do not skip the research to save time. The research is what saves the time, because it replaces rounds of "this looks generic, try again".

1. Intake: learn the business
2. Scout: collect real references
3. Brief: turn references into decisions
4. Checkpoint: user approves the direction
5. Build and check against the brief

## 1. Intake

You need three things before any research. Ask for whatever is missing, in one message:

- **Niche**: what kind of website (dental clinic, B2B SaaS for invoicing, streetwear store)
- **Name**: the business or product name
- **About**: what it does or sells, who for, what makes it different

If the user already gave these, do not ask again.

In the same message, offer these optional questions and make it clear they can skip them. Each one sharpens the research a lot, but none should block you:

- Who is the audience, and what is the one action the site should get them to take?
- Three words for how it should feel (calm, loud, premium, playful, technical...)
- Any sites they love or hate, in any industry?
- Existing brand assets: logo, colours, fonts, photos?
- Which pages or sections are needed, and what stack to build in?

For anything skipped, pick a sensible default and state it in the brief as an assumption so the user can correct it.

## 2. Scout

Read `references/sources.md` now. It lists every source, what each is good for, how to search it, and which ones block plain fetching.

**Plan the queries first.** Write down 4 to 6 search phrases before opening anything: the niche itself ("dental clinic website"), the page type ("booking landing page"), the mood words ("calm editorial"), and one adjacent niche whose design culture is stronger than this one's (a dentist can learn from skincare brands; an accounting tool from Linear-style dev tools). The adjacent query matters: if you only look inside the niche, you reproduce the niche's clichés.

**Cover four lenses**, not eighteen sites. The sources file groups the sites by lens. Use at least one source from each, more where the first comes up thin:

| Lens | Question it answers |
|---|---|
| Live websites | How do real, shipped sites in this space lay out a page? |
| UI patterns | How do good products solve this specific section (pricing, nav, booking form)? |
| Visual mood | What could it feel like: imagery, texture, colour, art direction? |
| Type and colour | Which specific fonts and palette? |

**Also look at 2 or 3 direct competitors** of the business (plain web search). Not to imitate, but to learn what visitors in this niche expect and to see what everyone does, so the design can stand apart from it.

**Go to the real site.** Gallery thumbnails are small and often outdated. When a gallery entry looks promising, open the live website it points to and look at that. Take a screenshot if you have a browser tool; reading the HTML alone tells you the structure but not how it feels.

**Record each keeper** as you go. Aim for 6 to 10 across the lenses. For each one:

- Name and URL (the real URL you actually opened)
- What specifically works: be concrete ("oversized serif headline set flush left against a narrow product photo", not "clean and modern")
- The one thing to borrow from it
- What to leave behind

Vague notes produce vague designs. If you cannot say what is specifically good about a reference, drop it.

**Honesty rule.** Only cite references you actually loaded in this session. Never invent a site, a URL or a description of a page you did not see: a fabricated reference is worse than none, because the user will trust it. If a source is blocked, login-walled or empty, say so and use another. If you have no web access at all, tell the user plainly that the research step cannot run, and ask whether they want to paste links or screenshots, or proceed from general knowledge with that caveat stated.

**Scale to the job.** A full site gets the full pass. For a single section or a "quick" request, do a short pass: 2 queries, 3 or 4 references, a brief of a few lines. Do not drop to zero.

## 3. Brief

Turn the references into decisions. Use the template in `references/brief-template.md` and save it as `design-brief.md` in the project, so the direction survives the conversation and later work can be checked against it.

The brief must commit. Every item is a specific choice with a reason traced to a reference or to the business:

- **Concept** in one sentence: the idea that makes this site this business's and no one else's
- **Layout**: section by section, with the structural idea for each
- **Type**: named fonts, where each is used, and where to get them (check the licence; prefer fonts that are free for commercial use, such as Google Fonts or Fontshare, unless the user has a licence)
- **Colour**: hex values with roles (background, text, accent, etc.), checked for readable contrast
- **Signature element**: the one thing a visitor would remember and describe to someone else
- **Imagery and motion**: what kind, and how restrained
- **Will not do**: the niche clichés and generic patterns this design deliberately avoids

Borrow principles, not property. Take the idea (an asymmetric grid, a type pairing, a way of pacing sections) and never the reference's logo, images, illustrations, copy or a pixel-level clone of its layout. Mix ideas from several references so the result is no one's copy.

## 4. Checkpoint

Show the user the direction before building: the concept line, the 3 or 4 strongest references with links, palette, fonts, section outline, signature element. Keep it short enough to read in a minute.

Where the references pulled in two clearly different directions, offer both as A and B with a recommendation, rather than averaging them into something bland.

Wait for a yes or for changes. Building a whole site on an unapproved direction is the expensive mistake this step exists to prevent. The one exception: if the user said up front to just build it without checking in, proceed and show the brief alongside the result.

## 5. Build and check

Build to the brief in the user's stack. If another skill for frontend or design implementation is available, use it for the build and treat the brief as its input.

While building:

- Write real copy for this business, in its voice. No lorem ipsum, and no filler like "Elevate your workflow".
- Never invent testimonials, customer logos, statistics, awards or reviews. If a section needs them, put a clearly marked placeholder and tell the user what to supply.
- Design mobile on purpose, not as a squeezed desktop.
- Keep text contrast readable and interactive elements keyboard-reachable.

When the build is done, read `references/slop-check.md` and run it against the result. Then look at it: open the page, take screenshots at desktop and phone widths if you can, and compare with the brief and the references. Ask of each section: would this pass in the galleries you just searched? Fix what falls short before presenting.

Present the result with a short note: what was built, which references shaped which decisions, any placeholders the user needs to fill, and what you could not verify.
