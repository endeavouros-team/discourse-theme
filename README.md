# EndeavourOS Forum Theme — Discourse Theme Component

Theme component for forum.endeavouros.org, derived from the 2026 redesign of
endeavouros.com and the wiki.

One component, two variants: Dark Navy and Light Lavender switch automatically
via Discourse's `$is-dark` mechanism — install it, add it to the active theme,
done. No Dark Reader needed.

## Palette

| Role | Dark | Light |
|---|---|---|
| Page background | `#07041a` | `#cccad3` |
| Header | `#090629` | `#cfced3` |
| Panels/Sidebar | `#0b0730` | `#cbc9d1` |
| Cards | `#110d35` | `#cfced3` |
| Primary accent (buttons) | `#6934a0` | `#6934a0` |
| Secondary accent | `#6968d3` | `#6934a0` |
| Text | `#c9c5e6` | `#0d0a25` |
| Titles | `#f2effb` | `#0d0a25` |

## Installation

1. Admin → Customize → Themes → **Install → From a repo**
   `https://github.com/endeavouros-team/discourse-theme`
2. Add the component to the active default theme
   (gear icon on the theme → Components → add).
3. Keep the default color schemes (both Dark *and* Light) enabled — the
   component overrides the variables depending on `$is-dark`.

## Customizing

All colors are centralized in `common/color_definitions.scss` under
`:root { --eos-… }` (one block per variant).

## Files

- `about.json` — theme metadata
- `common/color_definitions.scss` — color variables (dark + light)
- `common/common.scss` — structural overrides (header, buttons, topic list, …)

## License

This theme is part of the EndeavourOS project.

GPL-3.0 — see [LICENSE](LICENSE).

Deutsche Anleitung: [README.de.md](README.de.md)
