# Contribution Guide

This document describes how you can contribute documentation to Promitor.

The documentation for Promitor is stored in `/docs` and uses [Jekyll](https://jekyllrb.com/) with GitHub Pages.

## Running the documentation locally

You can easily run the documentation locally by using [Jekyll](https://jekyllrb.com/docs/):

1. Navigate to the `docs` directory

```shell
⚡ tkerkhove@tomkerkhove C:\promitor-legacy-docs
❯  cd docs
```

2. Serve documentation with Jekyll

```shell
⚡ tkerkhove@tomkerkhove C:\promitor-legacy-docs
❯  bundle exec jekyll serve
```

## Markdownlint

We use [markdownlint](https://github.com/DavidAnson/markdownlint)
to ensure that our markdown follows the same set of formatting guidelines.

You can install markdownlint by installing any required npm packages:

```shell
npm install
```

You can then run markdownlint using the following command:

```shell
npm run markdownlint
```

The markdownlint repository has information about various tools you can use to
integrate it with various different text editors.
