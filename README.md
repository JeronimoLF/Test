# Test

Minimal Next.js app (App Router, JavaScript) that displays **Test**.

## Local development

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

### Phone on same Wi‑Fi

```bash
npm run dev:lan
```

Then open `http://<your-pc-ipv4>:3000` on your phone (find IP with `ipconfig` on Windows).

## Deploy on Vercel

1. Push this repo to GitHub.
2. Import the repo at [vercel.com/new](https://vercel.com/new).
3. Use defaults: **Framework: Next.js**, **Output Directory:** leave empty.
4. Deploy.

## Scripts

| Command        | Description              |
| -------------- | ------------------------ |
| `npm run dev`  | Dev server (localhost)   |
| `npm run dev:lan` | Dev server (LAN access) |
| `npm run build`| Production build         |
| `npm run start`| Run production build     |
