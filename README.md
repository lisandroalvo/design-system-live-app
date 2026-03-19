# Design System Live Documentation

A comprehensive, interactive design system documentation app with live component examples and code snippets.

## Features

- 🎨 **Complete Color Palette** - Primary, neutral, and semantic colors with click-to-copy hex codes
- 📝 **Typography Scale** - Full type hierarchy from display to caption
- 📏 **Spacing System** - Consistent 4px-based spacing scale
- 🔘 **Interactive Components** - Buttons, forms, cards, badges, and more
- 💾 **Copy-to-Clipboard** - One-click copying for code snippets and colors
- 🔍 **Live Search** - Filter navigation items in real-time
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile
- 🎯 **Collapsible Sidebar** - Maximize content space when needed

## Getting Started

### Option 1: Direct File Access
Simply open `index.html` in your browser.

### Option 2: Local Server
For the best experience, run a local server:

```bash
# Using Python 3
python3 -m http.server 8080

# Using Node.js (if you have http-server installed)
npx http-server -p 8080
```

Then visit `http://localhost:8080` in your browser.

## Structure

```
design-system-live-app/
├── index.html          # Main HTML structure
├── styles.css          # Complete styling system
├── script.js           # Interactive functionality
└── README.md          # This file
```

## Sections

1. **Getting Started** - Installation and quick start guide
2. **Colors** - Color palettes with interactive swatches
3. **Typography** - Complete type scale with examples
4. **Spacing** - Visual spacing scale reference
5. **Buttons** - Button variants and sizes
6. **Form Controls** - Input fields, selects, checkboxes, radios
7. **Cards** - Card components and layouts
8. **Badges** - Status indicators and labels
9. **Icons** - Material Icons showcase
10. **Components** - Alerts, progress bars, spinners

## Design Tokens

All design tokens are available as CSS custom properties:

```css
/* Colors */
--color-primary: #3B82F6;
--color-success: #10B981;
--color-warning: #F59E0B;
--color-error: #EF4444;

/* Spacing */
--spacing-1: 4px;
--spacing-2: 8px;
--spacing-4: 16px;
--spacing-8: 32px;

/* Border Radius */
--radius-sm: 4px;
--radius-md: 8px;
--radius-lg: 12px;
```

## Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties
- **Vanilla JavaScript** - No framework dependencies
- **Material Icons** - Icon system
- **Highlight.js** - Code syntax highlighting
- **Inter Font** - Typography

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## License

MIT License - feel free to use this for your own projects!

## Author

Created with ❤️ for design system documentation
