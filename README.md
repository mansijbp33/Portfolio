# Personal Portfolio Website

Welcome to the source code of my personal portfolio website! I am **Mansi Jobanputra**, an IT student passionate about Data Science, AI, Machine Learning, and Web Development. 

This repository contains a clean, highly responsive, and interactive personal website built from scratch with pure HTML, CSS, and modern JavaScript.

---

## ✨ Features

- **Dark & Light Mode Integration:** Seamlessly toggle between dark and light themes. The user's preference is automatically saved locally so the website remembers their choice across sessions.
- **Sleek Dynamic Animations:** 
  - **Scroll Reveal.** Integrated with the AOS (Animate On Scroll) library, sections slide in naturally as you explore the page.
  - **"Breathing" Typography.** A lively floating animation cloud makes the Soft Skills section visually compelling.
  - **Animated Background Blob.** A subtle infinite moving gradient adds life behind the hero section.
- **Glassmorphism UI:** Features premium, semi-transparent layered UI components with soft backdrops.
- **Mobile First & Fully Responsive:** All grids and modules seamlessly collapse perfectly for mobile devices, tablets, and diverse browser widths.
- **Interactive Projects Showcase:** Fully configured hover cards with dynamic gradients.

## 🛠️ Technologies Used

No heavy frontend frameworks were used. The project highlights core frontend web fundamentals:
- **HTML5:** Semantic architecture
- **CSS3:** Native CSS variables (custom properties), CSS Flexbox/Grid, pseudo-elements, dynamic keyframe animations.
- **JavaScript (Vanilla):** DOM manipulation, theme persistence via `localStorage`, and intersection observers logic.
- **AOS (Animate On Scroll):** Third-party open-source CSS/JS scroll handler.
- **FontAwesome:** Scalable SVG iconography.

## 🚀 How to Run Locally

You don't need any complex development servers or dependencies to run this!

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mansijbp33/Portfolio.git
   ```
2. Navigate into your folder:
   ```bash
   cd Portfolio
   ```
3. Open the `index.html` file in your preferred web browser (Chrome, Firefox, Safari, Edge). That's it!

## ⚙️ Customization Guide

If you are cloning this project to build your own portfolio, here is how you update your resources:
- **Resume:** Replace `resume.pdf` in the root folder with your own PDF. Ensure the file name stays the same, or update the `href` on the Resume link inside `index.html`.
- **Project Images:** Locate the `.project-img` divs in `index.html` and replace the placeholder `unsplash.com` URLs with your actual local image paths.
- **Color Scheme:** All branding colors can be managed directly at the top of `styles.css` inside the `:root` and `[data-theme="dark"]` CSS variable blocks.

## 📞 Contact Me

Feel free to connect with me!
- **LinkedIn:** [Mansi Jobanputra](https://linkedin.com/in/mansijobanputra)
- **GitHub:** [@mansijbp33](https://github.com/mansijbp33)

---
*Clean Code. Minimalist Design. Constant Learning.*
