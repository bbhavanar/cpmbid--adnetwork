# CPMBid — Advertising Network Platform

A full-featured advertising network that connects **publishers** (website owners who want to monetize traffic) with **advertisers**, with built-in earnings management, targeting, and fraud detection.

🔗 **Live:** [cpmbid.com](https://cpmbid.com)  ·  🧪 **Custom build (beta):** [tts.cpmbid.com](https://tts.cpmbid.com)

> ⚙️ I operate the live platform (280+ registered users, 192+ websites submitted for monetization) and am engineering a fully custom replacement platform from scratch. This repo documents the custom build.

---

## What it does

Publishers sign up, submit their websites, and place ad units to earn revenue based on CPM (cost per 1000 impressions). Advertisers deposit funds and run targeted campaigns. Admins manage the whole marketplace — rates, payouts, approvals, and fraud monitoring.

## Key Features

- **Four user roles** — publisher, advertiser, sub-admin (with granular permissions), and admin
- **Ad-serving engine** with targeting by geo, device, category, browser/OS, and time of day
- **Offline GeoIP** using MaxMind GeoLite2 (no external API dependency)
- **AI-driven CPM/CPC pricing** and real-time fraud / invalid-traffic detection
- **Payments** — PayPal, crypto, wire, and manual, with per-publisher payout controls
- **Publisher dashboard** — earnings, impressions, traffic quality score, and improvement tips
- **Admin panel** — full control over CPM rates by country, revenue share, approvals, and settings
- **Extras** — referral system, analytics charts, support tickets, anti-adblock, async JS ad tags

## Tech Stack

- **Backend:** PHP, MySQL (normalized 30+ table schema)
- **Frontend:** HTML, CSS, JavaScript, Bootstrap, AJAX
- **Infrastructure:** Runs on both shared hosting and VPS; MaxMind GeoIP; PDO database layer with file/Redis caching

## My Role

I architected the requirements, designed the database schema, and built the platform iteratively (using AI coding tools as an assistant), then handled hosting and deployment myself. I also run the live production platform day to day — onboarding, payouts, CPM configuration, and fraud monitoring.

---

*Source code kept private. Visit the live site to see the platform in action.*
