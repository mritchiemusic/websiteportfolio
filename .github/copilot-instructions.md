# Project Guidelines

## Code Style
- Keep the site static: plain HTML and CSS, no build tooling unless explicitly requested.
- Match the existing multi-page pattern (`index.html`, `portfolio.html`, `music.html`, `contact.html`) and shared stylesheet usage in `css/style.css`.
- Preserve existing typography choices (Google Fonts: Montserrat and Esteban) and current visual language unless a redesign is requested.
- Use semantic HTML and meaningful `alt` text for images.

## Architecture
- This is a static portfolio site deployed via GitHub Pages (`CNAME` present).
- Pages are separate HTML files with a shared top navigation and shared global styles in `css/style.css`.
- Media assets live under `photos/` and `music/`; prefer reusing existing folders and naming conventions.

## Build and Test
- No project build step.
- For local preview, run from the project root:
  - `python3 -m http.server 8000`
- Validate by opening the main pages and checking navigation links, image loads, and responsive behavior.

## Conventions
- When changing navigation, keep links consistent across all page files.
- Prefer small, targeted CSS edits over introducing large new style systems.
- Keep relative paths correct from each page (especially for assets under `photos/`).
- Link to details instead of duplicating docs: see `README.md` for project overview.
