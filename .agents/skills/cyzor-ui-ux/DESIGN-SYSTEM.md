# CYZOR Design System — UI/UX Foundation

This file is the repository-facing visual contract for the CYZOR UI/UX skill.

## Brand tokens

| Token | Value | Role |
|---|---|---|
| --cyzor-bg | #f7f7f2 | Light page background |
| --cyzor-ink | #11110f | Primary text / dark control |
| --cyzor-muted | #72726b | Secondary text |
| --cyzor-line | #deded6 | Borders/dividers |
| --cyzor-lime | #c8ff00 | Brand accent |
| --cyzor-dark | #10100e | Dark surfaces |

## Typography

Current marketing foundation:
- Inter: UI/body/display
- DM Mono: technical labels, metadata, micro-labels

Do not introduce additional families without a product/design reason.

## Geometry

- Major radius: 14–16px.
- Dense control radius: smaller when appropriate.
- Avoid deeply nested rounded surfaces.
- Prefer alignment and spacing to excessive borders.

## Elevation

Use, in order:
1. spacing
2. surface contrast
3. border
4. subtle shadow

Avoid heavy or colored shadows as defaults.

## Layout

Marketing:
- constrained max-width
- 12-column desktop grid
- strong section rhythm
- deliberate asymmetric compositions where useful

Product:
- stable application shell
- predictable content width
- consistent sidebar/header geometry
- density matched to task frequency

## Component contracts

Every reusable interactive primitive should support:
- default
- hover
- focus-visible
- active
- disabled
- loading

Major product surfaces should support:
- loading
- empty
- error
- success
- permission
- long-content

## Responsive contracts

Test:
- mobile
- tablet/intermediate
- desktop
- wide desktop where relevant

Never only scale down desktop.

## AI response contracts

CYZOR chat/report UI should prefer structured blocks:
- summary
- metrics
- findings
- details
- contextual actions

Do not render unrelated module data merely because it is available.

## Accessibility

- semantic markup
- keyboard support
- visible focus
- accessible labels
- contrast
- reduced motion
- no color-only state
- touch targets around 44px where touch applies

## Anti-patterns

No generic AI gradient aesthetic, card-everything layouts, excessive glass,
random blobs, decorative badges, unnecessary pills, or animation without
interaction meaning.

## Change policy

When adding a repeated visual pattern:
1. compare existing patterns
2. identify whether it is genuinely reusable
3. update tokens/components
4. migrate affected screens where safe

Do not create parallel primitives for an existing pattern.

## Neural technology visual contract

For CYZOR's futuristic surfaces, the visual system may use controlled glow,
network traces, telemetry and layered dark planes when they communicate system
activity. Glow is a semantic state, not decoration.

- base: near-black graphite
- primary text: warm white
- secondary text: desaturated graphite
- signal: CYZOR lime
- structural lines: low-opacity white/graphite
- active nodes: lime with restrained bloom
- technical labels: DM Mono

Neural elements must have a relationship to architecture, agents, data or
intelligence. Decorative neural noise is prohibited.

## Premium marketing composition contract

Marketing pages may use expressive compositions, but they must remain governed by
CYZOR primitives. Define the page-level contract before adding local styles:

- max-width and grid
- display type scale
- body/technical type scale
- section spacing rhythm
- border hierarchy
- surface hierarchy
- accent budget
- motion budget
- mobile composition changes

### Accent budget
Lime should identify activation, intelligence, focus, connection or conversion.
In futuristic surfaces, a small glow may reinforce the same semantic role.
It should not become a general-purpose decoration color.

### Surface budget
Prefer background contrast and structural borders before shadows. A major page
should have a small, intentional set of surfaces rather than many card variants.

### Type wrapping
Headlines are composition. Validate their line breaks at desktop, tablet and
mobile widths. Do not accept accidental wrapping that changes the intended visual
meaning.

### Responsive art direction
At mobile widths, preserve the narrative hierarchy rather than the desktop geometry.
A diagram may become a vertical sequence, a split may become an editorial stack,
and dense evidence may become a focused fragment.
