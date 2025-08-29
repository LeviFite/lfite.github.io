### lfite.github.io
# GitHub Pages Starter

A minimal, standard-structured starter for a GitHub Pages site (user/organization or project page).

## Live Site

- **User/Org site (recommended):** `https://lfite.github.io/`
- **Project site:** `https://lfite.github.io/levifite/`

> Replace `LeviFite` and `lfite.github.io` with your GitHub info.

## What’s Included

- **README.md** — You’re reading it.
- **LICENSE** — MIT License for code. Change if needed.
- **.gitignore** — Ignores common build artifacts (Jekyll, Node), OS cruft, logs.

## Getting Started (Quick Setup)

1. **Create the repo**
   - For a user/organization site: name the repo exactly `lfite.github.io`.
   - For a project site: use any repo name (e.g., `lfite.github.io`).

2. **Add your web files**
   - At minimum include an `index.html` at the repo root.
   - Optional Jekyll structure if you want templating/themes: `_config.yml`, `_posts/`, layouts in `_layouts/`, etc.

3. **Enable Pages**
   - In **Settings → Pages**, choose the **Source**:
     - **Main branch** (root or `/docs`), or
     - **GitHub Actions** (recommended for custom builds).
   - Click **Save**. GitHub will publish to `https://lfite.github.io[/<REPO_NAME>]` after the first successful build.

4. **(Optional) Jekyll local preview**
   ```bash
   gem install bundler jekyll
   bundle init
   echo 'gem "github-pages", group: :jekyll_plugins' >> Gemfile
   bundle install
   bundle exec jekyll serve
   # open http://127.0.0.1:4000
