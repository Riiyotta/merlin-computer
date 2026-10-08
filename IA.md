# https://www.merlin.computer//

Source: https://www.merlin.computer// · website-builder crawl, 2026-10-07T11:14:27Z
Status: **measured-from-mirror** · production approved: **false**
27 routes · 7 templates · 22 unique sections

> Generated from `ia.json` by `build.mjs`. Edit the JSON, not this file.

## Shape of the site

The largest 3 templates (Blog posts, Legal pages, Home) account for 23 of 27 routes (85%). The remaining 4 routes span 4 templates.

| template | routes | share |
|---|---:|---:|
| Blog posts | 20 | 74% |
| Legal pages | 2 | 7% |
| Home | 1 | 4% |
| Pricing | 1 | 4% |
| Manifesto | 1 | 4% |
| Download | 1 | 4% |
| Blog | 1 | 4% |

## Page chrome

**27 routes carry chrome = `partial`** — Home, Pricing, Manifesto, Download, Legal pages, Blog, Blog posts.

## Sections by reuse

How widely a section is shared determines whether it belongs in a shared
component library or stays local to its page.

| section | category | templates | routes | scope |
|---|---|---:|---:|---|
| `shell.closing-footer` | SHELL | 6 | 26 | Appears on 26 routes. |
| `shell.skip-link` | SHELL | 6 | 26 | Appears on 26 routes. |
| `shell.page-nav` | SHELL | 4 | 24 | Appears on 24 routes. |
| `content.blog-content-article` | CONTENT | 1 | 20 | Appears on 20 routes. |
| `hero.story-hero` | HERO | 2 | 2 | Appears on 2 routes. |
| `content.legal-content` | CONTENT | 1 | 2 | Appears on 2 routes. |
| `commerce.pricing-plans` | COMMERCE | 1 | 1 | Appears on 1 route. |
| `content.blog-content` | CONTENT | 1 | 1 | Appears on 1 route. |
| `content.manifesto` | CONTENT | 1 | 1 | Appears on 1 route. |
| `features.browser` | FEATURES | 1 | 1 | Appears on 1 route. |
| `features.companion` | FEATURES | 1 | 1 | Appears on 1 route. |
| `features.install-merlin-in-three-steps` | FEATURES | 1 | 1 | Appears on 1 route. |
| `features.meetings` | FEATURES | 1 | 1 | Appears on 1 route. |
| `features.merlin-in-your-everyday` | FEATURES | 1 | 1 | Appears on 1 route. |
| `features.pricing-included` | FEATURES | 1 | 1 | Appears on 1 route. |
| `features.privacy` | FEATURES | 1 | 1 | Appears on 1 route. |
| `features.routines` | FEATURES | 1 | 1 | Appears on 1 route. |
| `hero.install-intro` | HERO | 1 | 1 | Appears on 1 route. |
| `proof.used-by-professionals-at` | PROOF | 1 | 1 | Appears on 1 route. |
| `shell.install-header` | SHELL | 1 | 1 | Appears on 1 route. |
| `support.faq` | SUPPORT | 1 | 1 | Appears on 1 route. |
| `support.pricing-faq` | SUPPORT | 1 | 1 | Appears on 1 route. |

**4 shared sections** appear in more than one template and belong in a component library.

**18 single-use sections** appear in exactly one template. Building these
as "reusable" components up front would be speculative — keep them page-local
until a second caller actually appears.

## Templates

### Home — `template.home`

1 route · `/` · chrome: **partial**

| # | category | section | |
|---:|---|---|---|
| 1 | SHELL | `shell.skip-link` | shared ×6 |
| 2 | HERO | `hero.story-hero` | shared ×2 |
| 3 | FEATURES | `features.merlin-in-your-everyday` | page-local |
| 4 | PROOF | `proof.used-by-professionals-at` | page-local |
| 5 | FEATURES | `features.routines` | page-local |
| 6 | FEATURES | `features.browser` | page-local |
| 7 | FEATURES | `features.meetings` | page-local |
| 8 | FEATURES | `features.companion` | page-local |
| 9 | FEATURES | `features.privacy` | page-local |
| 10 | SUPPORT | `support.faq` | page-local |
| 11 | SHELL | `shell.closing-footer` | shared ×6 |

### Pricing — `template.pricing`

1 route · `/pricing` · chrome: **partial**

