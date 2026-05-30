# 🚀 Conversa Landing Page Template (Open-Source)

[![Framework: Next.js 16](https://img.shields.io/badge/Framework-Next.js%2016-black?style=flat-square&logo=next.dot-js)](https://nextjs.org/)
[![Styling: Tailwind CSS v3](https://img.shields.io/badge/Styling-Tailwind%20CSS%20v3-blue?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![Package Manager: pnpm](https://img.shields.io/badge/Package%20Manager-pnpm-amber?style=flat-square&logo=pnpm)](https://pnpm.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](https://opensource.org/licenses/MIT)

A production-grade, high-performance, and **100% Config-Driven Open-Source Landing Page Blueprint** explicitly engineered for AI chat tools and enterprise SaaS applications. Architected natively using **Next.js 16 (App Router)**, **React 19**, **Tailwind CSS v3 (Native Compiler)**, and fully optimized via a highly deterministic **pnpm Workspace** pipeline.

Live Production URL: [conversa-landing.vercel.app](https://conversa-landing.vercel.app/)

---

## 💎 Architectural Highlights & Engineering Excellence

This repository template has been decoupled from hardcoded structural layers into a highly maintainable, scalable open-source ecosystem:

- **Full Configuration-Driven UI System:** Modify the core layout, sub-pages, pricing models, meta-tags, privacy clauses, FAQs, and navigation metrics dynamically without touching a single line of JSX/TSX core code. Everything is managed from centralized state models inside `./config/`.
- **Next-Gen Compilation (Tailwind CSS v3 Native):** Fully bypassed legacy PostCSS abstraction layers. Leveraging Tailwind v4's native compiler architecture for lightning-fast sub-millisecond local compilation and minimum production CSS bundle footprint.
- **Deterministic Package Integrity with pnpm:** Engineered over a single-node **`pnpm Workspace`** layout to guarantee strict peer dependency synchronization under React 19, avoiding ghost dependencies while shaving dependency overhead storage.
- **Cinematic Motion Layers:** Fluid UI micro-interactions, responsive disclosures, and scroll-bound layouts powered natively by **Framer Motion Core**.

---

## 📸 Visual Production Walkthrough

<p align="center">
  <img src="https://github.com/user-attachments/assets/4284e3f4-e57f-4509-8e26-318508a90b72" alt="Conversa Landing Page Premium Walkthrough" width="100%" />
</p>

---

## 📂 Exact Folder Structure & Taxonomy

```text
├── app/                      # Next.js 16 Active Routing Domain (App Router)
│   ├── components/           # Core Layout Injections & Section Modules
│   │   ├── layout/           # Global Structural Scaffolding (Header, Footer, Navigation)
│   │   └── sections/         # High-Performance Animated Sections (Hero, Pricing, FAQ)
│   ├── (sub-routes)/         # Scaled Multi-Page Ecosystem Pages
│   │   ├── demo/, contact/, cookies/, faq/, upgrade/, privacy/, signup/, support/, terms/
│   │   └── page.tsx          # Global Main Entry Point Layout Canvas
│   ├── sitemap.ts & robots.ts # Dynamic Search Engine Optimization (SEO) Pipelines
│   └── globals.css           # Tailwind CSS v3 Native Directives Injection Layer
├── components/               # Atomic Engine Architecture (Shadcn UI Blocks)
│   ├── ui/                   # Hardened Primitives (Radix UI Adaptations)
│   ├── login-form.tsx        # Centralized Authentication Components
│   └── signup-form.tsx       # Centralized Authentication Components
├── config/                   # The Control Tower (Pure TypeScript Modular Schemas)
│   ├── siteConfig.ts         # Master Global Identity Schema
│   ├── hero.ts & features.ts # Marketing & Core Feature Registries
│   ├── pricing.ts & upgrade.ts # Tier Monetization Schemas
│   ├── faq.ts & reviews.ts   # Interactive Accordion & Social Testimonial Assets
│   ├── privacy.ts & terms.ts # Hardened Legal Compliance Matrix Data
│   └── metadata.ts           # Unified OpenGraph (OG) Metadata State Core
├── lib/                      # Atomic Utility Hooks & Context Factories (`utils.ts`)
├── public/                   # Static CDN-Grade Assets (SVGs, Optimization Vectors)
├── pnpm-workspace.yaml       # Strict Monorepo Package Multi-Node Registry
└── pnpm-lock.yaml            # Hardened Native Peer Dependency Graph
