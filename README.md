# Fasihuddin Ahmer, portfolio

Single-page portfolio built with [Astro](https://astro.build) and hosted on Cloudflare Pages.

## Run locally

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # outputs to dist/
```

## Edit

- Content: `src/pages/index.astro`
- Styles: `src/styles/global.css`
- Resume PDF: `public/Fasihuddin-Ahmer-Resume.pdf`

## Deploy on Cloudflare Pages

1. Cloudflare dashboard, Workers & Pages, Create, Pages, Connect to Git.
2. Pick this repository.
3. Framework preset: Astro. Build command: `npm run build`. Output directory: `dist`.
4. Save and deploy. To use a custom domain such as `fasih.hivemindnestor.com`, add it under Custom domains.
