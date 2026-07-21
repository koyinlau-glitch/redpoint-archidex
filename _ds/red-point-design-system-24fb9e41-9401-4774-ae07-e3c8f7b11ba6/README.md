# Red Point Design System

A brand design system for **Red Point Signcraft** — a 40+ year Malaysian signage manufacturer repositioning from "signage vendor" to **Brand Impression Strategist**.

> **We make brands seen.**

This system is built to support the repositioning: every asset should make Red Point look like the senior partner you call when the work matters, not the cheapest fabricator on the list.

---

## 1. The Company

**Red Point Signcraft** (redpoint.com.my) is a Malaysia-based, family-run signage and brand-environment manufacturer with 40+ years of industrial-scale execution. Sister brand: **M Creative** (interior architecture & carpentry).

**Full scope:**
- Brand Impression & Signage Solutions (channel letters, monuments, building identity)
- LED Displays & Digital Signage
- Facade Systems
- Retail & Commercial Space Display
- Turnkey project delivery — single accountability across the four

**Strategic frame:** clients don't buy signs, they buy *visibility*. The system has to express scale, craft, and quiet authority — not "amazing solutions provider" energy.

**Audience:** retail chain ops/store-dev heads, corporate brand directors, developers/project directors, architects & ID consultants. Mid-to-senior, time-poor, reputation-aware. Trilingual (EN / Mandarin / BM). Klang Valley → SEA.

---

## 2. Source Material

Everything in this system was derived from materials supplied by the team. **The reader is not assumed to have access** — referenced here for traceability.

### Provided codebase / docs (read-only, via File System Access)
Mounted as `Red Point Signcraft/`:
- `_context/brand-context.md` — positioning, competitive frame, rules of engagement
- `_context/brand-voice.md` — tone, vocabulary, do/don't patterns, sample phrasing
- `_context/ideal-customer-profile.md` — personas, buying triggers, objection counters
- `positioning-statement.md` — formal positioning, differentiator pillars, messaging hierarchy
- `messaging-framework.md` — four content pillars, emotional/authority themes
- `linkedin-page-rewrite.md` — LinkedIn tagline, About, specialties
- `content-calendar-90day.md` — 13-week posting cadence + pillar mix

### Provided uploads (in `uploads/`, copied into `assets/`)
- `RP_Logo-red.png` → `assets/logo-redpoint-silver.png` — wordmark + chrome sphere
- `RP_Logo-white.png` → `assets/logo-redpoint-red.png` — wordmark for dark backgrounds + red sphere
- `IMG_6094.PNG` → `assets/img-hq-redpoint-daytime.png` — HQ exterior, black-and-white with selective color
- `Image02.png` → `assets/img-team-workshop.png` — team in red polos, workshop floor
- `Image03.png` → `assets/img-hq-redpoint-bw.png` — HQ B&W with red wordmark
- `Image05.png` → `assets/img-fabrication-detail.png` — close-up of channel-letter fabrication
- `redpoint-services-E-01-45d22f49.webp` → `assets/img-engineer-cad.webp` — engineer at CAD
- `REDPOINT-BrandColor.pdf` — brand color reference (image-based PDF; colors sampled directly from the master logo PNGs)

### Public reference
- Website: **www.redpoint.com.my**

---

## 3. Index — what's in this folder

| File / folder | What it is |
|---|---|
| `README.md` | This file — context, voice, visual foundations, iconography, index |
| `SKILL.md` | Agent skill manifest — read this first if you're a designer-agent dropped into the system |
| `colors_and_type.css` | Color tokens, type scale, semantic CSS vars. Load in every artifact. |
| `fonts/` | Self-hosted Avenir LT Pro (Light → Black, romans + obliques) + Poppins (legacy) |
| `assets/` | Logos, brand photography. `logo-redpoint-silver.png` for light grounds, `logo-redpoint-red.png` for dark |
| `preview/` | 28 specimen cards that populate the Design System tab — Brand, Colors, Type, Spacing, Components |
| `ui_kits/website/` | Hi-fi marketing-site recreation. `index.html` composes Header / Hero / Capabilities / Stats / Featured / Belief / Process / CTABand / Footer JSX components |

---

## 4. Content Fundamentals

**Voice in one line:** the senior practitioner who's delivered for four decades and doesn't need to oversell.

### Tone
Confident expert. No fluff. Quiet authority. **Specifics over superlatives.** Same DNA as M Creative — different subject matter.

### Person & address
- **"We"** for Red Point. **"You"** when speaking to the buyer.
- Never "I." This is an institution, not a founder voice.
- Direct address is fine in CTAs: *Brief us on your next rollout.*

