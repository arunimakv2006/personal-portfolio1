# ✿ Arunima KV — Personal Scrapbook Portfolio

A lightweight, playful, and expressive personal website built with HTML, CSS, and vanilla JavaScript. Designed with a custom aesthetic featuring pastel colors, decorative borders, handwritten accent typography, and interactive scrapbook elements.

---

## ✨ Features

- **Personal Scrapbook Aesthetic**: Styled using custom Google Fonts (`Fredoka`, `DM Sans`, `DM Mono`, and `Kalam`) alongside soft pastel palettes and interactive stickers/cards.
- **Dynamic Local Content Manager (Admin Modal)**: Built-in editing interface allowing fast customization of:
  - Hero header & "About Me" bio text
  - Skills collection
  - Featured projects (with support for GitHub & demo links)
  - Crafting studio gallery (supports image uploads stored in local storage)
  - Achievements and milestones
  - Contact links (Email, GitHub, LinkedIn)
- **Interactive Music Corner**: Enables users to dynamically manage a personal song wishlist locally.
- **Responsive Layout**: Designed to adapt seamlessly across desktop, tablet, and mobile screens.
- **Single-File Architecture**: Self-contained structure (`website_portfolio.html`) requiring no build tools, external web frameworks, or complex configurations to preview.

---

## 🛠️ Built With

* **HTML5** — Semantic page structure and accessibility markup.
* **CSS3** — Custom properties (variables), Grid & Flexbox layouts, keyframe animations, and micro-interactions.
* **JavaScript (ES6+)** — Client-side dynamic rendering, modal handling, and local storage persistence (`localStorage`).

---

## 🚀 Quick Start

### 1. Run Locally
Because this portfolio is built as a single, self-contained file, you don't need `npm` or local server setups to view it:
1. Download or clone this repository.
2. Double-click `website_portfolio.html` to open it in any modern web browser.

### 2. Customizing Your Content
1. Open the site in your browser.
2. Click the **"✎ Edit my site"** button in the top navigation bar or bottom-right corner.
3. Update your profile information, skills, projects, links, and crafting photos.
4. Changes are automatically saved to your browser's local storage.

---

## 📌 Deployment Notes

### Host on GitHub Pages
1. Push this repository to GitHub.
2. Rename `website_portfolio.html` to `index.html` (or set it as your root file).
3. Go to **Settings > Pages** in your GitHub repository.
4. Select `main` (or `master`) branch as the source and click **Save**.

### Upgrading to Production / Backend Integration
* **Local Storage Limits**: The built-in editor saves updates to the browser's `localStorage`. Content will not synchronize across different devices or visitors automatically.
* **Contact Form**: The current contact form acts as a local preview. To receive real emails from visitors, integrate a form backend service such as [Formspree](https://formspree.io/), [Web3Forms](https://web3forms.com/), or [EmailJS](https://www.emailjs.com/).
* **Persistent Admin**: To allow public visitors to view changes made in the editor, consider connecting a lightweight database (such as Firebase, Supabase, or Netlify CMS) and cloud image host (such as Cloudinary).

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).