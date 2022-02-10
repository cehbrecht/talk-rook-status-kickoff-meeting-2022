# Rook 4 CDS

Copernicus Cordex Workshop (ECMWF + IPSL):
* May 6th AND 7th, both days from 1:30PM to 4:30PM CET (Paris time zone).



## Installation

This presentation uses [reveal-ck](http://jedcn.github.io/reveal-ck/).
See [documentation](http://jedcn.github.io/reveal-ck/installation/) for installation.

```
gem install reveal-ck
```

The slides `slides.md` are written in Markdown.

You can generate the presentation with reveal-ck:
```
$ reveal-ck generate
$ reveal-ck serve
http://localhost:10000
```

## Using RevealJS

See:
https://github.com/hakimel/reveal.js/blob/master/README.md

Export as PDF:
https://revealjs.com/pdf-export/


Overview mode with `ESC`:
https://github.com/hakimel/reveal.js/blob/master/README.md#overview-mode

## Install on macOS

See:
https://github.com/rbenv/rbenv#upgrading-with-homebrew

```
$ brew install rbenv ruby-build
$ rbenv init
# $ eval "$(rbenv init - zsh)"
$ rbenv install 2.7.0
$ rbenv global 2.7.0
$ gem install reveal-ck
```
