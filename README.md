# Harmony STEAM Club website

Four static pages for Music, Art, and Robotics. Publish only the `docs` folder. No build step, JavaScript, dependencies, or paid services are required.

## Preview locally

Open `docs/index.html` in a browser. All links use relative paths, so the four pages work locally and under a GitHub Pages project URL.

For a local HTTP preview, run `uv run python -m http.server 8000 --directory docs`, then visit `http://localhost:8000`. Stop the server with Ctrl+C.

## Edit and publish

- Home: `docs/index.html`
- About: `docs/about/index.html`
- Activities: `docs/activities/index.html`
- Contact: `docs/contact/index.html`
- Shared styling: `docs/assets/styles.css`
- Existing logo extracted from page 2 of the supplied PDF: `docs/assets/harmony-logo.png`

Navigation and footer markup are repeated in each page. Keep all four in sync when changing shared links or the contact email. Replace the intentional people/activity placeholders as approved content becomes available.

Parents review changes before publication. Configure GitHub Pages in repository Settings → Pages: select Deploy from a branch, then `main` and `/docs`, and save. Updating that source branch publishes automatically.

Repository: https://github.com/zhouhaochengde-cmyk/harmony-steam-club-website

Expected website address after Pages is enabled: https://zhouhaochengde-cmyk.github.io/harmony-steam-club-website/

Only upload approved public files. Planning documents may contain private details and local file paths; keep those out of a public repository unless reviewed. Keep original resumes, consent records, and private photos outside the repository.
