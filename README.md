# Bibhudendu Behera – Portfolio

[![Deploy](https://github.com/bibhu342/bibhuai/actions/workflows/deploy.yml/badge.svg)](https://github.com/bibhu342/bibhuai/actions/workflows/deploy.yml)
[![HTML Validation](https://github.com/bibhu342/bibhuai/actions/workflows/html-validate.yml/badge.svg)](https://github.com/bibhu342/bibhuai/actions/workflows/html-validate.yml)
[![Accessibility](https://github.com/bibhu342/bibhuai/actions/workflows/axe.yml/badge.svg)](https://github.com/bibhu342/bibhuai/actions/workflows/axe.yml)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Portfolio of Bibhudendu Behera, multimodal AI evaluation and LLM quality specialist (Six Sigma Black Belt) and founder of VividFlow Studio.

**Live site:** https://bibhu342.github.io/bibhuai/

## What's on the site

- Experience: VividFlow Studio, freelance AI evaluation (Upwork), Innodata (Analyst – AI/LLM), IntouchCX, Tapzo
- Skills: generated image/video evaluation, RLHF preference ranking, audio and speech, vision and video annotation, text and reasoning checks
- Projects: Groundtruth (AI label-quality concept), CSV-Cleaner-Pro, PDF-Parser-Pro, Web-Extractor-Pro, and VividFlow Studio work (Kestrel Freight, Halden Solar, LumaSkin, TACET One, PRIMEUR)
- Certifications, contact form (Formspree) and downloadable resume

## Tech

- Static HTML, CSS and vanilla JavaScript, deployed to GitHub Pages from `main`
- Light and dark themes (`data-theme` on `<html>`); dark-mode and contrast overrides live in `css/contrast-fix.css`
- Google Analytics 4 behind a cookie-consent banner
- GitHub Actions: deploy, HTML minification, HTML validation, axe accessibility checks, Lighthouse CI, visual regression

## Editing

- Content lives in `index.html`. The `Minify HTML` workflow minifies HTML on every push to `main`, so edit the readable version and let CI minify it.
- Styles: `styles.css` with its minified copy `styles.min.css` (the page loads the `.min` file, so update both), then `css/contrast-fix.css` / `.min.css`, which load last.
- Resume: replace `assets/Bibhudendu_Behera_Resume.pdf`.
- Social preview image: `assets/images/og-image-2026.png` (1200×630).

Run locally:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Project structure

```
bibhuai/
├── index.html              # Main page
├── 404.html, privacy.html, terms.html
├── styles.css / styles.min.css
├── script.js / script.min.js
├── css/contrast-fix.css    # Theme and contrast overrides (loaded last)
├── assets/                 # Images, resume, social preview
├── site.webmanifest, robots.txt, sitemap.xml
└── .github/workflows/      # CI/CD
```

## Contact

- Email: [bibhu342@gmail.com](mailto:bibhu342@gmail.com)
- LinkedIn: [bibhudendu-behera](https://www.linkedin.com/in/bibhudendu-behera-b5375b5b)
- Upwork: [Bibhudendu B.](https://www.upwork.com/freelancers/~01ca3f8fff49f359ca)
- GitHub: [@bibhu342](https://github.com/bibhu342)

## License

MIT – see [LICENSE](LICENSE).
