# Orbit

Orbit is an accessible, dependency-free space exploration quiz in a single HTML file. Answer ten questions, track your score and progress, and learn from animated feedback and explanations. Results include an emoji reaction and an extra celebration for scores of 8 or higher.

The responsive layout supports light and dark themes, keyboard-friendly controls, and reduced-motion preferences.

**Play online:** https://azrarafeeq.github.io/space-quiz/

## Run locally

No installation, build step, or server is required. Open `index.html` in a modern web browser.

## Deployment

The site is published with GitHub Pages using `.github/workflows/pages.yml`. No application build is needed: the workflow checks inline JavaScript syntax and stages only `index.html` for publication.

Pull requests run the staging check without deploying. Pushes to `main` deploy the staged site; the workflow can also be started manually from the Actions tab on `main`. Repository Settings > Pages must use **GitHub Actions** as the source.
