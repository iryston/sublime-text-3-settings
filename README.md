# Sublime Text 3 settings

Sublime Text 3 sync settings repository

## Prerequisites

- [Sublime Text](http://www.sublimetext.com/) - if you haven't even installed the text editor yet, go and install the text editor.
- [Node Version Switcher](https://github.com/jasongin/nvs) - A cross-platform tool for switching between versions and forks of Node.js.

## Installation

**MAKE BACKUP BEFORE USING THIS COMMANDS**

- MacOS
```
rm -rf ~/Library/Application\ Support/Sublime\ Text\ 3/
```
```
git clone git@github.com:iryston/sublime-text-3-settings.git ~/Library/Application\ Support/Sublime\ Text\ 3/
```
- Linux
```
rm -rf ~/.config/sublime-text-3
```
```
git clone git@github.com:iryston/sublime-text-3-settings.git ~/.config/sublime-text-3
```

## Installed Plugins
Before using plugins, ensure that Node.js and related packages are installed on your system.


### Package Control
[Package Control](https://packagecontrol.io/) - an essential package manager for Sublime Text

### DocBlockr
[DocBlockr](https://packagecontrol.io/packages/DocBlockr) - Simplifies writing DocBlock comments in Javascript, PHP, CoffeeScript, Actionscript, C & C++

### EditorConfig
[EditorConfig](https://packagecontrol.io/packages/EditorConfig) - Helps developers maintain consistent coding styles between different editors

### Emmet
[Emmet](https://packagecontrol.io/packages/Emmet) - Official Emmet plugin for Sublime Text

### Git
[Git](https://packagecontrol.io/packages/Git) - Plugin for some git integration into sublime text

### GitGutter
[GitGutter](https://packagecontrol.io/packages/GitGutter) - Plugin to show information about files in a git repository

### HTML-CSS-JS Prettify
[HTML-CSS-JS Prettify](https://packagecontrol.io/packages/HTML-CSS-JS%20Prettify) - HTML, CSS, JavaScript, JSON, React/JSX and Vue code formatter for Sublime Text 2 and 3 via node.js

Install the NPM package
```npm -g install js-beautify```

### Sass
[Sass](https://packagecontrol.io/packages/Sass) - Sass and SCSS syntax for Sublime Text

### SideBarTools
[SideBarTools](https://packagecontrol.io/packages/SideBarTools) - Duplicate or compare files and copy paths from the Side Bar

### SublimeLinter - a plugin for Sublime Text that provides a framework for linting code.
[SublimeLinter documentation](http://www.sublimelinter.com/en/latest/index.html)

#### [SublimeLinter-csslint](https://packagecontrol.io/packages/SublimeLinter-csslint)
This linter plugin for SublimeLinter provides an interface to csslint.
It will be used with files that have the “CSS” syntax, or within <style> tags in HTML files.
Ensure that csslint (version 0.10.0 or later) is installed on your system.

To install csslint, do the following:
```npm install -g csslint```

#### [SublimeLinter-eslint](https://packagecontrol.io/packages/SublimeLinter-eslint)
This linter plugin for SublimeLinter provides an interface to ESLint. It will be used with files that have the “javascript” syntax.

Install eslint globally by typing the following in a terminal:
```npm install -g eslint```

#### [SublimeLinter-html-tidy](https://packagecontrol.io/packages/SublimeLinter-html-tidy)
This linter plugin for SublimeLinter provides an interface to tidy (either the html4 or html5 version). It will be used with files that have the “HTML” syntax.

Before installing this plugin, you must ensure that tidy or tidy5 are installed on your system. tidy5 will be used over tidy if available.

- MacOS – tidy comes preinstalled on recent versions of Mac OS X. You can install the html5 version by using Homebrew and `brew install tidy-html5`.
- Linux – You should be able to install tidy using the system’s package manager.

### Terminal
[Terminal](https://packagecontrol.io/packages/Terminal) - Launch terminals from the current file or the root project folder
