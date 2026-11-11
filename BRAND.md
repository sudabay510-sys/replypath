# ReplyPath — Brand identity

**Slug:** `replypath`  
**Tagline:** A 30-day client outreach system for freelancers — process only, no income promises.  
**Local port:** `5104`  
**Status:** Live. Payments processed by Gumroad (Monthly or Quarterly).

## Audience persona
Freelancers with real skills and a lumpy pipeline who need an outreach operating system.

Primary personas:
- **Feast-or-famine freelancer:** You deliver well but stop prospecting when busy.
- **Specialist switching niches:** You need a tighter ideal-client list and offer line.
- **Quiet expert:** You dislike hype — you want brief, honest messages.

## Voice & tone
- Clear, encouraging, specific — never hype or fear.
- Honest about limits (No income, client-count, or “land 10 clients” guarantees. Process education only.).
- Short sentences on landing; checklist language in plans.

## Color palette
Defined in `static/brand.css` (`:root` variables). Accent drives CTAs; background stays calm for long reading.

## Fonts (Google Fonts)
Linked via `https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;60…` in templates.

## Logo
`static/logo.svg` — simple wordmark-friendly monogram on rounded square. Use on white/light headers; keep clear space ≈ 0.25× logo height.

## Iconography / illustration
Prefer flat geometric icons, soft corners matching `--radius`, no stock-photo people with fake quotes. Plan peeks use list + accent dots.

## Sample copy lines
- Hero CTA: “Build my outreach plan”
- Honesty: “No income, client-count, or “land 10 clients” guarantees. Process education only.”
- Paywall: “Start my plan” links to the Gumroad checkout URL.

## Do
- Show Monthly and Quarterly prices, plus the renewal sentence, before checkout.
- Save the customer’s email before sending them to Gumroad.
- Keep disclaimers visible near plans.
- Mobile-first quiz (one question per screen).

## Don’t
- Fake testimonials, stats, or press logos.
- Guarantee results (income, rankings, behavior, bookings).
- Fake urgency (“only 2 spots left”).
- Auto-edit third-party listings (SignMatch) or promise AI magic without saying plans are rule-based in this prototype.

## Explicit palette (hex)

| Token | Hex |
|-------|-----|
| Background | `#0B1020` |
| Alt background | `#121A31` |
| Card | `#151D36` |
| Ink | `#E8ECF8` |
| Muted | `#9AA6C3` |
| Accent | `#F0B429` |
| Accent hover | `#D9A017` |
| On-accent | `#1A1405` |

**Display font:** Syne  
**Body font:** DM Sans

## Logo file
`static/logo.svg`


## Identity refresh (Nov 2026)

Visual layer only (`static/identity.css`, `static/logo.svg`, Google Fonts URL). Quiz questions, plan generation, routes, pricing, checkout/unlock, and safety notes are unchanged.

- **Concept:** Dark pipeline board, keyboard-first. A calm night-mode workspace: the landing page is the pipeline, the quiz is a command palette, and the plan is a weekly board.
- **Type:** Unbounded (display) / DM Sans (body)
- **Voice:** A focused peer who’s been freelancing for years: brief, practical, allergic to hype.
- **Persona (design assumption, not research):** Sam, freelance web designer between projects (assumption): Two retainer clients ended last month. Great at delivery, stops prospecting whenever busy.

| Color | Hex |
|---|---|
| Midnight | `#0E0F1A` |
| Panel | `#171828` |
| Raise | `#22243A` |
| Paper | `#F2F2F7` |
| Electric lime | `#C6FF3D` |
| Violet | `#7B61FF` |
| Lilac | `#B5A6FF` |

Full brand guide, persona, and journey: `quiz-to-plan-redesign/products/replypath/brand.html`.
