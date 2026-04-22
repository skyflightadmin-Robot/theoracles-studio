# Content audit — theoracles.studio (as of 2026-04-21)

Extracted verbatim from the live WordPress site. This is what needs to land in the Astro rebuild.

## Site structure

Four pages + one dead anchor:

- `/` — Home
- `/about/` — About
- `/portfolio/` — Portfolio (placeholder — no work listed yet)
- `/contact/` — Contact form
- `/#donate` — links from nav, but **no donate section currently exists** on the homepage. Decide: build one, or drop the link.

Primary nav order: Portfolio · Contact Us · About Us · Donate

Social links (footer area):
- X — https://x.com/oracles_studio
- Instagram — https://www.instagram.com/theoracles.studio/
- YouTube — https://www.youtube.com/@theoracles.studio

## Home

**Heading:** Who We Are

**Body:** We're a small nonprofit studio telling stories that promote the goodness of God's law.

Visuals: one hero photograph (`img_3333-1-edited.jpg`) and the gradient "THE ORACLES" wordmark treatment (`oracles.png`).

## About (`/about/`)

### What is The Oracles?

We're a small nonprofit studio telling stories that promote the goodness of God's law.

The name has its roots in the hebrew word מַשָּׂא (pronounced, mas-saw). מַשָּׂא is used about a dozen times in Isaiah to introduce a word from God.

### Why law and story?

We believe a large part of the Christian church has lost its love for the arts and for God's law.

As a studio we use the visual arts to tell stories that are designed to imprint the good, beautiful, and true nature of the law of God.

### Who are we?

Dabe is seasoned illustrator who acts as the director, creative influence, and primary storyteller.

Aaron is a former pastor who functions as the DP/Editor to bring the vision to life.

### God's Art Intro (Psalm 1)

> Blessed is the man
>     who walks not in the counsel of the wicked,
> nor stands in the way of sinners,
>     nor sits in the seat of scoffers;
> but his delight is in the law of the Lord,
>     and on his law he meditates day and night.

## Portfolio (`/portfolio/`)

Two category headings only — no projects listed yet:

- Christian Education
- Pastoral Care

Footer link: "Contact Us" → /contact/

**Implication for rebuild:** Portfolio needs a framework (grid, category headers, empty-state copy) but no real project entries yet. Treat as coming-soon / placeholder until Dabe delivers work samples.

## Contact (`/contact/`)

**Heading:** Reach out

**Body:** Do you need help telling a story? Are you a donor wondering about who we help? Do you have questions about our process? We'd love to hear from you!

**Form fields:**
- Name
- Email (required)
- Message
- Send button

## Observations

1. The current site is tiny — four pages, roughly 250 words of real copy. The rebuild is a design project, not a content migration.
2. Portfolio is empty. We need a decision: build a stub portfolio section with "more coming" language, or hide the link until there's work to show.
3. The `/#donate` link in nav goes nowhere. Either build a donate block on the homepage or drop it from nav.
4. Tone is plain, earnest, light on marketing language. The new design should echo that — no jargon, short sentences, specific claims.
5. The Psalm 1 quote on the About page is a strong candidate for typographic display treatment — it's the most texturally interesting copy on the site.
