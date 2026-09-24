# CYZOR V4 — Design System

Status: VALIDATED

## Tokens

### Colors

```
--bg: #030504
--surface: #080B0A
--surface-2: #111513
--text: #F5F7F3
--muted: #8B938D
--lime: #C8FF00
--line: rgba(245,247,243,.12)
--line-strong: rgba(200,255,0,.32)
--lime-soft: rgba(200,255,0,.12)
```

## Typography

Primary:
Inter

Technical:
DM Mono

Display hierarchy should be strong but not editorial.

## Layout

Desktop:
12-column structural grid.

Max content width:
1440px.

Primary horizontal padding:
32–64px depending on viewport.

Section spacing:
120–220px depending on density and visual importance.

## Surfaces

Use dark graphite surfaces with subtle borders.

Avoid heavy shadows.

Depth comes from:
- transparency
- contrast
- image scale
- lighting
- atmospheric layers
- structural lines

## Radius

Primary:
16px

Secondary:
12px

Small:
8px

Avoid excessive nested rounded containers.

## Buttons

Primary:
lime background + dark text.

Secondary:
transparent/dark surface + light border.

States:
default / hover / focus-visible / active / disabled / loading.

## Technical UI

DM Mono is reserved for:
- status
- telemetry
- system IDs
- small metadata
- technical labels

## Glow

Glow is semantic.

Allowed for:
- active nodes
- signals
- intelligence
- CTA
- system state

Not allowed as general decoration.

## Motion budget

Motion should be subtle and purposeful.

Preferred:
opacity
transform
scale
stroke/path animation
controlled filter/glow

Avoid layout-heavy animation.

## Responsive

Mobile is a recomposition.

Do not simply reduce desktop sizes.

Network diagrams become:
- vertical flows
- simplified node groups
- sequential relationships

## Accessibility

- semantic structure
- keyboard focus
- visible focus
- reduced motion
- accessible labels
- contrast
- no color-only state

## Design-system validation

Token coherence: PASS
Typography: PASS
Grid: PASS
Surface hierarchy: PASS
Interaction states: PASS
Motion budget: PASS
Responsive strategy: PASS
Accessibility baseline: PASS
