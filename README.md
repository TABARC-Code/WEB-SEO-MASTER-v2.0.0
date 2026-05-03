# web-seo-master

An expert Claude AI skill that actually knows how to make websites work.

Not just *look good* — actually *work*. Rank on Google. Convert visitors. Keep them coming back. Whether you're auditing a live site, building a landing page, or trying to figure out why your YouTube videos aren't getting watched, this skill has the methodology and the reference material to get it done.

Built on real-world best practices from 2026: Brian Dean's SEO research, MrBeast's production framework, creator intelligence from people who actually do this for a living, not just people who write about it.

## What It Does

Think of this as your ops manual for everything that happens after you publish something on the web.

You hand it a URL, a design problem, a YouTube thumbnail question, or a landing page that isn't converting — and instead of getting platitudes or generic advice, you get a structured methodology backed by research, worked examples, and the specific next steps to fix it.

### Audit & Diagnose
You give it a live website. It crawls the page, reads the source, understands the structure, identifies failures across six dimensions at once (technical SEO, on-page, local, UX, content quality, conversion potential), scores each one, and gives you a prioritised fix list. More importantly: it *explains why* something is failing, not just that it is. A broken hero section isn't just "bad UX" — it's "hero has two competing CTAs above the fold, no value prop in H1, pricing is hidden below fold, and no social proof near the booking button." Which fixes do you do first? The skill tells you by impact vs. effort.

### Build & Create
Raw HTML/CSS for landing pages. Optimised copy that works both for search engines and humans. Properly structured schema markup (LocalBusiness for venues, Article for blogs, FAQPage for FAQs, VideoObject for embedded videos). Forms designed to actually capture leads instead of eating them. Everything mobile-tested from 375px up. Not magic — just competent and production-ready.

### Optimise for Search
**Google:** keyword research that actually maps to business intent. On-page optimisation that treats each page like a unique rank target. Technical SEO that fixes crawlability and speed issues. E-E-A-T signals — the signals Google actually measures now. Local SEO for physical venues (NAP consistency, Google Business Profile, schema).

**YouTube:** because the same audience watching YouTube is also searching Google, and the skill bridges both. Titles in two variants (one for search ranking, one for human click-through rate). Descriptions with chapters that get parsed as "key moments." Hook science from real vieoss actual production framework. Retention tactics that aren't just "add B-roll" — they're specific pattern interrupts and story structures that measurably keep viewers watching.

**Core Web Vitals:** when a page is slow, conversion tanks before anything else matters. The skill diagnoses LCP (loading), INP (responsiveness), and CLS (stability) failures from HTML inspection alone. Knows the fixes in priority order.

**AI Search:** Google is surfacing AI-generated summaries of web pages now. Perplexity, ChatGPT, and other LLMs cite sources directly. This skill optimises so your content appears in those answers, not buried in the citations.

### Design & UX
Visual hierarchy isn't decorative — it's functional. The skill knows the six levers that control what a user's eye lands on first: size, contrast, position, spacing, weight, colour. Typography systems that scale responsively. Colour systems that work in light and dark mode. Mobile design that respects the thumb zone and respects accessibility (WCAG 2.2 AA).

Honest take: most websites fail at visual hierarchy. They have too many competing elements. The hero has two CTAs. The pricing is vague. Reviews are missing. The skill fixes that by actually thinking through what matters and removing what doesn't.

### Conversion & Retention
Every page has friction. Every form loses users. Every CTA placement is either smart or accidental. The skill does friction audits — walks through the actual conversion path and identifies where people get stuck. Knows which CTA copy converts (hint: not "Submit"). Knows where to place trust signals (within 100px of the primary button). Knows how many form fields you can ask before completion rates tank (answer: way fewer than you think).

For venues and local businesses specifically: booking flows, opening hours placement, membership as a conversion funnel, review strategies that actually work.

## How It's Organised

Four files that live inside Claude's context when you ask for help. You don't pick which one to load — Claude figures out what you need and loads the relevant sections automatically.

