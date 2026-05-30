# 🚀 Conversa Landing Page Template (Open-Source)

[![Framework: Next.js 16](https://img.shields.io/badge/Framework-Next.js%2016-black?style=flat-square&logo=next.dot-js)](https://nextjs.org/)
[![Styling: Tailwind CSS v4](https://img.shields.io/badge/Styling-Tailwind%20CSS%20v4-blue?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![Package Manager: pnpm](https://img.shields.io/badge/Package%20Manager-pnpm-amber?style=flat-square&logo=pnpm)](https://pnpm.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](https://opensource.org/licenses/MIT)

A high-performance, production-grade, and **Fully Config-Driven Open-Source Landing Page Template** built for AI chat tools and SaaS interfaces. Meticulously engineered using **Next.js 16 (App Router)**, **React 19 Runtime**, and **Tailwind CSS v4 (Native)**, optimized natively via **pnpm**.

Live Production URL: [conversa-landing.vercel.app](https://conversa-landing.vercel.app/)

---

## 💎 Architectural Highlights & Engineering Excellence

This repository has been decoupled from standard hardcoded layouts into a highly scaleable, configuration-first open-source blueprint:

- **100% Config-Driven UI:** Modify the hero layout, features matrix, pricing structure, FAQs, and navigation menus on the fly without changing a single line of JSX/TSX elements. Everything is centrally managed inside the `./config/` core directory.
- **Native Tailwind CSS v4 Engine:** Bypassed old legacy PostCSS compilation abstractions. This setup leverages Tailwind v4's native compiler for ultra-fast, sub-millisecond hot-reloading and heavily shaved production build bundles.
- **Deterministic Dependency Management:** Powered by **pnpm** to secure clean peer dependency execution graphs under React 19, avoiding ghost dependencies while drastically saving local disk cache storage.
- **Fluid Animation Dynamics:** Injected high-performance UI micro-interactions and scroll-bound layouts powered natively by **Framer Motion Core**.

---

## 📸 Visual Production Walkthrough

<p align="center">
  <img src="https://github.com/user-attachments/assets/4284e3f4-e57f-4509-8e26-318508a90b72" alt="Conversa Landing Page Premium Walkthrough" width="100%" />
</p>

---

## 📂 Structural Layout & Architecture

Unlike complex full-stack architectures, this frontend structure is explicitly layered between global configuration states and clean App Router conventions:

```text
├── app/                  # Next.js 16 Active Routing Domain
│   ├── components/       # Custom Content Modules (Decoupled from UI)
│   │   ├── layout/       # Modular Header, Footer, and Structural Wrappers
│   │   └── sections/     # Animated Content Units (Hero, Pricing, FAQ)
│   ├── demo/             # Template Sandbox Sandbox Simulator
│   └── globals.css       # Tailwind CSS v4 Base Configurations
├── components/           # Base Component Engine (Shadcn UI Layer)
│   └── ui/               # Primitive Atoms (Radix UI Adaptations)
├── config/               # The Control Center (Pure TS Configuration Models)
│   ├── hero.ts           # Dynamic Typography & Asset Registries
│   ├── pricing.ts        # Subscription Tier Pricing Schemas
│   └── siteConfig.ts     # Meta SEO & Application Properties
└── lib/                  # Atomic Utility Helper Modules
