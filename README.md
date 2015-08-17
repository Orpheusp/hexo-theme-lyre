# Lyre

A minimalist theme for [Hexo]. (This documentation is derived from hexo defualt theme [landscape]: https://github.com/hexojs/hexo-theme-landscape .)

## Installation

### Install

``` bash
$ git clone https://github.com/Orpheusp/hexo-theme-lyre.git themes/landscape
```

**Lyre requires Hexo 2.4 and above.**

### Enable

Modify `theme` setting in `_config.yml` to `lyre`.

### Update

``` bash
cd themes/lyre
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Sidebar
sidebar: right
widgets:
- category
- tag
- tagcloud
- archives
- recent_posts

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
```

- **menu** - Navigation menu
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox]
- **sidebar** - Sidebar style. You can choose `left`, `right`, `bottom` or `false`.
- **widgets** - Widgets displaying in sidebar
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID

## Features

## Development

### Requirements

- Hexo 2.4+

[Hexo]: http://zespia.tw/hexo/
