# Yuganter Veerwal | Portfolio Website

A responsive, animated personal portfolio built with plain HTML and CSS. No frameworks, no JavaScript, no build step.

## Features

- **Hero name effect:** the name drops in and "breaks" like a taekwondo board. Hover or focus it to split the halves again.
- **Responsive layout:** adapts from phones to wide desktops using CSS grid, flexbox and `clamp()` sizing.
- **Light and dark mode:** follows the visitor's system setting automatically.
- **Interactive CSS:** hover animations on stat cards, activity panels, timeline entries and skill chips.
- **Accessible:** visible keyboard focus, semantic sections, and animations switch off for visitors who prefer reduced motion.

## Sections

1. Hero
2. About (scores and sports levels)
3. Beyond the screen (taekwondo, basketball, debate and MUN)
4. Education (timeline)
5. Project (Mental Health Companion)
6. Skills (HTML, CSS, Java, C++, Python)
7. Contact

## Getting started

1. Download `index.html`.
2. Open it in any modern browser (double-click the file).

That's all. There is nothing to install.

## Customising

- **Colours:** edit the variables at the top of the `<style>` block (`--blue`, `--red`, `--amber`, `--bg`, `--ink`). Dark-mode values are set in the two `dark` rules just below them.
- **Text:** change the content directly in the HTML sections.
- **Email:** add your address after `mailto:` in the footer button, for example `mailto:you@example.com`.
- **Hero name:** the `data-t` attribute on the `<h1 class="name">` must match the visible name text. Update both if you change it.
- **More content:** copy a `.pane`, `.stat` or `.tl li` block to add another activity, stat or education entry.

## Deploying for free

- **GitHub Pages:** put `index.html` in a repository, then enable Pages in the repository settings.
- **Netlify:** drag and drop the folder containing `index.html` onto netlify.com/drop.

## Tech

- HTML5
- CSS3 (custom properties, grid, flexbox, clip-path, keyframe animations, `prefers-color-scheme`, `prefers-reduced-motion`)

## Author

Yuganter Veerwal
