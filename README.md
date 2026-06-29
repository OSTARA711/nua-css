# Nua.CSS

Lightweight CSS reset and browser normalisation stylesheet.

Nua.CSS provides a consistent, minimal foundation for building user interfaces across modern browsers.

---

## Installation

### NPM (recommended)

```bash
npm install @ostara711/nua-css

```
## What Nua.CSS does

Nua.CSS is a modern CSS reset and normalisation layer designed to:

- Provide consistent default styles across browsers 
- Remove unwanted browser-specific inconsistencies 
- Improve typography baseline 
- Standardise form element behaviour 
- Ensure responsive media defaults 
- Improve accessibility defaults 
- Support reduced motion preferences 
- Provide stable scrollbar styling 

It is not a UI framework, and it does not impose design systems.

---

## Features

### Layout & Box Model
- Universal `box-sizing: border-box`
- Predictable sizing across all elements

### Typography
- Clean default font stack (system UI fonts)
- Balanced headings (`text-wrap: balance`)
- Consistent line-height

### Media
- Responsive images, video, canvas
- No overflow issues by default

### Forms
- Normalised input, button, select, textarea styling
- Improved cursor and focus behaviour

### Accessibility
- Visible focus state (`:focus-visible`)
- Reduced motion support (`prefers-reduced-motion`)
- Accessible form controls baseline

### UX Improvements
- Smooth scrollbar styling (WebKit + Firefox)
- Predictable list and table defaults
- Consistent link behaviour

---

## Files included

| File               | Purpose                     |
|--------------------|-----------------------------|
| `dist/nua.css`     | Full readable version       |
| `dist/nua.min.css` | Minified production version |

---

## Project structure

```text
nua-css/
├── website/              # Cloudflare Pages site
├── package/              # Source CSS (single source of truth)
│   └── nua.css
├── dist/                 # NPM build output
│   ├── nua.css
│   └── nua.min.css
├── package.json
├── README.md
└── LICENSE
