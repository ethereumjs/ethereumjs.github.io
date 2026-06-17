# SYNOPSIS

[![Discord][discord-badge]][discord-link]

# INTRODUCTION

Website to give an overview of the various ``EthereumJS`` projects and an 
introduction to the ecosystem and the community.

Site is hosted at https://ethereumjs.github.io/ via [GitHub Pages](https://pages.github.com) and
built with the [github-pages](https://github.com/github/pages-gem) gem (Jekyll 3.x, custom layout + SCSS).
Local builds should use **Ruby 3.3.x** to match the Pages environment — see [Dependency versions](https://pages.github.com/versions/).

# SITE UPDATES

You can update the site by editing the markdown in [./index.md](./index.md) (via PR), build will be
triggered automatically on merge.

For information on repository metadata on GitHub pages see [this](https://help.github.com/articles/repository-metadata-on-github-pages/) article.

Custom CSS lives in [./assets/css/style.scss](./assets/css/style.scss). Use **Ruby Sass–compatible** syntax only (`lighten()`, no `@use` / `color.adjust()` — GitHub Pages runs Jekyll 3 + Ruby Sass, not Dart Sass).

# LIBRARY INCLUDES

The website uses [Font Awesome](http://fontawesome.io/) ``v4.7.x`` for some icons. To update the library
download the latest release from the website and replace the un-versioned ``font-awesome`` folder in the
``assets/`` folder.

In ``scss/_variables.scss`` update the ``$fa-font-path`` to point to the ``../font-awesome/fonts`` directory.


# LOCAL BUILD

Use **Ruby 3.3.x** — the same major/minor series as [GitHub Pages](https://pages.github.com/versions/). Do **not** use macOS system Ruby (2.6) or Ruby 4; both will cause gem or Sass mismatches.

[`.ruby-version`](./.ruby-version) pins **3.3.7**.

### Option A — rbenv (recommended)

```sh
brew install rbenv ruby-build
rbenv install 3.3.7
cd ethereumjs.github.io   # picks up .ruby-version
gem install bundler
```

### Option B — Homebrew Ruby 3.3

```sh
brew install ruby@3.3
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"   # Intel: /usr/local/opt/ruby@3.3/bin
ruby --version   # should show 3.3.x
gem install bundler
```

### Install gems & preview

```sh
./bin/setup
# or: bundle install

bundle exec jekyll serve
```

Compare your local gem set with GitHub Pages:

```sh
bundle exec github-pages versions
```

Open http://127.0.0.1:4000

See also [GitHub's Jekyll local setup guide](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll).

[discord-badge]: https://img.shields.io/static/v1?logo=discord&label=discord&message=Join&color=blue
[discord-link]: https://discord.gg/TNwARpR
