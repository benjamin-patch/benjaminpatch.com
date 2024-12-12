# Benjamin Patch
Public website for benjaminpatch.com, built with
[Pelican](https://getpelican.com/) and [Bootstrap](https://getbootstrap.com/).

## Pelican Site Updates

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

---

## Release Notes

### 2024.12.11
* Rebuild as a blog using Pelican.
* Rename 'master' git branch to 'main.'

### 2023.04.08
* Update with AE credits.

### 2022.07.15
* Update content to a 'Video Ediitng' focus.
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
* Add 'Astray' trailer and 'Cold Light' to filmography.

### 1.2.0
* 05 August 2017.
* Add 'Choice Words' and 'Doppler Salad' to filmography.
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
