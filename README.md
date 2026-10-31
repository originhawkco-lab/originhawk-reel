# ORIGIN HAWK — PRIME LIMITED

> **Strategy. Content. Technology. Growth. Everything under one roof.**

High-performance digital presence and marketing platform built for **Origin Hawk Prime Limited**.

---

## 🚀 One-Click Deployment to Vercel

### Option 1: Via GitHub & Vercel Dashboard (Recommended)
1. Push this repository to your GitHub account (`git push origin main`).
2. Visit [Vercel New Project](https://vercel.com/new) and select **Import Repository**.
3. **Framework Preset**: Select **Other** (Static).
4. **Root Directory**: `./` (leave default).
5. Click **Deploy**!

### Option 2: Via Vercel CLI
```bash
npx vercel
```
Follow the interactive prompts to deploy directly from your local terminal.

### Option 3: Drag & Drop (Vercel Deploy)
1. Zip or upload this project directory directly in the [Vercel Dashboard](https://vercel.com).
2. Deploys instantly with `vercel.json` providing automatic routing, gzip/brotli compression, and immutable cache headers.

---

## 🎨 Hero Section Architecture: Tri-Engine Lottie JSON + Three.js

The Hero section features a 100% video-free and photo-free, ultra-high-performance animation pipeline:

1. **Interactive Three.js WebGL Background**:
   - 420+ floating luminous particles mapped to the brand palette (`#B8E94E` lime, `#22C55E` emerald, `#2DD4BF` cyan).
   - Interactive mouse parallax tracking and revolving cybernetic icosahedron wireframe lattice.

2. **Tri-Engine Synchronized Lottie JSON Animations**:
   - **Engine 01 (Strategy & AI Core)**: `assets/animations/hero-strategy-ai.json` — 7-layer neural core with pulsating starburst, rotating gyro ring, and radar telemetry.
   - **Engine 02 (Creative Content Studio)**: `assets/animations/hero-creative-content.json` — 4K camera viewfinder, rotating iris shutter blades, audio-visual spectrum equalizer bars.
   - **Engine 03 (Tech & Exponential Growth Engine)**: `assets/animations/hero-tech-growth.json` — Ascending supersonic falcon chevron climbing exponential trajectory to the `+310%` target reticle.
   - All 3 engines play simultaneously in real time with interactive sync toggles, telemetry readouts, and direct scroll navigation to respective service stages.
   - Double-fallback safety: Fetches high-performance local `.json` files on HTTP/Vercel and seamlessly falls back to inline data on local `file:///` executions.

---

## 💻 Local Preview & Development

To test locally with live streaming HTTP server:

```bash
node server.js
```

Then open `http://localhost:8999` in your browser. Or open `index.html` directly in any web browser.

---

## 📁 Project Structure

```
├── assets/
│   ├── animations/
│   │   ├── hero-strategy-ai.json        # Lottie JSON 01: AI Strategy Core
│   │   ├── hero-creative-content.json   # Lottie JSON 02: Creative Content Studio
│   │   └── hero-tech-growth.json        # Lottie JSON 03: Tech & Growth Engine
│   └── Logo/
│       ├── Logo for tab heading.jpg     # Official Tab Favicon Mark
│       ├── Logo for header.svg          # Header Vector Logo
│       └── Logo.svg                     # Full Brand Vector Emblem
├── public/                              # Static Favicon Assets for Web Crawlers & CDNs
├── index.html                           # Main Production Web Application
├── preview.html                         # Live Mirror Preview Page
├── vercel.json                          # Vercel Configuration (Clean URLs, JSON headers, Caching)
├── package.json                         # NPM Scripts & Metadata
├── server.js                            # Node.js Static & Streaming HTTP Server
└── README.md                            # Documentation & Vercel Deployment Guide
```