```
web-seo-master/
├── SKILL.md                    # The main instruction set
│                               # Defines how Claude should behave
│                               # Workflow for each request type
│                               # Layout system, typography, technical scaffold
│                               # Kaizen philosophy
│
├── references/
│   ├── google-seo.md          # Everything Google ranking
│   │                          # Intent, E-E-A-T, keywords, on-page
│   │                          # Technical, Core Web Vitals, content strategy
│   │                          # Featured snippets, link building, AI search
│   │                          # Local SEO, keyword cannibalism, penalties
│   │
│   ├── youtube-seo.md         # YouTube as a ranking engine
│   │                          # Algorithm (real intelligence, not guesses)
│   │                          # Titles, thumbnails, descriptions, chapters
│   │                          # Retention tactics from actual creators
│   │                          # KVS method (keyword → video → SEO)
│   │                          # A/B testing, analytics, cross-platform strategy
│   │
│   ├── ux-design.md           # Visual and interaction design
│   │                          # Visual hierarchy, typography, colour systems
│   │                          # Layout patterns, mobile-first, accessibility
│   │                          # Micro-interactions, retention mechanics
│   │                          # Common design failures and how to fix them
│   │
│   └── cro.md                 # Making visitors convert
│                              # Friction audits, CTA optimisation
│                              # Trust signals, forms, email sequences
│                              # A/B testing, analytics, psychological triggers
│                              # Special sections for venues, e-commerce, SaaS
└── README.md                  # This file
```

Each reference file is self-contained. You can read it standalone, or Claude loads the relevant parts when you ask a question.

## Key Features

## Why This Exists

Most web optimization advice is either:
1. **Too generic.** "Improve your SEO" without saying *how*. "Make your CTA stand out" without explaining visual hierarchy.
2. **Too academic.** Dense theory that doesn't translate to "what do I do on Monday morning."
3. **Too scattered.** SEO advice in one place, design in another, conversion tactics in a third. Nobody connects them.

This skill is different.

It integrates everything. SEO means nothing if the page doesn't load fast (Core Web Vitals) or doesn't convert (CRO). A beautiful design means nothing if it ranks nowhere (SEO) or confuses users (UX). A high-converting page means nothing if nobody sees it (YouTube algorithm, Google ranking). They're not separate problems — they're interconnected.

Every audit flags failures across all dimensions at once. Every build includes SEO, design, and conversion thinking from the start. Every optimisation treats the page as a whole system, not isolated parts.

## What's Inside (Real Talk)

**google-seo.md** isn't a list of SEO tips. It's the methodology that separates pages that rank from pages that don't. Search intent framework (matching format, angle, and depth). E-E-A-T implementation (how to signal expertise and trustworthiness — it matters now). Keyword research as a workflow, not a magic search. On-page fundamentals that actually move rankings. Technical SEO that isn't just "get HTTPS" (table stakes by now). Core Web Vitals diagnosis you can do from HTML alone. How to handle keyword cannibalism when it happens. Penalty recovery when traffic drops. Local SEO specifics for venues, not just big brands.

**youtube-seo.md** is built from actual creator intelligence. The internal framework (the 3 metrics: CTR, AVD, AVP). Chucky Appleby's thumbnail science from an official YouTube interview. The KVS method (keyword → video → SEO) from practitioners who use it. Not algorithm speculation — actual framework from people who ship content regularly. Retention tactics that aren't "add more B-roll." The hook structure that works. Why chapters paradoxically increase watch time. How to title a video so it ranks *and* gets clicked. Description structure that YouTube crawls and LLMs parse.

**ux-design.md** explains how to guide a user's eye without saying "make the button bigger" a hundred times. Visual hierarchy as six specific levers (size, contrast, position, spacing, weight, colour). Typography systems that scale. Colour systems that work light and dark. The thumb zone map for mobile. When animations help vs. hurt. What makes a hero section actually work. The design anti-patterns that destroy conversion (two equal CTAs, brand name as H1, hidden pricing, no social proof near the button).

