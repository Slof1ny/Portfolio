# Henrycus Hugatama Risaldy Portfolio

This repository contains the personal portfolio website of Henrycus Hugatama Risaldy, focused on product management, project management, and business analysis.

## Overview

The site is a lightweight static portfolio built for easy deployment on GitHub Pages. It highlights:

- Professional summary and positioning
- Work experience
- Selected product and business analysis projects
- Tools, methods, and technical foundation
- Contact links and downloadable CV

## Project Structure

```text
.
|-- assets/
|   |-- Henrycus_Hugatama_CV.pdf
|   `-- profile.jpg
|-- .github/
|   `-- workflows/
|       `-- deploy.yml
|-- index.html
|-- styles.css
`-- README.md
```

## Local Preview

Because this is a static site, you can preview it by opening `index.html` directly in a browser.

If you prefer a local server, from the repository root run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

GitHub Pages deployment is configured through GitHub Actions in `.github/workflows/deploy.yml`.

After pushing this repository to GitHub:

1. Open the repository settings.
2. Go to `Pages`.
3. Ensure the source is set to `GitHub Actions`.
4. Push to `main` to trigger deployment.

## Notes

- The portfolio content is based on the provided CV and LinkedIn profile URL.
- The site is designed to be simple to maintain and easy to expand later with new sections or projects.
