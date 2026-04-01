# HESI Patient Reviews

An [Astro](https://astro.build) site featuring nursing case studies to help students prepare for HESI exams.

## 🚀 Live Site

Deployed to GitHub Pages: [https://sagreenxyz.github.io/hesi-patient-reviews](https://sagreenxyz.github.io/hesi-patient-reviews)

## 🛠️ Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📁 Project Structure

```
/
├── .github/workflows/deploy.yml   # GitHub Pages deployment workflow
├── public/                        # Static assets
├── src/
│   ├── layouts/
│   │   └── Layout.astro           # Shared page layout
│   └── pages/
│       ├── index.astro            # Home page
│       └── case-studies.astro     # Case studies listing
├── astro.config.mjs               # Astro configuration
└── package.json
```

## 📦 Deployment

Every push to `main` automatically builds and deploys the site to GitHub Pages via the workflow in `.github/workflows/deploy.yml`.

To enable GitHub Pages in your repository, go to **Settings → Pages** and set the source to **GitHub Actions**.
