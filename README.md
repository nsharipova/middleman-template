# Middleman ClearSight Edition

A nice default project template for [Middleman](http://middlemanapp.com), the fantastic static site building tool.

## Dependencies

- [Middleman](http://middlemanapp.com)
- [Slim](http://slim-lang.com/) templates
- [Sass](http://sass-lang.com/) with [Bourbon](http://bourbon.io/) & [Neat](http://neat.bourbon.io/)
- [CoffeeScript](http://coffeescript.org/) with [jQuery](http://jquery.com/)
- [Livereload](https://github.com/middleman/middleman-livereload)
- [PNGcrush](http://pmt.sourceforge.net/pngcrush/)
- [OptiPNG]()
- [JPEGoptim]()

## Setup

Quick setup:

```
./bin/setup
bundle exec middleman
```

Manual setup:

```
brew install pngcrush optipng jpegoptim
bundle
rake build:source
bundle exec middleman
```

## Usage

**Template usage below...replace with your own usage**

Clone this repo into your .middleman directory as clearsight

    git clone git@bitbucket.org:clearsightstudio/middleman-template.git ~/.middleman/clearsight

Now you can simply init new projects with the ClearSight template:

    middleman init -T=clearsight my-project

Just don't forget to update `~/.middleman/clearsight` every now and then.
