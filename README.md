# Zhuoyuan Li

Personal website: https://zhuoyl03.github.io/zhuoyuanl03.github.io/

Built with Astro, plain CSS, and Lucide icons.

## Development

Use Node.js 22 or later and pnpm 11.19.0.

```sh
pnpm install --frozen-lockfile
pnpm dev
pnpm build
```

Source pages are in `src/`; figures and PDFs are in `public/`.
Astro builds the static site to `dist/` using the project-site base path
`/zhuoyuanl03.github.io/`.

## Publishing

GitHub Pages serves the prebuilt files at the root of `main`.
Publish the contents of `dist/` alongside the source files after reviewing
the generated pages. Keep `.nojekyll` so the `_astro/` assets are served.
Source edits alone do not update the published HTML.

Include only the figures and PDFs referenced by the current site.
Local backups, dependency directories, and review notes are not release assets.
