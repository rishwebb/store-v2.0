<div align="center">

<img src="https://raw.githubusercontent.com/rishwebb/store-v2.0/main/assets/preview-hero.png" alt="Prismon Boutique Hero" width="100%" style="border-radius: 12px; margin-bottom: 24px;" />

# ✦ PRISMON BOUTIQUE ✦

**A premium, editorial-style e-commerce storefront built entirely with vanilla technologies.**

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/LocalStorage-4A154B?style=for-the-badge&logo=databricks&logoColor=white" alt="LocalStorage" />
</p>

<p align="center">
  <a href="https://www.instagram.com/erro_rcodee" target="_blank"><img src="https://img.shields.io/badge/Follow_Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="https://www.youtube.com/@Bingxxo" target="_blank"><img src="https://img.shields.io/badge/Subscribe_YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white" alt="YouTube" /></a>
  <a href="https://portfolio-rishav.pages.dev/" target="_blank"><img src="https://img.shields.io/badge/View_Portfolio-9370DB?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
</p>

[Explore Features](#-key-features) • [Installation](#-quick-start) • [Architecture](#-architecture) • [Design System](#-design-system)

</div>

<br />

> **The Philosophy**: "What if we could build an ultra-premium, interactive e-commerce experience without a single npm dependency, build step, or complex frontend framework?" Prismon Boutique is the answer. It proves that raw HTML, CSS, and Vanilla JavaScript can still deliver a Vogue-level, buttery-smooth user experience.

---

## ✨ Overview

**Prismon Boutique** is a fully functional, zero-backend Single Page Application (SPA). Designed with a high-end editorial aesthetic, it blends pristine whites, rich typography, and subtle lavender accents into a luxurious digital storefront. 

Everything you interact with—from the persistent shopping cart and multi-step checkout to the context-aware live chatbot—runs entirely client-side, powered by pure Vanilla JavaScript and `localStorage`.

<div align="center">
  <img src="https://raw.githubusercontent.com/rishwebb/store-v2.0/main/assets/preview-catalog.png" alt="Product Catalog Grid" width="100%" style="border-radius: 12px; margin-top: 16px; margin-bottom: 24px;" />
</div>

---

## 💎 Key Features

### 🛍️ Immersive Shopping Experience
- **Dynamic SPA Routing:** Hash-based navigation (`#home`, `#catalog`, `#category/:name`, `#checkout`) for instant page transitions without reloads.
- **Premium Catalog:** Browse exquisite skincare items with real-time filtering and sorting.
- **Quick-View Modals:** Intelligently designed product overlays with stock indicators and animated add-to-cart states.
- **Persistent Cart:** A `localStorage`-backed side-drawer cart that survives browser refreshes and tab closures.
- **Multi-Step Checkout:** A flawless journey from _Shipping_ → _Payment_ → _Review_ → _Animated Order Confirmation_.

### 🤖 Intelligent Chatbot
- **Context-Aware:** A live custom widget capable of answering questions about shipping, returns, ingredients, and tracking.
- **Polished UI:** Features smooth typing indicators, elegant message bubbles, and auto-hides gracefully when the cart opens.

### 🧩 Robust Multi-Page Architecture
- **7-Page Ecosystem:** Includes Home (SPA), About, Contact, Shipping & Returns, FAQs, Privacy Policy, and Terms.
- **Modular Assets:** Externalized CSS and JS guarantee absolute consistency for the navigation bar, footer, and global states across every single HTML file.
- **Connected Footer:** Fully wired customer care links and social media integrations opening in new tabs.

### 💅 Flawless UX Details
- **Toast Notifications:** Dynamic alerts for success, error, and cart actions.
- **Responsive Mastery:** Meticulously crafted to be mobile-first while expanding beautifully on ultrawide desktop monitors.
- **Testimonials:** Elegant verified-buyer review cards that build trust instantly.

---

## 🚀 Quick Start

Getting started is breathtakingly simple. 

**Zero build steps. Zero dependencies.**

```bash
# 1. Clone the repository
git clone https://github.com/rishwebb/store-v2.0.git

# 2. Enter the directory
cd store-v2.0

# 3. Serve literally any way you want (Example using npx)
npx -y serve . -l 3000
```
*Then simply open `http://localhost:3000` in your browser.*

---

## 🏗️ Architecture

```text
eshop/
├── index.html          # SPA shell (Home, Catalog, Checkout)
├── about.html          # Brand story & values
├── contact.html        # Interactive contact form
├── shipping.html       # Shipping & returns policy
├── faqs.html           # Interactive accordion FAQs
├── privacy.html        # Privacy policy
├── terms.html          # Terms of service
├── css/
│   └── styles.css      # Custom animations, transitions & overrides
├── js/
│   └── main.js         # The entire application engine (Singleton logic, routing, DOM rendering)
└── assets/
    └── preview-*.png   # High-res README screenshots
```

---

## 🎨 Design System

We believe in the power of restraint. By carefully selecting a minimal but striking palette, the products speak for themselves.

<table align="center">
  <tr>
    <td align="center"><b>Color</b></td>
    <td align="center"><b>Hex</b></td>
    <td align="center"><b>Usage</b></td>
  </tr>
  <tr>
    <td align="center">🤍 <b>Pure White</b></td>
    <td align="center"><code>#FFFFFF</code></td>
    <td>Global backgrounds, cards, glass elements.</td>
  </tr>
  <tr>
    <td align="center">🖤 <b>Rich Charcoal</b></td>
    <td align="center"><code>#1F2937</code></td>
    <td>Primary typography, bold headings.</td>
  </tr>
  <tr>
    <td align="center">💜 <b>Elegant Lavender</b></td>
    <td align="center"><code>#9370DB</code></td>
    <td>Primary CTA buttons, active states, highlights.</td>
  </tr>
  <tr>
    <td align="center">✒️ <b>Playfair Display</b></td>
    <td align="center"><i>Serif</i></td>
    <td>Logo, section headers, premium accents.</td>
  </tr>
  <tr>
    <td align="center">📝 <b>Inter</b></td>
    <td align="center"><i>Sans-Serif</i></td>
    <td>Body text, UI elements, button labels.</td>
  </tr>
</table>

- **Shapes:** Pill-shaped (`rounded-full`) buttons and heavily rounded (`rounded-3xl`) cards for a soft, inviting feel.
- **Motion:** Subtle hover lifts, smooth fade-ins, and delicate slide animations on all interactive elements.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE). 

---

<div align="center">

**[View Portfolio](https://portfolio-rishav.pages.dev/)** • **[Follow on Instagram](https://www.instagram.com/erro_rcodee)** • **[Subscribe on YouTube](https://www.youtube.com/@Bingxxo)**

<br/>

*Crafted with precision & passion by <b>Rishav</b>*
</div>
