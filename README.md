# Not So Secret Sauce

We realized that at [Highgroove](http://highgroove.com), some of the
documentation we provide to developers that helps them do their jobs better
wasn't really our "secret sauce."

This repository, and its deployed counterpart at
<http://not-so-secret-sauce.highgroove.com/> is the result of making that
material public. We hope it helps you be a better developer!

## Site Quickstart

### Ruby

The site runs on Ruby 1.9.2. If using rvm ...

    rvm install 1.9.2

The site is configured to use a gemset; create one and switch to it ...

    rvm gemset use 1.9.2@not-so-secret-sauce --create

### Jekyll

The site uses the [Jekyll static site
generator](https://github.com/mojombo/jekyll). Install it as a gem ...

    gem install jekyll

Run a local version of the site that automatically updates as files are added
or changed ...

    jekyll --auto --server

The site runs by default at <http://localhost:4000/>

### Git

This repository does not have a `master` branch like most git repositories;
instead, commits are added to the `gh-pages` branch so the site deploys
correctly to [GitHub Pages](http://pages.github.com).

### GitHub

As a Highgroover ...

1. Clone the repository
2. Commit to the `gh-pages` branch
3. Push changes back up

As an open source contributor ...

1. [Fork the repository](http://help.github.com/fork-a-repo/)
2. Branch off of or commit directly to the `gh-pages` branch
3. [Send a pull request](http://help.github.com/send-pull-requests/)

## Site Details

### Twitter Bootstrap 2.0

The site is styled by [Twitter Bootstrap
2.0](http://twitter.github.com/bootstrap/).

### Adding a New Topic

TODO

## License

[© GNU Free Documentation License Version
1.3](http://www.gnu.org/copyleft/fdl.html)