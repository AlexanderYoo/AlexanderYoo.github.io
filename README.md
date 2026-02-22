# YooCode Portfolio Astro
A modern, responsive developer portfolio for Alex (In Seon) Yoo, live at [alexanderyoo.github.io](https://alexanderyoo.github.io). Built with Astro and Tailwind CSS, featuring a glassmorphism design and smooth scroll animations.

## 🌐 Live Demo
[alexanderyoo.github.io](https://alexanderyoo.github.io)

## ✨ Key Features
- **Modern UI**: Clean design with glassmorphism effects.
- **Scroll Animations**: Smooth entry animations powered by AOS (Animate On Scroll).
- **Responsive Design**: Optimized for all screen sizes, from mobile to desktop.
- **Fast Performance**: Built with Astro for near-instant load times.
- **Data-Driven Content**: All portfolio content (projects, skills, experience) lives in TypeScript data files for easy updates.
- **SEO Optimized**: OpenGraph tags, Twitter cards, and JSON-LD structured data for rich search and social previews.
- **Accessibility**: Respects `prefers-reduced-motion` for users who prefer minimal animation.
- **Component-Based Architecture**: Modular components organized by feature for maintainability.

## 🛠️ Technologies
- **[Astro](https://astro.build/)**: The web framework for content-driven websites.
- **[Tailwind CSS](https://tailwindcss.com/)**: A utility-first CSS framework.
- **[TypeScript](https://www.typescriptlang.org/)**: Type-safe data files and configuration.
- **[AOS](https://michalsnik.github.io/aos/)**: Animate on scroll library.
- **[Lucide Icons](https://lucide.dev/)**: Beautiful & consistent icons.
- **[astro-icon](https://github.com/natemoo-re/astro-icon)**: Icon integration for Astro.

## 📁 Project Structure
```text
/
├── public/             # Static assets (images, favicon)
├── src/
│   ├── assets/          # Processed images and media
│   ├── components/      # Reusable UI components (NavBar, About, Projects, etc.)
│   ├── data/            # TypeScript data files (projects, skills, experience, navigation)
│   ├── layouts/         # Page templates
│   ├── pages/           # Project routes (index.astro)
│   └── styles/          # Global and animation CSS files
├── astro.config.mjs    # Astro configuration (site URL, integrations)
├── package.json        # Dependencies and scripts
└── tsconfig.json       # TypeScript configuration
```

## 🏗️ Architecture Overview
- **Single-page app**: `src/pages/index.astro` composes all sections (Hero, About, Projects, etc.) into one page.
- **Data-driven**: Portfolio content is externalized to `src/data/*.ts` files — update your projects, skills, or experience without touching component code.
- **Modular components**: Each page section is its own component in `src/components/`, organized by feature for clarity and reuse.

## 🚀 Getting Started
1. **Clone the repository**
2. **Install dependencies**: `npm install`
3. **Start the development server**: `npm run dev`
4. **Build for production**: `npm run build`

## 🌍 Deployment
Deployed to GitHub Pages. The site URL is configured in `astro.config.mjs` — update the `site` field if deploying to a different domain.

---
