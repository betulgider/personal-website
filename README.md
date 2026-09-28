# Betül Gider - Personal Portfolio

A lightweight, typography-led personal portfolio website designed for Betül Gider, a professional in People & Culture, Recruitment, and Project Management.

## Design Philosophy

The site follows a minimalistic and structural design approach, prioritizing content clarity and readability:
- **Typography-led**: Uses *Lora* (serif) for warm, approachable headings and *Inter* (sans-serif) for clean, readable body text.
- **Warm Neutral Palette**: Avoids generic corporate blues in favor of soft off-whites, deep charcoal, and a sophisticated clay/ochre accent.
- **Structural Integrity**: Heavily relies on whitespace, semantic HTML, and clean CSS timelines rather than bulky UI cards or unnecessary borders.
- **Accessible & Responsive**: Fully responsive (mobile-first), designed with WCAG contrast standards in mind, and includes smooth fade-in motion that respects performance.

## Tech Stack

- HTML5 (Semantic Structure)
- Vanilla CSS (Custom properties, grid/flexbox)
- Vanilla JavaScript (Intersection Observer for scroll animations)
- **Vite** (Fast local development and build tool)

## Getting Started

To run the site locally on your machine, you need [Node.js](https://nodejs.org/) installed.

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start the local development server**:
   ```bash
   npm run dev
   ```

3. **Build for production**:
   ```bash
   npm run build
   ```
   The production-ready static files will be generated in the `dist/` folder.

## Deployment

Because this is a static site built with Vite, it can be hosted essentially anywhere for free. You can deploy it easily by connecting this GitHub repository to platforms like:
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
- [GitHub Pages](https://pages.github.com/) 

Set the framework preset to "Vite" or the build command to `npm run build` and output directory to `dist`.
