<!-- Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B%2C+I'm+Prasanna+Adepu;Full-Stack+Developer+%7C+ML+Engineer;Building+things+that+ship+to+prod)](https://git.io/typing-svg)

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://portfolio-ten-chi-bsq7066miy.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adepu-prasanna)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prasannaadepu2005@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AdepuPrasanna)

---

## About Me

B.Tech CSE student (2027) · Malla Reddy Engineering College for Women, Hyderabad · CGPA 9.08

I build production-grade full-stack apps, ML pipelines, and real SaaS products — things that are deployed, used, and measured. 3 internships, 5+ shipped projects across cloud infra, OCR/AI pipelines, and REST APIs.

```
Latest internship  →  Backend Developer Intern @ Trivexa Technologies (May–Jun 2026)
Focus areas        →  Full-Stack · AI/ML · Micro-SaaS · Cloud-deployed systems
Open to            →  Internships · Collaborations · Freelance
```

---

## Tech Stack

**Languages & Frameworks**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

**Databases, Cloud & DevOps**

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**AI / ML**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=OpenCV&logoColor=white)

---

## Production Projects

### MRECW Results Portal — Full-Stack · Live

[![Live](https://img.shields.io/badge/Live-00C851?style=flat-square&logo=vercel&logoColor=white)](https://malla-reddy-women-s-engineering-res.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AdepuPrasanna/malla-reddy-women-s-engineering-results-website)

Stack: React 18 · TypeScript · Flask · Playwright · Firebase Firestore · Docker · Vercel · Render

Academic analytics platform for MRECW students — results, backlogs, class rankings, credits analysis, and SGPA/CGPA growth charts, all without login.

- Cache-first architecture: Firestore returns results in under 100 ms on a cache hit; Playwright scrapes the official exam cell portal only on a miss, saves to Firestore, and a background job keeps data fresh
- Rich analytics: per-semester SGPA/CGPA growth charts via Recharts, section-wide class rankings, backlog subject tracker, earned-vs-required credits analyzer
- Multi-stage Docker image handles the React build and Python/Playwright runtime in one file; Gunicorn on Render serves the API while Vercel CDN serves the static frontend
- Lighthouse 95+ Performance, 100 SEO, 100 Accessibility — lazy-loaded routes, vendor/charts/motion code splitting, React Query stale-while-revalidate, skeleton loaders, SSE streaming for batch class fetches
- Hall ticket search with autocomplete and persisted local history, side-by-side student comparison view, dark/light mode with persisted preference

---

### ASAF — AI-Enhanced Smart Antenatal Framework — Research · Full-Stack

[![Live](https://img.shields.io/badge/Live-00C851?style=flat-square&logo=vercel&logoColor=white)](https://asaf-two.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AdepuPrasanna/ASAF)

Stack: FastAPI · Python · Scikit-learn (Random Forest) · SQLite · React · JWT

Research prototype for pregnancy risk monitoring by Lady Health Workers in low-connectivity rural environments, documented in an academic research paper.

- Random Forest model achieves 86.2% accuracy classifying antenatal risk from patient vitals; falls back to an on-device decision tree when offline so health workers can still assess risk in the field
- Offline-first sync: patient records queued locally on disconnect, synced on reconnect via last-write-wins conflict resolution (Algorithm 1 from the paper); a built-in field conflict demo reproduces the sync scenario
- Security: PBKDF2-HMAC-SHA256 at 100,000 iterations, short-lived JWT sessions, per-user data isolation enforced at the query layer, full audit log of logins, edits, and syncs
- Three-tier RBAC: Admin for platform oversight, Health Worker for own patient records only, Patient companion view with pregnancy timelines and appointment reminders

---

### BizEase — Local Biz Digitizer — Micro-SaaS · Full-Stack

[![Live](https://img.shields.io/badge/Live-00C851?style=flat-square&logo=vercel&logoColor=white)](https://local-biz-digitizer.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AdepuPrasanna/Local-Biz-Digitizer)

Stack: React 19 · Node.js · Express · Supabase (PostgreSQL) · Tesseract.js OCR · Twilio · Docker

Mobile-first Micro-SaaS for kirana stores, cafes, and pharmacies to digitize billing, inventory, customer credit tracking, and supplier invoice processing entirely from a phone — no POS hardware needed.

- OCR invoice scanner: shop owners snap supplier invoices and Tesseract.js extracts product names, quantities, prices, and GST values, auto-updating inventory; low-confidence extractions are flagged for manual review before saving
- Instant WhatsApp receipts via Twilio API after every billing transaction — itemized bills with totals, discounts, and business contact sent directly to the customer's phone
- Khata credit ledger tracks outstanding balances, partial payments, and full transaction history per customer with real-time balance updates
- Multi-tenant security: Supabase Row Level Security ensures each shop reads and writes only its own data; JWT Auth, full Admin Console, and service_role key for safe server-side database access

---

### SafeSight — Deepfake Detection · AI Web App

[![Live](https://img.shields.io/badge/Live-00C851?style=flat-square&logo=vercel&logoColor=white)](https://safe-sight-ten.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AdepuPrasanna/safe-sight)

Stack: React · TypeScript · Vite · Supabase Edge Functions · Google Cloud Vision API · Node.js

AI-powered web app that detects deepfakes and classifies sensitive content in uploaded images.

- Google Cloud Vision API runs inference via Supabase Edge Functions, returning per-category confidence scores for deepfakes, adult content, violent material, and harassment — credentials never touch the browser
- Smart 0.6 confidence threshold filters out low-signal detections to reduce false positives; threshold is backend-configurable without frontend changes
- Drag-and-drop or click-to-upload React + TypeScript UI with a visual results dashboard showing per-category confidence bars and a final safe/flagged verdict

---

### Gridlock Hackathon 2.0 — Traffic Demand Prediction · Score 100/100

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AdepuPrasanna/Flipkart-hackthon)

Stack: Python · pandas

Flipkart Gridlock Hackathon 2.0 (HackerEarth) — traffic demand regression for Bengaluru mobility data across 41,778 test rows.

- Achieved a perfect leaderboard score of 100/100 (R² = 1.0, Submission ID: 128898705) using a spatiotemporal key-lookup approach: filter training data to the test day, build a deduplicated lookup on (geohash, day, timestamp) → demand, and merge onto the test set
- Lightweight and reproducible — full prediction pipeline runs in seconds on a laptop with no heavy model training required

---

### Phishing or Not Phishing — ML Survey & Web App

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AdepuPrasanna/Phishing-or-Not-Phishing-A-Survey-on-the-Detection-of-Phishing-Websites)

Stack: Python · scikit-learn · Flask · Jupyter Notebook

Comprehensive survey and implementation of phishing website detection using machine learning.

- Covers list-based, similarity-based, and feature-based ML classification strategies from academic literature
- Trained classification model (model.sav) distinguishes phishing from legitimate URLs based on extracted features; Flask web app accepts a URL and returns a real-time verdict
- Includes Jupyter notebook for EDA, model training, and evaluation; datasets of labeled phishing and legitimate URLs included

---

## Mini Projects & Full-Stack Practice

Six focused full-stack builds, each wiring a FastAPI + SQLite backend to a polished vanilla-JS frontend — built to practice specific backend and API concepts.

**Presence — Team Availability Tracker** · [GitHub](https://github.com/AdepuPrasanna/Team_Availability_Tracker)
Real-time availability dashboard. Toggle a switch, a PATCH request flips a boolean in SQLite, and the UI syncs back immediately. Demonstrates optimistic UI updates, audit logging via availability_log, and a stats polling endpoint that refreshes every 15 seconds.

**Paper Trail — Quick Notes App** · [GitHub](https://github.com/AdepuPrasanna/Quick_notes_application)
Full CRUD notes app with FastAPI, SQLite, and a polished single-page frontend. Supports note colours, inline editing, live client-side search, and persistent storage. Clean REST API: GET /api/notes, POST, PUT, DELETE with Pydantic validation.

**Verbatim — Quote Generator with History** · [GitHub](https://github.com/AdepuPrasanna/Quote_generator_with_history)
Fetches random quotes from the ZenQuotes external API via httpx, persists every fetch to SQLite, and displays a searchable, filterable history. Falls back gracefully to a local pool of 25 quotes when the external API is unreachable. Includes a favorites toggle and aggregate stats endpoint.

**The Cupping Board — Coffee Rating App** · [GitHub](https://github.com/AdepuPrasanna/Coffee_rating_application)
Full-stack voting app for 8 single-origin coffees. Each vote triggers a POST that runs UPDATE coffees SET votes = votes + 1, logs the event to a vote_log table, and re-ranks using a SQLite window function RANK() OVER (ORDER BY votes DESC). Optimistic UI with unvote support.

**Cardsmith — Profile Card Generator** · [GitHub](https://github.com/AdepuPrasanna/User_profile_card_generator)
Accepts form input, sends a POST to FastAPI, validates with Pydantic (required fields, username sanitization, 280-char bio limit), and returns a formatted profile card with server-derived initials, avatar colour, and card number. In-memory store; no DB needed.

**Brain Blitz — Quiz Game App** · [GitHub](https://github.com/AdepuPrasanna/Quiz_game_application)
Interactive quiz game with three question types (single-select, multi-select, fill-in-the-blank), a 20-second countdown timer per question, randomised question order, and a score ring + answer summary screen at the end. Pure HTML/CSS/JS — no build step.

---

## Internship Experience

| Period | Role | Company |
|--------|------|---------|
| May 2026 – Jun 2026 | Backend Developer Intern | Trivexa Technologies Pvt. Ltd. — recognized directly by Founder & CEO |
| Jul 2025 – Sep 2025 | Software Development Intern | Coursevita — built AI-powered OCR document scanning app (Flask, MongoDB) |
| Aug 2025 | Web Development Intern | VaultofCodes (Google for Education Partner) |

---

## Certifications

| Provider | Certifications |
|----------|----------------|
| Cisco | C, C Advanced, Python, Networks |
| Oracle | Java, SQL, Oracle Certified Professional |
| Microsoft Azure | Cloud & AI |
| Infosys | Java 2024 |
| Cambridge | English for Employability |

---

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=AdepuPrasanna&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=AdepuPrasanna&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

[![GitHub Streak](https://streak-stats.demolab.com/?user=AdepuPrasanna&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

---

## Let's Connect

Open to internships, collaborations, and freelance work in full-stack, AI/ML, and SaaS.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://portfolio-ten-chi-bsq7066miy.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adepu-prasanna)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prasannaadepu2005@gmail.com)

---

*Made with ❤️ by Prasanna Adepu*
