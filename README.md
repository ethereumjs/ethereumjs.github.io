# SYNOPSIS

[![Discord][discord-badge]][discord-link]

# INTRODUCTION

Website to give an overview of the various ``EthereumJS`` projects and an 
introduction to the ecosystem and the community.

Site is hosted at https://ethereumjs.github.io/ via [GitHub Pages](https://pages.github.com) and
build with [Jekyll](https://jekyllrb.com/) (see also ["Jekyll and GH Pages"](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/)).

It uses the [Cayman](https://github.com/jasonlong/cayman-theme) theme available as an option on GitHub.

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

To build the site locally you have to have a working [Ruby](https://www.ruby-lang.org) ``2.4.x`` environment (you can use the [RVM](https://rvm.io/) Ruby version manager for this) and ``bundle`` and ``Jekyll`` installed.

Install the ``GitHub pages`` gem from the ``Gemfile`` with:

```
bundle install
```

See also [this article](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) for further installation instructions.

The site can then be build with:

```
jekyll build
```

And being served on http://127.0.0.1:4000 with:

```
jekyll serve
```

[discord-badge]: https://img.shields.io/static/v1?logo=discord&label=discord&message=Join&color=blue
[discord-link]: https://discord.gg/TNwARpR
