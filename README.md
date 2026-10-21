# THE DVG — Modern 3D Portfolio

An interactive, high-performance 3D portfolio powered by Three.js, GSAP ScrollTrigger, and WebGL.

---

## 🚀 Deploy to Vercel

This repository is pre-configured for instant zero-configuration deployment on **Vercel**.

### Option 1: Automatic Deployment via Vercel Dashboard (Recommended)

1. Go to [vercel.com](https://vercel.com) and log in.
2. Click **"Add New..."** → **"Project"**.
3. Import your GitHub repository: `Dvg27/PortfolioDVG`.
4. Keep the default settings:
   - **Framework Preset**: Other
   - **Root Directory**: `./`
5. Click **"Deploy"**.
6. Every time you push to the `main` branch, Vercel will automatically build and deploy your updates.

---

### Option 2: Deploy via Vercel CLI

You can also deploy directly from your local terminal using the Vercel CLI:

```bash
# Log in to Vercel and deploy preview
npx vercel

# Deploy directly to production
npx vercel --prod
```

---

## 💻 Local Development

To run the project locally on your machine:

```bash
# Using npx serve
npx serve .

# Or using npm
npm start
```

Then open `http://localhost:3000` (or the port indicated in your terminal) in your browser.

---

## 📁 Project Structure

```
├── index.html       # Complete application (HTML5, Three.js 3D canvas, GSAP choreographies, GLSL shaders)
├── vercel.json      # Vercel deployment headers, security policies, and asset caching rules
├── package.json     # Node scripts for local development and build commands
├── .gitignore       # Excluded build artifacts and OS cache files
└── README.md        # Deployment instructions and project overview
```

## 🛠 Tech Stack

- **Three.js (r134)**: Procedural 3D models, dynamic lighting, responsive camera waypoints
- **GSAP & ScrollTrigger**: Cinematic timeline transitions and scroll-bound animations
- **HTML5 Canvas**: Dot-matrix portraits, matrix code rain, wave visualizers, Lissajous curves
- **Vanilla CSS3**: Cyberpunk glassmorphism, responsive grid, Syne & JetBrains Mono typography
