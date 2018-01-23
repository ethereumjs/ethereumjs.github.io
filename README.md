# SYNOPSIS

[![Gitter](https://img.shields.io/gitter/room/ethereum/ethereumjs-lib.svg?style=flat-square)](https://gitter.im/ethereum/ethereumjs-lib) or #ethereumjs on freenode 

# INTRODUCTION

Website to give an overview of the various ``EthereumJS`` projects and an 
introduction to the ecosystem and the community.

Site is hosted at https://ethereumjs.github.io/ via [GitHub Pages](https://pages.github.com) and
build with [Jekyll](https://jekyllrb.com/) (see also ["Jekyll and GH Pages"](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/)).

You can update the site by editing the markdown in [./index.md](./index.md) (via PR), build will be
triggered automatically on merge.

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



