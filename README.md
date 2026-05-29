# Test

Minimal Next.js app (App Router, JavaScript) that displays **Test**.

## Local development

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Deploy on Vercel

1. Push this repo to GitHub (`git push origin main`).
2. Import at [vercel.com/new](https://vercel.com/new) from `JeronimoLF/Test`.
3. Use these settings (important):
   - **Framework Preset:** Next.js
   - **Root Directory:** *(empty)*
   - **Build Command:** *(default — `next build`)*
   - **Output Directory:** *(empty — do not use `public`)*
   - **Node.js Version:** 20.x or 22.x

Do **not** add a custom `vercel.json` unless you know you need it — Vercel auto-detects Next.js from `package.json`.

## Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Dev server (localhost) |
| `npm run dev:lan` | Dev server (phone on same Wi‑Fi) |
| `npm run build` | Production build |
| `npm run start` | Run production build |
