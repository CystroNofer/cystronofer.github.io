# Nofer Portfolio

Personal portfolio for Nofer Xue, focused on technical art, real-time rendering, game development, and graphics programming.

The site is built with [Astro](https://astro.build/) and deployed as a static site to GitHub Pages.

## Development

Requirements:

- Node.js 22 or later
- npm

Install dependencies and start the local development server:

```sh
npm install
npm run dev
```

Create a production build:

```sh
npm run build
```

Preview the production build locally:

```sh
npm run preview
```

## Project structure

```text
public/                  Static images and résumé
src/components/         Reusable Astro components
src/data/portfolio.ts   Skills and project content
src/layouts/            Shared page layout
src/pages/              Site routes
src/styles/global.css   Global design system and responsive styles
```

## Deployment

The GitHub Actions workflow in `.github/workflows/deploy.yml` builds and deploys the site to GitHub Pages when changes are pushed to `main`. The live site is configured for:

<https://cystronofer.github.io>

## Migration status

This branch is an in-progress Astro rework of the original static portfolio. The previous site included English and Chinese pages, detailed project galleries, and additional media. Those materials remain available in the separate `cystronofer.github.io - Backup` folder for reference while the redesign is completed.
