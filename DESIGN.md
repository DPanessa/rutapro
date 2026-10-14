---
name: Field Operations & Commerce
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#444653'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#006c4a'
  on-secondary: '#ffffff'
  secondary-container: '#82f5c1'
  on-secondary-container: '#00714e'
  tertiary: '#532a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#743d00'
  on-tertiary-container: '#ffa85d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#85f8c4'
  secondary-fixed-dim: '#68dba9'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#005137'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system is engineered for field sales representatives, route logistics supervisors, and commercial field teams operating in dynamic, variable light environments. The tone is utilitarian, dependable, and executive: structured to eliminate operational friction and ensure absolute clarity on the go.

The visual style follows a Corporate / Modern framework. It pairs high-clarity content surfaces with balanced visual weight, clean structural divisions, and robust contrast ratios. Visual noise is minimized to prioritize critical operational data points—such as visit windows, customer statuses, route telemetry, and check-in triggers—enabling swift, error-free field actions.

## Colors

The palette establishes an authoritative, reliable environment built specifically for outdoor and high-glare legibility:

- **Primary (`#1E40AF` - Cobalt Blue):** Anchors core actions, navigation headers, primary touchpoints, and active navigational directions.
- **Secondary (`#059669` - Emerald):** Denotes verified completion, successful check-ins, achieved quotas, and active status states.
- **Tertiary (`#D97706` - Amber):** Highlights pending items, in-transit alerts, schedule variances, and mandatory action requirements.
- **Neutral (`#64748B` - Slate):** Powers metadata, structural dividers, secondary icons, and muted context labels.

### Canvas & Surface Architecture
- **Base Background:** `#F8FAFC` (Slate-50) maintains eye comfort across long shifts while preserving pure white (`#FFFFFF`) for elevated cards.
- **Surface Borders:** `#E2E8F0` (Slate-200) defines clean borders and structure without visually overwhelming content.
- **High-Contrast Text:** `#0F172A` (Slate-900) ensures AAA-compliant readability for headlines and operational metrics.

## Typography

The type system is powered by Inter across all levels. Neutral grotesque letterforms with tall x-heights maintain optimal legibility even on compact mobile screens or under direct sunlight.

Numerical figures must always use tabular figures (`font-variant-numeric: tabular-nums`) for currency values, address coordinates, and time windows. Operational labels (e.g., status badges, client identification codes) leverage uppercase styling with loose tracking to reinforce rapid categorization.

## Layout & Spacing

The layout is built on a responsive mobile-first fluid grid optimized for portrait handheld devices, scaling to tablet dashboards for split-screen navigation and route auditing.

- **Mobile (<768px):** Single-column stack with `1rem` screen margin and `0.75rem` vertical separation between visit nodes. Minimum interactive height is strictly enforced at 44px (recommended 48px for primary route actions).
- **Tablet / Large Display (≥768px):** 12-column grid with `1.5rem` margins and `1rem` gutters. Accommodates dual-pane views: list overview on the left (5 cols) and interactive map with CRM context on the right (7 cols).

## Elevation & Depth

To maintain visual clarity in variable lighting, the system avoids diffuse, low-contrast shadows in favor of structured borders combined with crisp, localized elevation:

- **Flat/Canvas (`Level 0`):** `#F8FAFC`, no shadow.
- **Card/Resting Surface (`Level 1`):** Pure white background (`#FFFFFF`), solid border `1px solid #E2E8F0`, and an ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.06), 0 1px 2px -1px rgba(15, 23, 42, 0.04)`.
- **Interactive/Pressed Card (`Level 2`):** Border switches to `1px solid #CBD5E1`, shadow expands: `0 4px 6px -1px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Floating Operational Modules (`Level 3` - Bottom sheets, floating action bars):** `0 10px 15px -3px rgba(15, 23, 42, 0.1), 0 4px 6px -4px rgba(15, 23, 42, 0.05)`, edged with a subtle top border `1px solid #E2E8F0`.

## Shapes

The design uses balanced, modern curves (`roundedness: 2`):
- **Small components (Badges, tags, form controls):** `0.375rem` (6px) to `0.5rem` (8px).
- **Cards and Containers:** `0.75rem` (12px) to `1rem` (16px).
- **Modals, Bottom Sheets:** `1rem` (16px) top radius.
- **Action Buttons:** `0.5rem` (8px) for maximum spatial balance and easy touch targeting.

## Components

### Buttons
- **Primary Action (Check-in, Start Route):** `#1E40AF` background, `#FFFFFF` text, `48px` minimum height, bold label (`label-lg`), `0.5rem` radius. Active state scales down slightly (`0.98`) to confirm touch feedback.
- **Secondary Action (Call Client, Reschedule):** Surface `#FFFFFF`, border `1px solid #CBD5E1`, text `#1E40AF`.
- **Destructive/Issue Action (Report Incident):** Soft red background (`#FEF2F2`), border `1px solid #FCA5A5`, text `#DC2626`.

### Status Badges (Insignias)
- **Pending (`Pendiente`):** Slate-100 (`#F1F5F9`) background, text Slate-700 (`#334155`), dot indicator in Slate-500 (`#64748B`).
- **In Transit (`En Camino`):** Amber-50 (`#FFFBEB`) background, text Amber-800 (`#92400E`), dot indicator in Amber-500 (`#F59E0B`).
- **Completed (`Completado`):** Emerald-50 (`#ECFDF5`) background, text Emerald-800 (`#065F46`), dot indicator in Emerald-600 (`#059669`).
- Structure: Height `24px`, horizontal padding `8px`, radius `4px`, font `label-sm`.

### Visit Route Cards
- Structured container with left-hand vertical state accent line (`3px` solid indicator).
- Displays chronological step index, account commercial name, delivery/visit window, and pending tasks counter.
- Direct tap-to-navigate action icon embedded on the right flank (`44x44px` target).

### Form Inputs & Checklists
- Text inputs require `48px` height, filled background `#FFFFFF`, border `1px solid #CBD5E1`, and clear floating labels to prevent input errors on mobile.
- Form checkboxes for store audits provide extra-large target boxes (`20x20px` visual box within a `44x44px` target area) with high-contrast emerald checks upon completion.

### Route Sticky Bar
- Fixed bottom container (`Level 3`) displaying current active stop, distance remaining, and a unified primary split-button for "Arrived" and "GPS Navigation".