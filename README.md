<div align="center">

# Kartik Sharma

### Full-Stack & Shopify Developer · IEEE Author · Gurugram, India

[![Portfolio](https://img.shields.io/badge/Portfolio-kartiksharma.io-0C447C?style=flat-square&logo=safari&logoColor=white)](https://kartiksharma.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-kartik--sharma-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kartik-sharma)
[![GitHub followers](https://img.shields.io/github/followers/kartik010?style=flat-square&logo=github&logoColor=white&color=181717)](https://github.com/kartik010)
[![MERCI](https://img.shields.io/badge/mercidehradun.com-live-27500A?style=flat-square)](https://mercidehradun.com)
[![KETE](https://img.shields.io/badge/kernelectech.in-live-27500A?style=flat-square)](https://kernelectech.in)

**MCA '25 · Amity University &nbsp;&nbsp;|&nbsp;&nbsp; BCA '21 · GGSIPU**

*Building production-grade web experiences — from ultra-luxury Shopify storefronts to blockchain DApps.*

</div>

---

## At a Glance

<div align="center">

| 🌐 Live Sites | 📄 IEEE Papers | ⚡ Years Building | 🛠 Tech Stacks |
|:---:|:---:|:---:|:---:|
| **4** | **1** | **2+** | **5+** |

</div>

---

## About Me

I'm a full-stack and Shopify developer based in Gurugram, India. I've built and shipped production products across EdTech, e-commerce, blockchain, and corporate web — working as the sole developer at a startup and as a freelance engineer across multiple client verticals.

My work spans the full lifecycle: architecture, design systems, CMS setup, payment integrations, DNS/deployment, SEO, and analytics. I care deeply about both the code and the craft — how it's built matters as much as how it looks.

I also have a published IEEE paper on peer-to-peer energy trading using the Solana blockchain, presented at **ICRITO 2025**.

```
Frontend    →   Next.js 14 · React · TypeScript · Tailwind · HTML/CSS/JS · GSAP
CMS         →   Sanity · Shopify Liquid · Framer
Auth/Video  →   Clerk · Mux
Payments    →   Razorpay
AI          →   OpenAI API
Blockchain  →   Solana · Anchor · Web3.js · Phantom Wallet
Database    →   Supabase · Drizzle ORM · PostgreSQL
Deployment  →   Vercel · GoDaddy DNS
Analytics   →   GA4 · Google Search Console
```

---

## Featured Projects

### 01 · MERCI Dehradun — Shopify Redesign

> **Live →** [mercidehradun.com](https://mercidehradun.com) | `Shopify` `Liquid` `CSS` `Vanilla JS`

Premium lifestyle and fashion brand based in Dehradun. Hired as their Shopify developer to audit and redesign the existing store — no platform migration, precision surgery inside the **Prestige theme by Maestrooo**. Target aesthetic: ultra-luxury comparable to Hermès, Loro Piana, Diptyque.

**Before →**
- Stale hero banners from old seasonal campaigns
- Broken 404 pages on multiple collection routes
- Empty `alt` tags across all product images (SEO + accessibility failure)
- Duplicated mega-menu entries causing navigation confusion
- No consistent typographic hierarchy on product pages

**After →**
- Full UX audit with documented issue log delivered to client
- New `header.liquid` — rebuilt navigation architecture from scratch
- Custom `merci-header.css` + `merci-header.js` — all prefixed `mc-` to prevent Prestige conflicts
- Homepage redesigned in **Riviera Cream** direction — editorial, ultra-luxury
- Typography system: **Cormorant Garamond** (display) + **Jost** (body)

**How I built it →**
1. Conducted full UX audit — mapped every broken route, missing asset, and UX failure into a documented issue log
2. Studied reference brands (bonadea.com, goodearth.in) and defined the Riviera Cream direction
3. Rebuilt `header.liquid` from scratch — all CSS/JS prefixed `mc-` to avoid Prestige theme conflicts
4. Redesigned homepage sections using Cormorant Garamond for display and Jost for body text

---

### 02 · Vision 1000 — EdTech LMS Platform

> **Live →** [vision1000.in](https://vision1000.in) | `Next.js 14` `TypeScript` `Clerk` `Mux` `Sanity` `Razorpay` `OpenAI`

Full learning management system built entirely solo at **SMARRTIF AI** — greenfield to production in under 6 months. Course creation, video lessons, student dashboards, AI-generated content, and real payment flows.

**The Brief →**
- Zero existing product — truly greenfield, no handoff
- Sole developer with no team
- Video streaming at scale required
- Payment subscriptions + one-time purchase plans
- AI features to differentiate from competitors

**What I Shipped →**
- **Clerk** auth — SSO, magic links, role-based access (student / instructor / admin)
- **Mux** video — adaptive streaming, upload pipeline, auto-generated thumbnails
- **Razorpay** payments — subscription lifecycle + one-time purchases + webhook handling
- **Sanity CMS** — structured content for courses, instructors, and blog
- **OpenAI API** — course outline suggestions + AI-generated quizzes from lesson transcripts

**How I built it →**
1. Chose Next.js 14 App Router + TypeScript — Server Components for fast loads, Client Components for interactive dashboards
2. Integrated Mux — built upload pipeline (pre-signed URLs to Mux ingest), adaptive bitrate player, auto-generated thumbnails
3. Set up Razorpay with webhook handlers in Next.js API routes — subscription lifecycle written to Supabase
4. Added OpenAI API layer — course outline suggestions and auto-generated quizzes from lesson transcripts via GPT-4

---

### 03 · KETE — kernelectech.in

> **Live →** [kernelectech.in](https://kernelectech.in) | `HTML` `CSS` `JS` `Vercel` `GoDaddy DNS` `GA4`

End-to-end build and deployment of a corporate website for **Kern Elec Tech Experts** — an electrical, instrumentation, and solar energy company. Delivered everything: code, deployment, domain, email, analytics, and SEO.

**Before →**
- No web presence at all
- No domain, no professional email
- No analytics or search visibility
- All inquiries managed via WhatsApp

**After →**
- Full site live on `kernelectech.in`
- Vercel deployment + GoDaddy A record + CNAME configured
- MX records for GoDaddy Workspace Email (`contact@kernelectech.in`)
- GA4 + Google Search Console — sitemap submitted and indexed
- SEO-ready: semantic HTML, meta tags, structured data

**How I built it →**
1. Built the full site in plain HTML/CSS/JS — no framework overhead, lean, fast, self-maintainable
2. Deployed on Vercel, configured GoDaddy DNS — A record to Vercel IP, CNAME for `www` subdomain
3. Set up MX records for GoDaddy Workspace Email so client can send from their own domain
4. Created GA4 property, submitted XML sitemap to Search Console, verified domain ownership

---

### 04 · P2P Energy Trading — Solana DApp

> **IEEE ICRITO 2025** | `Solana` `Anchor` `TypeScript` `React` `Web3.js` `Phantom Wallet`

A peer-to-peer energy trading system on Solana blockchain — combining original research with a working DApp. Prosumers list surplus energy, consumers bid in real time, all settled on-chain without a utility intermediary.

**Research Gap →**
- Energy markets rely entirely on central utility intermediaries
- High settlement fees, slow clearing cycles
- No trustless P2P solution at micro-transaction scale
- Ethereum too slow and expensive for energy micro-trades

**Solution Built →**
- Anchor smart contracts — energy listing, bid submission, trade settlement
- Phantom Wallet — connect, sign, and execute energy trade transactions
- Sub-cent fees, ~400ms finality on Solana
- On-chain matching + off-chain React dashboard with live trade feed
- Published and presented in **IEEE proceedings at ICRITO 2025**

**How I built it →**
1. Chose Solana over Ethereum for ~65k TPS throughput and sub-cent fees — critical for energy micro-transactions
2. Wrote smart contracts using Anchor framework — listing, bid, and settlement programs deployed to devnet
3. Built Phantom Wallet integration with `@solana/wallet-adapter` — connect, sign, read on-chain state
4. Designed React dashboard — live trade feed, wallet balance, transaction history from Solana RPC

---

### 05 · Tapodhani — Vastu Consultancy Site

> **Live →** [creative-states-818272.framer.app](https://creative-states-818272.framer.app) | `Framer` `Cal.com` `Framer CMS`

Brand and booking site for a Vastu consultancy practice. Needed to feel calm, trustworthy, spiritual — with a fully automated booking flow.

**Client Brief →**
- No existing brand identity or website
- Bookings managed manually via calls and WhatsApp
- Client non-technical — site must be self-maintainable

**What I Delivered →**
- Full Framer site: Home, Services, About, Blog, Contact
- Hero: *"Align Your Space, Align Your Life"* — full-bleed imagery, CTA above the fold
- **Cal.com** booking embed — zero manual coordination for appointments
- Stats: 80% repeat consultations · 10+ yr avg consultant experience · 70% remedy adoption
- Testimonials, team, philosophy, and services sections

**How I built it →**
1. Chose Framer CMS — client updates blog posts, team bios, and services without any developer help
2. Designed brand identity — calm, earthy tones, spiritual but modern, full-bleed photography
3. Embedded Cal.com booking widget — clients schedule consultations with zero back-and-forth
4. Built all 5 pages with Framer CMS powering the Blog so client publishes articles independently

---

### 06 · The Design Edit — Portfolio Site

> `HTML` `CSS` `Canvas API` `Vanilla JS` · *Zero external dependencies*

Single-file portfolio for **Sumit Chander** — a floral and event designer. Cinematic and immersive, delivered as one HTML file with no external dependencies and images extracted from a PDF brief.

**Constraints →**
- Single deliverable — one HTML file, no folders, no CDN
- All images came from a PDF brief only
- Zero external libraries
- Needed to feel high-end, not template-like

**What I Built →**
- **Canvas scrub hero** — image sequence driven by scroll position using lerped frame index
- **3D card tilt** — `mousemove` calculates `rotateX/Y` from cursor offset relative to card center
- **Magnetic cursor** — custom cursor tracks mouse via lerp, snaps to interactive elements
- **Base64-embedded images** — truly zero dependencies, single file delivery

**How I built it →**
1. Extracted all images from the PDF, optimized them, base64-encoded each one directly into HTML
2. Built canvas scrub hero — image sequence into `<canvas>`, frame index driven from scroll position
3. Added 3D card tilt — `mousemove` listener drives CSS `perspective` transform in real time
4. Built magnetic cursor — `div` tracks mouse via lerp, snaps with distance-based attraction force

---

## Work Experience

| Period | Role | Company |
|--------|------|---------|
| 2024 – Present | Shopify Developer | MERCI Dehradun · Freelance |
| 2023 – 2024 | Software Developer | SMARRTIF AI · Sole dev on Vision 1000 |
| 2022 | Frontend Developer Intern | IIT Delhi |
| 2021 | Frontend Developer Intern | BIJAK |

---

## Research and Publication

**P2P Energy Trading Using Solana Blockchain**
*IEEE ICRITO 2025 · Presented and Published*

Proposed and implemented a decentralised peer-to-peer energy trading model using Solana smart contracts — demonstrating trustless, low-latency energy markets without utility intermediaries. Chose Solana for ~65k TPS throughput and sub-cent transaction fees, making it viable for energy micro-transactions at scale.

---

## Education

| Degree | Institution | Year |
|--------|-------------|------|
| MCA — Master of Computer Applications | Amity University | 2023–2025 |
| BCA — Bachelor of Computer Applications | GGSIPU | 2018–2021 |

---

<div align="center">

**Open to freelance projects and full-time roles**

`Shopify` · `Next.js` · `Full-stack` · Remote or Gurugram

[![Portfolio](https://img.shields.io/badge/kartiksharma.io-000000?style=for-the-badge&logo=safari&logoColor=white)](https://kartiksharma.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kartik-sharma)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kartik010)

</div>
