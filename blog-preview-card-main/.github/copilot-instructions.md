# AI Agent Instructions for Blog Preview Card Project

## Project Overview
This is a Frontend Mentor challenge implementation of a responsive blog preview card component. The project follows a mobile-first approach with specific design requirements and accessibility considerations.

## Key Files and Structure
- `index.html` - Main markup with semantic HTML structure
- `styles.css` - All styles following BEM naming convention
- `/assets/fonts/` - Local font files (Figtree font family)
- `/design/` - Reference design files for mobile (375px) and desktop (1440px) layouts
- `style-guide.md` - Design tokens and specifications

## Design System
### Colors
- Primary: Yellow (hsl(47, 88%, 63%))
- Neutral: White, Gray-500 (42%), Gray-950 (7%)

### Typography
- Font: Figtree (weights: 500, 800)
- Base paragraph size: 16px
- Uses both Google Fonts CDN and local font files

## Development Patterns
### HTML Conventions
- Semantic HTML5 elements (`<article>`, `<main>`)
- BEM class naming: `block__element--modifier`
- ARIA attributes for accessibility
- Example structure:
```html
<article class="article" aria-labelledby="article-title">
  <img class="article__image" src="..." alt="...">
  <span class="article__category">...</span>
```

### CSS Patterns
- Mobile-first responsive design
- Base breakpoints: 375px (mobile) to 1440px (desktop)
- Focus/hover states required for interactive elements
- Content should be responsive between 320px and large screens
- WCAG compliance required

## Testing Guidelines
- Test responsive behavior across full range (320px+)
- Verify hover/focus states on interactive elements
- Ensure proper rendering of custom fonts
- Validate accessibility using screen readers

## Important Notes
- Project uses local assets - no external dependencies except Google Fonts
- Design is static JPG - implement exact spacing using best judgment
- All required assets are pre-optimized in `/assets` folder