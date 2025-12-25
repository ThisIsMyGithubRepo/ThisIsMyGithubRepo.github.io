# ThisIsMyGithubRepo.github.io

A simple GitHub Pages site for ThisIsMyGithubRepo using Jekyll.

## Local development (recommended)

1. Install Ruby (Windows: RubyInstaller + MSYS2) or use WSL.
2. Install Bundler and dependencies:

```bash
bundle install
```

3. Run the dev server:

```bash
bundle exec jekyll serve --livereload
```

Open http://127.0.0.1:4000 in your browser.

## If this repo is named `<your-username>.github.io`

GitHub will serve the site from the repository root automatically when you push.

## Add content

- Pages: Add Markdown files at the repo root or in subfolders.
- Posts: Add files in `_posts/` using `YYYY-MM-DD-title.md`.

## Notes

- Replace `url` in `_config.yml` with your GitHub Pages URL.
- If you want an automated build/deploy workflow (Actions), tell me and I'll add one.
 - Replace `url` in `_config.yml` with your GitHub Pages URL.
 - The site now uses the `BDHU/minimalist` remote Jekyll theme (see `remote_theme` in `_config.yml`).
 - If you want an automated build/deploy workflow (Actions), tell me and I'll add one.
## CI / CD

- A GitHub Actions workflow has been added at `.github/workflows/jekyll-deploy.yml`.
- It runs on pushes to `main` or `master`, builds the site with Jekyll, and deploys the generated `_site` to GitHub Pages using the official Pages actions.
- If your default branch is different, update the `on.push.branches` setting in the workflow or rename your branch to `main`.
- Ensure GitHub Pages is enabled in the repository settings (Pages → Build and deployment) and that the `pages` permission is allowed for Actions (usually enabled by default).

## Contact

If you want specific content or sections added to this README (license, build steps, screenshots), tell me what to include and I'll update it.
