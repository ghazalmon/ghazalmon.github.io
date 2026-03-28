# Ghazal's Homepage

Personal website for Ghazal.

## Stack
- Astro (static site generator) — fast, simple, great for content sites
- Tailwind CSS for styling
- TypeScript
- Deployed as static HTML

## Design Principles
- Clean, minimal, elegant
- Mobile-first responsive design
- Fast load times — optimize images, minimal JS
- Accessible (WCAG 2.1 AA)

## Development
```bash
npm run dev      # Start dev server
npm run build    # Build for production
npm run preview  # Preview production build
```

## Project Structure
```
src/
  pages/       # Astro pages (.astro)
  layouts/     # Layout components
  components/  # Reusable components
  styles/      # Global styles
  content/     # Content (markdown, etc.)
public/        # Static assets (images, fonts, favicon)
```

## Conventions
- Use Astro components (.astro) for pages and layouts
- Use Tailwind utility classes; avoid custom CSS unless necessary
- Optimize all images (WebP preferred, with fallbacks)
- Keep bundle size minimal — avoid unnecessary JS frameworks
