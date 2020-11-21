# The Loft — Website

Welcome to the source code of The Loft's [website](https://loftware.org)

## Infrastructure

The site is developed as a [Jekyll](https://jekyllrb.com) website,
and is being served by [GitHub Pages](https://pages.github.com).

## Conventions and Guidelines

* Avoid unnecessary HTML tags; use Markdown formatting to the degree possible.
* Wrap lines at 80 columns to support diff-friendly change tracking.

## Development Hints

Creating a complete installation of jekyll and all the parts needed for github
pages development can be fraught.  If you install
[docker-compose](https://docs.docker.com/compose/), you can start a webserver
serving the site at http://localhost:4000 by invoking

```
docker-compose up
```

in the root directory of your working copy.
