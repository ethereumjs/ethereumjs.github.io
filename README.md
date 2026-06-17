# SYNOPSIS

[![Discord][discord-badge]][discord-link]

# INTRODUCTION

Website to give an overview of the various ``EthereumJS`` projects and an 
introduction to the ecosystem and the community.

Site is hosted at https://ethereumjs.github.io/ via [GitHub Pages](https://pages.github.com) and
built with [Jekyll 4](https://jekyllrb.com/) (custom layout + SCSS, no theme).

# SITE UPDATES

You can update the site by editing the markdown in [./index.md](./index.md) (via PR), build will be
triggered automatically on merge.

For information on repository metadata on GitHub pages see [this](https://help.github.com/articles/repository-metadata-on-github-pages/) article.

Custom CSS can be added in [./assets/css/style.scss](./assets/css/style.scss).

# LIBRARY INCLUDES

The website uses [Font Awesome](http://fontawesome.io/) ``v4.7.x`` for some icons. To update the library
download the latest release from the website and replace the un-versioned ``font-awesome`` folder in the
``assets/`` folder.

In ``scss/_variables.scss`` update the ``$fa-font-path`` to point to the ``../font-awesome/fonts`` directory.


# LOCAL BUILD

Requires **Ruby >= 3.3 and < 4.1** (see [`Gemfile`](./Gemfile)). The macOS system Ruby (2.6) is too old. Ruby **4.0.x** works; [`.ruby-version`](./.ruby-version) pins **3.3.7** as the recommended default.

### Option A — Homebrew (simplest on macOS)

```sh
brew install ruby
echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
gem install bundler
```

On Intel Macs, use `/usr/local/opt/ruby/bin` instead of `/opt/homebrew/opt/ruby/bin`.

### Option B — rbenv

```sh
brew install rbenv ruby-build
rbenv install 3.3.7
cd ethereumjs.github.io   # picks up .ruby-version
gem install bundler
```

### Install gems & preview

```sh
./bin/setup
# or: bundle install

bundle exec jekyll serve
```

Open http://127.0.0.1:4000

See also [GitHub's Jekyll local setup guide](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll).

[discord-badge]: https://img.shields.io/static/v1?logo=discord&label=discord&message=Join&color=blue
[discord-link]: https://discord.gg/TNwARpR
