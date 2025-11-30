# Pillars of Thought

A Jekyll-ready, GitHub Pages-compatible recreation of the Philosophy Bro aesthetic—rebuilt with "Pillars of Thought" branding and four pillar pages: Theology, Philosophy, Policy, and History.

## Getting Started
1. Install Ruby and Bundler.
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run locally:
   ```bash
   bundle exec jekyll serve
   ```
   Visit http://localhost:4000 to preview.

## Posts & Pillars
- Create new posts in `_posts/` using the `YYYY-MM-DD-title.md` naming convention.
- Add `pillar` front matter (`Theology`, `Philosophy`, `Policy`, or `History`) to have posts appear on the corresponding pillar page.
- Pillar pages live under `/pillars/<pillar>/` and are ready to share directly.

## Deploying to GitHub Pages
- Push the repository to GitHub and enable GitHub Pages (e.g., `main` branch or `/docs` folder as desired).
- The included `github-pages` gem keeps configuration aligned with Pages defaults.
