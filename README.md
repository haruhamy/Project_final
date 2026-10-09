# Nature Gallery — WD4E Week 4 Final Project

This project is based on the official `RD-week4-final_project_starter` structure, with all nine starter images and both paragraphs replaced. It uses only HTML and CSS, and works offline because the nine original SVG landscape images are included locally.

## Open

Double-click `index.html` or open it with VS Code Live Server. Do not move `index.html` away from `css/` or `images/`.

## Assignment requirements

- Mobile-first layout: one CSS Grid column with `gap: 10px`.
- Tablet (`min-width: 772px`): two columns, circular figures, last figure spans both columns.
- Desktop (`min-width: 992px`): every third figure spans both columns; border radius removed; no `max-width` property.
- Reduced motion: `scroll-behavior: auto` under `prefers-reduced-motion: reduce`.
- Dark scheme: dark figure background, light yellow text, black borders.
- Every one of the nine SVG images has descriptive alternative text.
- Original `Jump to the Top` link is preserved.

## Before submission

Host with GitHub Pages (Settings > Pages > Deploy from a branch > main / root). Check the hosted URL using W3C Nu HTML Checker (`https://validator.w3.org/nu/`) and WAVE (`https://wave.webaim.org/`). Set operating system preferences to dark mode / reduce motion to confirm each relevant media query works. An offline static check is not the same as running the external validators on the hosted site.
