# Benjamin Patch

Public website for benjaminpatch.com, built with
[Pelican](https://getpelican.com/) and [Bootstrap](https://getbootstrap.com/).

Code syntax highlighting provided by [highlight.js](https://highlightjs.org/).

## Pelican Site Updates

Built and tested in a `Python 3.13.3` venv.

Dependency declaration in `requirements.txt`. Rebuild by running:

```bash
pip install -r requirements.txt
```

### Development

```bash
rm -rf output/*
invoke regenerate
invoke livereload
```

### Production

```bash
rm -rf output/*
make publish
```

Push the newly generated site to the `gh-pages` branch. GitHub Pages should
automatically update the production site within a few minutes.

## GitHub Master to Main Update

```bash
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```

## Release Notes

### 2025.05.13

- Publish "When Vibe Coding Fails: Python Kickstart (part 1)" article.
- Set Python version for pyenv.

### 2025.04.17

- Update to a Python 3.13.3 build.
- Update Bootstrap CSS to version 5.3.5.
- Add controllable meta descriptions for all pages.
- Refactor all templates to consistently use 2 spaces.

### 2025.03.03

- Update to Python 3.13.2 build.
- Correct and adjust content in "Python venv" article.

### 2025.02.14

- Publish article "DeepSeek-R1: The Promise and Peril..."

### 2025.02.04

- Update Bluesky links to [@benjaminpatch.com](https://bsky.app/profile/benjaminpatch.com).
- Improve styling of blockquotes.

### 2025.01.30

- Publish article "Simple Python Virtual Environments: Linux and Mac."
- Clean up presentation of information on index pages.
- Enable syntax highlighting of common coding languages with [highlight.js](https://highlightjs.org/).
- Load Bootstrap stylesheet from CDN.
- Create initial dependency declaration with `pip freeze`.

### 2024.12.18

- Evenly round corners on all sides of header and footer.
- Publish article "The Journey of Artificial Intelligence."

### 2024.12.11

- Rebuild as a blog using Pelican.
- Rename "master" git branch to "main."