### Casing
- **Sentence case** for body copy and most headlines. Editorial, not shouty.
- **Title Case** sparingly — section labels, eyebrow tags, button text on primary CTAs.
- **ALL CAPS** reserved for: the wordmark, eyebrow kickers (small + tracked), and signage-style numbered callouts (`PROJECT 037`).
- Never SCREAMING headlines.

### Numerals
- **Always use numerals for proof:** `40+ years`, `12 weeks`, `180-meter LED facade`, `8 outlets in 6 weeks`.
- Specifics are the moat — `national retail chain, 40-outlet rollout, 12-week delivery` beats "leading brands trust us."
- Acceptable to anonymize the client but **never** the specs.

### Punctuation
- En-dashes for ranges (`40+ years`, `KL – Penang – JB`) and em-dashes for asides.
- Periods inside short declarative sentences. *"The launch lands. The brand shows up."*
- No exclamation marks. Ever.

### Emoji
**Almost none.** Only acceptable in social bios at the end of a CTA line (e.g. `🌐 www.redpoint.com.my`). No emoji in product UI, decks, web copy. No emoji "cards." No 🎉 ✨ 🚀.

### Vocabulary

**Lean into:** *make brands seen, brand impression, visibility, large-scale, industrial-scale, at scale, 40+ years, four decades, proven, turnkey, end-to-end, one partner, one accountability, in-house fabrication, craftsmanship, facade, LED, retail display, rollout-ready, on time, on spec.*

**Avoid:** *affordable, best price, cheap, budget-friendly, leading, premier, your trusted partner in…, one-stop solution, revolutionary, game-changing, amazing, excited to share, world-class, innovative.*

### Sample phrasing

**Good headline:** *Forty years making brands seen at the scale they're built for.*
**Good caption:** *180-meter LED facade. 12 weeks from brief to switch-on. One vendor, one accountability.*
**Good CTA:** *Brief us on your next rollout.* / *See how we delivered.* / *Request a scope review.*

**Bad (avoid):** *Your trusted leading signage solution provider in Malaysia!* / *We are excited to share our latest amazing project for one of our valued clients!*

### The publishing test
Read it aloud. If it sounds like a brochure, kill it. If it sounds like a senior person explaining the job to a peer, ship it.

---

## 5. Visual Foundations

The visual system has one job: look like the **senior partner** the buyer brings in when the work matters. Industrial. Architectural. Engineered. Quiet.

### Color
A three-layer palette — small, deliberate, no rainbow.

- **Red Point Red `#DE2027`** — the brand. Used **as accent** — never as a flooded background or a gradient wallpaper. Reserved for the brand mark, button primaries, key callouts, the underline on a stat. Used sparingly, it carries weight.
- **Sphere Red gradient** (`#E55544 → #D92026 → #752012`) — only inside the logomark sphere. Do not extract for general UI.
- **Black `#0B0B0C` → True Black `#000000`** — primary surface for hero, oversized type, photography mattes. Echoes the actual HQ facade.
- **Silver / Chrome gradient** (`#E4E5E6 → #CDCED1`) — sister mark color, used on metallic UI accents (rules, the silver mark), and as the cool neutral against the red.
- **Warm/cool gray neutrals** (`#F5F5F4 → #1A1A1A`) — surfaces, borders, body text. See `colors_and_type.css`.
- **Pure white `#FFFFFF`** — secondary surface; copy on dark photography.

Do **not** use other hues. No teal/purple gradients, no pastels, no semantic green/blue except for the standard form-state colors (defined in CSS, used quietly).

### Backgrounds
- **Mostly flat solid color** — `#FFFFFF`, `#0B0B0C`, `#F5F5F4`, `#1A1A1A`. No noisy patterns.
- **Photography** as full-bleed hero is the dominant visual device — see Imagery below.
- **No textures, no repeating patterns, no hand-drawn illustrations.** This is a fabricator, not a craft studio.
- **One legal gradient:** the metallic radial used inside the logomark sphere. Do not introduce others.
- **Section bands of pure black** are a signature device — they should feel like a black aluminium cladding panel, not a fashion-brand mood.

### Imagery / Photography
Red Point's strongest visual asset.

