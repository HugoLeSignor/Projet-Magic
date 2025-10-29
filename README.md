# Magic: The Gathering Website

A website dedicated to Magic: The Gathering, featuring news, products, and game information.

## 🛠️ Technologies & Languages

### Languages
- **SCSS**
- **HTML**

### Tools & Preprocessors
- **Sass/SCSS** - CSS preprocessor for advanced styling
- **Node.js & npm** - Development tooling

### Key Features

#### Advanced SCSS Architecture
This project implements a professional SCSS structure:

```scss
// Main style.scss imports
@use 'base/fonts';
@use 'base/base';
@use 'abstracts/variables';
@use 'components/nav';
@use 'components/card';
@use 'components/btn';
@use 'layouts/header';
@use 'layouts/promo';
@use 'layouts/hero';
@use 'layouts/news';
@use 'layouts/cta';
@use 'layouts/latest';
@use 'layouts/footer';
```

#### Organized File Structure
- **Base**: Typography, reset, and utilities
- **Abstracts**: Variables for colors, fonts, and breakpoints
- **Components**: Reusable UI elements (navigation, cards, buttons)
- **Layouts**: Page sections (hero, news, footer, CTA)

### Project Structure
```
├── assets/
│   ├── scss/         # Source SCSS files
│   ├── css/          # Compiled CSS
│   ├── img/          # Game assets
│   └── fonts/        # Custom typography
├── node_modules/     # Dependencies
├── index.html
├── package.json
└── package-lock.json
```

## 🎴 Theme
Magic: The Gathering themed website featuring:
- Product showcases
- Latest news and updates
- Call-to-action sections
- Mobile app promotion
- Dark theme with accent colors

### Development Benefits
- Modular and maintainable code
- Easy theme customization through variables
- Reusable components
- Professional build process
