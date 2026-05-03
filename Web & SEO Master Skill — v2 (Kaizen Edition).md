---
name: web-seo-master
description: >
  Expert skill for maximising website performance, SEO, UX, and user retention across web and YouTube.
  Use whenever a user asks about: website design, landing pages, SEO strategy, Google rankings, keyword research,
  on-page/technical SEO, Core Web Vitals, page speed, schema markup, E-E-A-T, backlinks, YouTube SEO,
  video titles/descriptions/tags/thumbnails, channel growth, watch time, CTR optimisation, visual hierarchy,
  typography, colour systems, accessibility (WCAG), CRO (conversion rate optimisation), bounce rate,
  user retention, navigation design, mobile-first design, calls-to-action, content strategy, AI search (GEO/AIO),
  internal linking, or any task producing a website or web component.
  Trigger for partial questions like "rank my video", "make my site faster", "improve my CTR", "design a homepage",
  "my bounce rate is high", or "help with my YouTube channel". Covers the full stack: Google SEO + YouTube SEO
  + UX/GUI design + conversion + retention — always apply together.
---

# Web & SEO Master Skill — v2 (Kaizen Edition)

Research-backed skill for producing websites, content strategies, and SEO plans that rank highly,
convert visitors, and retain users. 2026 best practices across Google SEO, YouTube SEO, UX, and CRO.

---

## STEP 0 — Always Do This First

Before responding to ANY request:
1. Read this SKILL.md in full
2. Load all relevant reference files (see table below)
3. If auditing a live site: fetch the URL, then fetch 2-3 inner pages for fuller signal

| Topic | File | Load When |
|---|---|---|
| Google SEO — technical, on-page, off-page, local | `references/google-seo.md` | Any SEO or audit task |
| YouTube SEO — full creator system | `references/youtube-seo.md` | Any YouTube task |
| UX, visual design, retention | `references/ux-design.md` | Any design or UX task |
| CRO — conversion, trust, testing | `references/cro.md` | Any conversion or audit task |

**For full site audits or full strategies: load all four.**

---

## Core Philosophy

1. **Search intent first** — match content and design to what the user *actually* wants
2. **Audience satisfaction drives all signals** — rankings, watch time, CTR, conversions follow genuine quality
3. **Performance is a prerequisite** — a slow or broken page cannot convert or rank regardless of quality
4. **Mobile-first without exception** — Google indexes mobile; most YouTube views are mobile
5. **E-E-A-T on every page** — Experience, Expertise, Authoritativeness, Trustworthiness are ranking factors
6. **Accessibility = quality signal** — WCAG-compliant design ranks better, converts better, retains more
7. **Kaizen mindset** — every output should include the next improvement cycle, not just a one-off fix

---

## Quick-Reference Signal Tables

### Google SEO — 2026 Ranking Signals (ranked by weight)
| Signal | What It Means in Practice |
|---|---|
| Search intent match | Format + angle + depth must match what top results show |
| E-E-A-T | Author credentials, first-person proof, trust signals, citations |
| Core Web Vitals (field) | LCP < 2.5s, INP < 200ms, CLS < 0.1 — CrUX data, not just lab |
| Topical authority | Semantic cluster coverage of a niche beats isolated content |
| Relevant backlinks | Same niche, high authority > generic high-DA links |
| Engagement signals | CTR from SERP, dwell time, scroll depth, return visits |
| Mobile-first indexing | Mobile HTML is what Google crawls and ranks |
| Structured data | Schema unlocks rich results; improves entity understanding |
| HTTPS + security | Table stakes; failing here is an immediate disqualifier |

### YouTube SEO — 2026 Algorithm Signals
| Signal | Benchmark |
|---|---|
| Audience retention (AVP) | >50% good; >70% exceptional |
| Click-through rate (CTR) | 4–10%+ healthy (niche varies) |
| Viewer satisfaction | Likes, post-watch surveys, replay behaviour |
| Metadata relevance | Keyword in title first 40 chars, description first 25 words |
| Session initiation | Does your video start YouTube sessions? High-value signal |
| Engagement depth | Comments, shares, saves, mid-video subscribes |
| Closed captions | Manual .srt only; auto-ASR ~70% accurate; transcript is crawlable |
| Consistent cadence | Algorithm rewards reliable publishing schedules |

### UX & Retention — Core Checklist
- Visual hierarchy working in < 50ms: size → contrast → position → spacing → weight → colour
- One primary CTA per section; never two competing equal-weight buttons
- Trust signal within 100px of every primary CTA
- Mobile: tap targets ≥ 44px; body font ≥ 16px; no horizontal scroll
- Accessibility: contrast ≥ 4.5:1 body, ≥ 3:1 large text; keyboard-navigable; ARIA on interactive elements

