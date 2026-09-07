# Atlas Portfolio

## Local development

```bash
pnpm install
pnpm dev
```

Create a production build with `pnpm build`. The static output is written to `dist/`.

## Deployment

The repository includes ready-to-use configuration for Vercel and Netlify. Import the repository in either service, leave the defaults in place, and deploy.

## Host editor

Click **Edit site** and use the configured demo password in `src/main.jsx`. The current editor intentionally stores content in the browser's local storage, so it is appropriate for a personal demo but does not share edits between visitors or securely protect content. A production host editor needs an authenticated database/CMS (for example Supabase or Firebase) before it is publicly relied upon.
