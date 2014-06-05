# Adapt Sublime
## Sublime Text 3 Package

Adapt-Sublime is a Sublime Text 3 package for working with the the [Adapt Learning Framework](https://github.com/adaptlearning/adapt_framework). The package is a collection of snippets for working with Adapt components. Once installed (easiest method is using package control) you can simply type any of the commands such as `adapt-text` and hitting TAB. You can also start typing the command and cycle through a list of available commands.

## Installation

The easiest way to install Adapt-Sublime is with [Package Control](https://sublime.wbond.net/) and adding the repository directly with `Package Control: Add Repository` from the command pallette (`CTRL+SHIFT+P` for Windows or `CMD+SHIFT+P` for Mac OS).

You should type the master repository URL directly `https://github.com/jamieshepherd/adapt-sublime` and hit enter. This adds the repository to your Package control list. You can then open the command pallette again (`CTRL+SHIFT+P`) and install the package as usual with `Package Control: Install Package`. Adapt-sublime should show in the list, and Package Control will install the package shortly.

To recap, that's two simple steps for installing with Package Control:
* `Package Control: Add Repository` -> `https://github.com/jamieshepherd/adapt-sublime`
* `Package Control: Install Package` -> `adapt-sublime`

**Updates will automatically install if you've installed the extension by this method**

You can alternatively simply drop the .sublime_package file in your Sublime %APPDATA% folder.

## Usage

The following are the current available commands for adapt-sublime:

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

## Screenshots

![alt text](https://github.com/jamieshepherd/adapt-sublime/raw/master/Images/adapt-sublime-1.jpg "Simple dropdown snippets")

Simple dropdown snippets

![alt text](https://github.com/jamieshepherd/adapt-sublime/raw/master/Images/adapt-sublime-2.jpg  "Easy component generation, TAB through entities")

Easy component generation, TAB through entities

![alt text](https://github.com/jamieshepherd/adapt-sublime/raw/master/Images/adapt-sublime-3.jpg  "Sublime search guesses snippet titles")

Sublime search guesses snippet titles

## Contributing

Please feel free to fork and contribute snippets to this small package. New snippets are welcome, please add them to the Source folder. As multiple people may be working on individual snippets at the same time, please do not compile a .sublime_package, this will be done after a successful merge.

## License

This repository is released as open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
