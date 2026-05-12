# Guta Demisu Kebede — Personal Website

> **A premium personal brand website for a mathematician, researcher, and digital educator at Dilla University, Ethiopia.**

[![Built With](https://img.shields.io/badge/Built%20With-HTML5%20%2F%20CSS3%20%2F%20JS-gold?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-teal?style=flat-square)]()
[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--1430--7367-green?style=flat-square)](https://orcid.org/0000-0002-1430-7367)

---

## 📋 Project Overview

This is the personal portfolio and academic website for **Guta Demisu Kebede**, a mathematician and lecturer at the Department of Mathematics, College of Natural and Computational Sciences, **Dilla University, Ethiopia**. The site serves as a unified professional hub for his academic research, educational content, and digital presence.

---

## ✨ Features

- **Loader animation** with mathematical symbol and progress bar
- **Sticky navbar** with scroll-based styling and active section highlighting
- **Animated hero section** with typing effect, floating math symbols, and an animated orb
- **Statistics bar** with animated counters
- **About section** with professional biography and skill tags
- **Skills cards** with animated progress bars triggered on scroll
- **Publications section** showcasing 5 peer-reviewed research papers with links
- **YouTube Studio section** (Guta Maths Studio @GMS_21) with video showcase cards
- **Social media section** (TikTok @frewon21, YouTube, ORCID, Email, LinkedIn, Telegram)
- **Achievements section** with animated counters
- **Mathematics interactive section** with equations from Guta's research domain
- **Vision & Philosophy section** with quote cards
- **Contact section** with a functional form + contact info panel
- **Responsive mobile menu** with hamburger toggle
- **Back-to-top button**
- **SEO meta tags** and **Schema.org structured data**
- **Scroll reveal animations** throughout

---

## 🛠 Technologies Used

| Layer | Technology |
|---|---|
| Markup | HTML5 (semantic) |
| Styling | CSS3 (custom properties, grid, flexbox, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Icons | Font Awesome 6.5 (CDN) |
| Fonts | Google Fonts — Playfair Display + DM Sans + DM Mono |
| Animations | Pure CSS + Intersection Observer API |
| No frameworks | Zero React / Vue / Angular dependencies |

---

## 🚀 Setup & Deployment

### Local Development

```bash
# No build step needed — open directly
open index.html
# or
npx serve .
```

### Deploy to GitHub Pages

```bash
git init
git add index.html README.md
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/guta-demisu-kebede.git
git push -u origin main
# Enable GitHub Pages in repo Settings → Pages → Branch: main
```

### Deploy to Netlify

1. Drag and drop the folder at [app.netlify.com](https://app.netlify.com)
2. Or connect the GitHub repo for automatic deploys

### Deploy to Vercel

```bash
npx vercel --yes
```

---

## 🎨 Customization Guide

### Color Tokens (in `:root`)

```css
--gold:   #c9a84c   /* Primary accent — headers, highlights */
--teal:   #2ec4b6   /* Secondary accent — tags, links */
--ink:    #0a0d14   /* Dark background */
--cream:  #f5f0e8   /* Body text */
--muted:  #7a8499   /* Secondary text */
```

Change any token and every element using it updates automatically.

### Adding Your Photo

Replace the `about-photo-placeholder` div with:

```html
<img src="your-photo.jpg" alt="Guta Demisu Kebede" style="width:100%;height:100%;object-fit:cover;" />
```

### Adding a New Publication

Copy a `.pub-card` block in the Publications section and update:
- Year in `.pub-year`
- Journal in `.pub-journal`
- Title in `.pub-title`
- Authors in `.pub-authors`
- Description in `.pub-desc`
- Link in `.pub-link`

### Updating Social Links

Search for `href="#"` placeholders and replace with real URLs for LinkedIn, Telegram, GitHub, etc.

### Updating Typed Phrases

In the JavaScript section, edit the `phrases` array:

```javascript
const phrases = [
  'Mathematics Researcher',
  'University Lecturer',
  // add your own...
];
```

---

## 🔍 SEO Optimization Notes

The site includes:

- **`<title>`** with name + keywords
- **`<meta name="description">`** — 155 characters, keyword-rich
- **`<meta name="keywords">`** — targeted academic and personal branding terms
- **Open Graph tags** for social sharing (`og:title`, `og:description`, `og:type`)
- **Schema.org Person schema** in JSON-LD with ORCID and social sameAs
- **Semantic HTML5** (`<section>`, `<nav>`, `<footer>`, `aria-label`)
- **`alt` attributes** on all meaningful images

### Recommended Next Steps for SEO

- Add `<meta property="og:image">` with a professional headshot (1200×630px)
- Register with Google Search Console
- Submit a sitemap (can be auto-generated via Netlify plugin)
- Add `lang="en"` on `<html>` (already included)

---

## 🔮 Future Improvements

- [ ] Add real YouTube API integration to pull live video thumbnails and stats
- [ ] Add a blog/notes section for mathematical writing
- [ ] Integrate a headshot photograph
- [ ] Add Google Scholar citation count via API
- [ ] Add a downloadable CV/Resume PDF button
- [ ] Implement dark/light mode toggle
- [ ] Add Disqus or Giscus for comments on research summaries
- [ ] Add multilingual support (Amharic / English)
- [ ] Add actual YouTube embed iframes for featured videos
- [ ] Connect contact form to Formspree or EmailJS for real email delivery

---

## 📦 File Structure

```
/
├── index.html       # Complete website (HTML + CSS + JS in one file)
└── README.md        # This file
```

---

## 👤 About Guta Demisu Kebede

**Guta Demisu Kebede** is a mathematician, lecturer, and researcher at:

> Department of Mathematics  
> College of Natural and Computational Sciences  
> Dilla University, Dilla, Ethiopia (P.O. Box 419)

**ORCID:** [0000-0002-1430-7367](https://orcid.org/0000-0002-1430-7367)  
**Email:** gutademisu82991@gmail.com  
**YouTube:** [Guta Maths Studio (@GMS_21)](https://www.youtube.com/@GMS_21)  
**TikTok:** [@frewon21](https://www.tiktok.com/@frewon21)

### Selected Publications

| Year | Journal | Title |
|---|---|---|
| 2025 | Taylor & Francis | A High-Order Numerical Scheme for Singularly Perturbed Parabolic Time Delay Problem |
| 2024 | BMC Research Notes / Springer | Efficient Numerical Approach for Two-Parameter Parabolic Problems |
| 2024 | Frontiers in Applied Math & Stats | Third-Degree B-Spline Collocation for Two-Parameter Problems |
| 2023 | Wiley Computational & Mathematical Methods | Fitted Numerical Approach for Two-Parameter Parabolic Problem |

---

## 📄 License

MIT License — free to use, customize, and redistribute with attribution.

---

*Built with precision — for a mathematician who bridges equations and education.*
