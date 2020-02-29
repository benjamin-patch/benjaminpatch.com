# Benjamin Patch
Public website for benjaminpatch.com, built with
[Jekyll](https://jekyllrb.com/).

## Bootstrap Submodule
This project contains the Bootstrap front-end framework as a git submodule. When
cloning the repo, use this command to ensure the appropriate assets are included
and initialized:

```
$ git clone --recurse-submodules [SSH or HTTPS repo URL]
```

If you already cloned the project and forgot `--recurse-submodules`, you can
combine the `git submodule init` and `git submodule update` steps by running
`git submodule update --init`.

To also initialize, fetch and checkout any nested submodules, use the foolproof:

```
$ git submodule update --init --recursive
```

For more information, please read:
[Git Tools - Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)

## Ruby Dev Environment: Linux
- Install `rbenv` by cloning the GitHub repo
- Set rbenv to `v1.1.2` via git
- Install `ruby-build` as a rbenv plugin
- Set ruby-build to `v20200214` via git

Add rbenv to your local PATH (bash shell):
```
$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bash_profile
```

Set up rbenv in your shell:
```
$ ~/.rbenv/bin/rbenv init
```
Follow the printed instructions to set up rbenv shell integration.

Restart your shell so that PATH changes take effect.
On Linux, log out and then log back in.

Check your local Ruby environment with this command:
```
$ curl -fsSL https://github.com/rbenv/rbenv-installer/raw/master/bin/rbenv-doctor | bash
```

Install Ruby 2.6.5:
```
$ rbenv install 2.6.5
```

Set global Ruby version:
```
$ rbenv global 2.6.5
```

Check local gem environment:
```
$ gem env home
```
This should return the path to rbenv in `USER_HOME/.rbenv/versions/...`

Install bundler:
```
$ gem install bundler
```

Install missing gem packages:

```
$ bundle install
```

Update gem packages if desired:

```
$ bundle update
```

Build site and launch Jekyll server:

```
$ bundle exec jekyll serve
```

The development site will load at
[http://localhost:4000](http://localhost:4000/).


## Ruby Dev Environment: Windows 10
### Linux Subsystem
* https://docs.microsoft.com/en-us/windows/wsl/install-win10
* https://gorails.com/setup/windows/10

### Bundler Reference
* http://bundler.io

### Node.js for Middleman Server
* https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions

### Local Filepath
* /mnt/c/websites/benjaminpatch.com

---

## Release Notes

### 2020.02.1
* Change to time-based version numbers (yyyy.mm.x)
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
