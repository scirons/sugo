# Sciron's Hugo Theme

A simple grid-based Hugo theme I plan on using for my personal website, [Scirons](https://scirons.com) inspired by the greatest Swiss & Dutch design artists.

## Get started
```sh
hugo new site new-site
cd new-site
git clone https://github.com/scirons/sugo themes/sugo
echo "theme = 'sugo'" >> config.toml
cp themes/sugo/static/style.css static/
```

## Features

- Makes one RSS feed for the entire site at `/index.xml`
- Stylesheet is in `/style.css` and includes important style attributes for grids/partials.
- If a post is tagged, links to the tags are placed at the bottom of the post.