---

## Workflow by Request Type

### AUDIT an existing website
Load: `references/google-seo.md` + `references/ux-design.md` + `references/cro.md`

Audit sequence — always in this order:
1. **Intent match** — does each page serve the query that would land a user there?
2. **E-E-A-T** — trust signals, author attribution, first-person proof, credentials
3. **Technical SEO** — crawlability, schema, URL structure, canonical, sitemap
4. **Core Web Vitals** — LCP, INP, CLS (flag likely issues from HTML inspection)
5. **On-page** — H1/title/meta, keyword placement, heading hierarchy, content quality
6. **Local SEO** (if applicable) — NAP consistency, GBP signals, LocalBusiness schema
7. **UX & design** — visual hierarchy, hero section, CTA placement, mobile
8. **CRO** — conversion path, social proof, friction points, email capture

Output format for every audit:
- Score each dimension 0–100
- Pass / Warn / Fail per finding with one-line explanation and one-line fix
- Priority action table: Fix | Impact (High/Med/Low) | Effort (High/Med/Low) | Expected Outcome
- Kaizen next cycle: what to re-audit after fixes are applied

### CREATE a website / landing page / component
Load: `references/ux-design.md` + `references/cro.md`

Steps:
1. Establish: purpose, target audience, primary conversion goal, brand constraints
2. Apply the Layout Architecture (below)
3. Apply the Typography & Colour System (below)
4. Embed technical SEO scaffold (semantic HTML, schema, meta, canonical)
5. Annotate code with inline design decision comments
6. End with "Optimisation Notes" + "Next Iteration" suggestions

### OPTIMISE for Google SEO
Load: `references/google-seo.md`

Steps:
1. Identify intent type (informational / navigational / commercial / transactional)
2. Audit E-E-A-T signals on the page
3. Run Core Web Vitals assessment from page source signals
4. Check on-page fundamentals (H1, title, meta, URL, schema)
5. Identify internal linking gaps
6. Produce prioritised fix list: quick wins first, structural changes second

### CREATE or OPTIMISE YouTube content
Load: `references/youtube-seo.md`

For a new video: keyword → title (2 variants) → description → tags → thumbnail brief → hook script → chapters
For existing video: audit CTR (title+thumbnail), audit AVP (hook+pacing), audit metadata (keyword coverage)
Always produce: SEO-first title variant + CTR-first title variant + hybrid recommendation

### UX / design / layout question
Load: `references/ux-design.md`

Apply: visual hierarchy first → mobile-first → conversion principles → accessibility
Always include: one concrete before/after example relevant to the user's context

### FULL STRATEGY (site + content + YouTube + SEO)
Load: all four reference files

Output structure:
1. Audience & intent analysis
2. Keyword strategy (Google + YouTube — these differ; map separately)
3. Content architecture (site structure + YouTube channel structure)
4. Technical SEO foundations
5. UX & design system brief
6. CRO plan
7. KPIs & measurement framework
8. 30/60/90 day kaizen roadmap

---

## Layout Architecture

### Page Section Sequence (Conversion-Optimised)
```
Hero
  → H1 (primary keyword + clearest benefit)
  → Supporting sub-headline (removes biggest objection)
  → Hero image/video (reinforces the benefit; never decorative)
  → Primary CTA (one only; high contrast; benefit-led label)
  → Micro-copy (removes anxiety: "No credit card" / "Book in 60 seconds")
  → Social proof strip (star rating + count OR logo strip)

Problem/Value Prop Section
  → Agitate the pain; position as the solution

Features → Benefits
  → Features tell; benefits sell. Always translate.

Social Proof Section
  → Testimonials: specific outcomes, named, photo, role

Objection Handling (FAQ)
  → Answer the 5 most common reasons people don't convert

Risk Reversal
  → Guarantee / free trial / refund policy near final CTA

Footer CTA
  → Repeat primary CTA
```

### Visual Hierarchy — Six Levers (priority order)
1. **Size** — largest = most important; H1 dominates; CTAs larger than body
2. **Contrast** — high contrast draws the eye; accent colour used only for primary CTA
3. **Position** — above fold + top-left (F/Z-pattern); CTA always above fold
4. **Spacing** — whitespace = breathing room; group related items (Gestalt proximity)
5. **Weight** — bold → regular → light; max 3 weight variants per page
6. **Colour** — accent colour reserved for primary CTA only; diluting it = losing it

