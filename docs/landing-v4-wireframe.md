# CYZOR V4 — Low-Fidelity Wireframe

## Wireframe rules
This document is structural only. It intentionally contains no final art direction, 3D rendering, glow, texture, photography or polished graphics.

Legend:
- [TEXT] = HTML content
- [CARD] = reusable card using the future Card Visual System
- [ASSET] = future generated visual
- [ACTION] = interactive control

## Global desktop canvas
- viewport reference: 1440px wide
- content max width: 1280–1360px
- 12-column grid
- horizontal gutter: 32px
- section vertical rhythm: 96–160px
- header height: 76px
- page background is reserved for a later background system

## 01 — NAVIGATION
Position: full width, top.
Height: 76px.
Layout: logo left / navigation center / status + primary action right.
Elements:
[BRAND] [NAV LINKS] [SYSTEM STATUS] [ACTION]
No future asset required.

Mobile:
brand left / menu action right; secondary navigation collapses.

## 02 — HERO
Height target: 720–820px desktop.
Grid: 5 columns text / 7 columns visual.
Left:
[EYEBROW]
[HEADLINE]
[SUPPORTING TEXT]
[ACTION PRIMARY]
[ACTION SECONDARY]
[SMALL SYSTEM STATES]
Right:
[ASSET: HERO-NEURAL-CORE]
Function: primary visual focal point.
Desktop asset box: 720×560px, ratio ~1.29:1.
Expected production type: transparent PNG/SVG/WebP-alpha.
Mobile: asset moves below text, target 100% width, max 430px.

## 03 — SYSTEM INTRODUCTION
Two-column structure.
Left:
[SECTION LABEL]
[HEADLINE]
[TEXT]
Right:
[ASSET: SYSTEM-ARCHITECTURE]
Desktop asset box: 650×480px, ratio ~1.35:1.
Expected transparent asset.
Below/right optional [TECHNICAL MARKERS].
Mobile: text then asset.

## 04 — AI WORKFORCE
Full-width dark system section.
Top:
[SECTION LABEL + HEADLINE]
[SUPPORTING TEXT]
Main:
[ASSET: AI-WORKFORCE]
Desktop asset box: 1080×520px, ratio ~2.08:1.
Expected transparent asset.
Below:
[AGENT CARD] [AGENT CARD] [AGENT CARD] [AGENT CARD]
These are HTML cards, not baked into the image.
Mobile: asset becomes vertical/recomposed; cards stack horizontally scrollable or 2-column.

## 05 — MODULE ECOSYSTEM
Intro row:
[SECTION LABEL + HEADLINE] / [TEXT]
Main:
[ASSET: MODULE-ECOSYSTEM]
Desktop asset box: 920×500px, ratio ~1.84:1.
Expected transparent asset.
Around/below visual:
[MODULE CARD] [MODULE CARD] [MODULE CARD] [MODULE CARD]
Only a controlled number of cards; do not create a 12-card wall.
Additional modules represented inside the asset or compact navigation list.
Mobile: visual first, then compact module list/cards.

## 06 — DATA → CONTEXT → INTELLIGENCE → DECISION → ACTION
Split layout.
Left:
[HEADLINE]
[TEXT]
Right:
[ASSET: DATA-FLOW]
Desktop asset box: 720×320px, ratio 2.25:1.
Expected transparent asset.
Below:
[PROCESS CARD] [PROCESS CARD] [PROCESS CARD]
Mobile: flow becomes vertical.

## 07 — PRODUCT EVIDENCE
Full-width product showcase.
Top:
[SECTION LABEL]
[HEADLINE]
[TEXT]
Main:
[ASSET: PRODUCT-INTERFACE]
Desktop asset box: 1160×620px, ratio ~1.87:1.
Expected transparent asset.
Below/overlay:
[PRODUCT CARD] [METRIC/STATE CARD] [AI CONTEXT CARD]
Important: cards contain only truthful non-numeric/product-state information unless real data is supplied.
Mobile: product visual becomes full-width with cards below.

## 08 — SECURITY / INFRASTRUCTURE
Two-column.
Left:
[ASSET: SECURITY-INFRASTRUCTURE]
Desktop: 560×440px.
Right:
[HEADLINE]
[TEXT]
[SECURITY CARD]
[ACCESS CARD]
Assets transparent.
Mobile: visual then copy/cards.

## 09 — DECISION SURFACE
Wide visual section.
[SECTION LABEL]
[HEADLINE]
[TEXT]
[ASSET: DECISION-SURFACE]
Desktop: 980×440px.
Below:
[DECISION CARD]
[INSIGHT CARD]
[ACTION CARD]
Mobile: visual followed by stacked cards.

## 10 — FINAL CTA
Large closing section.
Left:
[ASSET: FINAL-CTA-VISUAL]
Desktop: 600×500px.
Right:
[SECTION LABEL]
[HEADLINE]
[TEXT]
[ACTION PRIMARY]
Mobile: visual above CTA.

## 11 — FOOTER
Logo / compact navigation / legal / system identity.

## Asset map
| Asset | Desktop | Mobile | Transparency |
|---|---:|---:|---|
| Hero Neural Core | 720×560 | max 430w | required |
| System Architecture | 650×480 | 100% width | required |
| AI Workforce | 1080×520 | recomposed | required |
| Module Ecosystem | 920×500 | 100% width | required |
| Data Flow | 720×320 | 100% width | required |
| Product Interface | 1160×620 | 100% width | required |
| Security Infrastructure | 560×440 | 100% width | required |
| Decision Surface | 980×440 | 100% width | required |
| Final CTA Visual | 600×500 | 100% width | required |

## Wireframe validation
- structure is a landing page, not a banner: PASS
- visual areas explicitly reserved: PASS
- asset sizes defined before generation: PASS
- mobile behavior defined: PASS
- text remains HTML: PASS
- final art intentionally absent: PASS

Status: COMPLETE — proceed to Card Visual System.
