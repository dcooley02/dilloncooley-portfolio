# Dillon Cooley — Personal Portfolio (archived)

> **Archived.** This plain HTML/CSS site is no longer the live portfolio.
>
> **Current site:** [https://dilloncooley.us](https://dilloncooley.us)  
> **Source:** [dcooley02/dilloncooley-win95](https://github.com/dcooley02/dilloncooley-win95) (Windows 95 desktop portfolio)
>
> A historical copy may still be viewable at  
> [dcooley02.github.io/dilloncooley-portfolio](https://dcooley02.github.io/dilloncooley-portfolio/) (GitHub Pages only; no custom domain).

Built with plain HTML and CSS — no frameworks, no build tools. Kept for reference and history; not under active development.

## Project structure

```
/
├── index.html              # Main portfolio page
├── style.css               # Global styles
├── assets/
│   ├── me.jpg
│   └── helo.jpeg
└── home/
    ├── pdf-viewer.css
    ├── resume/
    └── thesis/
```

## Running locally

```bash
npx serve .
# or
python3 -m http.server
```

## Deploy / domain notes

- Custom domain `dilloncooley.us` is owned by **dilloncooley-win95** (this repo no longer ships a `CNAME`).
- Prefer the live site for resume, thesis, and social previews.

## GitHub archive

Optional: in the repo **Settings → General → Danger Zone → Archive this repository** so GitHub marks the project read-only.
