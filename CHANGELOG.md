# 📦 Changelog

All notable changes to this project will be documented here.

---

## [v1.0.0] – 2025-05-04  
🔹 **Initial Release: ScrollReveal Portfolio**

### ✨ Added
- Forced Dark Mode with `class="dark"` in `<html>`
- Tailwind CDN and responsive layout
- “How I Write User Stories” section with tabbed cards:
  - “My Format” and “Real Examples”
- ScrollReveal.js integrated for animated sections
- Case Study cards with hover/scale effects
- Placeholder links for Google Drive and Figma

### 📌 Notes
- No dark/light toggle (dark mode locked)
- Optimized for recruiters and hiring managers

---

## 📍 Planned Features
- Add downloadable resume button
- Section for certifications badges with logos
- Mobile nav toggle

# 📦 Change Log

## Version: `v2.0` – Visual Grid & Certifications Upgrade  
**Date:** 2025-06-12  
**Author:** Lumier Rodriguez (FundsCatcher)

---

### 🎯 Overview

This version overhauls the layout and visual structure of the portfolio to improve content flow, highlight certifications, and showcase work examples in a more engaging, modern format.

---

### ✨ Added

- **Pill-style Sticky Navbar** with scroll-aware highlighting (ScrollSpy)
- **"My Skills" Section** moved immediately after the banner, showing:
  - Platform/tool logos (Salesforce, Python, Azure, Power BI, etc.)
  - Modern grid layout with icon/text tiles
- **"Certifications" Section** with:
  - Logos (Atlassian, Aha!, PMI, OpenAI, ServiceNow)
  - Tooltips showing full cert title
  - External links opening in new tabs
  - Placeholder tile for PMP Certification
- **"Works / Case Studies" Section**:
  - 3-column responsive visual grid
  - Instagram-style project previews
  - Hover overlays with name & subheading
  - External links open in new tabs
- **ScrollSpy JavaScript** to track and highlight nav links
- **Tooltips on Certification Tiles**

---

### ✅ Changed

- Reordered sections for logical flow:  
  `Skills → Certifications → Works → Contact`
- Replaced all emojis with real product logos via CDN
- Updated project thumbnails to use hover + fade effects

---

### 🧼 Clean-Up & Refactors

- Removed emoji icons from skills/certs
- Applied consistent spacing, shadows, and hover transitions
- Ensured all external links use `target="_blank"`

---

### 📌 Known Tasks

- PMP cert placeholder needs link
- More project thumbnails can be added to `/assets/`
- Future work: Mobile layout responsiveness & modal cert previews

---

