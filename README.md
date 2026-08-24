# 🚐 GPasada — Transport Cooperative Financial Management System

A mobile application interface for transport cooperatives inspired by GCash's visual language and UX patterns, designed for high-resolution displays (2556 × 1179 px).

---

## 🚀 Deploying to Vercel

This repository is pre-configured and ready to be deployed instantly on [Vercel](https://vercel.com).

### Option 1: Deploy via GitHub (Recommended)
1. Push this repository to your GitHub account:
   ```bash
   git add .
   git commit -m "Initial commit for GPasada"
   git push origin main
   ```
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import your **GPASADA** repository.
4. Keep the default settings (Framework Preset: **Other**) and click **Deploy**.

---

### Option 2: Deploy via Vercel CLI
If you have Node.js and the Vercel CLI installed:
```bash
# 1. Install Vercel CLI (if not already installed)
npm install -g vercel

# 2. Deploy to preview environment
vercel

# 3. Deploy directly to production
vercel --prod
```

---

## 🛠️ Local Development & Testing
To test the site locally:
```bash
npx serve .
```
Or open [index.html](index.html) directly in any modern browser.

---

## 📁 Project Structure
- [`index.html`](index.html): Self-contained high-fidelity mobile application interface.
- [`vercel.json`](vercel.json): Vercel routing, security headers, and static hosting configuration.
- [`package.json`](package.json): Project metadata and development scripts.
- [`.gitignore`](.gitignore): Ignore `.vercel` and build artifacts.
