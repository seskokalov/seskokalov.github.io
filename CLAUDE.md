# PhiloStack — Website Project

## Company Identity

**Name:** PhiloStack
**Tagline:** We build the systems your business runs on.
**Origin:** From Greek *philos* (φίλος) — friend, one who loves — combined with *stack* (technology foundation). Named for Filip, whose name means "lover of strength" (from Philippos: philos + hippos).

**Location:** Skopje, North Macedonia
**Market:** SMBs across Europe, starting from the Balkans. Primary vertical: retail/fashion, expanding to others.
**Email:** hello@philostack.com
**Social handles:** @philostack (claim on Instagram, LinkedIn, GitHub, Twitter)

## Core Services

1. **ERP Solutions** — Custom development, integration, consulting. Pantheon ERP, SQL Server, stored procedures, triggers, automations.
2. **Web Applications** — ASP.NET Core / Blazor production apps. Inventory management, e-commerce, order fulfillment, POS integration.
3. **Business Intelligence** — Power BI dashboards, custom SQL views, data pipelines, analytics.
4. **System Integration & Automation** — Connecting ERPs with webstores, fiscal printers, courier APIs, third-party systems.

## Tech Stack

SQL Server, Power BI, ASP.NET Core, Blazor, Pantheon ERP, Python, Azure, SQL Agent, Fiscal printer integration (PF-550), REST APIs, QuestPDF, Telegram Bots, pyodbc.

## Brand Voice & Tone

- **Professional but human** — not corporate jargon, not startup hype
- **Confident, not arrogant** — we know what we're doing because we've been in production for years
- **Direct** — no fluff, no buzzwords. "We automate the workflows you're still doing by hand."
- **Technical credibility** — we speak the language of DBAs, sysadmins, and ERP consultants
- **Trustworthy** — the kind of company a CFO would trust with their systems

## Design System

### Colors
```css
--ink: #0a0f1a;          /* Primary text */
--ink-soft: #2a3148;     /* Secondary text */
--ink-muted: #5a6380;    /* Tertiary text */
--surface: #f8f7f4;      /* Page background (warm off-white) */
--surface-warm: #f0eeea; /* Section backgrounds */
--surface-card: #ffffff;  /* Card backgrounds */
--accent: #1a5cff;       /* Primary blue */
--accent-soft: #e8efff;  /* Blue tint */
--gold: #c4922a;         /* Secondary accent (origin story, tags) */
--gold-soft: #fdf6e8;    /* Gold tint */
```

### Typography
- **Display/Headings:** DM Serif Display (serif, elegant, editorial)
- **Body/UI:** Outfit (clean, modern, excellent readability)
- **Code/Monospace:** JetBrains Mono (technical credibility)

### Design Principles
- Warm off-white backgrounds, NOT stark white
- Subtle noise texture overlay for depth
- Cards with soft borders, generous padding
- Blue accent top-bar animation on card hover
- Pill-shaped buttons and tags
- Generous whitespace
- No generic AI aesthetics (no purple gradients, no Inter font, no cookie-cutter layouts)

## File Structure

```
philostack/
├── CLAUDE.md              ← You are here
├── index.html             ← Main landing page (single file, all CSS/JS inline)
├── assets/
│   ├── screenshots/       ← Portfolio screenshots (masked versions)
│   │   ├── erp-integration.png
│   │   ├── ecommerce-platform.png
│   │   └── powerbi-dashboard.png
│   ├── logo/              ← Logo files when ready
│   └── og-image.png       ← Social sharing image
└── README.md
```

## Current Status

- [x] Company name finalized: PhiloStack
- [x] Trademark preliminary check: CLEAN (no conflicts found)
- [x] Landing page v1 built (index.html)
- [ ] Domain registration (check philostack.com, philostack.dev)
- [ ] Social media handles claimed (@philostack)
- [ ] Portfolio screenshots: need to mask sensitive data and insert
- [ ] Logo design
- [ ] OG image / social sharing meta tags
- [ ] Contact form backend (Formspree, Netlify Forms, or custom)
- [ ] Deploy (Netlify, Vercel, or custom hosting)
- [ ] Instagram campaign strategy & content

## Screenshot Masking Requirements

When adding portfolio screenshots, ALL of the following must be masked/anonymized:
- **Company names** — replace with generic names or blur
- **Customer names** — blur or replace entirely
- **Real financial figures** — replace with realistic but fake numbers
- **Database names** — replace `MK_MAGNETIK_2018` with generic names
- **Store location names** — generalize (e.g., "Store A", "Location 1")
- **Invoice numbers and dates** — randomize
- **Brand names** from suppliers — blur or generalize unless you have permission
- **Any personally identifiable information (PII)**

Keep the UI/layout/design clearly visible — the goal is to showcase the quality of the work, not the specific client data.

## Portfolio Projects (for Work section)

### 1. Multi-Store Retail ERP Integration
- **Tag:** ERP · Retail
- **Description:** Automated price changes, stock transfers, and POS synchronization across 5+ retail locations with real-time inventory tracking.
- **Tech:** SQL Server, Pantheon ERP, T-SQL stored procedures, SQL Agent, fiscal printer integration

### 2. Fashion E-Commerce Platform
- **Tag:** Web App · E-commerce
- **Description:** Full-stack Blazor web application connecting online orders directly to ERP fulfillment — from click to shipment.
- **Tech:** ASP.NET Core, Blazor, SQL Server, nopCommerce, REST APIs

### 3. Executive Sales Dashboard
- **Tag:** Power BI · Analytics
- **Description:** Real-time Power BI reporting across all store locations — revenue, margins, stock levels, and payment analytics in one view.
- **Tech:** Power BI, SQL Server views, DAX, scheduled refresh

## Next Steps

1. **Screenshots** — Provide raw screenshots to Claude for masking, then place masked versions in `assets/screenshots/`
2. **Logo** — Generate or commission a logo (the current "PS" square mark works as a placeholder)
3. **Deploy** — Push to Netlify/Vercel for a live URL
4. **Instagram** — Plan content strategy (next phase)

## Development Notes

- The landing page is a single HTML file with all CSS inline — no build step needed
- Google Fonts loaded from CDN (DM Serif Display, Outfit, JetBrains Mono)
- Form currently shows an alert on submit — needs a real backend
- Fully responsive (mobile-first breakpoints at 900px and 600px)
- No JavaScript frameworks — pure HTML/CSS with minimal inline JS for the form
- To add screenshots: replace the `.work-thumb-inner` placeholder divs with `<img>` tags
