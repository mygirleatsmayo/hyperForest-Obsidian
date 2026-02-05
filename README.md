# HyperForest

A dark Obsidian theme inspired by the VS Code theme "Forest Pink" — featuring vibrant pinks, greens, and purples on a deep forest background.

![Theme Preview](https://img.shields.io/badge/obsidian-theme-8b5cf6)

## Features

- **Forest Pink Color Palette** — Deep greens with vibrant pink accents
- **Custom Checkboxes** — 21 alternative checkbox styles (!, ?, -, *, etc.)
- **Style Settings Integration** — Toggle custom checkboxes on/off
- **Syntax Highlighting** — Optimized for readability with distinct colors
- **American Typewriter Font** — Classic serif for a unique reading experience

## Installation

### Community Themes (Coming Soon)
1. Open Obsidian **Settings → Appearance → Themes**
2. Search for "HyperForest"
3. Click **Install and use**

### Manual Installation
1. Download `theme.css` and `manifest.json`
2. Create folder: `YourVault/.obsidian/themes/hyperForest/`
3. Place both files in the folder
4. Go to **Settings → Appearance → Themes**
5. Select "HyperForest"

## Custom Checkboxes

HyperForest includes 21 custom checkbox types. Enable them in **Settings → Style Settings → HyperForest → Custom Checkboxes**.

| Syntax | Icon | Color | Use Case |
|--------|------|-------|----------|
| `- [x]` | ✓ | Green | Complete |
| `- [!]` | ⚠️ | Yellow | Important |
| `- [?]` | ❓ | Hot Pink | Question |
| `- [-]` | ✕ | Pink | Cancelled |
| `- [/]` | ◐ | Muted | In Progress |
| `- [*]` | ⭐ | Yellow | Star/Highlight |
| `- [b]` | 🔖 | Pink | Bookmark |
| `- [I]` | 💡 | Yellow | Idea |
| `- [p]` | 👍 | Green | Pro/Positive |
| `- [c]` | 👎 | Pink | Con/Negative |
| `- [i]` | ℹ️ | Teal | Info |
| `- [l]` | 📍 | Purple | Location |
| `- [<]` | 📅 | Teal | Scheduled |
| `- [>]` | ➡️ | Teal | Forwarded |
| `- [S]` | 💰 | Green | Savings |
| `- [u]` | 📈 | Green | Trending Up |
| `- [d]` | 📉 | Pink | Trending Down |
| `- [f]` | 🔥 | Pink | Fire/Urgent |
| `- [k]` | 🔑 | Yellow | Key Point |
| `- [w]` | 🎂 | Purple | Win/Celebrate |
| `- [n]` | 📌 | Hot Pink | Note |
| `- ["]` | ❝ | Muted | Quote |

## Color Palette

```css
--background-primary: #0d1f0d;     /* Deep forest green */
--text-normal: #ffb3d9;            /* Soft pink */
--text-accent: #ff1493;            /* Deep pink */
--code-string: #2ecc71;            /* Bright green */
--code-keyword: #ff1493;           /* Deep pink */
--code-function: #9b59b6;          /* Purple */
--code-type: #1abc9c;              /* Teal */
```

## Customization

### Style Settings Plugin
Install [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) to access theme options:
- Toggle custom checkboxes
- More options coming soon

### CSS Snippets
Check the `snippets/` folder for optional enhancements.

## Credits

- Inspired by [Forest Pink VS Code theme](https://marketplace.visualstudio.com/items?itemName=sainnhe.forest-pink)
- Custom checkbox icons from [Font Awesome](https://fontawesome.com/)
- Checkbox implementation inspired by [AnuPpuccin theme](https://github.com/AnubisNekhet/AnuPpuccin)

## License

MIT License — feel free to modify and share!

## Support

Found a bug or have a suggestion? [Open an issue](https://github.com/mygirleatsmayo/hyperForest-Obsidian/issues)
