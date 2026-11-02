> House style of Digital Card Services & Solutions (dcs.nl): Deep Navy chrome, white canvas, one DCS Blue accent, Space Grotesk headings over Hanken Grotesk.

The visual language of Digital Card Services & Solutions B.V. (DCS), a mobile
app studio in Baarn that builds iOS and Android apps for Dutch public-sector
organisations, SMEs and other clients. Use it for everything DCS says as
itself: dcs.nl pages, pitch decks, proposals and whitepapers, case studies,
the cover and frame around a client prototype, internal tools and dashboards.

A prototype *for* a client is designed in the client's own brand, not in this
one. DCS appears there only on the surfaces it owns: the pitch cover, the
presentation frame, a "Ontworpen door dcs." footer line.

## 1. Visual Theme & Atmosphere

Calm, technical and trustworthy — a studio that ships software for
municipalities and provinces, not a hype agency. The system rests on two
grounds: a **white, airy canvas** for reading and working, and **Deep Navy
(`#0C1A2E`) chrome** for the moments that carry the brand — the hero, the
footer, a pitch cover, an app's dark header. **DCS Blue (`#2F5FE0`)** is the
single accent and the only saturated colour on the page; it marks what you
can do, never decoration.

The mood comes from restraint and precision rather than effects: generous
whitespace, a tight grotesk headline, crisp 1px lines, real product
screenshots in phone frames, maps and data drawn cleanly. It should read as
engineered, Dutch and direct.

**Key characteristics**
- White `--bg` canvas with `#F5F7FB` surfaces; Deep Navy only for chrome and hero bands
- One accent: DCS Blue — primary buttons are white text on blue
- Space Grotesk for headings, labels, tabs and numbers; Hanken Grotesk for everything you read
- Hairline `#E6E9F0` borders and soft navy-tinted shadows instead of heavy cards
- Sticky header with a frosted (blurred, translucent white) background on scroll
- Product imagery: real app screens in device frames, maps, clean diagrams — no stock photos of people pointing at screens

## 2. Color

### Brand
- **DCS Blue** `#2F5FE0` (`--accent`): primary actions, links, active states, focus rings, the dot in the logo. The only accent.
- **Blue 600** `#2750C4` (`--accent-hover`): hover and pressed state of DCS Blue; also blue text on light tints when more contrast is needed.
- **Blue 300** `#7D9CF0` (`--accent-light`): links, icons and accent text on Deep Navy (6.6:1). Never use DCS Blue itself for text on navy (3.2:1).
- **Blue Tint** `#EEF3FE` (`--surface-warm`): selected rows, info callouts, the canvas behind editors and tools.
- **Deep Navy** `#0C1A2E` (`--navy`): hero bands, footer, pitch covers, app chrome, the logo tile.
- **Navy 2** `#16263D` (`--navy-2`, `--fg-2`): raised panels, inputs and buttons on navy; secondary heading colour on light.

### Neutrals
- **White** `#FFFFFF` (`--bg`): the main canvas.
- **Surface** `#F5F7FB` (`--surface`): alternating sections, cards, table headers.
- **Ink** `#1B2738` (`--fg`): body text and headings on light (15:1).
- **Slate** `#6B7689` (`--muted`): secondary text, captions, metadata. 4.6:1 on white; on `--surface` use it only at 18px and up.
- **Line** `#E6E9F0` (`--border`): dividers, card and input borders.
- **On-navy muted** `#A9B6CF` (`--on-navy-muted`): secondary text on Deep Navy.

### Semantic
- **Success** `#15803D`, **Warning** `#B45309`, **Danger** `#B91C1C` — all at least 5:1 on white. Pair each with an icon and a word; colour is never the only signal.

### Ratios
Roughly 80% white and surface, 15% navy, 5% blue. If blue covers more than a button, a link colour and an active state on one screen, it is overused.

## 3. Typography

- **Display — Space Grotesk** (`--font-display`), weights 500–700: h1–h3, section labels, tabs, buttons in navigation, big numbers and KPIs. Tracking `-0.02em` from 32px up.
- **Body & UI — Hanken Grotesk** (`--font-body`), weights 400/500/600: paragraphs, form fields, buttons, table cells, captions.
- **Mono — JetBrains Mono** (`--font-mono`): code, API names, technical identifiers only.
- Both families from Google Fonts; fall back to the system UI stack.

| Role | Font | Size / line height | Weight |
|---|---|---|---|
| Display (hero) | Space Grotesk | 60 / 1.05 | 700 |
| H1 | Space Grotesk | 44 / 1.1 | 700 |
| H2 | Space Grotesk | 32 / 1.15 | 600 |
| H3 | Space Grotesk | 24 / 1.25 | 600 |
| Eyebrow / label | Space Grotesk | 13 / 1.3, uppercase, +0.08em | 600 |
| Lead | Hanken Grotesk | 18–20 / 1.6 | 400 |
| Body | Hanken Grotesk | 16 / 1.6 | 400 |
| Small / caption | Hanken Grotesk | 14 / 1.5 | 400 |
| Button | Hanken Grotesk | 15–16 / 1 | 600 |

