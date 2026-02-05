# Public FAQ

A simple React site with a single `div` with `id="faq_placeholder"` for hosting a public FAQ.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy to Vercel

1. **Push to Git**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Public FAQ placeholder"
   git branch -M main
   git remote add origin <your-repo-url>
   git push -u origin main
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com) and sign in.
   - Click **Add New** → **Project** and import your Git repository.
   - Vercel will detect the Vite app; keep the default build settings.
   - Click **Deploy**.

   Or use the CLI:
   ```bash
   npm i -g vercel
   vercel
   ```

After deployment, the page will render the `#faq_placeholder` div. You can later inject or replace its content (e.g. with an FAQ widget or script).
