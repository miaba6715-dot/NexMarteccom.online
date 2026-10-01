# NexMart Ecom

A modern e-commerce marketing platform dashboard with VIP order grabbing, earnings management, real-time analytics, multilingual support, and a complete admin control center.

## 🚀 Live Demo & Development

- **Built With:** React 19, TypeScript, Vite, Tailwind CSS, Lucide Icons, Web Audio API
- **Framework:** Vite Single Page Application (SPA)

---

## 🛠️ Getting Started

### Prerequisites

- Node.js 18+ or 20+
- npm, yarn, pnpm, or bun

### 1. Installation

```bash
npm install
```
*(or `bun install` / `pnpm install`)*

### 2. Development Server

```bash
npm run dev
```

Runs the local development server at `http://localhost:3000`.

### 3. Production Build

```bash
npm run build
```

Compiles TypeScript and bundles production-ready assets into the `dist/` directory.

### 4. Local Preview

```bash
npm run preview
```

Previews the production build locally.

---

## 🌐 Deployment Instructions

### Option 1: Deploy to Vercel (Recommended - 1 Click)
1. Go to [Vercel Dashboard](https://vercel.com/new).
2. Connect your GitHub repository `NexMarteccom.online`.
3. Vercel automatically detects Vite:
   - **Framework Preset:** Vite
   - **Build Command:** `npm run build`
   - **Output Directory:** `dist`
4. Click **Deploy**.

### Option 2: Deploy to Netlify
1. Go to [Netlify](https://app.netlify.com/start).
2. Import the repository `NexMarteccom.online`.
3. Set build settings:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
4. Click **Deploy Site**.

### Option 3: Deploy to Cloudflare Pages
1. Go to Cloudflare Dashboard > **Workers & Pages** > **Create application** > **Pages**.
2. Connect GitHub and select `NexMarteccom.online`.
3. Select preset: **Vite**.
4. Output directory: `dist`.
5. Click **Save and Deploy**.

### Option 4: Deploy to GitHub Pages
1. Go to your repository on GitHub: `Settings` > `Pages`.
2. Under **Build and deployment**, select **GitHub Actions**.
3. Push to `main` to trigger the automated build and deployment.

---

## 📁 Project Structure

```
├── public/                 # Static assets and downloadable archive
├── src/
│   ├── components/         # UI views, modals, top bar, admin deck, header
│   │   ├── HomeView.tsx    # NexMart Ecom header & quick action dashboard
│   │   ├── TopBar.tsx      # URL simulator & quick action bar
│   │   ├── BottomNav.tsx   # Mobile bottom navigation tabs
│   │   ├── Modals.tsx      # Deposit, Withdraw, About & Service dialogs
│   │   └── ...
│   ├── services/           # Audio alerts & local notification engine
│   ├── data.ts             # Initial data, VIP plans, user state
│   ├── types.ts            # TypeScript interfaces & types
│   ├── languages.ts        # Multilingual dropdown configurations
│   ├── App.tsx             # Main application orchestrator
│   └── main.tsx            # Vite entry point
├── package.json            # Project dependencies and scripts
├── tsconfig.json           # TypeScript configuration
└── vite.config.ts          # Vite build configuration
```
