[GitHub_README.md](https://github.com/user-attachments/files/27005847/GitHub_README.md)
## Hi there 👋

<!--
**kartik010/kartik010** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
<div align="center">

# Kartik Sharma

**Full-Stack & Shopify Developer · IEEE Author · Delhi/Gurugram, India**

[![Portfolio](https://img.shields.io/badge/Portfolio-kartiksharma.io-000000?style=flat-square&logo=safari&logoColor=white)](https://kartiksharma.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-kartik--sharma-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kartik-sharma)
[![Email](https://img.shields.io/badge/Email-kartik%40email.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kartik@email.com)

MCA '25 · Amity University &nbsp;|&nbsp; BCA '21 · GGSIPU

*Building production-grade web experiences — from ultra-luxury Shopify storefronts to blockchain DApps.*

</div>

---

## About

I'm a full-stack and Shopify developer based in Gurugram, India. I've built and shipped production products across EdTech, e-commerce, blockchain, and corporate web — working both as a sole developer at a startup and as a freelance engineer across multiple client verticals.

My work spans the full lifecycle: architecture, design systems, CMS setup, payment integrations, DNS/deployment, SEO, and analytics. I care deeply about the craft — both the code and how it looks.

I also have a published IEEE paper on peer-to-peer energy trading using the Solana blockchain, presented at ICRITO 2025.

---

## Featured Projects

### 01 — MERCI Dehradun · Shopify Redesign
> *Premium lifestyle & fashion brand · Dehradun, India*

**Live:** [mercidehradun.com](https://mercidehradun.com)

MERCI is a luxury lifestyle brand. I was brought in as their Shopify developer to audit and redesign their existing store — no platform migration, no theme change — just precision improvements inside the **Prestige theme by Maestrooo**.

**What I found (Before):**
- Stale hero banners with outdated seasonal campaigns
- Broken 404 pages on multiple collection routes
- Empty `alt` tags across all product images (SEO + accessibility failure)
- Duplicated mega-menu entries causing navigation confusion
- No consistent typographic hierarchy on collection and product pages

**What I built (After):**
- Full UX audit with documented issue log
- Brand-new `header.liquid` — rebuilt navigation architecture from scratch
- Custom `merci-header.css` + `merci-header.js` — all prefixed `mc-` to avoid Prestige theme conflicts
- Homepage redesign in the **Riviera Cream** direction — editorial, ultra-luxury, comparable to Hermès, Loro Piana, Diptyque
- Typography system: **Cormorant Garamond** (display) + **Jost** (body)
- Reference brands studied: bonadea.com, goodearth.in

**Stack:** Shopify Liquid · Prestige Theme · CSS · Vanilla JS · Figma

---

### 02 — Vision 1000 · EdTech LMS Platform
> *SMARRTIF AI · Sole Developer · 2023–2024*

**Live:** [vision1000.in](https://vision1000.in) *(or your actual URL)*

Vision 1000 is a full-featured EdTech platform I built entirely solo as the only developer at SMARRTIF AI. Went from zero to production — architecture, UI, integrations, deployment.

**What I built:**
- Complete LMS with course creation, video lessons, quizzes, and student dashboards
- Auth system via **Clerk** — SSO, magic links, role-based access (student / instructor / admin)
- Video infrastructure via **Mux** — adaptive streaming, upload pipeline, thumbnails
- CMS via **Sanity** — structured content for courses, instructors, and blog
- Payments via **Razorpay** — subscription plans, one-time purchases, webhook handling
- AI features via **OpenAI API** — course content suggestions, quiz generation
- Responsive UI in **Next.js 14 + TypeScript** — App Router, Server Components, optimistic UI

**Scale:** Built and shipped solo in under 6 months.

**Stack:** Next.js 14 · TypeScript · Clerk · Mux · Sanity CMS · Razorpay · OpenAI API · Vercel · Tailwind CSS

---

### 03 — KETE · kernelectech.in · Corporate Website
> *Kern Elec Tech Experts · Electrical, Instrumentation & Solar Energy*

**Live:** [kernelectech.in](https://kernelectech.in)

End-to-end build and deployment of a corporate website for KETE — an electrical, instrumentation, and solar energy company.

**What I delivered:**
- Full site in plain **HTML · CSS · JS** — no framework overhead, fast and lean
- Deployed on **Vercel** with custom GoDaddy domain (`kernelectech.in`)
- DNS configuration: A record, CNAME, MX records for GoDaddy Workspace Email
- **Google Search Console** setup — sitemap submission, coverage monitoring
- **GA4** property setup — event tracking, traffic sources
- SEO-ready: semantic HTML, meta tags, structured data

**Stack:** HTML · CSS · JavaScript · Vercel · GoDaddy DNS · GA4 · Google Search Console

---

### 04 — P2P Energy Trading DApp · Solana Blockchain
> *IEEE ICRITO 2025 · Research + Implementation*

**IEEE Paper:** Published & Presented at ICRITO 2025

A peer-to-peer energy trading system built on the **Solana blockchain** — combining original research with a working DApp implementation.

**What I built:**
- Smart contracts (programs) on Solana using the **Anchor framework**
- **Phantom Wallet** integration — connect, sign, and execute energy trade transactions
- On-chain trade matching logic — prosumers list energy, consumers bid in real time
- Off-chain dashboard in **TypeScript** + **React** — live trade feed, wallet balances, transaction history
- Gas-efficient transaction design leveraging Solana's ~400ms finality and sub-cent fees

**Research contribution:** Demonstrated viability of decentralized, trustless P2P energy markets as an alternative to utility grid intermediaries. Published in IEEE proceedings.

**Stack:** Solana · Anchor Framework · TypeScript · React · Phantom Wallet · Web3.js

---

### 05 — Tapodhani · Vastu Consultancy Site
> *Freelance · Framer + Cal.com*

A brand and booking site for a Vastu consultancy practice — built in **Framer** with **Cal.com** scheduling integration.

**What I delivered:**
- Full site design and build in Framer
- Cal.com embed for seamless appointment booking
- Brand identity and visual language for the practice
- Mobile-optimised, fast-loading, no-code maintainable by the client

**Stack:** Framer · Cal.com · Custom Domain

---

### 06 — The Design Edit · Portfolio Site
> *Sumit Chander · Floral & Event Designer · Freelance*

A high-craft, single-file portfolio for a floral and event designer — built to feel editorial and immersive, with zero dependencies.

**What I built:**
- **Scroll-driven canvas frame animation** — scrub-controlled hero sequence
- **3D card tilt effects** — mouse-tracked perspective transform on project cards
- **Magnetic cursor** — custom cursor that snaps to interactive elements
- **Base64-embedded images** — extracted from a PDF brief, embedded directly for single-file delivery
- Zero external libraries — pure HTML, CSS, JS

**Stack:** HTML · CSS · Vanilla JS · Canvas API

---

## Work Experience

### Shopify Developer — MERCI Dehradun *(2024–Present)*
Reviewing and improving the existing Shopify store within the Prestige theme. UX audit, navigation rebuild, homepage redesign.

### Software Developer — SMARRTIF AI *(2023–2024)*
Sole developer on the VISION 1000 EdTech platform. Built the entire product from scratch — frontend, backend integrations, CMS, payments, video, AI.

### Frontend Intern — IIT Delhi
Frontend performance optimisation and component work.

### Frontend Intern — BIJAK
Frontend development and SEO improvements.

---

## Tech Stack

```
Frontend       Next.js 14 · React · TypeScript · Tailwind CSS · HTML/CSS/JS
CMS & Content  Sanity CMS · Shopify Liquid · Framer
Auth & Video   Clerk · Mux
Payments       Razorpay
AI             OpenAI API
Blockchain     Solana · Anchor · Web3.js · Phantom Wallet
Database       Supabase · Drizzle ORM · PostgreSQL
Deployment     Vercel · GoDaddy · DNS Configuration
Analytics      GA4 · Google Search Console
Design         Figma · GSAP · Canvas API
```

---

## Research & Publications

**P2P Energy Trading Using Solana Blockchain**
*IEEE ICRITO 2025 · Presented & Published*
Proposed and implemented a decentralised peer-to-peer energy trading model using Solana smart contracts — demonstrating trustless, low-latency energy markets without utility intermediaries.

---

## Education

**MCA — Master of Computer Applications**
Amity University · 2023–2025

**BCA — Bachelor of Computer Applications**
Guru Gobind Singh Indraprastha University (GGSIPU) · 2018–2021

---

<div align="center">

**[kartiksharma.io](https://kartiksharma.io) · [LinkedIn](https://linkedin.com/in/kartik-sharma) · [IEEE Paper](#)**

*Open to freelance projects and full-time roles.*

</div>

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
