# Compile BH Prototype one using Hugo Icon Theme

![](images/screenshot.png)

## Installation from scratch

Follow the themes guide on the [Hugo website](https://gohugo.io/themes/installing-and-using-themes/). Briefly, within your Hugo folder:

```sh
$ cd themes
$ git clone https://github.com/SteveLane/hugo-icon.git
```

## Getting started

## Adding additional pages

If you'd like to add additional pages, say for a blog, place your content in `/content/blog/` (with an `_index.md` and additional markdown files for each entry).

To link to it from the main menu, add the following line to `layouts/partials/nav.html`:

```html
<a href="/blog" onclick="location.href='/blog';">Blog</a>
```

## Addition Information

## Changelog

A changelog for the initial port by @SteveLane is [here](changelog.md); if you fork this theme and make changes, please list them.