- **Color treatment:** desaturated or selective color. The world is monochrome; **Red Point red is the only colour that survives**. Building shells, machinery, faces — neutral. Polos, signage, the wordmark — vivid.
- **Sourcing:** own work first — real workshop, real install crews, real night switch-ons. **Stock is allowed** when own imagery isn't available, but it must read as **localized to Malaysia / SEA** (people, signage scripts, streetscapes) — never generic global stock. When stock is used as a hero, **stamp it with the brand mark** (bottom-right, white wordmark on a 55% black plate) so it doesn't look like a stock library.
- **Tone:** warm-shadow, cool-highlight. Industrial. A little grain is fine; gloss-retouched is wrong.
- **Crop:** confident, architectural — look up at facades, look down at workbenches.
- **Night shots** are the brand's secret weapon — LED reveal, illuminated wordmark, traffic streaks.
- People are shown **doing the work** — never posed against a cyclorama.

### Type
The brand face is **Avenir LT Pro** — Adrian Frutiger's humanist geometric sans, self-hosted from `fonts/`. One family carries the whole system; the visual contrast comes from weight, not from a second face.

- **Display:** `Avenir LT Pro Black` (900) — hero statements, big oversized type.
- **Subhead / UI:** `Avenir LT Pro Heavy` (700) — H2/H3, button labels, eyebrow kickers.
- **Body lead:** `Avenir LT Pro Medium` (500) — large body, intro paragraphs.
- **Body default:** `Avenir LT Pro Book` (400) — paragraphs, captions.
- **Body light:** `Avenir LT Pro Light` (300) — large display body where Book reads too heavy.
- **Mono:** `JetBrains Mono` (400/500) — specs, project numbers, dimensions, codes (`PRJ-0238`, `180 m × 12 m`).
- **Numerals** prefer tabular figures for stats and proof-points.

The wordmark itself is a custom-drawn squared geometric — *not* Avenir. Don't try to recreate it from the system face.

See `colors_and_type.css` for the full scale.

### Spacing
- **4px base unit.** Tokens: `4, 8, 12, 16, 24, 32, 48, 64, 96, 128`.
- Generous on hero compositions — the brand is about scale; the layout should breathe.
- Tight inside data/spec callouts — they should look engineered.

### Borders
- **`1px` solid** — the workhorse. Color is `--border` (warm-cool dark gray on light, light gray on dark).
- **`2px` solid** for emphasized rules — section breaks, the underline beneath a stat.
- **No dashed borders.** No double borders. No inset/outset.

### Corner radii
- **`0`** is the default — sharp, architectural, signage-like.
- **`2px`** for inputs and chips when softness is needed.
- **`9999px` (pill)** for the eyebrow tag — explicit echo of the dot in the logo.
- **`50%` (circle)** for the brand mark, avatars.
- Avoid `8px`, `12px`, `16px` web-rounding tropes. They make the brand look like every SaaS landing page.

### Shadows / Elevation
- **Minimal.** This is a print/industrial system, not Material.
- One shadow on lifted cards: `0 1px 2px rgb(0 0 0 / 0.04), 0 8px 24px -8px rgb(0 0 0 / 0.08)`.
- **No glow effects, no neon shadows.** The exception: an *optional* LED-glow treatment on hero imagery to suggest illuminated signage — used **only on photography**, never on UI elements.

### Hover states
- **Buttons:** background goes one shade darker (red → deeper red; black stays black, accent edge appears).
- **Links:** underline appears, color does **not** change.
- **Cards:** subtle lift (translate-y `-2px`, shadow intensifies) + thin red rule underneath the title.
- **Images:** very slight zoom (`scale(1.02)`) over 400ms; no filter changes.

### Press states
- Buttons compress (`scale(0.98)`) and darken a touch.
- No "bounce" animations. Crisp.

### Animation
- **Easings:** `cubic-bezier(0.22, 1, 0.36, 1)` (ease-out-quart) is the default. Linear for marquees. **Never** spring-bouncy.
- **Durations:** 150ms (micro), 250ms (component), 600ms (hero reveal). Don't go longer.
- **Use sparingly.** Fade-in on scroll for hero content. A 1-frame "switch-on" flash for LED-style numbers. That's it.

### Transparency & blur
- Use sparingly. Acceptable for: full-screen image overlays (black at 40–70% opacity for legibility), the sticky header on a photo hero (black `rgba(11,11,12,0.7)` + `backdrop-filter: blur(12px)`).
- **No frosted "glass" cards** scattered through the page.

### Cards
- **Default card:** white surface, `1px` border in `--border-subtle`, `0` radius, no shadow.
- **Lifted card:** add the one elevation shadow above.
- **Dark card:** `#0B0B0C` surface, body in `--fg-on-dark`, accent rule in red.
- Never a "rounded card with colored left border" — that pattern is banned.