| # | category | section | |
|---:|---|---|---|
| 1 | SHELL | `shell.skip-link` | shared ×6 |
| 2 | HERO | `hero.story-hero` | shared ×2 |
| 3 | COMMERCE | `commerce.pricing-plans` | page-local |
| 4 | FEATURES | `features.pricing-included` | page-local |
| 5 | SUPPORT | `support.pricing-faq` | page-local |
| 6 | SHELL | `shell.closing-footer` | shared ×6 |

### Manifesto — `template.manifesto`

1 route · `/manifesto` · chrome: **partial**

| # | category | section | |
|---:|---|---|---|
| 1 | SHELL | `shell.skip-link` | shared ×6 |
| 2 | SHELL | `shell.page-nav` | shared ×4 |
| 3 | CONTENT | `content.manifesto` | page-local |
| 4 | SHELL | `shell.closing-footer` | shared ×6 |

### Download — `template.download`

1 route · `/download` · chrome: **partial**

| # | category | section | |
|---:|---|---|---|
| 1 | SHELL | `shell.install-header` | page-local |
| 2 | HERO | `hero.install-intro` | page-local |
| 3 | FEATURES | `features.install-merlin-in-three-steps` | page-local |

### Legal pages — `template.legal`

2 routes · `/privacy`, `/terms` · chrome: **partial**

| # | category | section | |
|---:|---|---|---|
| 1 | SHELL | `shell.skip-link` | shared ×6 |
| 2 | SHELL | `shell.page-nav` | shared ×4 |
| 3 | CONTENT | `content.legal-content` | page-local |
| 4 | SHELL | `shell.closing-footer` | shared ×6 |

### Blog — `template.blog`

1 route · `/blog` · chrome: **partial**

| # | category | section | |
|---:|---|---|---|
| 1 | SHELL | `shell.skip-link` | shared ×6 |
| 2 | SHELL | `shell.page-nav` | shared ×4 |
| 3 | CONTENT | `content.blog-content` | page-local |
| 4 | SHELL | `shell.closing-footer` | shared ×6 |

### Blog posts — `template.blog-post`

20 routes · `/blog/{slug}/` · chrome: **partial**

| # | category | section | |
|---:|---|---|---|
| 1 | SHELL | `shell.skip-link` | shared ×6 |
| 2 | SHELL | `shell.page-nav` | shared ×4 |
| 3 | CONTENT | `content.blog-content-article` | page-local |
| 4 | SHELL | `shell.closing-footer` | shared ×6 |

## Section reference

### CONTENT

_The substantive body of a page: articles, listings, resources and general sections._

**`content.blog-content`** — Blog index body: the headline 'A little more to think about.', a featured post, and the list of all twenty posts as linked cards.

· Appears on 1 route. · appears on 1 routes

**`content.blog-content-article`** — A single blog post: title, long-form body in headed sections, and an author byline. All twenty posts share this structure.

· Appears on 20 routes. · appears on 20 routes

**`content.legal-content`** — Body of the Privacy and Terms pages: a dated legal document ('Last updated') with a page title, an intro, a contents index and plain-language policy sections.

· Appears on 2 routes. · appears on 2 routes

**`content.manifesto`** — The manifesto page body: a long-form, first-person story ('Less managing. More living.') in three movements (the day we know, the room Merlin makes, your time yours to spend), illustrated with four images.

· Appears on 1 route. · appears on 1 routes

### HERO

_Page-opening block: the main headline (h1) and first call to action._

**`hero.install-intro`** — Download page opening: thanks the visitor, states that the download starts automatically, and offers fallbacks (download again, Intel Mac build) so a blocked download does not end the journey.

· Appears on 1 route. · appears on 1 routes

**`hero.story-hero`** — Opens the home and pricing pages with the page's promise as an h1 (home: 'Your time. Yours again.'; pricing: 'Make room for the rest of your day.'), one supporting sentence, the primary 'GET MERLIN FOR MAC' call to action on home, and the embedded hero-corner-nav (brand mark plus Pricing/Manifesto links).

· Appears on 2 routes. · appears on 2 routes

### SUPPORT

_Questions and contact: FAQs, help, forms._

**`support.faq`** — Home-page FAQ 'Good questions. Clear answers.': a short list of getting-started and capability questions (what Merlin helps with, what is needed, own browser, how Companion works) plus an 'ask Merlin' prompt for anything else.