**cro.md** is friction audit methodology. Walking through an actual conversion path and identifying where people get stuck. CTA copy that converts (outcome verb + benefit, not "Submit"). Where to place trust signals (within 100px of the primary action). How many form fields before completion tanks (fewer than you think). A/B testing strategy that measures what matters. Email sequences that nurture instead of broadcast. Specific sections for venues (opening hours, booking flows, membership), e-commerce (product pages, checkout, cart recovery), and SaaS (free trial, pricing pages, qualification).

All of it is written for *doing*, not for *reading*. Worked examples throughout. Real failures and real fixes. The Games Haven audit is an actual website that was crawled and analysed using this skill. (I was passing in an Uber and spotted this place so used as a n example only.)

## How to Use

Just ask. Seriously.

Ok so I was passing in an Taxi and used this comapny as an example. No idea what they did or do. But They do get free advertisement.

### Common Real Scenarios

**Your site isn't ranking and you don't know why.**
```
/web-seo-master Audit gameshaven.co.uk and tell me what's failing
```
You get back: a report with scores across six dimensions, specific failures flagged, and a prioritised fix list. Not vague advice like "improve your SEO" — actual structural problems like "your H1 is the brand name instead of your primary keyword" and "your hero section has two competing CTAs that split attention."

**You need a landing page fast.**
```
/web-seo-master Build a landing page for a board game café in Nottingham. 
Target: families and gamers 25-45. Goal: table bookings. Price: £7.50pp.
```
You get production-ready HTML/CSS code. Mobile tested from 375px. Schema markup included. Design decision comments throughout. Not a Figma mockup — actual working code you can ship.

**Your YouTube videos get views but nobody stays watching.**
```
/web-seo-master I'm uploading "how to run your first D&D campaign". 
Generate me a title, description, chapters, and hook script.
```
You get two title variants (one optimised for search ranking, one for human click-through). A 300+ word description with chapters that YouTube parses as "key moments." 15-second hook that sets up stakes and delivers immediate value. Not generic — specific to this exact topic.

**Your form is bleeding signups.**
```
/web-seo-master My contact form has 8 fields and I'm getting ~2% completion. 
Help me fix it.
```
You get a friction audit that identifies which fields are destroying completion rate, rewrites the labels to reduce anxiety, cuts the form down to the essentials, and adds micro-copy ("takes 60 seconds to fill out") that removes last-second hesitation.

**Your landing page converts but Core Web Vitals are in the red.**
```
/web-seo-master My LCP is 4.2s, INP is 300ms, CLS is 0.18. 
What's the issue and how do I fix it?
```
From the HTML alone, the skill can diagnose: unoptimised hero image (>200KB), render-blocking JavaScript from a booking widget, missing explicit width/height on images. Fixes listed in priority order.

**You're launching a local business and don't know where to start with SEO.**
```
/web-seo-master I'm opening a board game café in Nottingham. 
What's the complete local SEO checklist?
```
You get: Google Business Profile setup (what fields matter), NAP consistency across all directories, LocalBusiness schema template, review strategy, opening hours placement, keyword strategy for local searches.

## What's in Each Section (Without the Fluff)

**google-seo.md** covers how Google actually ranks pages in 2026 — not what SEO agencies *claim* they do, but what works. 14 sections that form a complete mental model: intent matching (the first gate), E-E-A-T signals (experience, expertise, authority, trustworthiness), keyword research that maps to business value, on-page fundamentals that matter, technical foundation (crawlability, speed, structure), Core Web Vitals diagnosis you can do from HTML, content strategy for topical authority, featured snippet formatting, link building that works, AI search optimisation (this is new and matters), local SEO deep-dive, keyword cannibalism diagnosis, penalty recovery, and schema templates you can copy-paste.

