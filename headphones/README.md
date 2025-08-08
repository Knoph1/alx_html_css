# ALX HTML/CSS Project - Headphones Webpage

## Overview

This project is part of the **ALX Front-End Specialization** and focuses on implementing a fully functional web page from scratch, following a provided design in Figma.  
The page must be created using only **HTML and CSS** — without JavaScript or external CSS frameworks.

The final result should match the provided designer file as closely as possible, following responsive and accessibility best practices.

---

## 🎯 Objectives

- Convert a static design (Figma) into a pixel-perfect responsive webpage.
- Apply advanced HTML & CSS knowledge for layout, styling and responsiveness.
- Ensure mobile compatibility and accessibility compliance.

---

## 📂 Project Structure

```
alx_html_css/
└── headphones/
    ├── index.html      # Main HTML file
    ├── styles.css      # CSS styling
    └── README.md       # Documentation
```

---

## 📂 Tasks

### **Task 0 — Setup & README**

- **Objective:** Familiarize yourself with the design in Figma and prepare the environment.
- **Actions:**
  - Open [Figma Project](https://www.figma.com) and duplicate to drafts.
  - Download fonts and image assets.
  - Create `README.md` (this file) describing the project.
- **Deliverables:**
  - `README.md`
  - `.gitignore` (optional, but recommended to exclude system files).

---

### **Task 1 — Header/Hero Section**

- **Files:** `0-index.html`, `0-styles.css`
- **Objective:** Create the top hero section with navigation and introductory text.
- **Notes:**
  - Use semantic HTML: `<header>`, `<nav>`, `<section>`.
  - Mobile menu collapses into a hamburger icon.
  - Background image or solid color based on the design.
  - Responsive typography and layout.

---

### **Task 2 — “What We Do” Section**

- **Files:** `1-index.html`, `1-styles.css`
- **Objective:** Add a section describing the company's services.
- **Special Requirement:** Use custom font icons from `holberton_school-icon.zip`.
- **Steps:**
  - Copy Task 1 files and rename to Task 2 filenames.
  - Include the icon font in HTML `<head>` via `@font-face` or `<link>`.
  - Create 3–4 service blocks with icon, title, and description.
  - Keep styles generic for reuse in future sections.

---

## 🎨 Styling Guidelines

- **Reset CSS:** Include a basic CSS reset at the top of every stylesheet.
- **Variables:** Define CSS variables for colors, font sizes, and spacing.
- **Selectors:** Use simple, reusable class selectors (avoid over-specific targeting).
- **Layout:** Use flexbox or grid for alignment.
- **Images:** Store all in `/images` folder.

---

## 📱 Responsiveness

- **Desktop (≥ 1000px):** Fixed max width, centered content.
- **Tablet (481px–999px):** Adjust typography and spacing.
- **Mobile (≤ 480px):** Stack sections vertically, hide desktop menu, show hamburger icon.

---

## 📦 Assets

- **Image assets:** Provided in `images/` folder.
- **Icon fonts:** `holberton_school-icon.zip` contains CSS and font files — extract and link.
- **Favicons:** Include `favicon.ico` and `favicon.png` in `<head>`.

---

## 🖼 Example Screens
| Desktop View | Mobile View |
|--------------|-------------|
| ![Desktop](images/desktop_preview.png) | ![Mobile](images/mobile_preview.png) |

---

---

## 🛠 Tools & Resources

- **Figma** – for design specifications.
- **Fonts** – Download from:
  - [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
  - [Spin Cycle OT](https://fonts.adobe.com/fonts/spin-cycle-ot)
- **Code Editor** – VS Code or any preferred IDE.

---

## 📏 Design Notes

- Some Figma values are in floats — rounding is acceptable.
- Ensure content scales well between desktop and mobile.
- Use relative units (`em`, `rem`, `%`) for flexibility where appropriate.

---

## 📱 Responsive Rules

- Switch to **mobile view** at `max-width: 480px`.
- Use **flexbox** and/or **CSS grid** for layout control.
- Images and text should scale proportionally.

---

## 🚀 Deployment

Once complete, host the page using:
- **GitHub Pages**
- **Vercel**
- **Netlify**

Example for GitHub Pages:
```bash
git add .
git commit -m "Initial project setup"
git push origin main
```
Then enable Pages in repository settings.

---

## ✅ Final Checklist

- [ ] Matches Figma design layout.
- [ ] Fully responsive on all devices.
- [ ] No external CSS or JS used.
- [ ] Fonts match specifications.
- [ ] All hover and active styles implemented.
- [ ] Semantic HTML structure.

---

---

## 📄 License
This project is part of the **ALX HTML/CSS Curriculum** and follows its guidelines.  
Design by **Nicolas Philippot**.

---

## 📌 Author

Designed by **Nicolas Philippot** (UI/UX Designer).  
Implemented by **Knoph Ayieko** as part of the **ALX Front-End Specialization**.

---

&copy; August 8, 2025 | ALX Africa - Knoph Ayieko | All rights reserved.
