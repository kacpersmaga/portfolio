# kacpersmaga.com — Personal Portfolio

My personal developer portfolio built with Astro and Tailwind CSS.

**Live:** [kacpersmaga.com](https://kacpersmaga.com)

## Tech Stack

- [Astro 5](https://astro.build) — static site generation
- [Tailwind CSS 4](https://tailwindcss.com) — utility-first styling
- [@astrojs/sitemap](https://docs.astro.build/en/guides/integrations-guide/sitemap/) — auto-generated sitemap

## Project Structure

```
src/
├── components/
│   ├── bento/          # Bento grid cards (Hero, Expertise, ProjectsCard, ...)
│   ├── ProjectCard.astro
│   ├── ProjectModal.astro
│   └── ...
├── layouts/
│   └── Layout.astro    # Base HTML, meta tags, theme toggle
├── pages/
│   ├── index.astro
│   └── projects.astro
└── styles/
    └── global.css      # CSS variables, dark/light theming
```

## Getting Started

```bash
npm install
npm run dev
```

| Command           | Action                        |
| ----------------- | ----------------------------- |
| `npm run dev`     | Start dev server at `localhost:4321` |
| `npm run build`   | Build production site to `./dist/` |
| `npm run preview` | Preview production build locally |

## Features

- Bento grid layout
- Dark / light mode (persisted via `localStorage`)
- Project modals with architecture diagrams
- SEO: Open Graph, JSON-LD structured data, sitemap, `robots.txt`
- Lighthouse 100 performance score