Headlines are sentence case, short and concrete. Line length 60–75 characters for body copy.

## 4. Spacing & Grid

- 4px base unit; use the `--space-*` steps (4, 8, 12, 16, 20, 24, 32, 48), with 64/96 for section rhythm.
- 12-column grid, max width 1200px, gutters 32px desktop / 24px tablet / 16px phone.
- Section padding 96px desktop, 72px tablet, 48px phone.
- Mobile app screens: 16px side margins, 8pt rhythm, 44pt minimum hit targets, respect safe areas.

## 5. Layout & Composition

- **Web pages:** sticky frosted header (logo left, nav centre/right, one blue "Contact" or "Plan een gesprek" button). A Deep Navy hero with white Space Grotesk headline, a one-line lead in `--on-navy-muted`, and a product visual (phone frames, map, dashboard) on the right. Light sections below, alternating `--bg` and `--surface`. Navy footer.
- **Proof before claims:** case studies, app-store screenshots, client logos (with permission) and concrete numbers that come from a real source.
- **Pitch decks:** navy cover slide with the logo tile; content slides on white with a navy title band or a navy left rail; one idea per slide; product screens large.
- **Documents and whitepapers:** white pages, navy cover, Space Grotesk headings, Hanken body at 11–12pt, blue only for links and key figures.
- **Dashboards and tools:** navy top bar or left rail, Blue Tint canvas, white panels with Line borders, blue for the selected item.
- **App screens (DCS's own apps):** white or navy background, bottom tab bar with Space Grotesk labels, DCS Blue for the active tab and primary button.

## 6. Components

- **Logo:** the lowercase wordmark `dcs` in Hanken Grotesk, tight tracking, with a round DCS Blue dot after it ("dcs."). On navy the letters are white; on white they are Deep Navy. The **brand mark** is the wordmark on a white rounded tile (corner ≈ 20% of tile height) — used as app icon, favicon and on the navy pitch cover. Never recolour the dot, never stretch or outline the wordmark.
- **Primary button:** DCS Blue fill, white Hanken 600 text, `--radius-sm` (8px), 44–48px high, 20–24px horizontal padding; hover Blue 600. One primary button per view.
- **Secondary button:** white with a 1px Line border and Ink text; on navy, Navy 2 fill with white text.
- **Text link:** DCS Blue, underline on hover; Blue 300 on navy.
- **Card:** white, 1px Line border, `--radius-md` (12px), `--shadow-sm`; `--shadow-md` on hover for clickable cards. No coloured left borders.
- **Input:** 44px high, white, 1px Line border, `--radius-sm`; focus = 2px DCS Blue ring with 2px offset. Label above in Hanken 500 14px; helper and error text below.
- **Tag / chip:** Blue Tint fill, Blue 600 text, `--radius-pill`, Hanken 500 13px.
- **Table:** `--surface` header row in Space Grotesk 600 13px; 1px Line row dividers; numbers right-aligned in tabular figures.
- **Phone frame:** neutral dark frame with real screens; shown at an angle only on navy heroes, straight everywhere else.
- **Icons:** 1.5–1.75px stroke monoline, `currentColor`, rounded joins (Lucide-style). No emoji as icons.

## 7. Motion & Interaction

- Short and functional: 150–200ms for hover and press, 250–300ms for panels and sheets, `cubic-bezier(0.2, 0, 0, 1)`.
- Header gains its frosted background and a Line bottom border after scrolling 8px.
- Cards lift with the shadow change only; no scale bounce.
- Respect `prefers-reduced-motion`: drop movement, keep opacity fades.

## 8. Voice & Brand

- **Dutch first**, English second; the site is bilingual. Write `je` in product and marketing copy; `u` only where the client context asks for it.
- Direct, concrete and calm: what we build, for whom, and what it changes. Plain language (B1 level) for public-sector audiences.
- Name real work and real technology — React Native, Firebase, Supabase, maps, push notifications — and avoid buzzwords ("next-level", "revolutionair", "disruptief").
- DCS has shipped 40+ apps in over ten years; use that only as stated, and never invent metrics or client results.
- Public-sector work must meet WCAG 2.1 AA (Besluit digitale toegankelijkheid overheid) and the AVG/GDPR; designs show accessible states and privacy-respecting defaults by default.

## 9. Anti-patterns

- A second accent colour, gradients on buttons, or purple/indigo anywhere.
- DCS Blue text on Deep Navy, or Slate text on `--surface` below 18px.
- Navy used for whole content pages; navy is chrome and hero, not the reading surface.
- Inter, Roboto or system fonts on headings instead of Space Grotesk.
- Stock photography, 3D blobs, glowing orbs, glassmorphism beyond the header.
- Emoji as icons, rounded cards with coloured left borders, filler copy or invented numbers.
- Putting the DCS brand on a client's prototype screens — client work uses the client's brand.

## Not synced from Open Design

- Written as literal colours computed from color-mix(): --accent-active. They won't follow later edits to the colours they mix.
- Fonts are named by family only (hosted faces); no font files were copied.
- No components or assets: Open Design design systems carry tokens and guidance only.
