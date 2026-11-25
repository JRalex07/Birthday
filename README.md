# Birthday

A small interactive birthday-surprise page built with HTML, CSS, and browser JavaScript.

## Features

- A gift-opening interaction that reveals a personalized birthday message.
- Animated text, stickers, and optional falling-particle effects.
- Responsive layout adjustments for mobile screens.
- Reduced-motion handling for CSS effects and the falling-particle effect.
- SweetAlert2 and TypeIt for dialogs and text animations.

## Run locally

The project is static and has no build step. Clone the repository and open `index.html` in a modern browser. For a local web server, run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Customize

- Update the birthday messages and interaction text in `index.html`.
- Replace the files in `assets/` to change the wallpaper, gift, and stickers.
- The current page loads SweetAlert2, TypeIt, and web fonts from external CDNs, so those features require an internet connection.

## Accessibility and layout

The page includes viewport-aware sizing for narrow screens and reduces CSS transitions/animations and falling particles when the operating system requests reduced motion.
