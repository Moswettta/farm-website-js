# Green Valley Farm — React Website

A clean, modern, fully responsive homepage for a family farm / agricultural business. Built with **React + Vite + Tailwind CSS v4**.

## Features

- Responsive design (mobile-first)
- Smooth scroll navigation
- Hero, About, Products, Features, Testimonials, and Contact sections
- Demo contact form
- Custom farm-themed color palette
- Fast development with Vite

## Prerequisites

- **Node.js** 18+ (recommended 20 or 22)
- **npm** 9+ (comes with Node)

## Quick Start (Expedited)

```bash
# 1. Go into the project folder
cd farm-website

# 2. Install dependencies
npm install

# 3. Start the development server
npm run dev
```

Then open the URL shown in the terminal (usually **http://localhost:5173**).

That's it — the site will hot-reload as you edit files.

## Available Scripts

| Command          | Description                          |
|------------------|--------------------------------------|
| `npm run dev`    | Start development server with HMR    |
| `npm run build`  | Build production assets into `dist/` |
| `npm run preview`| Preview the production build locally |

## Project Structure

```
farm-website/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Hero.jsx
│   │   ├── About.jsx
│   │   ├── Products.jsx
│   │   ├── Features.jsx
│   │   ├── Testimonials.jsx
│   │   ├── Contact.jsx
│   │   └── Footer.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css          # Tailwind + custom theme
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Customization Tips

- **Colors**: Edit the `@theme` section in `src/index.css`
- **Content**: Update text and product data directly in the component files
- **Images**: Replace the emoji placeholders / gradient blocks with real `<img>` tags or background images
- **Form**: The contact form currently shows an alert. Hook it up to Formspree, Netlify Forms, or your own backend

## Deploy

### Vercel / Netlify (easiest)
1. Push the project to GitHub
2. Import the repo in Vercel or Netlify
3. Build command: `npm run build`
4. Output directory: `dist`

### Manual static hosting
```bash
npm run build
# Upload the contents of the `dist/` folder to any static host
```

## License

This project is free to use and modify for personal or commercial farm websites.
