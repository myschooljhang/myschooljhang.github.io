# MySchool Jhang — Official Website

<div align="center">

![MySchool Jhang](https://img.shields.io/badge/MySchool-Jhang-1f303b?style=for-the-badge)
![AI School](https://img.shields.io/badge/AI-School-db1e27?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-ee9928?style=for-the-badge&logo=github)
![Bilingual](https://img.shields.io/badge/Bilingual-EN%20%2F%20%D8%A7%D8%B1%D8%AF%D9%88-1f303b?style=for-the-badge)

**🌐 Live Site:** https://myschooljhang.github.io/myschool

**📱 Learning Portal:** https://massabfarooq.pythonanywhere.com

*Jhang's first AI School — Playgroup to Class 8 · Grow With Us*

</div>

---

## 🏫 About

**MySchool Jhang** is Jhang's first AI-powered school, founded by **Massab Farooq**. It combines Oxford & Cambridge traditional subjects with world-class AI courses adopted from MIT, Stanford, OpenAI Academy, and AI4K12 — delivered through a live online learning portal serving students from Playgroup to Class 8.

**📍 Address:** 27 Lalazar, Satellite Town, Jhang, Punjab, Pakistan

---

## ✨ Website Features

### 🎨 Design & UX
- **Brand identity** — Navy `#1f303b` · Crimson `#db1e27` · Gold `#ee9928` (extracted from school logo)
- **School logo** embedded in nav, hero card, footer, why-us section, and CTA band
- **Typography** — Playfair Display (English headings) · Gulzar (Urdu headings) · AlviNastaleeq (Urdu body) · DM Sans (English body)
- **Fully responsive** — mobile, tablet, desktop

### 🇵🇰 Bilingual (English / اردو)
- Full **EN ↔ اردو toggle** with RTL layout support
- Urdu uses authentic **Nastaleeq typography** — Gulzar for headings, AlviLahoriNastaleeq for body
- Language preference **saved in localStorage** — persists across visits
- All sections, nav, footer, chatbot, and course cards fully translated

### 📢 News & Announcements
- **Scrolling ticker** (crimson bar) with live announcements
- **Featured news card** + 3 supporting cards in editorial grid layout
- Direct links to Facebook page for full updates

### 🎓 Two-Track Curriculum

#### Track 1 — Traditional Subjects (Oxford / Cambridge)

| Subject | Framework |
|---------|-----------|
| Mathematics | Cambridge Primary |
| Science | Cambridge Science |
| English | Oxford English |
| Urdu | National Curriculum |
| Islamiat | Pakistan Curriculum |
| Social Studies | Oxford Studies |
| Computer Science | Cambridge ICT |
| Art & Design | Cambridge Arts |

#### Track 2 — AI Courses (World-Class)

| Course | Source | Classes |
|--------|--------|---------|
| AI in My World | MIT Media Lab | PG–Class 2 |
| Scratch & Block Coding | MIT Scratch / CSTA AI4K12 | Class 3–5 |
| Machine Learning for Kids | Google Teachable Machine + IBM ML4Kids | Class 4–6 |
| AI Prompt Engineering | OpenAI Academy K-12 | Class 3–8 |
| Robotics & Automation | Univ. of Florida K-12 + AI4K12 | Class 6–8 |
| Python for AI Beginners | CSTA Standards | Class 7–8 |
| AI Ethics & Digital Citizenship ★ | California CDE + CSTA 2025 | All classes |
| Data Literacy & Thinking | WEF Future Skills 2030 | Class 6–8 |

### 📐 Classes Covered

```
Playgroup → Nursery → Prep → Class 1 → Class 2 → Class 3 → Class 4
→ Class 5 → Class 6 → Class 7 → Class 8
```

### 🏅 Verified Credentials
- **7 official Credly badge embeds** — founder Massab Farooq's verified digital certifications
- Displayed using official Credly embed API (single `embed.js` script)
- Each badge independently verifiable at [credly.com/users/massab-farooq](https://www.credly.com/users/massab-farooq)
- Tamper-proof, cryptographically verified by Pearson/Credly

### 🤖 AI Parent Chatbot
- Floating chat button — bottom-right corner of every page
- Powered by **Claude AI (claude-sonnet-4-20250514)**
- Knows full school context: address, classes, AI courses, registration process
- **Bilingual** — detects Urdu/English and replies in the same language
- 5 quick-tap suggestion pills for common parent queries
- Typing indicator, message history, fallback to Facebook on error

### 📍 Contact Section
- Address: 27 Lalazar, Satellite Town, Jhang
- Phone / WhatsApp link
- Google Maps deep link
- Learning portal and Facebook links

### 📲 Social Media

| Platform | Handle |
|----------|--------|
| Facebook | [@MySchoolJhang](https://www.facebook.com/MySchoolJhang/) — 2,381+ likes |
| TikTok | [@myschooljhang1](https://www.tiktok.com/@myschooljhang1) |
| Instagram | [@bestschooljhang](https://www.instagram.com/bestschooljhang) · [@myschooljhang](https://www.instagram.com/myschooljhang) |
| GitHub | [myschooljhang](https://github.com/myschooljhang) |

---

## 🚀 Deployment

This site deploys **automatically** via GitHub Actions on every push to `main`.

### First-time setup (one time only)

1. Go to [github.com/myschooljhang/myschool](https://github.com/myschooljhang/myschool)
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select **GitHub Actions**
4. Click **Save**

Every future push to `main` auto-deploys within ~60 seconds.

**Live URL:**
```
https://myschooljhang.github.io/myschool
```

### How auto-deploy works

```
Push to main
    ↓
GitHub Actions triggered  (.github/workflows/deploy.yml)
    ↓
checkout → configure-pages → upload-artifact → deploy-pages
    ↓
Live at https://myschooljhang.github.io/myschool ✅
```

---

## 📁 Project Structure

```
myschool/
├── index.html                  ← Entire website (single self-contained file)
│                                 Includes: HTML · CSS · JS · logo (base64)
│                                 Credly badges · AI chatbot · bilingual content
├── .github/
│   └── workflows/
│       └── deploy.yml          ← GitHub Actions auto-deploy to GitHub Pages
└── README.md                   ← This file
```

> **Why a single file?** Zero build tools. Zero npm. Zero dependencies.
> The entire website loads from one `index.html` — upload anywhere, works everywhere.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 (semantic) |
| Styling | Pure CSS3 — variables, Grid, Flexbox, animations |
| Interactivity | Vanilla JavaScript (ES6+) |
| English Fonts | Google Fonts — Playfair Display, DM Sans |
| Urdu Fonts | Google Fonts — Gulzar (headings) · jsDelivr CDN — AlviNastaleeq (body) |
| AI Chatbot | Anthropic Claude API (`claude-sonnet-4-20250514`) |
| Credentials | Credly Official Embed API |
| Deployment | GitHub Actions → GitHub Pages |
| Dependencies | Zero npm packages |

---

## 🔗 All Links

| Resource | URL |
|----------|-----|
| 🌐 Website | https://myschooljhang.github.io/myschool |
| 📱 Learning Portal | https://massabfarooq.pythonanywhere.com |
| 🏅 Credly Profile | https://www.credly.com/users/massab-farooq |
| 📘 Facebook | https://www.facebook.com/MySchoolJhang/ |
| 🎵 TikTok | https://www.tiktok.com/@myschooljhang1 |
| 📸 Instagram | https://www.instagram.com/bestschooljhang |
| 🐙 GitHub | https://github.com/myschooljhang |

---

## 📋 Changelog

| Version | What Changed |
|---------|-------------|
| v1.0 | Initial website — hero, subjects, app promo, social, footer |
| v1.1 | GitHub Pages deployment + auto-deploy workflow |
| v1.2 | Urdu/English toggle · AlviNastaleeq font · Gulzar headings |
| v1.3 | Brand redesign — logo colors extracted · school logo embedded · Playgroup–Class 8 |
| v1.4 | News & Announcements section · scrolling ticker |
| v1.5 | Contact section — 27 Lalazar, Satellite Town, Jhang |
| v1.6 | Credly credentials section — 7 official badge embeds |
| v1.7 | AI parent enquiry chatbot — Claude-powered, bilingual |
| v1.8 | Two-track curriculum — Traditional (Oxford/Cambridge) + AI courses (MIT/Stanford/AI4K12) |
| v1.9 | AI School rebrand — "Grow With Us" tagline throughout |

---

<div align="center">

© 2026 MySchool Jhang · A **Massab Farooq** Initiative · AI School · Grow With Us 🇵🇰

*27 Lalazar, Satellite Town, Jhang, Punjab, Pakistan*

</div>
