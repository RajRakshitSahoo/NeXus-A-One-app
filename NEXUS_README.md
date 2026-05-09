# 🌌 NEXUS — Your Universe of Everything
### Version 2.0 · Single-File Web Application

> **One platform. Fashion. Food. Movies. Everything.**  
> A fully functional, self-contained lifestyle super-app built in a single HTML file — no frameworks, no server, no build step required.

---

## 🔗 Live Site

> Deploy your NEXUS site instantly using one of the free methods below. Once deployed, paste your live URL here:

```
🌐 Live URL: https://your-site-name.netlify.app
              (Replace with your actual URL after deployment)
```

**Recommended — Netlify Drop (60 seconds, no account needed):**
1. Go to 👉 [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag & drop `index.html` from this ZIP
3. Your live URL appears instantly — copy and share it!

---

## 📋 Table of Contents

1. [Overview](#-overview)
2. [Live Demo / Hosting](#-live-demo--hosting)
3. [Features at a Glance](#-features-at-a-glance)
4. [Sections in Detail](#-sections-in-detail)
   - [🏠 Home](#-home)
   - [👗 Fashion Shop](#-fashion-shop)
   - [🍛 Food & Dining](#-food--dining)
   - [🎬 Movies & Tickets](#-movies--tickets)
5. [Partner Integrations](#-partner-integrations)
6. [User Authentication System](#-user-authentication-system)
7. [Shopping Cart](#-shopping-cart)
8. [Design System](#-design-system)
9. [Data Sources & Datasets](#-data-sources--datasets)
10. [File Structure](#-file-structure)
11. [How to Run](#-how-to-run)
12. [How to Deploy (Free)](#-how-to-deploy-free)
13. [Browser Compatibility](#-browser-compatibility)
14. [Technical Architecture](#-technical-architecture)
15. [Known Limitations](#-known-limitations)
16. [Future Roadmap](#-future-roadmap)
17. [Credits](#-credits)

---

## 🌟 Overview

**NEXUS** is an ultra-premium, dark-themed lifestyle super-app prototype that unifies three major consumer verticals into a single seamless experience:

| Vertical | Powered By | Real Data |
|----------|-----------|-----------|
| 👗 Fashion Shopping | Amazon.in · Flipkart | Myntra dataset (44,424 products) |
| 🍛 Food Ordering | Swiggy · Zomato | Swiggy scrape (1,749 restaurants) + Paradise Biryani menu |
| 🎬 Movie Booking | District by Zomato | Curated real-time seat-booking system |

The entire app lives inside **one HTML file (`index.html`)** — open it in any browser and it works instantly, including offline for browsing and internal features.

---

## 🚀 Live Demo / Hosting

> NEXUS is a standalone HTML file. To get a shareable live URL, deploy it using any of these **free, no-code methods** — all take under 2 minutes.

### Option 1 — Netlify Drop *(Fastest, no account needed)*
1. Visit [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop `index.html` onto the page
3. Your live URL (e.g. `https://cool-name-123.netlify.app`) is ready instantly

### Option 2 — GitHub Pages *(Permanent, free)*
1. Create a new repo at [github.com](https://github.com) → name it `nexus`
2. Upload `index.html`
3. Go to **Settings → Pages → Branch: main → Save**
4. Your URL: `https://yourusername.github.io/nexus`

### Option 3 — Vercel *(Clean custom subdomain)*
1. Sign up free at [vercel.com](https://vercel.com)
2. Drag & drop the HTML file in the dashboard
3. Get a URL like `https://nexus.vercel.app`

### Option 4 — CodePen *(Instant preview link)*
1. Go to [codepen.io](https://codepen.io) → New Pen
2. Paste all HTML into the HTML pane
3. Click **Save** → share the pen URL

---

## ✨ Features at a Glance

| Feature | Status |
|---------|--------|
| 🏠 Animated hero landing page | ✅ |
| 👗 Fashion product catalog (30 products) | ✅ |
| 🔍 Search, filter & sort (fashion) | ✅ |
| 🛒 Amazon.in deep-link per product | ✅ |
| 🛍 Flipkart deep-link per product | ✅ |
| ⚡ Flash sale countdown timer | ✅ |
| 🍛 Restaurant discovery grid (20 venues) | ✅ |
| 🟠 Swiggy deep-link per restaurant | ✅ |
| 🔴 Zomato deep-link per restaurant | ✅ |
| 🍽 Full Paradise Biryani menu (31 items) | ✅ |
| 📍 City/location selector + GPS detection | ✅ |
| 🎬 8-movie cinema grid | ✅ |
| 🗺 Interactive seat map (real-time style) | ✅ |
| 🎟 District by Zomato booking link per movie | ✅ |
| 🛒 Universal cart (Fashion + Food) | ✅ |
| 🔐 User Sign In / Register (localStorage) | ✅ |
| 👤 Persistent login session | ✅ |
| 🌐 Global search across all sections | ✅ |
| 📱 Mobile responsive design | ✅ |
| 🎨 Ultra-premium dark UI | ✅ |

---

## 📱 Sections in Detail

### 🏠 Home

The landing page greets users with:
- **Animated cosmic background** — floating gradient orbs with a dot-grid overlay and subtle noise texture
- **Hero section** — large typographic headline with gradient text, three CTA buttons (Shop / Food / Movies)
- **Feature cards** — 3 glowing summary cards for each vertical with live stats (44K+ products, 1.7K+ restaurants, 8 films)
- **Feature strip** — 5 platform highlights (Fast Delivery, Secure Payments, Easy Returns, NEXUS Rewards, 24/7 Support)

---

### 👗 Fashion Shop

#### Data
Powered by the **Myntra styles dataset** (44,424 items). 30 curated products are displayed with randomly assigned realistic pricing and ratings.

#### Features
- **Partner Banner** — prominent Amazon.in and Flipkart buttons at the top of the section
- **Flash Sale Strip** — live countdown timer (resets every 12 hours)
- **Filter chips** — All, Men, Women, T-Shirts, Shirts, Kurtas, Jeans, Shoes, Watches, Bags, Sunglasses
- **Search bar** — filters by product name, color, or article type in real time
- **Sort** — by Relevance, Price (low/high), Best Discount, Top Rated
- **Load More** — paginates results (15 per page)
- **Product cards** each contain:
  - Product image (real Myntra images where available, placeholder fallback)
  - Discount badge (e.g. "40% OFF")
  - Brand / article type
  - Product name, price, MRP (struck through)
  - Star rating + review count
  - **+ ADD TO BAG** (adds to universal cart)
  - **♡ Wishlist** button (hover-reveal)
  - **🛒 Amazon** — opens Amazon.in search for that exact product in a new tab
  - **🛍 Flipkart** — opens Flipkart search for that exact product in a new tab

---

### 🍛 Food & Dining

#### Two Tabs

**Tab 1 — Restaurants**
- Powered by **Swiggy cleaned dataset** (1,749 restaurants → 20 shown)
- Partner banner with direct Swiggy and Zomato links
- City selector (Bhubaneswar, Mumbai, Delhi, Bangalore, Hyderabad, Kolkata, Chennai, Pune, Ahmedabad)
- GPS location detection button
- Cuisine filter chips (Biryani, Pizza, Burgers, Chinese, Indian, Fast Food)
- Search by restaurant name or cuisine
- Each restaurant card shows: name, cuisines, star rating, delivery time, location
- **🟠 Swiggy** and **🔴 Zomato** buttons deep-link to that restaurant

**Tab 2 — Paradise Biryani Menu**
- Full menu of **31 items** with real food photographs
- Veg / Non-Veg visual indicator (green square for veg, red triangle for non-veg)
- Item name, description, price in ₹
- **+ ADD** button (adds to universal cart)
- **Order on Swiggy** and **Order on Zomato** links per menu item

---

### 🎬 Movies & Tickets

#### Movie Grid
- 8 currently showing films (May 2026)
- Genre filter chips (All, Action, Drama, Comedy, Thriller, Sci-Fi, Horror)
- Each movie card shows: poster, title, IMDb-style rating, genre tag, certificate (U/UA/A), duration, language, format badges (2D / 3D / IMAX / 4DX)
- **Select Showtime →** opens the internal NEXUS seat-booking modal
- **🎟 Book on District by Zomato** — opens District by Zomato for that film in a new tab

#### Interactive Seat Booking (NEXUS Internal)
When a user selects a showtime:

1. **Showtime buttons** — past shows are automatically greyed out and disabled based on current time
2. **Visual seat map** — 8 rows × 14 seats with aisle gaps
3. **Three pricing tiers:**
   - PREMIUM (rows A–C) — highest price
   - EXECUTIVE (rows D–F) — mid price
   - GENERAL (rows G–H) — lowest price
4. Seats toggle between Available / Selected / Taken
5. Taken seats are deterministically generated (different per movie + showtime)
6. Max 8 seats per booking
7. **Booking summary** appears after selecting seats: Movie, Showtime, Seats, Ticket Price, Convenience Fee (15%), **Total**
8. **CONFIRM & PAY** triggers a confirmation alert with booking details

---

## 🤝 Partner Integrations

| Section | Partner | What Opens |
|---------|---------|-----------|
| Fashion | **Amazon.in** | Fashion category page |
| Fashion | **Flipkart** | Clothing & Accessories page |
| Fashion (per product) | **Amazon.in** | Search results for that exact product name |
| Fashion (per product) | **Flipkart** | Search results for that exact product name |
| Food | **Swiggy** | swiggy.com |
| Food | **Zomato** | zomato.com |
| Food (per restaurant) | **Swiggy** | Deep-link search for that restaurant |
| Food (per restaurant) | **Zomato** | Search for that restaurant |
| Food (per menu item) | **Swiggy / Zomato** | Search for that dish |
| Movies | **District by Zomato** | district.zomato.com |
| Movies (per film) | **District by Zomato** | Film-specific page on District |

---

## 🔐 User Authentication System

- **Sign Up** — name, email, password; stored in `localStorage`
- **Sign In** — email + password validation against stored user
- **Session persistence** — stays logged in on refresh via `localStorage`
- **User menu** — avatar dropdown with profile info and logout
- **Social login** — Google / Apple buttons (UI only, for prototype)

---

## 🛒 Shopping Cart

- **Universal cart** — accepts items from Fashion Shop and Food Menu
- **Slide-in drawer** — accessible from the cart icon in the navigation
- **Line items** — product name, quantity controls (+/−), price, remove button
- **Order total** — auto-calculated
- **Checkout** — placeholder button (no real payment gateway)

---

## 🎨 Design System

| Token | Value |
|-------|-------|
| Background | `#04060e` (near-black) |
| Card | `#0e1220` |
| Primary accent | `#00f5c4` (neon teal) |
| Secondary accent | `#ffb830` (warm gold) |
| Danger | `#ff2d55` (crimson) |
| Violet | `#7c3aed` |
| Text | `#f2f4ff` |
| Muted | `#5a6690` |
| Fonts | Bebas Neue (display), DM Sans (body) |
| Radii | 12px cards, 8px buttons, 50px chips |
| Shadows | Multi-layer coloured glows per section |

---

## 📁 File Structure (ZIP Contents)

```
NEXUS_Website.zip
├── index.html              ← Main app (fully self-contained)
├── NEXUS_README.md         ← This file
└── HOW_TO_DEPLOY.md        ← Step-by-step deployment guide
```

> **Note:** `index.html` is fully self-contained and works by itself. No other files are required for the app to function.

---

## ▶️ How to Run

### Standalone (Recommended)
```
1. Extract NEXUS_Website.zip
2. Double-click index.html, or open in any browser
3. Done — no installation, no internet required for core features
```

### Local Development Server (Optional)
```bash
# Python 3
cd path/to/extracted/folder
python3 -m http.server 8080
# Open http://localhost:8080
```
```bash
# Node.js (npx)
npx serve .
```

---

## 🌐 How to Deploy (Free)

> See **`HOW_TO_DEPLOY.md`** in this ZIP for detailed step-by-step instructions with screenshots guidance.

### Quick Reference

| Platform | Time | Account Needed | URL Format |
|----------|------|----------------|------------|
| Netlify Drop | ~60 sec | ❌ No | `random-name.netlify.app` |
| GitHub Pages | ~5 min | ✅ Yes (free) | `username.github.io/nexus` |
| Vercel | ~3 min | ✅ Yes (free) | `nexus-name.vercel.app` |
| CodePen | ~2 min | ❌ No | `codepen.io/pen/...` |

---

## 🌍 Browser Compatibility

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 100+ | ✅ Full |
| Firefox | 100+ | ✅ Full |
| Edge | 100+ | ✅ Full |
| Safari | 15+ | ✅ Full |
| Chrome Android | Latest | ✅ Full |
| Safari iOS | 15+ | ✅ Full |
| Internet Explorer | Any | ❌ Not supported |

---

## ⚙️ Technical Architecture

```
index.html
├── <head>
│   ├── Google Fonts CDN (Bebas Neue + DM Sans)
│   └── <style> — ~850 lines of CSS
│       ├── CSS custom properties (design tokens)
│       ├── Layout: nav, sections, hero, grids, modals, cart
│       ├── Component styles: cards, buttons, chips, seat map
│       └── Animations: fadeUp, orbDrift, shimmer, pulseGlow
│
├── <body>
│   ├── .cosmos — animated background orbs
│   ├── <nav> — sticky top navigation with auth area
│   ├── #sec-home — hero + feature strip
│   ├── #sec-shop — flash sale + product grid
│   ├── #sec-food — location bar + restaurant/menu tabs
│   ├── #sec-movie — movie grid
│   ├── #booking-modal — seat selection modal
│   ├── .cart-drawer — slide-in cart
│   └── #auth-modal — login / register modal
│
└── <script> — ~580 lines of vanilla JS
    ├── FASHION_DATA[] — 30 products (inline JSON)
    ├── FOOD_DATA{} — menu + restaurants (inline JSON)
    ├── MOVIES[] — 8 films (inline JSON)
    ├── Navigation, Cart, Shop, Food, Movies logic
    └── Auth: login, register, session management
```

**Dependencies:** Zero external JS libraries. Google Fonts only (CDN, optional).

---

## ⚠️ Known Limitations

| Limitation | Detail |
|-----------|--------|
| **No real backend** | Auth uses localStorage. Not suitable for production |
| **Password security** | Passwords stored as Base64 — prototype only |
| **Partner links** | Open partner platform's homepage/search — not actual cart pages |
| **Movie booking** | Seat data is pseudo-random, not a real ticketing backend |
| **Location detection** | GPS returns city name only |

---

## 🗺 Future Roadmap

- [ ] **Backend integration** — Node.js / Firebase for real auth and orders
- [ ] **More fashion pages** — Full 44K Myntra catalog with pagination
- [ ] **Real-time restaurant availability** — Swiggy / Zomato API
- [ ] **Payment gateway** — Razorpay / UPI integration
- [ ] **User profile page** — Order history, saved addresses
- [ ] **PWA support** — Install as app on mobile

---

## 🙏 Credits

| Resource | Source |
|---------|--------|
| Fashion dataset | Myntra Product Dataset (Kaggle) |
| Restaurant data | Swiggy restaurant scrape (Kaggle) |
| Food menu & images | Paradise Biryani menu scrape |
| Fonts | Google Fonts — Bebas Neue, DM Sans |
| Partner logos/links | Amazon.in, Flipkart, Swiggy, Zomato, District by Zomato |
| Architecture & UI | Built from scratch — no templates |

---

## 📄 License

This project is a **prototype / educational demo**. All dataset content is used for demonstration purposes only. Brand names (Amazon, Flipkart, Swiggy, Zomato, District) are trademarks of their respective owners. No commercial use is implied.

---

<div align="center">

**NEXUS** · Built with ❤️ · One Stop. Infinite Possibilities.

`v2.0` · `Single HTML File` · `Zero Dependencies` · `Works Offline`

</div>
