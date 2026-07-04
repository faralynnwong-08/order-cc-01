# Order CC 01

This project is a static single-page web app for a restaurant ordering demo.

## GitHub Pages

The repository is prepared for GitHub Pages deployment with:
- a Pages workflow in [.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml)
- a [.nojekyll](.nojekyll) file to prevent Jekyll processing

### Deploy steps
1. Push this repository to GitHub.
2. Open the repository Settings → Pages.
3. Select "GitHub Actions" as the source.
4. The workflow will publish the site automatically on pushes to the main branch.

To preview locally, run:

```bash
python3 -m http.server 8000
```