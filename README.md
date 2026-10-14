# 🎮 GAMELAND

A fictional video game store website with a dark "gaming" look, CSS animations and a catalog of featured deals. Final project for the Markup Languages (LM) course.

## ✨ Features

- **Sticky header** with logo, search bar and navigation (Store, cart and Login). It stays visible while scrolling and has a blur effect.
- **Background carousel** in the hero section: 5 images that fade in and out, built with CSS animations only (no JavaScript).
- **Popular categories** with an accordion effect: PC, PlayStation, Xbox and Nintendo. On hover, the category expands and reveals its name.
- **Featured deals** in a responsive grid with 8 games, each one with:
  - cover art, a platform tag (PC, PS4, PS5, XBOX, SWITCH) and a discount tag,
  - current price and crossed-out previous price,
  - a floating tooltip on hover with the **PEGI** rating, description and price.
- **Responsive design**: on screens up to 768 px wide, the header and categories stack vertically.
- Entrance animations, neon glows and smooth transitions.

## 🛠️ Technologies

- **HTML5**: semantic structure (`header`, `nav`, `main`, `section`, `article`, `footer`).
- **CSS3**: CSS variables, Flexbox, Grid, `@keyframes`, transitions, `backdrop-filter` and media queries.

## 📁 Project Structure

```
Trabajo-final/
├── index.html                                  # Page structure
├── style.css                                   # Styles and animations
├── Captura de pantalla 2026-03-18 141158.png   # Carousel image
├── Captura de pantalla 2026-03-18 141234.png   # Carousel image
├── Captura de pantalla 2026-03-18 141257.png   # Carousel image
├── Captura de pantalla 2026-03-18 141321.png   # Carousel image
└── README.md
```

## 🚀 Getting Started

No installation or dependencies required.

1. Clone the repository:
   ```bash
   git clone https://github.com/Adrian-0708/Trabajo-final.git
   ```
2. Enter the folder:
   ```bash
   cd Trabajo-final
   ```
3. Open `index.html` in your browser (double-click it, or use the *Live Server* extension in VS Code).

> **Note:** the game covers and the fifth carousel image are loaded from the internet (Amazon and Unsplash), so you need a connection to see them.

## 📌 Project Status

This is a UI mockup: the search bar, cart, login and links don't have any functionality yet. Possible future improvements:

- Add JavaScript for the search bar and the cart counter.
- Create pages for each category and each game.
- Store the covers in the repository itself so it doesn't depend on external links.

## 👤 Author

**Adrian-0708** · [github.com/Adrian-0708](https://github.com/Adrian-0708)

---

© 2026 GAMELAND. Final project LM.
