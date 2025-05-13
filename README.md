# Benjamin Patch
Public website for benjaminpatch.com, built with
[Pelican](https://getpelican.com/) and [Bootstrap](https://getbootstrap.com/).

Code syntax highlighting provided by [highlight.js](https://highlightjs.org/).

## Pelican Site Updates

Built and tested in a `Python 3.13.3` venv.

Dependency declaration in `requirements.txt`. Rebuid by running:

```
pip install -r requirements.txt
```

### Development
```
rm -rf output/*
invoke regenerate
invoke livereload
```

### Production
```
rm -rf output/*
make publish
```
Push the newly generated site to the `gh-pages` branch. GitHub Pages should
automatically update the production site within a few minutes.

## GitHub Master to Main Update
```
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```

## Release Notes

### 2025.05.12
* Set Python version for pyenv

### 2025.04.17
* Update to a Python 3.13.3 build.
* Update Bootstrap CSS to version 5.3.5.
* Add controllable meta descriptions for all pages.
* Refactor all templates to consistently use 2 spaces.

### 2025.03.03
* Update to Python 3.13.2 build.
* Correct and adjust content in "Python venv" article.

### 2025.02.14
* Publish article "DeepSeek-R1: The Promise and Peril..."

### 2025.02.04
* Update Bluesky links to [@benjaminpatch.com](https://bsky.app/profile/benjaminpatch.com).
* Improve styling of blockquotes.

### 2025.01.30
* Publish article "Simple Python Virtual Environments: Linux and Mac."
* Clean up presentation of information on index pages.
* Enable syntax highlighting of common coding languages with [highlight.js](https://highlightjs.org/).
* Load Bootstrap stylesheet from CDN.
* Create initial dependency declaration with `pip freeze`.

### 2024.12.18
* Evenly round corners on all sides of header and footer.
* Publish article "The Journey of Artificial Intelligence."

### 2024.12.11
* Rebuild as a blog using Pelican.
* Rename "master" git branch to "main."

### 2023.04.08
* Update with AE credits.

### 2022.07.15
* Update content to a "Video Ediitng" focus.
* Update to RapidWeaver Classic project.

### 2022.01.05
* Create social tags.
* Update description tags.

### 2022.01.01
* Update copyright year and 2022 rates.
* Update resume.

### 2021.09.28
* Rebuild site using RapidWeaver 8.
* Add 2021 Demo Reel.

### 2020.02.01
* Change to time-based version numbers (yyyy.mm.dd)
* Connect with GitHub profile 

### 2.0.0
* 25 February 2020
* Rebuild with [Jekyll](https://jekyllrb.com/)

### 1.4.0
* 04 June 2019.
* Update content with more focus on Avid certification and The Post Workshop.

### 1.3.0
* 31 March 2018.
* Add "Astray" trailer and "Cold Light" to filmography.

### 1.2.0
* 05 August 2017.
* Add "Choice Words" and "Doppler Salad" to filmography.
* Update headshot.

### 1.1.1
* 27 March 2016.
* Minor grammar adjustment.

### 1.1.0
* 22 January 2016.
* Rewrite copy to express cinema major and history minor.
* Refine typography and layout.

### 1.0.1
* 26 June 2015.
* Minor content edits.
* Activate clean URLs.

### 1.0.0
* 18 June 2015.
* Initial public release.
* HTTPS everywhere.
* Google Analytics installed and tested.
* Nginx config includes related domain redirects.
* Sitemap submitted to Google, Bing, and Yandex.
