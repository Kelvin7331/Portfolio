# Kelvin Mwichwiri — Personal Portfolio Website

<div align="center">

![Portfolio Preview](Portfolio.jpeg)

**Full Stack Developer · Network Engineer · IT Specialist**

*Founder, [Kelvinet Technologies](https://kelvinettechnologies.netlify.app) · Maua, Meru, Kenya*

[![Live Site](https://img.shields.io/badge/Live%20Site-Visit-0aefb5?style=for-the-badge&logo=googlechrome&logoColor=000)](https://kelvin7331.github.io/Portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kelvin-mwichwiri-969296307)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kelvin7331)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kelvinmwichwiri1@gmail.com)

</div>

---

## Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [Sections](#-sections)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Customisation Guide](#-customisation-guide)
- [Performance](#-performance)
- [Accessibility](#-accessibility)
- [Browser Support](#-browser-support)
- [Contact](#-contact)
- [License](#-license)

---

## 📌 Overview

A modern, fully responsive **personal portfolio website** built with pure HTML5, CSS3, and Vanilla JavaScript — no frameworks, no dependencies, no build step required. Designed with a **dark editorial aesthetic**, the site showcases professional skills, featured projects, services, and client testimonials while maintaining fast load times and top-tier accessibility.

> *"Deciphering Complexity, Creating Simplicity."* — Kelvin Mwichwiri

---

## 🌐 Live Demo

> https://kelvin7331.github.io/Portfolio/
---

## ✨ Features

| Feature | Description |
|---|---|
| 🌙 **Dark Editorial Theme** | Deep navy-black background with teal accent (`#0aefb5`) |
| 📱 **Fully Responsive** | Mobile-first layout using CSS Grid and Flexbox |
| 🎬 **Scroll Animations** | `IntersectionObserver`-powered reveal with staggered delays |
| 🧭 **Smart Navbar** | Hides on scroll-down, reappears on scroll-up, glassmorphic on scroll |
| 📊 **Animated Skill Bars** | Progress bars and counters animate only when in viewport |
| 🎨 **Ambient Hero** | CSS blob animation + grid overlay background |
| 💬 **Contact Form** | Client-side validated form with `mailto:` fallback |
| ♿ **Accessible** | ARIA roles, labels, live regions, semantic HTML5 |
| ⚡ **Zero Dependencies** | Pure HTML/CSS/JS — no npm, no bundler, no framework |
| 🔝 **Back-to-Top** | Smooth scroll button that appears after 400px scroll |
| 🖱️ **Hover Interactions** | Cards lift, images zoom, buttons glow on hover |
| 🔠 **Custom Fonts** | Syne (display) + DM Sans (body) via Google Fonts |

---

## 📋 Sections

### 1. Hero
Full-viewport landing section with animated ambient blobs, CSS grid overlay, avatar with pulsing ring, a headline, role descriptor, call-to-action buttons, and a quick-stats row (Years Experience, Projects Delivered, Certifications).

### 2. About
Two-column layout featuring a profile photo with a spinning dashed accent ring, a personal bio, certifications displayed as pill tags (CCNA, HCIA, CCNP, Google IT Support), and a downloadable resume button.

### 3. Skills
Categorised skill cards with animated progress bars and proficiency counters, grouped into **Technical Skills** (Web Development, Networking & Security, IT Support, Database Management, Tools & Platforms) and **Professional Skills** (Collaboration, Problem-Solving).

### 4. Projects
A responsive project grid featuring:
- **Kelvinet E-commerce Platform** — AI chatbot + secure payments
- **e-DocSafe Platform** — Document management with Firebase + IndexedDB
- **SmartVendor POS** — Real-time POS with analytics
- **Smart IT Helpdesk Chatbot** — AI-powered IT support & ticketing
- **Portfolio Website** — This site

Each card includes an image thumbnail with hover zoom + overlay, description, and links to live demo and GitHub.

### 5. Services
Icon-led service cards covering Web Development, Networking Solutions, IT Support & Consultancy, and AI & Automation.

### 6. Testimonials
Client review cards with quote marks, star ratings, client avatars, company logos, and role descriptions.

### 7. Contact
Two-column layout — direct contact methods (Phone, WhatsApp, Email) + social links on the left; a validated contact form on the right. The form constructs and opens a pre-filled `mailto:` link on submit.

### 8. Footer
Minimal branding footer with dynamic copyright year.

---

## 🛠️ Tech Stack

```
HTML5          — Semantic markup, ARIA accessibility attributes
CSS3           — Custom properties, Grid, Flexbox, keyframe animations
Vanilla JS     — IntersectionObserver, scroll events, form handling
Google Fonts   — Syne (700/800) + DM Sans (300–600)
Font Awesome   — v6.5.0 icon library (CDN)
```

No build tools. No package manager. No framework. Drop the files in a folder and open `index.html`.

---

## 📁 Project Structure

```
portfolio/
│
├── index.html              # Main HTML — all sections
├── style.css               # All styles — variables, layout, animations
├── README.md               # This file
│
├── Kelvin-Logo.jpg         # Favicon + navbar logo
├── Pic_file.png            # Hero & about section photo
│
├── e-commerce-platform.jpeg    # Project thumbnail
├── e-DocSafe_Pro.jpeg          # Project thumbnail
├── project-SmartVendor.jpeg    # Project thumbnail
├── Helpdesk-chatbot.jpeg       # Project thumbnail
├── Portfolio.jpeg              # Project thumbnail
│
├── Firefly.jpg             # Testimonial client avatar
├── client3.jpg             # Testimonial client avatar
├── Picsart_client.jpg      # Testimonial client avatar
├── client5.png             # Testimonial client avatar
│
├── Outlook-MMH.png         # Testimonial company logo
├── logo.png                # Testimonial company logo
├── 1738549562498.jpg       # Testimonial company logo
│
└── resume.pdf              # Downloadable CV (linked in About section)
```

---

## 🚀 Getting Started

### Option 1 — Open Locally

No server needed for basic viewing:

```bash
# Clone or download the project
git clone https://github.com/Cayvoh254-ke/portfolio.git
cd portfolio

# Open in browser
open index.html         # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

Or drag `index.html` into any modern browser.

### Option 2 — Local Dev Server (Recommended)

Using VS Code's **Live Server** extension:
1. Open the project folder in VS Code
2. Right-click `index.html` → **Open with Live Server**
3. Auto-reloads on file save

Using Python's built-in server:
```bash
# Python 3
python -m http.server 8080
# then visit http://localhost:8080
```

### Option 3 — Deploy

The site is static — deploy anywhere:

| Platform | Command / Steps |
|---|---|
| **GitHub Pages** | Push to `gh-pages` branch or enable Pages in repo settings |
| **Netlify** | Drag the folder to [netlify.com/drop](https://app.netlify.com/drop) |
| **Vercel** | `npx vercel` in the project directory |
| **Firebase Hosting** | `firebase init hosting` → `firebase deploy` |

---

## 🎨 Customisation Guide

All design tokens are CSS custom properties in `:root` at the top of `style.css`. Change the entire theme by editing these values:

```css
:root {
  --accent:      #0aefb5;   /* Primary brand colour (teal) */
  --accent-2:    #3b82f6;   /* Secondary accent (blue) */
  --bg:          #050b12;   /* Page background */
  --bg-card:     #0c1824;   /* Card/panel background */
  --text:        #e2eaf4;   /* Primary text */
  --text-muted:  #7a96b0;   /* Secondary text */
  --font-head:   'Syne', sans-serif;
  --font-body:   'DM Sans', sans-serif;
}
```

### Update Personal Info

| What to change | Where |
|---|---|
| Name, title, bio | `index.html` — Hero and About sections |
| Profile photo | Replace `Pic_file.png` |
| Logo | Replace `Kelvin-Logo.jpg` |
| Phone / Email / WhatsApp | Contact section `href` attributes |
| Social links | `<a>` tags in the Contact section socials row |
| Resume | Replace `resume.pdf` |
| Stats (Years, Projects, Certs) | Hero `.hero-stats` div |

### Add a New Project

Copy a `.project-card` block inside `#projects` and update:
```html
<article class="project-card reveal">
  <div class="project-thumb">
    <img src="your-image.jpg" alt="Project name screenshot" class="project-img" loading="lazy">
    <div class="project-overlay" aria-hidden="true"></div>
  </div>
  <div class="project-body">
    <h3 class="project-title">Project Name</h3>
    <p class="project-desc">Short description of what it does and the value it delivers.</p>
    <div class="project-links">
      <a href="https://demo-link.com" target="_blank" rel="noopener" class="project-link demo-link">
        <i class="fas fa-arrow-up-right-from-square"></i> Live Demo
      </a>
      <a href="https://github.com/..." target="_blank" rel="noopener" class="project-link code-link">
        <i class="fab fa-github"></i> GitHub
      </a>
    </div>
  </div>
</article>
```

### Add a Skill Card

Copy any `.skill-card` block inside `#skills` and update the category, percentage (`data-target` + `data-width`), and tags:
```html
<div class="skill-card reveal">
  <div class="skill-icon-wrap">
    <i class="fas fa-your-icon skill-icon"></i>
  </div>
  <h3 class="skill-category">Category Name</h3>
  <div class="skill-progress-wrap">
    <span style="font-size:0.78rem;color:var(--text-muted);">Proficiency</span>
    <span class="skill-pct" data-target="85">0%</span>
  </div>
  <div class="skill-bar-track">
    <div class="skill-bar-fill" data-width="85"></div>
  </div>
  <div class="skill-tags">
    <span class="skill-tag">Tag One</span>
    <span class="skill-tag">Tag Two</span>
  </div>
</div>
```

---

## ⚡ Performance

- All images use `loading="lazy"` (deferred loading for below-fold images)
- Google Fonts loaded with `preconnect` hints to reduce DNS lookup time
- Animations are hardware-accelerated (`transform` and `opacity` only)
- Scroll listeners use `{ passive: true }` to avoid jank
- `IntersectionObserver` is used instead of scroll-position polling
- `prefers-reduced-motion` media query disables all animations for users who prefer it
- Font Awesome loaded from CDN with cache headers

---

## ♿ Accessibility

- Semantic HTML5 elements (`<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`)
- All interactive elements are keyboard-navigable
- `aria-label` on navigation, social links, buttons, and the avatar
- `aria-expanded` on the hamburger button (reflects open/closed state)
- `aria-hidden="true"` on all decorative icons and visual elements
- `aria-live="polite"` on the contact form status message
- `role="status"` on the form feedback paragraph
- Sufficient colour contrast ratios on all text/background combinations
- Skip-to-content behaviour via smooth anchor scrolling

---

## 🌍 Browser Support

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Opera 76+ | ✅ Full |
| IE 11 | ❌ Not supported |

*Requires support for CSS Custom Properties, CSS Grid, `IntersectionObserver`, and `backdrop-filter`.*

---

## 📬 Contact

**Kelvin Mwichwiri Gitonga**
Founder, Kelvinet Technologies · Maua, Meru, Kenya

| Channel | Details |
|---|---|
| 📧 Email | [kelvinmwichwiri1@gmail.com](mailto:kelvinmwichwiri1@gmail.com) |
| 📞 Phone | +254 795 064 874 |
| 💬 WhatsApp | [+254 748 816 048](https://wa.me/254748816048) |
| 🔗 LinkedIn | [linkedin.com/in/kelvin-mwichwiri-969296307](https://www.linkedin.com/in/kelvin-mwichwiri-969296307) |
| 🐙 GitHub | [github.com/Cayvoh254-ke](https://github.com/Cayvoh254-ke) |
| 📘 Facebook | [facebook.com/itz.qevoh](https://www.facebook.com/itz.qevoh) |
| 🎥 YouTube | [youtube.com/@kelvinettechnologies](https://www.youtube.com/@kelvinettechnologies) |
| 🐦 Twitter/X | [x.com/Cay_Voh254](https://x.com/Cay_Voh254) |

---

## 📄 License

```
MIT License

Copyright (c) 2025 Kelvin Mwichwiri Gitonga

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

<div align="center">

Built with purpose · Powered by technology · Made in Kenya 🇰🇪

**[⬆ Back to Top](#kelvin-mwichwiri--personal-portfolio-website)**

</div>
