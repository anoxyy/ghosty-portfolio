# 🌸 Ghosty Portfolio — Experimental Interface Lab

An experimental portfolio website showcasing interface design experiments with precision-crafted animations and interactions. Built with Next.js, featuring split-flap displays, scramble text effects, and smooth GSAP animations.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fanoxyy%2Fghosty-portfolio)

---

## ✨ Features

- **Split-Flap Display** — Retro airport-style animated text with authentic sound effects
- **Scramble Text** — Dynamic text scrambling on hover interactions
- **Smooth Scroll** — Butter-smooth scrolling powered by Lenis
- **GSAP Animations** — Professional scroll-triggered animations and parallax effects
- **Responsive Design** — Optimized for all screen sizes from mobile to desktop
- **Dark Theme** — Sleek dark interface with accent highlights
- **Noise Effects** — Subtle animated noise overlays for texture
- **Performance Optimized** — Fast page loads with Next.js 15 App Router

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| **Framework** | Next.js 15 (App Router) |
| **Styling** | Tailwind CSS |
| **Animations** | GSAP + ScrollTrigger |
| **Smooth Scroll** | Lenis |
| **Typography** | Bebas Neue, Inter, Geist Mono |
| **Language** | TypeScript |
| **Deployment** | Vercel |

---

## 🚀 Quick Deploy

### Deploy to Vercel (Recommended)

Click the button below for instant deployment:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fanoxyy%2Fghosty-portfolio)

**Automatic configuration:**
- Zero configuration needed
- Automatic builds on every push
- Global CDN deployment
- Free SSL certificate
- Custom domain support

### Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/anoxyy/ghosty-portfolio)

**Build settings:**
- Build command: `npm run build`
- Publish directory: `.next`

### Deploy to Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Fanoxyy%2Fghosty-portfolio)

---

## 💻 Local Development

### Prerequisites

- Node.js 18.x or higher
- npm, yarn, or pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/anoxyy/ghosty-portfolio.git
   cd ghosty-portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open in browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
npm start
```

---

## 📁 Project Structure

```
ghosty-portfolio/
├── app/
│   ├── globals.css          # Global styles
│   ├── layout.tsx            # Root layout with fonts
│   └── page.tsx              # Main page with sections
├── components/
│   ├── hero-section.tsx      # Hero with split-flap text
│   ├── signals-section.tsx   # Latest updates carousel
│   ├── work-section.tsx      # Project grid
│   ├── principles-section.tsx # Design principles
│   ├── colophon-section.tsx  # Credits & contact
│   ├── animated-noise.tsx    # Noise effect overlay
│   ├── scramble-text.tsx     # Text scramble animation
│   ├── split-flap-text.tsx   # Split-flap display
│   └── ui/                   # shadcn/ui components
├── public/
│   ├── icon.svg              # Favicon
│   └── *.png                 # Icons and assets
└── styles/
    └── globals.css           # Tailwind directives
```

---

## 🎨 Customization

### Change Colors

Edit `app/globals.css` to modify the color scheme:

```css
:root {
  --accent: 120 100% 50%;     /* Accent color (HSL) */
  --foreground: 0 0% 95%;     /* Text color */
  --background: 0 0% 5%;      /* Background color */
}
```

### Update Content

- **Hero Text:** `components/hero-section.tsx`
- **Projects:** `components/work-section.tsx` (experiments array)
- **Signals:** `components/signals-section.tsx` (signals array)
- **Principles:** `components/principles-section.tsx`
- **Credits:** `components/colophon-section.tsx`

### Add New Sections

1. Create a new component in `components/`
2. Import and add to `app/page.tsx`
3. Update navigation in `components/side-nav.tsx`

---

## 📦 Dependencies

### Core
- `next` — React framework
- `react` / `react-dom` — UI library
- `typescript` — Type safety

### Styling
- `tailwindcss` — Utility-first CSS
- `class-variance-authority` — Component variants
- `clsx` / `tailwind-merge` — Class name utilities

### Animation
- `gsap` — Professional animation library
- `@studio-freight/lenis` — Smooth scroll

### UI Components
- `@radix-ui/*` — Headless UI primitives
- Custom components built with shadcn/ui

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Developer

**ghosty**

- Instagram: [@corpsealone](https://instagram.com/corpsealone)
- Telegram: [@excanor](https://t.me/excanor)

---

## 🌟 Acknowledgments

- Design inspired by experimental interface labs and signal processing aesthetics
- Typography: Bebas Neue, Inter, Geist Mono
- Animations powered by GSAP
- Built with Next.js and Tailwind CSS

---

<p align="center">
  <strong>Crafted with precision. Built for the future.</strong><br>
  © 2026 ghosty. All rights reserved.
</p>
