# hackercupai.github.io

## How to build the site locally

Install dependencies

```bash
brew install rbenv
rbenv init
rbenv install 3.1.2
rbenv rehash
gem install bundler -v 2.4.15
```

Build the site

```bash
bundle install
bundle exec jekyll serve
```