### Layout rules
- **Editorial grid.** 12-column on desktop, generous gutters. Asymmetric where it makes sense — a 7+5 split is more interesting than a stale 6+6.
- **A signature device:** big red dot / red square in the top-left of a hero, sized like a logo bullet — echoes the wordmark's dot.
- **Numbered project callouts** (`PROJECT — 037`) as small mono kickers above a hero image.
- Header is a thin, fixed dark bar; footer is a wide black slab with the wordmark big.
- Avoid web-design tropes: no carousels-of-features-with-icons, no "stats grid with 4 colored boxes," no "trusted by [grid of grey logos]." Use one named project with the actual scope instead.

### Use of the brand mark
- Wordmark + sphere is the lockup. Don't separate.
- **Silver sphere** for light backgrounds. **Red sphere** for dark backgrounds.
- Minimum clear space = the diameter of the sphere on all sides.
- Never recolor the wordmark to anything other than `#DE2027` (on light) or white (on dark).
- Never apply effects, outlines, or shadows.

---

## 6. Iconography

### Approach
Red Point doesn't have its own icon system in the provided materials. The brand's iconographic energy comes from **the logomark dot itself** — that red sphere is the strongest single visual asset and should be reused as a bullet, an active-state indicator, an end-of-line accent.

### Icon library
We're using **Lucide** (https://lucide.dev) via CDN as the system icon set. Rationale:
- Clean 1.5-stroke line icons — match the engineered, industrial feel.
- Comprehensive — covers business/marketing/retail icons (Building, Factory, Lightbulb, MapPin, Zap, ArrowUpRight, etc).
- License: ISC, free to use.
- Stroke-only, monochrome — inherits color easily and doesn't fight the photography.

**Substitution flag:** Red Point hasn't provided a custom icon set. If one exists or is created later, swap in the SVGs and document them here. Until then, Lucide is the system.

```html
<!-- Load from CDN -->
<script src="https://unpkg.com/lucide@0.453.0/dist/umd/lucide.min.js"></script>
<i data-lucide="building-2"></i>
```

### Usage rules
- **Stroke:** 1.5px (Lucide default). Never fill icons.
- **Color:** inherit from text. Red only when actively indicating the brand (active nav, primary action), otherwise neutral.
- **Size:** 16, 20, 24, 32 px. Match the cap-height of adjacent type.
- **No icon stacking** in feature cards. One icon per concept, max — and prefer a real photograph or project number instead.
- **No emoji icons.** No unicode arrows as decorative chrome (an arrow inside a button label is fine — use `→` or Lucide `ArrowRight`).

### The red-dot bullet
A reusable graphic element: an 8–12px solid red `#DE2027` circle. Use as:
- A list-item bullet on dark surfaces.
- An end-of-line "active" indicator (`Workshop Open ●`).
- The decorative period at the end of a kicker line (`PROJECT — 037 ●`).

This is the one piece of brand-specific iconography. Use it.

### Logos in the wild
- `assets/logo-redpoint-silver.png` — full color, silver sphere, on light grounds.
- `assets/logo-redpoint-red.png` — wordmark in white, red sphere, on dark grounds.

---

## 7. UI Kits

See `ui_kits/website/` — a hi-fi recreation of the redpoint.com.my marketing site, rebuilt to match the new repositioning rather than the existing (weak) site. Components are factored into reusable JSX modules.

The existing redpoint.com.my site is acknowledged in the brand brief as a weak point that doesn't reflect the quality of the actual work. This UI kit is therefore **aspirational** — what the site *should* look like given the repositioning. It is not a 1:1 replica of the current production site.

---

## 8. Caveats

- **No production codebase was provided** — only positioning, voice, content strategy docs, brand photography, and a logo. The UI kit is therefore a design-led interpretation rather than a code-derived recreation.
- **The brand-color PDF could not be machine-read** (image-based). Colors were sampled directly from the master logo PNGs at high fidelity. If the PDF specifies official Pantone/CMYK numbers, please share them and we'll update.
- **The brand face is licensed `Avenir LT Pro`** \u2014 supplied directly and self-hosted in `fonts/`. Make sure any production deployment of these assets carries the appropriate Avenir license (Linotype/Monotype). The companion `Poppins` files in `fonts/` are unused by this system but included for legacy support if existing print/print-adjacent assets need them.
- **No production icon set was provided** — using Lucide as a placeholder system.
- **No sample decks or slide templates were provided** — none generated. Available on request.
- **No Mandarin/BM type pairing** has been specified. If marketing assets need CJK, recommend pairing with `Noto Sans SC` and `Noto Sans` respectively. Flag for review.
