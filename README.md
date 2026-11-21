# Pizdec Glass

Frosted glass on a blue wallpaper for Obsidian. Sidebars, the tab bar, menus and the command palette
are blurred glass. The editor and dialogs are raised navy platforms, so text never sits on raw glass.

Sister theme of [Pizdec Dark](https://github.com/sennafaris28/pizdec-dark).

## Palette

| Colour | Role |
|---|---|
| `#0055b1` → `#082990` → `#03205b` | wallpaper (diagonal gradient) |
| `#283862` (translucent) | glass: sidebars, tab bar, status bar, menus, popovers |
| `#000f21` | platform: editor, modals |
| `#1b3156` | raised: cards, fields, table headers |
| `#2a3a45` | dividers (`---` and tables only) |
| `#009afe` | main accent: links, buttons, tags, focus rings, selection |
| `#59e7df` | secondary accent: scrollbars, inline code, bullets, checkboxes, quotes, caret, active file and tab, `==highlights==` |

No grey outlines, all headings white. On desktop the panes float as rounded cards with gaps so the
wallpaper shows; on phones and tablets the layout stays edge-to-edge with lighter blur.

## NoteBoard

With the [NoteBoard](https://github.com/sennafaris28/noteboard) plugin (1.1.0+), the board gets blue
panels and slate-blue raised cards on the navy platform, with cyan "today" markers. Quest colours
stay your own picks.

## Install

Copy `theme.css` and `manifest.json` into `<vault>/.obsidian/themes/Pizdec Glass/`, then pick
**Pizdec Glass** in Settings → Appearance → Themes. Built for dark mode.

## Performance

Blur is drawn by the GPU. If scrolling long notes feels heavy, lower `--pg-blur` (for example
`blur(10px)`) in a CSS snippet.

## License

MIT
