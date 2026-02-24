# AI Mobile Games Strategy — 2-Page Strategy Document

## Project Overview
Executive-grade 2-page HTML document to secure $35k/year resources for an Agentic AI strategy in mobile games at **Carry1st**. Targets **Robin Cocker, CEO**. Page 1 = strategic case, Page 2 = the concrete ask.

## Key File
- `index.html` — the complete self-contained 2-page document (renamed from `ai_games_strategy.html` for GitHub Pages)

## Tech Stack
- Single HTML file, fully self-contained
- Google Fonts CDN: **Syne** (headers, 600/700/800 weight) + **DM Sans** (body)
- Inline CSS, inline SVG chart
- No JS frameworks, no build step

## Design System
- **Theme**: Dark cinematic — background `#07070c`, surfaces `#0e0e18`/`#131320`
- **Accent colors**: Cyan `#00e5ff`, Blue `#4d7cff`, Purple `#a855f7`, Magenta `#e040fb`
- **Gradient**: `linear-gradient(135deg, #00e5ff, #4d7cff, #a855f7, #e040fb)`
- **Typography**: Syne 800 for headings (gradient text), DM Sans for body
- **Base font size**: 11.2px
- **Page size**: 210mm x 297mm (A4), padding 18px 22px

## Visual Effects
- Floating ambient gradient orbs with float animation
- Dot grid overlay (22px spacing, 2.5% opacity)
- Animated shimmer on top glow line
- Corner accent SVGs (cyan top-left, purple bottom-right)
- Glowing left-edge accent bars on each pillar card (color-matched)
- **Chart heartbeat pulse**: 3-layer dot (white core → cyan → glow ring) travels along AI curve via SVG `animateMotion`, 3s loop
- **Divergence pulse**: Dashed line at Q4 with blur glow
- **Print**: Dark theme preserved via `print-color-adjust: exact`

## Page 1: The Strategic Case

### Content Structure (5 Pillars from 17 Original Points)

#### Pillar 1: Exponential Productivity (Points #1, #2, #3, #9)
- Non-linear output growth via chained agent workflows
- Cross-team tooling leverage (one AI lead → all teams)
- Time-to-first-playable acceleration
- Balancing tables/reward curves automation

#### Pillar 2: Scalable Content & Live Ops (Points #4, #5, #12)
- Procedural + agentic pipelines for F2P retention
- Autonomous event deployment with economy tweaks
- Near-zero marginal content cost

#### Pillar 3: Player Intelligence & Growth (Points #6, #7, #8, #15)
- Per-segment adaptive difficulty/quest/narrative (LTV)
- FTUE/D1/D7 retention improving CPI
- Autonomous hypothesis generation for A/B testing
- Telemetry-to-action loop for economy balancing

#### Pillar 4: Quality & Risk Reduction (Points #10, #16, #18)
- 1,000s of simulated gameplay sessions
- Design philosophy encoded in agent frameworks
- Formalized cross-team workflows

#### Pillar 5: Strategic Advantage (Points #11, #19, #20)
- Internal IP / defensible tech advantage
- Early adoption / industry positioning
- License/spin-off optionality

### Layout (top to bottom)
1. **Header** — gradient title + confidential badge + date
2. **Thesis banner** — centered, gradient border
3. **Pillars 1-4** — 2x2 CSS grid with icon + bullets + metric badge
4. **Pillar 5** — full-width 4-column grid (label + 3 strategy columns)
5. **Metrics row** — 4 cards (3-5x, 60%, 30-50%, 24/7) with gradient numbers
6. **Chart panel** — SVG divergence chart with heartbeat pulse, fills remaining space

### Chart Details (SVG viewBox 520x130)
- Y-axis: top = High cost, bottom = Low cost
- Manual: flat line near top (y≈18-24), gray
- AI-Augmented: curves from y=20 → y=102, gradient stroke
- Divergence annotation at Q4

## Page 2: The Ask

### Layout (top to bottom)
1. **Header** — "The Ask: $35k/year"
2. **Big number card** — $35k/yr with explanation (less than half a mid-level engineer)
3. **Team restructure** — 3 cards in grid:
   - **Denzil** → Agentic AI Lead (existing, refocused)
   - **JD** → Game Dev & Maintenance (existing, refocused)
   - **New Hire** → Dev Support (the $35k ask, junior-to-mid)
4. **ROI comparison** — Without vs With investment (red ✕ vs green ✓)
5. **Context bar** — 3 metrics: $35k vs $80k+, Q2 2026 first pipeline, 0 revenue risk
6. **Final CTA** — "$35k to unlock compounding returns..." with "The only risk is waiting."

## Git Setup
- Repo initialized at `D:\Claude\AI_OnePager`
- Main file is `index.html` (for GitHub Pages compatibility)
- Ready to push to GitHub → enable Pages → deploy from `main` branch root

## Deployment
- **GitHub Pages**: push to public repo, enable Pages on `main` / root
- **Netlify Drop**: drag folder to app.netlify.com/drop
- **Slack sharing**: share the live URL or zip the HTML file

## Known Decisions
- Metrics row sits **above** the chart on Page 1
- Print styles keep **dark theme** per user preference
- Chart uses `flex: 1` to fill remaining vertical space
- `page-break-before: always` separates the two pages for print
