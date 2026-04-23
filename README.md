<div align="center">

# Kartik Sharma

**Full-Stack & Shopify Developer · Gurugram, India**

[![Portfolio](https://img.shields.io/badge/kartiksharma.io-000?style=flat-square&logo=safari&logoColor=white)](https://kartiksharma.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kartik-sharma)
[![Email](https://img.shields.io/badge/kk769sharma@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kk769sharma@gmail.com)
[![GitHub](https://img.shields.io/badge/kartik010-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kartik010)

</div>

---

```typescript
const kartik = {
  location:   "Gurugram, India",
  education:  ["MCA @ Amity University '25", "BCA @ GGSIPU '21"],
  working:    ["Shopify Dev @ MERCI Dehradun", "Freelance full-stack"],
  stack:      ["Next.js", "TypeScript", "Shopify Liquid", "Solana", "Sanity"],
  published:  "IEEE — Smart Grids on Blockchain using Solana (Aug 2025)",
  reviewed:   "Peer Reviewer @ IEEE UPCON-2025",
};
```

---

## Stats

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=kartik010&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kartik010&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

<img src="https://streak-stats.demolab.com/?user=kartik010&theme=tokyonight&hide_border=true" />

</div>

---

## Projects

---

### MERCI Dehradun — Shopify Redesign
[mercidehradun.com](https://mercidehradun.com) · `Shopify Liquid` `Prestige Theme` `CSS` `JS`

Premium lifestyle and fashion brand based in Dehradun. Brought in to audit and redesign their Shopify store — working inside the Prestige theme by Maestrooo, no platform migration.

| Before | After |
|--------|-------|
| Stale hero banners from old campaigns | Full UX audit with client issue log |
| Broken 404 on collection routes | `header.liquid` rebuilt from scratch |
| Empty alt tags sitewide | Riviera Cream editorial direction |
| Duplicated mega-menu entries | Cormorant Garamond + Jost type system |
| No typographic hierarchy | All CSS prefixed `mc-` — zero theme conflicts |

**How I built it**
1. UX audit — documented every broken route, missing asset, and UX failure
2. Defined the Riviera Cream direction studying bonadea.com and goodearth.in
3. Rebuilt `header.liquid` + `merci-header.css/js` from scratch, all `mc-` prefixed
4. Redesigned homepage — hero, collection grid, editorial strips

---

### Vision 1000 — EdTech LMS
[vision1000.in](https://vision1000.in) · `Next.js 14` `TypeScript` `Clerk` `Mux` `Sanity` `Razorpay` `OpenAI`

Built solo at SMARRTIF AI. 3 courses, 21 lessons, $59/course, AI student assistant. Greenfield to production.

| Brief | Shipped |
|-------|---------|
| No existing product, no team | Clerk — SSO, magic links, role-based access |
| Video streaming at scale | Mux — adaptive streaming, 21 lessons |
| Per-course purchases | Razorpay — payments + webhooks |
| Content management | Sanity CMS — courses, instructors, blog |
| AI features | OpenAI — student assistant chatbot |

**How I built it**
1. Next.js 14 App Router + TypeScript — Server Components for speed, Client for interactivity
2. Mux upload pipeline — pre-signed URLs to Mux ingest, adaptive bitrate player
3. Razorpay webhook handlers in API routes — purchase events write to Supabase
4. OpenAI — chatbot that answers student questions scoped to course content

---

### KETE — kernelectech.in
[kernelectech.in](https://kernelectech.in) · `HTML5` `CSS3` `GSAP` `SVG` `Vercel` `GoDaddy DNS`

Corporate site for an electrical, instrumentation and solar energy company. Dark industrial aesthetic, delivered end-to-end.

| Before | After |
|--------|-------|
| No web presence | Full site with dark industrial design |
| No domain or email | Interactive India–Nepal SVG project map |
| No analytics | GSAP scroll-triggered animations |
| Leads via WhatsApp only | Partner logo carousel |
| | GA4 + Search Console + MX email |

**How I built it**
1. Plain HTML/CSS/JS + GSAP — no framework, fast, lean, self-maintainable by client
2. Built interactive SVG map of India–Nepal showing real project locations
3. Vercel deployment + GoDaddy DNS — A record, CNAME, MX records for Workspace Email
4. Delivered end-to-end: AI-generated logo, blog system, 6+ real project portfolios

---

### P2P Energy Trading — Solana DApp
`Solana` `Anchor` `Next.js` `TypeScript` `Phantom Wallet` `Web3.js`

**IEEE Published** — Smart Grids on Blockchain Using Solana as a Ledger (Aug 2025)
**Peer Reviewer** — IEEE UPCON-2025

| Research Gap | Solution |
|-------------|----------|
| Energy markets rely on central intermediaries | Anchor smart contracts on Solana |
| High fees, slow settlement | Phantom Wallet — connect, sign, execute |
| No trustless P2P at micro-scale | Sub-cent fees, ~400ms finality |
| Ethereum too slow and expensive | On-chain matching + React dashboard |

**How I built it**
1. Chose Solana — ~65k TPS + sub-cent fees, viable for energy micro-transactions
2. Anchor framework — listing, bid, and settlement programs on devnet
3. `@solana/wallet-adapter` — Phantom connect, sign, read on-chain state
4. React dashboard — live trade feed, wallet balance, transaction history from Solana RPC

---

### Tapodhani — Vastu Consultancy
[creative-states-818272.framer.app](https://creative-states-818272.framer.app) · `Framer` `Cal.com` `Framer CMS`

Brand and booking site for a Vastu consultancy. Spa-like feel, fully automated bookings post-launch.

- 5 pages: Home, Services, About, Blog, Contact
- Cal.com embed — clients book consultations with zero back-and-forth
- Framer CMS — client publishes blog posts independently, no dev needed
- 80% repeat clients · 10+ yr avg consultant experience · 70% remedy adoption

---

### The Design Edit — Portfolio
`HTML5` `CSS3` `Canvas API` `Vanilla JS` · Zero dependencies · Single file

Portfolio for floral and event designer Sumit Chander. One HTML file, no libraries, images from a PDF brief.

- Canvas scrub hero — scroll-driven frame-by-frame sequence
- 3D card tilt — `mousemove` drives `rotateX/Y` perspective transform
- Magnetic cursor — lerp-tracked, distance-based snap to interactive elements
- Base64-embedded images — truly zero dependencies

---

### NJ Interior — Interior Design Website
`Next.js` · 100/100 Lighthouse SEO · 10+ scroll animations

Performance-optimized interior design site with a perfect Lighthouse SEO score.

---

## Experience

```
Dec 2025 – Mar 2026   Software Developer       SMARRTIF AI      Built Vision 1000 solo end-to-end
Jan 2025 – Nov 2025   Frontend Dev Intern      SMARRTIF AI      30% load time reduction, chatbot + email flows
Jun 2025 – Jul 2025   Research Intern          IIT Delhi        Next.js UI components, 25% page transition reduction
Oct 2022 – Jan 2023   SDE-1 Frontend Intern    BIJAK            90+ Lighthouse scores across 4 production sites
2024 – Present        Shopify Developer        MERCI Dehradun   Freelance
```

---

## Stack

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Shopify](https://img.shields.io/badge/Shopify-96BF48?style=flat-square&logo=shopify&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white)
![Sanity](https://img.shields.io/badge/Sanity-F03E2F?style=flat-square&logo=sanity&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Framer](https://img.shields.io/badge/Framer-0055FF?style=flat-square&logo=framer&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)
![Mux](https://img.shields.io/badge/Mux-000?style=flat-square&logo=mux&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-02042B?style=flat-square&logo=razorpay&logoColor=3395FF)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## Research

**Smart Grids on Blockchain Using Solana as a Ledger** · Published Aug 2025
Decentralised smart grid infrastructure using Solana as a trustless settlement ledger.

**Peer Reviewer — IEEE UPCON-2025**
Reviewed technical submissions for the IEEE Uttar Pradesh Section International Conference.

---

## Education

| Degree | Institution | Year | GPA |
|--------|-------------|------|-----|
| MCA | Amity University, Noida | 2025 | 6.42 / 10 |
| BCA | GGSIPU, New Delhi | 2021 | 6.4 / 10 |

---

## Certifications

- Advanced Front-End with React — DUCAT
- Industry 4.0 & IIoT — IIT Kharagpur
- Cloud IoT & Edge ML — IIT Kharagpur
- AI & Robotics — IIT Madras

---

<div align="center">

Open to freelance and full-time roles — Shopify · Next.js · Full-stack · Remote or Gurugram

[![Portfolio](https://img.shields.io/badge/kartiksharma.io-000?style=for-the-badge&logo=safari&logoColor=white)](https://kartiksharma.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kartik-sharma)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kk769sharma@gmail.com)

</div>
