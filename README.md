# 🛡️ Atlasone AI

**The Peer-to-Peer AI Civic Audit, Smart Incident Resolution, & Decentralized Loyalty Grid**

Atlasone AI is a mobile-first, high-fidelity hyperlocal civic platform designed to empower citizens to become active community auditors. By leveraging on-device machine learning, simulated e-governance API pipelines, and a gamified loyalty reward economy, Atlasone Bridges the gap between residents and municipal authorities to resolve public infrastructure issues (e.g., pavement degradation, clogged drainage, broken public facilities) seamlessly.

---

## 🚀 Key Features

- 📱 **Capacitor Hybrid Mobile Integration**: Accesses native-style device capabilities, including location tracking and camera uploads.
- 🧠 **On-Device Edge ML Diagnostics**: Leverages an offline-first quantized image classification model executing in WebAssembly memory to automatically diagnose and tag defects with zero-network requirements.
- 📡 **CPGRAMS Government Dispatch Gateway**: Dynamically formats reports into compliant grievance structures conforming to standard e-governance guidelines.
- 🪙 **Civic Karma Loyalty Grid**: Awards "Eco-Coins" to users for reporting, verifying resolutions, and joining NGO volunteer projects, which are redeemable for public transport transit vouchers.

---

## 🏗️ Project Directory Structure

```text
├── assets/                  # Public static assets & images
├── src/
│   ├── components/          # Extracted modular UI subcomponents
│   ├── mockApi.ts           # Intercepts /api requests with client-side state
│   ├── types.ts             # Shared TypeScript types, interfaces, and enums
│   ├── App.tsx              # Main high-fidelity workspace dashboard and state
│   ├── index.css            # Tailwind global stylesheet
│   └── main.tsx             # Application entry point
├── package.json             # Build commands, scripts, and npm dependencies
├── vite.config.ts           # Vite server, environment configuration, and alias maps
├── HACKATHON_SUBMISSION.md  # Raw markdown submission guidelines
└── HACKATHON_SUBMISSION.html# Rich, printable HTML submission summary page
```

---

## ⚙️ Local Development Setup

To run this project locally on your machine:

### 1. Install Dependencies
Ensure you have Node.js installed, then run:
```bash
npm install
```

### 2. Run Development Server
Boot the localized Vite dev server on port `3000`:
```bash
npm run dev
```
Open your browser and navigate to `http://localhost:3000`.

### 3. Build for Production
To bundle the client-side SPA into static distribution assets:
```bash
npm run build
```
Vite will compile and compress all JavaScript, CSS, and asset files into the standard `dist/` directory, ready to be hosted on any static cloud server (e.g., GitHub Pages, Netlify, Vercel, Firebase Hosting).

---

## 📦 How to Deploy to a Git Repository (GitHub)

If you have downloaded the project's source ZIP and wish to push it to a new GitHub repository, follow these quick terminal commands:

1. **Initialize the repository locally**:
   ```bash
   git init
   ```
2. **Stage all files** (this will ignore heavy folders like `node_modules` automatically due to `.gitignore`):
   ```bash
   git add .
   ```
3. **Commit the files**:
   ```bash
   git commit -m "Initial commit: Atlasone AI Civic Platform"
   ```
4. **Create a new repository** on GitHub, then link it to your local environment:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
   ```
5. **Rename your default branch to main and push**:
   ```bash
   git branch -M main
   git push -u origin main
   ```

---

## 🏆 Hackathon Submission Documents

If you are submitting this project to a hackathon, we have pre-compiled complete, submission-ready files:
* **`HACKATHON_SUBMISSION.md`**: Text-based breakdown containing project summary, problem descriptions, technical stacks, architecture, and metrics.
* **`HACKATHON_SUBMISSION.html`**: A beautiful, print-ready, high-contrast dashboard summarizing your work. Double-click it in your file explorer or open it in a browser, and click **"Export / Print to PDF"** to generate a clean PDF presentation instantly.
