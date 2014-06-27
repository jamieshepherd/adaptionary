# Adaptionary
## Sublime Text 3 Package

*Formerly Adapt-Sublime*

Adaptionary is a Sublime Text 3 package for working with the the [Adapt Learning Framework](https://github.com/adaptlearning/adapt_framework). The package is a collection of snippets for working with Adapt components. Once installed (easiest method is using package control) you can simply type any of the commands such as `adapt-text` and hitting TAB. You can also start typing the command and cycle through a list of available commands.

## Installation

The easiest way to install Adaptionary is with [Package Control](https://sublime.wbond.net/) which once installed can be brought up with the command pallette (`CTRL+SHIFT+P` for Windows or `CMD+SHIFT+P` for Mac OS).

Type and select `Package Control: Install Package` from the menu and start searching for Adaptionary. Adaptionary should show in the list, and when selected, Package Control will install the package automatically. That's it!

To recap, that's two simple steps for installing with Package Control:
* `Package Control: Install Package` -> `Adaptionary`

**Updates will automatically install if you've installed the extension by this method**

You can alternatively simply drop the .sublime_package file from releases in to your Sublime %APPDATA% folder.

## Usage

The following are the current available commands for Adaptionary:

- `adapt-accordion`, `adapt-accordion-item`
- `adapt-gmcq`, `adapt-gmcq-item`
- `adapt-graphic`, `adapt-graphic-full`
- `adapt-hotgraphic`, `adapt-hotgraphic-item`
- `adapt-matching`, `adapt-matching-item`
- `adapt-mcq`, `adapt-mcq-item`
- `adapt-media`
- `adapt-narrative`, `adapt-narrative-item`
- `adapt-text`
- `adapt-textinput`, `adapt-textinput-item`
- `adapt-vmcq`

You can now also add parent elements, such as contentObjects, articles, and blocks:

- `adapt-contentObject`
- `adapt-article`
- `adapt-block`

## Screenshots

![alt text](https://github.com/jamieshepherd/adaptionary/raw/master/Images/adaptionary-1.jpg "Simple dropdown snippets")

Simple dropdown snippets

![alt text](https://github.com/jamieshepherd/adaptionary/raw/master/Images/adaptionary-2.jpg  "Easy component generation, TAB through entities")

Easy component generation, TAB through entities

![alt text](https://github.com/jamieshepherd/adaptionary/raw/master/Images/adaptionary-3.jpg  "Sublime search guesses snippet titles")

Sublime search guesses snippet titles

## Contributing

Please feel free to fork and contribute snippets to this small package. New snippets are welcome, please add them to the Source folder. Please do not compile a .sublime_package.

## License

This repository is released as open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
