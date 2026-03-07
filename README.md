# Botanica

A high-performance plant storefront demo built with **Astro** and **JavaScript**. Designed for top Lighthouse scores (performance, accessibility, SEO, best practices).

## Run locally

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321).

## Build

```bash
npm run build
npm run preview   # preview production build
```

## Lighthouse optimizations

- **Semantic HTML**: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, landmarks and headings
- **Accessibility**: Skip link, `aria-label` on nav/buttons, form labels, focus styles
- **Performance**: Static output, no client JS by default, `loading="lazy"` and explicit `width`/`height` on images, `fetchpriority="high"` only on LCP hero image, `preconnect` for image origin
- **SEO**: Meta description, theme-color, single H1, descriptive alt text

## Stack

- [Astro](https://astro.build) (static)
- [Tailwind CSS](https://tailwindcss.com) via `@astrojs/tailwind`
- No TypeScript (JS only in `.astro` frontmatter and config)

Design inspired by the Botanica template (templates/src/pages/201-250/249-Botanica.tsx).
