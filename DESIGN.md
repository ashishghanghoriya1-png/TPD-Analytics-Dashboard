# RSK MP TPD Analytics Dashboard — Apple Design System Tokens (`DESIGN.md`)

## 1. Visual Thesis
Quiet `#F5F5F7` canvas, pure `#FFFFFF` 18px-radius surfaces with `rgba(0,0,0,0.08)` hairline borders, `-apple-system` SF-Pro-style display typography (`-0.025em` tracking), a frosted sticky control bar (`saturate(180%) blur(20px)`), and `#1D1D1F` / `#0071E3` active pills.

## 2. Color Tokens
- `--bg`: `#F5F5F7` (Apple Light Canvas)
- `--surface`: `#FFFFFF` (Pure Card Surface)
- `--surface-subtle`: `#F5F5F7` (Inset / Secondary Surface)
- `--surface-border`: `rgba(0, 0, 0, 0.08)` (Hairline Border)
- `--border-hover`: `rgba(0, 0, 0, 0.16)`
- `--text-main`: `#1D1D1F` (Apple Charcoal Ink)
- `--text-body`: `#3A3A3C`
- `--text-muted`: `#6E6E73`
- `--text-dim`: `#86868B`
- `--blue-primary`: `#0071E3` (Apple Blue)
- `--emerald-primary`: `#248A3D` (Accessible Green)
- `--amber-primary`: `#B25000` (Accessible Amber)
- `--rose-primary`: `#D70015` (Apple Red)
- `--purple-primary`: `#5E5CE6` (Apple Indigo)

## 3. Typography & Radii
- `--font-sans`: `-apple-system, BlinkMacSystemFont, "SF Pro Display", "SF Pro Text", "Plus Jakarta Sans", sans-serif`
- `--font-mono`: `"SF Mono", "JetBrains Mono", monospace`
- Display tracking: `-0.025em` on `h1` and `.panel-title`
- Card radius: `18px`
- Pill / Action button radius: `9999px`

## 4. Interaction & Motion Tokens
- Easing: `power2.out` / `cubic-bezier(0.25, 0.1, 0.25, 1)`
- Panel / Card settle: `0.30s`, `y: 10px -> 0`, `stagger: 0.04s`
- KPI number roll: `0.45s`, `power2.out`
- Reduced-motion fallback: `0.12s` opacity-only fade (`prefers-reduced-motion: reduce`)
