# High Street Motors

**High Street Motors** is a clean, responsive car showroom website built using **only HTML & CSS**. The design focuses on a luxury black-and-red theme to showcase premium vehicles and make browsing elegant and simple.

---

## 🔎 Project Overview

* **Purpose:** A static website to display a curated collection of luxury cars, their specs, and contact options for inquiries and test drives.
* **Built with:** HTML5 and CSS3 only — no JavaScript, frameworks, or server-side code.
* **Pages included:** Home (`index.html`), Inventory (`inventory.html`) and Contact (`contact.html`).

---

## 🚀 Features

* Responsive layout using CSS grid and flexible sizing
* Hero/header area with large visual banner
* Cards for featured cars with image, specs and price
* Inventory listing with filter-ready markup (no JS) for easy extension
* Car detail/gallery layout (single car page template)
* Contact section for inquiries and test drive requests
* Consistent black & red luxury theme and accessible typography

---

## 📁 File Structure (example)

```
/ (project root)
├─ index.html         # Home page
├─ inventory.html     # All cars / listing
├─ contact.html       # Contact & inquiry form
├─ style.css          # Central stylesheet (theme, layout, components)
├─ /cars/             # (optional) per-car detail pages
└─ /assets/           # images, logos, icons
```

---

## 🛠 How to run (local)

1. Download or clone the repository to your computer.
2. Open `index.html` in your browser (double-click or right-click → Open with → Browser).

> No build tools required — purely static files.

---

## ✍️ How to publish on GitHub (quick steps)

1. Initialize a git repository (if you haven't):

```bash
git init
git add .
git commit -m "Initial commit — High Street Motors"
```

2. Create a repo on GitHub, then follow the instructions they give you to push:

```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git branch -M main
git push -u origin main
```

3. (Optional) Enable GitHub Pages in repository settings and set the branch to `main` and folder to `/` to publish as a static site.

---

## 🧩 Notes & Tips

* The site is intentionally JavaScript-free. If you later want interactive features (image galleries, filters, contact submission), you can add small scripts or wire the contact form to a service like Formspree, Netlify Forms, or a backend.
* Use the `inventory.html` markup as a template for adding more cars — each `.car-card` uses a consistent structure (image, title, specs, price, details link).
* Keep images optimized (WebP or compressed JPG/PNG) to improve load performance.

---

## 🤝 Contributing

If you want changes or additions (extra pages, mobile improvements, print styles, or a lightweight JS gallery) — open an issue or send a PR with a clear description.

---

## 📬 Contact

If you need help publishing the site on GitHub or want a deployment-ready version, message me with the repository link and I’ll help.

---

© High Street Motors — Static HTML/CSS showcase
