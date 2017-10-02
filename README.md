# tomduncs/fabricator

This is a fork of [Fabricator](http://fbrctr.github.io), consolidating several modifications that have evolved after use on various projects:

* Loading jQuery as a separate javascript file - this helps to prevent problems when using the toolkit in a Wordpress theme.
* Renaming structures to modules
* Adding a third material "elements" for raw unclassed html elements e.g. input, table, button
* Re-ordering the sidebar
* Adding a Handlebars helper function "default" e.g. for customising text on a component that is included in multiple places
* Including Normalize.css
* Including some other starter css and skeleton structure
* Minor language/copy changes

# Fabricator

> _fabricate_ - to make by assembling parts or sections.

Fabricator is a tool for building website UI toolkits - _think ["Tiny Bootstraps, for Every Client"](http://daverupert.com/2013/04/responsive-deliverables/#tiny-bootstraps-for-every-client)_

## Quick Start

```shell
$ curl -L https://github.com/fbrctr/fabricator/archive/master.tar.gz | tar zx --strip 1
$ npm start
```

## Documentation

#### [Read the docs →](http://fbrctr.github.io/docs)

## Demo

#### [Default Fabricator Instance →](http://fbrctr.github.io/demo)

## Credits

Created by [Luke Askew](http://twitter.com/lukeaskew).

Logo by [Abby Putinski](https://abbyputinski.com/)

## License

[The MIT License (MIT)](http://opensource.org/licenses/mit-license.php)