### Performance Rules (Non-Negotiable)
- LCP element (hero image) must load < 2.5s — preload it, use WebP/AVIF, < 200KB
- No image without explicit `width` + `height` attributes (CLS cause #1)
- Defer all non-critical JS (booking widgets, chat, analytics, social scripts)
- Lazy-load all below-fold images (`loading="lazy"`)
- CDN for all static assets (Cloudflare free tier minimum)

---

## Typography System

| Element | Responsive Size | Weight | Line Height | Rule |
|---|---|---|---|---|
| H1 hero | clamp(40px, 6vw, 96px) | 700–900 | 1.1–1.2 | One per page; keyword placed naturally |
| H2 section | clamp(28px, 4vw, 56px) | 600–700 | 1.2–1.3 | Keyword-relevant; scannable |
| H3 subsection | clamp(22px, 3vw, 36px) | 500–600 | 1.3–1.4 | Question-format for featured snippets |
| H4 | clamp(18px, 2.5vw, 28px) | 500 | 1.4 | Rare; only when needed |
| Body | clamp(16px, 1.5vw, 18px) | 400 | 1.5–1.7 | Max 70 chars per line (65ch container) |
| CTA label | 16–20px | 600–700 | 1 | Action verb + benefit; never "Submit" |
| Caption | 12–14px | 400 | 1.4 | Never below 12px |

```css
/* Fluid typography — 2026 standard */
h1 { font-size: clamp(2.5rem, 6vw, 6rem); line-height: 1.15; }
body { font-size: clamp(1rem, 1.5vw, 1.125rem); line-height: 1.6; }
.body-container { max-width: 65ch; } /* Prevents over-long lines */
```

---

## Technical SEO Scaffold (Apply to Every Page Built)

```html
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Primary Keyword | Brand Name</title><!-- ≤60 chars; keyword first -->
  <meta name="description" content="Benefit-led. Keyword included. CTA implied. ≤155 chars.">
  <link rel="canonical" href="https://example.com/page/">
  <!-- Preload LCP image -->
  <link rel="preload" as="image" href="hero.webp" fetchpriority="high">
  <!-- Open Graph -->
  <meta property="og:title" content="...">
  <meta property="og:description" content="...">
  <meta property="og:image" content="..."><!-- 1200×630px -->
  <meta property="og:url" content="...">
  <!-- Schema — choose the right type for the page -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "LocalBusiness",  // WebPage / Article / Product / FAQPage etc.
    "name": "...",
    "url": "...",
    "address": { "@type": "PostalAddress", "streetAddress": "...", "addressLocality": "..." },
    "telephone": "...",
    "openingHours": ["Mo-Fr 09:00-18:00"]
  }
  </script>
</head>
<body>
  <!-- Semantic structure — every page -->
  <header role="banner"><nav aria-label="Main navigation">...</nav></header>
  <main id="content">
    <h1>Primary Keyword — Value Prop</h1>
    <!-- Content -->
  </main>
  <footer role="contentinfo">...</footer>
  <!-- Defer non-critical scripts -->
  <script src="analytics.js" defer></script>
</body>
```

**Schema types — choose correctly:**
| Page Type | Schema |
|---|---|
| Local venue / business | `LocalBusiness` with address, hours, phone, geo |
| Blog post / article | `Article` or `BlogPosting` with author, datePublished |
| FAQ section | `FAQPage` — drives accordion rich results |
| Tutorial / guide | `HowTo` with steps |
| Product | `Product` with offers, reviews |
| Video embed page | `VideoObject` with embedUrl, duration, thumbnail |
| Any page with nav | `BreadcrumbList` |
| Homepage/brand | `Organization` with sameAs social profiles |

---

## Local SEO Essentials (For Any Venue / Local Business)

This section exists because local SEO is commonly missed and high-impact.

### Google Business Profile — Highest-Impact Local Signal
- [ ] Claimed, verified, 100% complete
- [ ] Primary category = most specific accurate match
- [ ] Business description: keyword-rich, benefit-led, 750 chars max
- [ ] All attributes filled (hours, accessibility, payment methods)
- [ ] Real photos: exterior, interior, team, products/services
- [ ] Weekly Google Posts (offers, events, updates)
- [ ] Q&A populated with your own FAQs (pre-empts bad questions)
- [ ] Reviews: ask every customer; respond to every review within 48h

### NAP Consistency (Critical)
Name, Address, Phone **must be byte-for-byte identical** across:
- Website (every page footer)
- Google Business Profile
- Apple Maps, Bing Places, Yelp, Facebook, industry directories

Even minor differences ("St." vs "Street") confuse Google's entity graph.

### LocalBusiness Schema (Copy-Paste Template)
```json
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "name": "Business Name",
  "url": "https://example.com",
  "telephone": "+44-1234-567890",
  "email": "info@example.com",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "123 High Street",
    "addressLocality": "Nottingham",
    "postalCode": "NG1 1EH",
    "addressCountry": "GB"
  },
  "geo": { "@type": "GeoCoordinates", "latitude": 52.954, "longitude": -1.141 },
  "openingHoursSpecification": [
    { "@type": "OpeningHoursSpecification", "dayOfWeek": ["Monday","Tuesday","Wednesday"],
      "opens": "16:00", "closes": "23:00" },
    { "@type": "OpeningHoursSpecification", "dayOfWeek": ["Thursday","Friday","Saturday","Sunday"],
      "opens": "10:30", "closes": "23:00" }
  ],
  "sameAs": [
    "https://www.facebook.com/businessname",
    "https://www.instagram.com/businessname"
  ]
}
```

---

## YouTube Production Checklist

### Pre-Production
- [ ] Keyword identified via YouTube Autocomplete + VidIQ/TubeBuddy score
- [ ] Top 5 competing videos watched — format, length, what's missing noted
- [ ] Hook planned: specific payoff stated in first 10 seconds (no welcome intros)
- [ ] Jenga moment planned: preview end result early to create investment
- [ ] Chapter structure mapped
- [ ] Thumbnail shoot planned as separate session (not video screenshots)
- [ ] 3+ thumbnail variations to create

### At Upload
- [ ] Filename: `primary-keyword-phrase.mp4` (before upload)
- [ ] **Title**: keyword in first 40 chars; ≤60 chars; curiosity gap or power word
- [ ] **Description**: keyword in first 25 words; 00:00 chapters; 200–350 words; 2–3 hashtags at end
- [ ] **Tags**: 8–12; first = exact keyword; then variations; then broader topics
- [ ] **Thumbnail**: high contrast; ≤3 elements; readable at phone size; matches title promise
- [ ] **Manual captions**: upload corrected .srt (never rely on auto-ASR)
- [ ] **Playlist**: added to relevant playlist immediately
- [ ] **End screen**: at 20s from end — subscribe + recommended video
- [ ] **Cards**: 2–3 info cards at relevant moments
- [ ] **Pin a comment** immediately: question or key resource

### Post-Upload (48 Hours)
- [ ] CTR below channel average → swap thumbnail now
- [ ] Retention at :30 below 60% → hook problem; note for next video
- [ ] Reply to all comments

---

## User Retention Strategies

### On-Site
- **Internal linking**: 3–8 contextual links per page; keep users in your ecosystem
- **Related content widget**: "You might also like" after every article
- **Table of contents**: on any page > 1000 words; reduces abandonment from overwhelm
- **Reading time indicator**: sets expectations; reduces early exits on long content
- **Email capture with value exchange**: "Get [specific resource]" not "Subscribe to newsletter"
- **Exit-intent popup**: triggered by cursor leaving viewport; last chance before they go
- **Page speed**: 1-second delay = 7% conversion drop; 53% mobile abandon after 3s

### YouTube
- **Hook ≤ 10 seconds**: payoff stated before any intro ritual
- **Pattern interrupt every 60–90s**: angle change, B-roll, graphic, zoom
- **Open loops mid-video**: "later I'll show you the one thing that changed everything..."
- **Chapters**: paradoxically increase overall watch time (navigation = less frustration)
- **End screens + next video**: always have a "next" ready; playlists autoplay
- **Community tab posts**: maintain engagement signal between uploads

---

## Measurement Framework

### Google SEO KPIs
| Metric | Tool | Target / Red Flag |
|---|---|---|
| Organic clicks + impressions | Google Search Console | Week-over-week growth |
| Core Web Vitals pass rate | GSC / CrUX | ≥75% URLs "Good" on all 3 metrics |
| Keyword positions (primary KWs) | GSC / Ahrefs | Top 10; page 2–3 = quick win opportunity |
| CTR from SERP | GSC | ≥3% (varies by position; below = title/meta problem) |
| Engagement rate / dwell time | GA4 | >50% engaged sessions; >2 min avg |
| Indexed pages | GSC Coverage | 0 errors; 0 wrongly excluded |
| Core Web Vitals trend | GSC | Improving over 28-day rolling window |

### YouTube KPIs
| Metric | Where | Target / Red Flag |
|---|---|---|
| Impressions CTR | Studio → Reach | 4–10%+; below = thumbnail/title problem |
| Average view percentage (AVP) | Studio → Engagement | >50% good; <30% = hook/pacing problem |
| Average view duration (AVD) | Studio → Engagement | Above niche average |
| Traffic source: YouTube Search | Studio → Reach | Increasing % over time |
| Retention at :30 mark | Studio → Audience | Below 60% = hook failure |
| Subscribers per video | Studio | Positive trending |

### UX / CRO KPIs
| Metric | Tool | Red Flag |
|---|---|---|
| Primary conversion rate | GA4 | Declining or stagnant baseline |
| Bounce rate | GA4 | >70% = intent mismatch or UX failure |
| Scroll depth | Hotjar / GA4 | <50% = above-fold problem |
| CTA click rate | Heatmap + GA4 events | Low = CTA copy, contrast, or position |
| Form abandonment field | Hotjar form analytics | Specific field causing drop-off |
| Core Web Vitals (field) | CrUX / GSC | Any metric in red/amber = fix before CRO |

---

## Failure Mode Diagnosis Table

| Symptom | Likely Root Cause | First Fix |
|---|---|---|
| Good rankings, low CTR | Title/meta not benefit-led; thumbnail weak | Rewrite title with curiosity gap; add power word; rewrite meta |
| Good CTR, high bounce | Intent mismatch OR slow load OR hero fails | Check intent match first; then CWV; then hero section relevance |
| Low YouTube watch time | Weak hook; slow pacing; filler content | Rewrite first 30s; add pattern interrupts; cut filler ruthlessly |
| Low YouTube impressions | Weak metadata; niche too broad; new channel | Keyword research; title/tags/description overhaul; niche down |
| Local rankings weak | NAP inconsistency; missing GBP; no LocalBusiness schema | Fix NAP first; add schema; complete GBP 100% |
| Rankings dropping | Content freshness; competitor improvement; algorithm update | Refresh with new data + experience; improve E-E-A-T signals |
| Low conversions despite traffic | Trust deficit; CTA friction; social proof absent | Add reviews near CTA; simplify conversion path; add guarantee |
| Slow Core Web Vitals | Unoptimised hero image; render-blocking JS; poor hosting | WebP hero <200KB; defer JS; CDN; upgrade hosting |
| High form abandonment | Too many fields; unclear labels; no inline validation | Remove every non-essential field; add descriptive labels; inline ✓ |
| Email signups near zero | No value exchange offered | Replace "Subscribe" with "Get [specific resource]" |

---

## Quick Wins Checklist (Do These Before Anything Else)

**SEO:**
- [ ] Primary keyword in `<title>` (first 3 words), H1, first 100 words, URL slug
- [ ] Meta description is benefit-led, ≤155 chars, includes keyword, ends with implied CTA
- [ ] All images: descriptive alt text + explicit `width` + `height` + WebP/AVIF format
- [ ] Schema markup correct for page type and validated in Rich Results Test
- [ ] FAQPage schema on any page with FAQ content
- [ ] Canonical tag on every page (self-referencing minimum)

**Local SEO (venues):**
- [ ] NAP identical across site footer, GBP, and all directory listings
- [ ] LocalBusiness schema with complete hours, address, phone, geo
- [ ] GBP 100% complete with real photos and recent posts

**UX/CRO:**
- [ ] One clear primary CTA above the fold — no competing equal-weight buttons
- [ ] Trust signal (reviews count, guarantee, logo strip) within 100px of primary CTA
- [ ] Hero H1 communicates value in ≤10 words without brand knowledge required
- [ ] Email capture has a specific value exchange, not just "subscribe"

**Performance:**
- [ ] Hero image preloaded, WebP, < 200KB, explicit width/height
- [ ] Non-critical JS deferred (booking widgets, chat, social embeds, analytics)
- [ ] Mobile tested at 375px viewport: no horizontal scroll, font ≥ 16px, CTAs reachable

**YouTube:**
- [ ] Title: keyword in first 40 chars; ≤60 chars total
- [ ] Description: keyword in first 25 words; chapters from 00:00
- [ ] Manual .srt captions uploaded
- [ ] Video in a playlist; end screen and cards set
- [ ] Thumbnail: ≤3 elements; readable at phone size

---

## Kaizen Cycle (Apply After Every Output)

Every audit, build, or optimisation should end with a "Next Iteration" note:

```
KAIZEN NEXT CYCLE:
After [these fixes] are live for 4 weeks:
1. Check GSC for impression/click changes on target pages
2. Re-check CWV in GSC field data (28-day lag on CrUX)
3. Monitor YouTube CTR at 48h after thumbnail changes
4. Run a heatmap session on updated hero section
5. Re-audit the [highest-impact] finding that was deferred
```

The goal is never a finished site — it's a site that improves every cycle.

---

*Load reference files for deep implementation detail on any specific domain.*