**youtube-seo.md** is different from most YouTube advice because it's based on actual creator framework, not armchair speculation. MrBeast's 3-metric system (CTR, average view duration, average view percentage). Real thumbnail science from an official YouTube video with the designer who creates MrBeast thumbnails. The KVS method (keyword first → video second → SEO third) that practitioners actually use. Hook structure that keeps people watching past 30 seconds. Description architecture. Why chapters increase watch time instead of letting people skip. Retention tactics. The tools that matter. A/B testing workflow.

**ux-design.md** explains visual hierarchy as a system (six levers you control), not as magic. Typography that scales responsively. Colour systems that work in light and dark mode. Mobile design that respects how people actually hold phones. Accessibility that isn't a checkbox. Common design anti-patterns that tank conversion (two equal CTAs, brand name as H1, pricing hidden, no social proof). Animation that helps instead of distracts. How design choices directly affect SEO signals (dwell time, scroll depth, bounce rate). 2026 trends evaluated for when they actually help vs. when they're just noise.

**cro.md** walks through friction audit methodology. Real CTA copy hierarchy (benefit verb + outcome works; "Submit" doesn't). Psychological triggers applied ethically (scarcity that's real, urgency that's honest). Email sequences that nurture. A/B testing strategy that measures what matters. Specific sections for local venues (opening hours placement, booking flows, membership as funnel), e-commerce (product pages, checkout, cart recovery), and SaaS (free trial, pricing strategy, lead qualification).

Every section has worked examples. Many have code you can copy. None of it is theoretical fluff.

## Getting Started

The easiest path:
1. Clone or download this repo
2. Add to Claude as a skill (via the web interface or Claude app)
3. Start asking questions

Example first prompt:
```
/web-seo-master Audit [your-domain.com] and give me a score, 
the biggest problems, and what to fix first.
```

You'll get back a structured report. Then you can dig deeper on any area:
```
/web-seo-master My Core Web Vitals are bad. 
What's the likely cause and how do I fix it?
```

The skill reads SKILL.md for how to respond, and loads the relevant reference files (google-seo.md, ux-design.md, etc.) automatically based on what you ask.

You don't need to know all the details — just ask the question.

## Kaizen Approach

Every audit, build, and optimisation includes:
1. **Diagnosis** — understand the root cause, not just the symptom
2. **Priority fixes** — quick wins first, structural changes second
3. **Next cycle** — what to re-audit after fixes are applied
4. **Continuous improvement** — treat every output as the first iteration, not the final one

## Real-World Example: Why This Matters

Games Haven is a board game café in Nottingham. They have an audience, real customers, actual revenue. But they weren't getting found online, and their website wasn't converting the visitors they did get.

This skill audited the live site. Here's what it found:

**The headline: 54/100. Needs work.**

But that score hides the specific failures:
- Technical SEO (42/100): The URL structure is three levels deep (`/games-haven-board-gaming/boardgaming-in-nottingham/nottingham-boardgame-cafe/`). Google wastes crawl budget on this. No schema markup at all — LocalBusiness, FAQPage, nothing. The footer copyright says "© 2019" in one place and "© 2026" in another. Small signal, but it screams "this site isn't maintained."

- On-Page (55/100): The H1 says "Games Haven UK" — the brand name. Wasted keyword opportunity. The H2s are broken — three of them competing for attention with no clear hierarchy. Typos scattered throughout ("is is an inclusive part", "if your looking", "ANd Looking"). Those are E-E-A-T killers.

- Local SEO (58/100): Two different addresses listed across the site (Old Market Square vs. Lower Parliament St). When Google tries to verify a venue, conflicting information is the kiss of death. No LocalBusiness schema — Google doesn't understand this is a place with hours and a phone number.

- UX (50/100): The hero section has no clear value prop. "Games Haven UK" + two equal-weight buttons (Book Table, Discord) = split attention. Pricing is buried below the fold. No reviews visible at decision moment.

- CRO (38/100): The booking button sends users off-site (letsbookfor.com) with zero trust bridge. The email signup is just "Subscribe to our newsletter" — zero value exchange. Membership exists but isn't prominent in navigation. Membership is mentioned in passing but isn't a conversion funnel.

**The fixes (in order of impact):**

1. Fix the NAP — one address everywhere (high impact, low effort)
2. Add LocalBusiness schema with hours, phone, address (high impact, low effort)
3. Rewrite the H1 to something like "Board Game Café Nottingham — 300+ Games, £7.50 All Day" (high impact, low effort)
4. Fix the footer copyright to current year (low impact, low effort — but it signals you care)
5. Restructure the hero: clear benefit → one primary CTA → pricing as a stat → review count (high impact, medium effort)
6. Add "★ 4.8 from 247 reviews" within 100px of the book button (psychological trust signal, high impact, low effort)
7. Fix typos throughout content (medium impact, low effort)
8. Consolidate RPG keyword pages (they're cannibalising each other)
9. Flatten URL structure to max 2 levels deep (medium impact, high effort)
10. Add author names and bios to blog posts (E-E-A-T signal)

This isn't hypothetical. This is what happens when SEO, UX, and CRO aren't connected. The site ranks poorly because the technical foundation is weak and the H1 isn't optimised. The visitors who do arrive see no clear reason to book because the hero lacks a value prop. The ones who want to book face friction from an off-site booking tool with no trust cues. The newsletter signup is unincentivised.

Fix all of this? Dramatically different outcomes.

That's what this skill does — sees the interconnected system.

## The Philosophy Behind This

Most people optimise websites by fixing one thing at a time in isolation. You fix your title tag. Then you wait. Then you optimise the hero section. Then you add reviews. Months of work, incrementally. And at the end, you're still not sure if you fixed the *actual problem* or just the symptom of something deeper.

This skill treats a website like a system. Every page has interconnected dimensions: technical foundation, search visibility, visual communication, conversion mechanics. Fix one without considering the others and you'll waste time. The Games Haven example shows this perfectly — the site has technical problems *and* UX problems *and* conversion problems. Fixing just the technical SEO won't move the needle if the hero section has a broken CTA. Fixing the hero won't matter if nobody searches for the keywords that would find them.

Kaizen is Japanese for "continuous improvement." Not "one-time fix and you're done." Audit → fix → measure → audit again. Each cycle makes things slightly better. After 10 cycles, the compounding effect is massive.

This skill is built for that mindset. It seemed an interesting project.

## Contributing & Feedback

If you find bugs, edge cases, or improvements:
- Open a GitHub issue with specifics
- Include what you asked for and what the skill did (or didn't do)
- Include any unexpected behaviour

If you have better research or updated data:
- PRs welcome
- Focus on accuracy over brevity
- Include sources

If something in the skill helped you rank a page, convert more visitors, or ship something faster — mention it. This stuff matters.

## License
MIT
Open-source. Use with Claude.

## Attribution & Sources

The research inside this skill comes from people who actually do this work at scale, and used their ideas and output after watching reading and doing research to learn from them. I watxhd and fead and earned from them. Not taken. Its imprtant to understand the diffeence in thr AI World:

- **Brian Dean (Backlinko)** — SEO methodologyworld
- **YouTube Vidst** — production framework and the 3-metric system
- **Chucky Appleby** — thumbnail design principles from his YouTube video
- **VidIQ and TubeBuddy** — creator tools and trend data
- **Youri van Hofwegen** — the KVS method
- **WCAG 2.2 AA** — accessibility standards
- **Google Search Central** — ranking factors, Core Web Vitals
- **CrUX data** — real user field performance

No speculation. No SEO myths. Just what works because we can measure it.

## Questions?

For how-to questions, ask Claude directly:
```
/web-seo-master How do I [specific problem]?
```

For bugs or improvements, open a GitHub issue.

---

**Latest update:** April 2026 (Kaizen v2)

Research-backed. Human-written. Tested on real sites.