· Appears on 1 route. · appears on 1 routes

**`support.pricing-faq`** — Answers the plan and billing questions that block a purchase (which plan, what credits are, rollover, running out, annual option, how to get started) as six expandable question/answer pairs.

· Appears on 1 route. · appears on 1 routes

### SHELL

_Site chrome: navigation, header, footer, announcement bars and other elements carried across pages._

**`shell.closing-footer`** — Closes every page except the download page: on the home page a final conversion block ('Your next free moment starts at 16:42', 'GET MERLIN FOR MAC') with an animated sky/beach scene, followed by the site-wide footer links, copyright and wordmark.

· Appears on 26 routes. · appears on 26 routes

**`shell.install-header`** — Slim header of the download/thank-you page: the Merlin app icon only, with no navigation, so the visitor stays focused on installing.

· Appears on 1 route. · appears on 1 routes

**`shell.page-nav`** — Page-top container holding the main navigation (Merlin brand mark with the Pricing and Manifesto links) on every inner page. On the home and pricing pages the same hero-corner-nav is instead embedded inside hero.story-hero, so those pages have no separate page-nav node.

· Appears on 24 routes. · appears on 24 routes

**`shell.skip-link`** — Keyboard-accessibility affordance: an off-screen link ('Skip to plans', 'Read the blog'...) that is the first focusable element and jumps past the page chrome to the page's main content anchor. One ctas[] entry: label plus #anchor href.

· Appears on 26 routes. · appears on 26 routes

### FEATURES

_Product explanation: capabilities, benefits, workflows and integrations._

**`features.browser`** — Home-page demonstration that Merlin can act inside a web browser: a simulated session comparing flights, ordering food and browsing a job listing, headed 'If it happens in a browser, Merlin can help.'

· Appears on 1 route. · appears on 1 routes

**`features.companion`** — Home-page chapter on Companion, the in-place helper: highlight text or ask about what is on screen (Option + Space) in any app, with demos in Photoshop and Finder and a rephrase-a-sentence example.

· Appears on 1 route. · appears on 1 routes

**`features.install-merlin-in-three-steps`** — Three illustrated install steps (open your download, move Merlin to Applications, open Merlin) that carry a new user from downloaded file to a running app.

· Appears on 1 route. · appears on 1 routes

**`features.meetings`** — Home-page chapter on meetings: Merlin records the call, produces a transcript, summary, key decisions and action items, then turns the outcome into PDFs, decks, spreadsheets and websites.

· Appears on 1 route. · appears on 1 routes

**`features.merlin-in-your-everyday`** — Shows Merlin working quietly in everyday notifications: an animated notification card with a sound toggle and a replay control, introducing the home story before the product claims begin.

· Appears on 1 route. · appears on 1 routes

**`features.pricing-included`** — States that every plan includes the same capabilities, as six short feature cards (context, browser, in-place help, meetings, creation, routines), so price is not read as a feature gate.

· Appears on 1 route. · appears on 1 routes

**`features.privacy`** — Home-page trust section 'Personal work. Private by design.': four short claims (independent audit, approval first, no model training, protection in storage and transit) that remove the privacy objection before the final call to action.

· Appears on 1 route. · appears on 1 routes

**`features.routines`** — Home-page story chapter 'First, a little context.': shows Merlin pulling context from connected apps (Gmail, Slack, Calendar, Linear, Notion, Granola) into a catch-up and a recurring routine, with a pause-routine control.

· Appears on 1 route. · appears on 1 routes

### PROOF

_Trust evidence: customer logos, quotes, ratings._

**`proof.used-by-professionals-at`** — Social proof strip on the home page: the line 'Used by professionals at' followed by five third-party company logos (Notion, Salesforce, Harvard, HubSpot, McKinsey). Logos are real trademarks (customer-logo role, never fabricated).

· Appears on 1 route. · appears on 1 routes

### COMMERCE

_Pricing and plans so the visitor can choose._

**`commerce.pricing-plans`** — Lets a visitor compare the three monthly plans (Pro, Ultra, Max) by description, price and included credits, and start the download from any of them. Plan name is items[].title, its description is items[].body; price and credit lines go in body[] in plan order; each plan has one ctas[] entry.

· Appears on 1 route. · appears on 1 routes
