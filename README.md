# Sahneeis.de

**Single-Page-Website** based on Bourbon, Neat, Bitters, Refills and created by Middleman. Originally forked from the [Proteus gem](https://github.com/thoughtbot/proteus) which provide some shortcuts.

# Template

Feel free to clone this repositority as starting point for your own single-page-website

## Getting Started

Set up your project in your code directory
```
git clone git@github.com:netzfisch/sahneeis.de.git your-project-folder
cd your-project-folder
git remote rm origin
git remote add origin your-git-url
```

Install dependencies:
```
bundle install
```

Run the server for local preview
```
middleman server
```

Deploy to FTP, Github Pages, etc.
```
middleman build
middleman deploy

```

## Update

To update the gems do
```
bundle update
```

If you need to update refills CSS skeleton do
```
cd source/assets/stylesheets/
gem install bitters
bitters remove
bitters install
git diff
```

Inspect the diff and than commit.

## Includes
--------
* [HAML](http://haml.info):
  Simple template markup
* [Coffeescript](http://coffeescript.org):
  Write javascript with simpler syntax
* [Sass](http://sass-lang.com):
  CSS with superpowers
* [Bourbon](http://bourbon.io):
  Sass mixin library
* [Neat](http://neat.bourbon.io):
  Semantic grid for Sass and Bourbon
* [Bitters](http://bitters.bourbon.io):
  Scaffold styles, variables and structure for Bourbon projects.
* [Font Awesome](http://fortawesome.github.io/Font-Awesome):
  The iconic font and CSS toolkit
* [Middleman Live Reload](https://github.com/middleman/middleman-livereload):
  Reloads the page when files change
* [Middleman Deploy](https://github.com/karlfreeman/middleman-deploy):
  Deploy your Middleman build via rsync, ftp, sftp, or git (deploys to Github Pages by default)

## Directories

Stylesheets, fonts, images, and javascript files go in the `/source/assets/` directory.
Vendor stylesheets and javascripts should go in each of their `/vendor/` directories.

## Contributing

If you have problems, please create a
[GitHub Issue](https://github.com/netzfisch/sahneeis.de/issues).

Have a fix or want to add a feature?
[Pull Requests](https://github.com/netzfisch/sahneeis.de/pulls) are welcome!

# License

The following directories and their contents are Copyright of netzfisch. You may
not reuse anything therein without my permission:

* source/assets/audio/
* source/assets/images/

Everything else is free software, and may be redistributed under the terms specified in the LICENSE file.
