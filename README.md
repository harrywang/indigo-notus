# About

Tailpages (Tailwind + Github Pages) is a Github Pages (Jekyll) Template based on Tailwind

This is based on:

- [Indigo Minimalist Jekyll Template](https://sergiokopplin.github.io/indigo)
- [Notus JS: Free Tailwind CSS UI Kit and Admin](https://github.com/creativetimofficial/notus-js)

# Setup and Testing

NOTE: for Mac M1 users:

- follow https://www.earthinversion.com/blogging/how-to-install-jekyll-on-appple-m1-macbook/ to install jekyll ARM compatible version


then follow the instruction below:

- Install [Jekyll](https://jekyllrb.com) and [Bundler](https://bundler.io/).
- Clone the forked repo on your machine
- Enter the cloned folder via terminal and run `bundle install`
- (optional for Jekyll 3.0) run `bundle add webrick` according to https://github.com/github/pages-gem/issues/752
- Then run `bundle exec jekyll serve`
- Open it in your browser: `http://localhost:4000`
- Do you want to use the [jekyll-admin](https://jekyll.github.io/jekyll-admin/) plugin to edit your posts? Go to the admin panel: `http://localhost:4000/admin`. The admin panel will not work on GitHub Pages, [only locally](https://github.com/jekyll/jekyll-admin/issues/341#issuecomment-292739469).

# Customization

You can change `_config.yml` to customize your site.
