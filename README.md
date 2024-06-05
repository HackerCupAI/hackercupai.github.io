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

If it worked you should see an output in your console like `Server address: http://127.0.0.1:4000`