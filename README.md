# sublime-less2css

Sublime Text 2 Plugin to compile less files to css on save

# Features


 * Automatically compile less -> css on save when editing a .less file in sublime
 * Reports compilation errors
 * Compile all less files in a directory to css files
 * Auto-compile less files that @import the current less file
 * Per-project output paths
 
NB This plugin requires lessc to be in your execution path 

# Installation

## Install The Plugin

Either clone into your sublime packages directory, or just use [Package Control](https://github.com/wbond/sublime_package_control/)

## Install Requirements

Less2Css requires lessc to compile less to css.

### Mac OS X / Linux(Ubuntu/Debian…)

1. Install [NodeJS](http://nodejs.org) (you may need nodejs-legacy - see [issue #23](https://github.com/timdouglas/sublime-less2css/issues/23))
2. Install npm([NodeJS Package Manager](https://npmjs.org/doc/README.html))
3. Install [less](http://lesscss.org)

## 
    npm install less -gd
    

### Windows

1. Clone [less.js-windows](https://github.com/duncansmart/less.js-windows)
2. Add the path of your less.js-windows to PATH environment variable([How to?](http://msdn.microsoft.com/en-us/library/ee537574.aspx)).

[中文版详细安装教程](http://fdream.net/blog/article/783.aspx)

# Credits

Huge thanks to everyone who has contributed to the plugin

Massive thanks has to go to the team behind the [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements) project who solved the inability to set project-specific settings

And of coure thanks to Alexis Sellier for creating less in the first place!
