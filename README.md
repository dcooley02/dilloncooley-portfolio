# Dillon Cooley — Personal Portfolio

Personal portfolio site for [dilloncooley.us](https://dilloncooley.us). Built with plain HTML and CSS — no frameworks, no build tools.

## Features

- Dark/light mode toggle with `localStorage` persistence and system preference detection (no flash on load)
- Responsive layout that works on mobile and desktop
- Inline PDF viewer for resume and thesis with a download fallback
- Open Graph and Twitter Card meta tags for social sharing

## Project Structure

```
/
├── index.html              # Main portfolio page
├── style.css               # Global styles
├── assets/
│   ├── me.jpg
│   └── helo.jpeg
└── home/
    ├── pdf-viewer.css      # Shared styles for PDF viewer pages
    ├── resume/
    │   ├── index.html      # Resume viewer
    │   └── resume.pdf
    └── thesis/
        ├── index.html      # Thesis viewer
        └── thesis.pdf
```

## Running Locally

No build step required. Open `index.html` directly in a browser, or serve the directory with any static file server:

```bash
npx serve .
# or
python3 -m http.server
```

## Deploying

The site is a fully static, deploy anywhere — GitHub Pages, Netlify, Vercel, or any web host. No configuration needed beyond pointing the host at the repository root.
