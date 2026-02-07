# Firefox Theme - Catppuccin Macchiato Edition

A modern Firefox theme for Linux with full GTK integration and Catppuccin Macchiato color scheme support.

## Features

- **Catppuccin Macchiato Colors**: Beautiful, cohesive dark color palette with:
  - Dark background: `#1e1e30` (titlebar), `#24273e` (content)
  - Primary accent: Pink/Magenta for highlights and interactive elements
  - Red for close button, Blue for maximize, Yellow for minimize
  
- **Custom Window Control Buttons**: High-quality SVG window control buttons with:
  - **Hover-based Icon Visibility**: Icons appear only when you hover over buttons (clean default appearance)
  - **Interactive States**: Normal (plain circles) → Hover (icons visible) → Active (darkened with shadow)
  - **Light & Dark Variants**: Separate button designs for light and dark themes
  - **Backdrop Buttons**: Reduced opacity buttons for inactive windows

- **GTK Integration**: Full integration with GNOME/GTK theme preferences for consistent system appearance

- **Multiple Color Variants**:
  - Dark theme (Macchiato - warm darks)
  - Light theme (Latte palette)
  - Adaptive theme (follows system preference)
  - Nord theme option

## Installation

1. Clone or download this theme directory
2. Place it in your Firefox profile's `chrome` directory:
   ```
   ~/.mozilla/firefox/[profile-id]/chrome/
   ```
3. Restart Firefox to apply the theme

## Customization

### Color Scheme
Edit `colors/dark.css` or `colors/light.css` to customize:
- Toolbar colors
- Button colors
- Text colors
- Accent colors

### Window Buttons
SVG button files are located in `titlebuttons/`:
- `titlebutton-close-*.svg` (red buttons)
- `titlebutton-maximize-*.svg` (blue buttons)
- `titlebutton-minimize-*.svg` (yellow buttons)

Each button has variants for:
- Normal state (no icon visible)
- Hover state (icon appears)
- Active state (pressed appearance)
- Backdrop state (inactive window)

## Theme Structure

```
catppucin/
├── colors/              # Color schemes
│   ├── dark.css        # Dark theme colors (Macchiato)
│   ├── light.css       # Light theme colors
│   └── ...
├── titlebuttons/       # Window control button SVGs
├── parts/              # Component styles
├── pages/              # Page-specific styling
└── theme.css           # Main theme file
```

## Credits

- Based on GNOME WhiteSur GTK theme aesthetic
- Colors from [Catppuccin](https://github.com/catppuccin) project
- Custom SVG window button designs
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/73dae267-9dfa-49d8-a1ca-84fb4802e8a3" />
