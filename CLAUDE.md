# Hezico Assets

## Project Overview
A library of reusable templates and assets for Hezico. This repo contains production-ready templates that can be used across Hezico projects.

## Structure
- `templates/` - Reusable page/component templates
- Each template lives in its own subdirectory under `templates/`

## Conventions
- Templates should be self-contained with all necessary HTML, CSS, and JS in their directory
- Use modern, clean HTML5/CSS3/JS (ES6+)
- No external dependencies unless absolutely necessary — prefer vanilla implementations
- Each template directory should contain an `index.html` as the entry point
- Keep assets (images, fonts, icons) local to each template directory when possible

## Code Style
- 2-space indentation
- Use semantic HTML elements
- CSS: BEM-like naming or utility classes, mobile-first responsive design
- JS: ES6+ modules, no jQuery
