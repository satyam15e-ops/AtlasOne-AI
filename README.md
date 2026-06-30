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
