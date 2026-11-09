# Sources

Eighteen galleries, grouped by the question each answers. Use at least one per lens.

## How to reach them

Sites differ in how they can be read. Try in this order:

1. **Direct fetch** of the URL pattern below. Works for the sites marked *fetch OK*.
2. **A real browser tool**, if you have one. Needed for sites marked *browser*, which reject plain fetches (403/429) or render everything with JavaScript. A browser also lets you take screenshots, which is the best way to judge a design.
3. **Web search with `site:`**, for example `site:land-book.com fintech`. Works for every site and is the fallback when the two above fail. Results give you entry pages you can then open.

Sites marked *login* show only a preview without an account. Use what is public; do not try to sign in, create accounts or get around a wall. If the user is signed in within a browser you control, their session may show more.

URL patterns change. If one 404s, do not guess further: fall back to `site:` search.

Replace `{q}` with a URL-encoded query and `{slug}` with a hyphenated one.

## Lens 1: Live websites

Real, shipped sites. Best source for layout, page structure and pacing. Each entry links to a live site: open it.

| Site | Best for | How to search | Access |
|---|---|---|---|
| Land-book | Landing pages, widest range of niches | `https://land-book.com/?search={q}` | browser |
| Lapa Ninja | Landing pages by industry category, full-page captures | `https://www.lapa.ninja/category/{slug}/` or `/search/?q={q}` | browser |
| One Page Love | Single-page sites, by type and industry | `https://onepagelove.com/?s={q}` or `/inspiration/{slug}` | fetch OK |
| SiteInspire | Curated, restrained, editorial and agency work; filters by style and type | `https://www.siteinspire.com/` then search or filter | browser (rate-limits) |
| Awwwards | Ambitious, award-level, heavy on motion and interaction | `https://www.awwwards.com/inspiration_search/?text={q}` or `/websites/{category}/` | fetch OK |
| Recent | A feed of freshly launched, well-designed sites; good for what is current | `https://recent.design/` (browse; little search) | fetch OK |

Awwwards work is often impractical for a small business site (slow, heavy, hard to build). Use it for one bold idea, not as the template.

## Lens 2: UI patterns

How real products solve a specific screen or section: pricing tables, navigation, onboarding, checkout, dashboards, forms.

| Site | Best for | How to search | Access |
|---|---|---|---|
| Mobbin | Screens and flows from real shipped apps and web products | `https://mobbin.com/browse/web/apps` | login for most |
| Refero | Real web product screens, searchable by page type and element | `https://refero.design/search?query={q}` | login for most |
| Collect UI | Element-level examples by category (landing page, pricing, sign up, 404...) | `https://collectui.com/challenges/{slug}` | fetch OK |

Collect UI is sourced from Dribbble shots, so treat it as concept work (see below).

## Lens 3: Visual mood

Art direction, imagery, texture, colour feeling. Use to decide how it should feel, not how it should be structured.

| Site | Best for | How to search | Access |
|---|---|---|---|
| Dribbble | Polished UI shots, illustration, branding | `https://dribbble.com/search/{slug}` | browser |
| Behance | Full case studies: brand systems, complete web projects with reasoning | `https://www.behance.net/search/projects?search={q}` | browser |
| Layers | Designer community posts, current product and web design | `https://www.layers.to/` (browse) | fetch OK, JS-heavy |
| Muzli | Curated daily design picks and search across sources | `https://search.muz.li/` or `site:muz.li {q}` | browser |
| Savee | Moodboard images: posters, layouts, photography, type | `https://savee.it/search/?q={q}` | login for most |
| Cosmos | Moodboard collections, strong on art direction and photography | `https://www.cosmos.so/` | login for most |
| Pinterest | Broadest moodboard source for any niche | `https://www.pinterest.com/search/pins/?q={q}` | browser, login prompts |

**Concept work warning.** Dribbble, Collect UI and much of Pinterest show mockups that were never built: no real content, no mobile version, no constraints. They are fine for mood, colour and a single visual idea. Do not take page structure from them; take structure from Lens 1.

## Lens 4: Type and colour

| Site | Best for | How to search | Access |
|---|---|---|---|
| Typewolf | Which fonts good sites actually use, pairings, free alternatives | `https://www.typewolf.com/site-of-the-day`, `/google-fonts`, `/fonts/{slug}` | fetch OK |
| Colors & Fonts | Ready palettes with hex values, font pairings, gradients | `https://www.colorsandfonts.com/` | fetch OK |

Typewolf often names commercial fonts. Before committing to one, check the licence; if it is paid and the user has no licence, use Typewolf's suggested free alternative or a comparable face from Google Fonts or Fontshare.

The most reliable type and colour source is still the live sites you kept from Lens 1: inspect what they use (font names in the CSS, colours in the styles) and note it.

## Query tips

- Search the niche, then the page type, then the mood, then an adjacent niche. One query per site is rarely enough; two different queries on one good site beat one query on four.
- Gallery search is tag-based and literal. "dentist" may return nothing where "health" or "medical" returns plenty. Go broader if a query is empty.
- If a niche has almost no good examples (many local-service niches), that is useful: the bar is low, and borrowing from an adjacent, better-designed niche will stand out.
- Prefer recent work. A gallery entry several years old may point to a site that has since changed or died.
