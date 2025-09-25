Agency Jekyll theme
====================

Agency theme based on [Agency bootstrap theme ](https://startbootstrap.com/template-overviews/agency/)

# How to use

###Portfolio 

Portfolio projects are in '/_posts'

Images are in '/img/portfolio'

###About

Images are in '/img/about/'

###Team

Team members and info are in '_config.yml'

Images are in '/img/team/'


# Demo

View this jekyll theme in action [here](https://y7kim.github.io/agency-jekyll-theme)

# Build locally

```
# install dependencies
sudo pacman -S ruby ruby-erb
gem install bundler jekyll

bundle init

# keep gems in the repo (no sudo needed)
bundle config set --local path 'vendor/bundle'
bundle config set --local bin  'vendor/bundle/bin'

# (optional but useful) ensure bundler doesn’t try system paths
unset GEM_HOME GEM_PATH

# install
bundle install

# serve
bundle exec jekyll serve
```
