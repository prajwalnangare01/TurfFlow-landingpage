# TurfFlow — Your Turf. Automated.

> Modern, high-conversion landing page and interactive product showcase for **TurfFlow** — the turf booking and automation platform for sports facility operators and turf owners.

![TurfFlow Preview](logo.png)

---

## 🚀 Overview

TurfFlow automates turf bookings, payments, WhatsApp conversations, and daily operations from one centralized platform. It solves manual booking friction (endless availability queries, payment screenshot verification, double bookings, and late night calls) by giving turf owners:

- **24/7 WhatsApp AI Bot:** Automated slot availability, instant booking links, and real-time confirmations.
- **Direct Online Booking Portal:** Interactive visual slot picker with 5-minute temporary holds preventing conflicts.
- **Automated UPI & Card Payments:** 0% commission payment links with instant verification and automated WhatsApp receipt delivery.
- **Facility Operations Console:** Live pitch occupancy status, slot overrides, split-billing records, and player history.

---

## 🎨 Design & Tech Stack

- **Framework / UI:** HTML5 + Tailwind CSS (via CDN)
- **Typography:** Headings: **Geist** (650/700) • Body & UI: **Inter** (400/500/600) • Numbers & Data: **Geist Mono**
- **Icons:** [Lucide Icons](https://lucide.dev/)
- **Mobile Responsive:** 100% responsive down to 360px viewports with zero horizontal overflow
- **Error Handling:** Branded, sports-themed 404 page (`404.html`) with quick recovery navigation
- **Hosting / Deployment:** Configured for one-click deployment on [Vercel](https://vercel.com) via `vercel.json` with clean URLs and security headers

---

## ⚡ Deployment on Vercel

### Option 1: Import via Vercel Dashboard
1. Go to [vercel.com/new](https://vercel.com/new).
2. Select your repository: `prajwalnangare01/TurfFlow-landingpage`.
3. Keep default settings (Framework Preset: **Other** / Static).
4. Click **Deploy**.

### Option 2: Deploy via Vercel CLI
```bash
npm i -g vercel
vercel
```

---

## 💻 Local Development

You can run this project locally with any static web server:

```bash
# Python 3
python -m http.server 8080

# Or with Node.js
npx serve .
```

Then visit `http://localhost:8080` in your browser.

---

## 📄 License

Proprietary — All rights reserved by TurfFlow.
