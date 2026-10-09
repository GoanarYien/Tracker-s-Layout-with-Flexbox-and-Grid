# SpendWise Dashboard Shell (Capstone Foundation)

A modern, responsive financial dashboard shell built using **CSS Grid**, **Flexbox**, and **CSS Custom Properties** as part of the Week 4 visual design challenge.

## ✨ Features & Architecture
- **CSS Grid Layout:** Used for the macro dashboard shell structure (`grid-template-columns: 260px 1fr`) separating the sidebar and main content area.
- **Flexbox Integration:** Applied across headers, sidebars, navigation bars, and category cards for precise alignment and distribution.
- **CSS Custom Properties (`:root`):** A centralized theming system covering brand color, accent color, surface background, and text colors.
- **Responsive Design:** Features a mobile media query (`max-width: 768px`) that collapses the dashboard layout into a clean single-column view optimized for mobile devices and verified via DevTools.
- **Card Micro-Interactions:** Smooth hover and keyboard-accessible focus animations (`transform` and `box-shadow`) under 250ms.
- **Dark Theme Stretch Goal:** Built-in automatic dark theme support using `@media (prefers-color-scheme: dark)` overrides.

## 📂 Project Structure
- `index.html`: Contains semantic markup for the dashboard shell, navigation, header, and 6 category cards.
- `style.css`: Houses the stylesheet implementing layout grids, flex properties, variables, and responsive rules.
- `README.md`: Project documentation.