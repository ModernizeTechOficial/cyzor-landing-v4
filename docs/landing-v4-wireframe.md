# CYZOR V4 — Low-Fidelity Wireframe

## Status
OFFICIAL — single generated wireframe for V4.

## Reference
Desktop reference: 1440px.
Mobile reference: responsive recomposition, not a separate visual artifact.

## Structural contract

### 01 — Header
Desktop height: 80px.
Logo left, navigation center, primary CTA right.
Mobile: logo + compact menu.

### 02 — Hero
Desktop target height: 800px.
Two-column composition:
- left: eyebrow, headline, supporting text, primary CTA, secondary CTA;
- right: future visual asset placeholder.
Asset placeholder target: 1440×800 reference area in composition; production asset must be isolated/transparent and dimensioned according to its final container.
Mobile: text first, visual below.

### 03 — Logos / Trust
Target height: 120px.
Reserved for optional real customer/partner evidence only.
No invented logos or trust numbers.

### 04 — Module Ecosystem
Target height: ~520px.
Section title + module cards + view-all action.
Primary visible modules: CRM, ERP, Projects, People, Documents, BI, Automations.
Additional modules remain accessible without creating a wall of cards.

### 05 — Product Demonstration
Target height: ~700px.
Large product-interface visual area plus explanatory copy and benefit list.
The interface is a future production asset; product claims must remain truthful.

### 06 — AI Workforce
Target height: ~520px.
Section label, headline, supporting text, CTA and large AI visual area.
The future asset represents specialized agents and their relationship to CYZOR AI Manager.

### 07 — Benefits
Target height: ~300px.
Four concise benefit cards:
- Modular
- Scalable
- Secure
- Flexible

Cards use the future Card Visual System.

### 08 — Testimonials / Cases
Target height: ~400px.
Reserved for real customer evidence only.
If verified customer data is unavailable, this section must be replaced or omitted rather than fabricated.

### 09 — Final CTA
Target height: ~300px.
Strong closing statement, supporting text and primary CTA.

### 10 — Footer
Target height: ~300px.
Brand, navigation groups, company/legal links, social links and privacy/terms.

## Mobile composition

Reference width: 375px.
Order:
Header → Hero text → Hero visual → Trust → Modules → Product → AI → Benefits → Testimonials/verified proof → CTA → Footer.

Cards stack/recompose instead of preserving desktop density.

## Asset placeholders

All future complex visual areas must remain independent from HTML text and cards.

Required future asset candidates:
- HERO VISUAL
- PRODUCT INTERFACE
- AI WORKFORCE
- optional supporting system visuals if required by final composition

Every production asset must later receive an exact manifest entry with:
function, desktop container, mobile behavior, ratio, format, alpha/transparency and safe area.

## Structural rules

- No final visual treatment in this document.
- No embedded typography inside production assets.
- No invented customer evidence.
- No additional wireframe image.
- This document plus the single official wireframe image are the structural source of truth.

Next phase: Card Visual System — exactly one image.
