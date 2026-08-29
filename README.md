# Octavian Banica — static HTML conversion

Framework-free static conversion of the public `OctavianBanicaUS/OctavianBanicaWeb` site.

## Stack
- HTML5 — one physical `index.html` per route
- CSS — `css/site.css`
- JavaScript — `js/site.js`
- No React, Astro, Node.js runtime, npm dependency, or build step is required.

## Mobile/accessibility
The responsive behavior is retained and hardened for phones and tablets:
- collapsible navigation below 43rem
- one-column layouts on narrow screens
- flow diagrams stack instead of overflowing
- full-width actions on very small screens
- responsive typography with `clamp()`
- visible keyboard focus indicators
- skip-to-content link
- reduced-motion support
- viewport metadata on every page

## Source
The original GitHub repository was not modified.

## Asset note
The source photographs were not altered or approximated. The converted About page references the original public avatar asset directly from GitHub so it remains identical to the source.
