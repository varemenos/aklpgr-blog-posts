# How to drain every single drop of juice out of Sublime Text
- Adonis K.
- varemenos
- 2013/09/30
- CSS
- published

## Prologue

Countless frontend developer use Sublime Text and I'm no exception. This piece of software is so awesome, functional and customizable that forces you to love it.

Anyway, in this blog post I will share some of the packages and settings I'm using daily and since they make my day so much easier (This post will focus on Sublime Text 3 since I've switched to it about a month ago).

---

## Package Control

Before we dig deep into the package world of Sublime Text, let me first quote a description of what Package Control is.

> A Sublime Text 2/3 package manager for easily discovering, installing, upgrading and removing packages. Also includes an automatic updater and package creation tool. Packages can be installed from GitHub, BitBucket or custom package repositories. The plugin uses a channel and repository system to allow users to find new packages over time without any work. It also supports working with packages that were manually installed.

### Installation

There are different instructions depending on the version of Sublime Text you are using:

* For v2 you can find there [here](https://sublime.wbond.net/installation#st2)
* For v3 you can find there [here](https://sublime.wbond.net/installation#st3)

### How to install a Package via Package Control

To install a package via Package Control you first have to display the Package Control palette which you can do by either using the shortcut `Ctrl` + `Shift` + `P` or by using the menu and going to `Preferences` -> `Package Control`. You will now be presented with the Package Control palette which offers you some options, one of them is `Package Control: Install Package`. Once you select it, the palette will display a list of available packages you can choose to install. Once you choose a package for installation, a message will appear in the status bar indicating the installation process, at the end of which you might need to restart Sublime Text so that the package can be initiated.

---

## Packages

Most of Sublime Text's functionality comes from the Packages you decide to install. What I mean by functionality? Thats:

* build systems
* system highlighting
* themes and color schemes
* text handling functions and shortcuts + more
* Sublime Text UI enhancers
* more

### Must have packages

#### BracketHighlighter

It's a bracket and tag highlighter for Sublime Text

#### SideBarEnhancements

Enhancements to Sublime Text sidebar. Files and folders.

#### Package Syncing

Keep your different Sublime Test installations synchronized across different machines. The package is using a different attempt rather than just build a link. It is basically syncing your user folder and you can define which files you would like to include in the sync. On the other hand you can also exclude files from the sync for example for platform depending settings or packages.

#### HTML5

HTML5 bundle for Sublime Text forked by Textmate's HTML5 bundle

#### Emmet

 the essential toolkit for web-developers. Emmet takes the snippets idea to a whole new level: you can type CSS-like expressions that can be dynamically parsed, and produce output depending on what you type in the abbreviation. Emmet is developed and optimized for web-developers whose workflow depends on HTML/XML and CSS, but can be used with programming languages too.

#### Emmet CSS Snippets

Emmet CSS snippets for Sublime Text. Works with CSS, LESS, SCSS and Sass.

#### Dictionaries

Hunspell UTF8 dictionaries for Sublime Text. [Spell check]

#### SublimeCodeIntel

Full-featured code intelligence and smart autocomplete engine

### Custom Syntax Highlighters

#### SCSS

The TextMate SCSS Official Bundle. Now Compatible with SublimeText

#### ApacheConf.tmLanguage

You can now get your .htaccess files with syntax highlighting

#### Git Config

syntax highlighting for git files

#### INI

syntax highlighting for .ini files

#### JavaScriptNext - ES6 Syntax

Better JavaScript language definition for SublimeText. This builds on the language files commonly used and adds more fine grained matching and also includes new features from ECMAScript 6 like modules, succinct methods, arrow functions, classes, and accessors (ES5).

### Themes and Schemes

#### Theme - Soda

This is by far the most used theme of Sublime Text

Dark and light custom UI themes for Sublime Text 2 and Sublime Text 3.

#### Tomorrow Color Schemes

I'm always switching between Tomorrow or Tomorrow Night when writing code, it's just so easy on my eyes.

#### TextMate-Kuroir-Theme

I use this quite a lot when writing blog posts in markdown. This you can't find to Package Control but you can add by opening the Package Control panel, selecting `Package Control: Add Repository` and then inserting this url: `https://github.com/MarioRicalde/TextMate-Kuroir-Theme.git`. After that you can install it just like any other package listed in Package Control.

#### Dayle Rees Color Schemes

A ton of awesome color schemes

Sublime Text 2 Themes (textmate) created by Dayle Rees.

#### QuickThemes

QuickThemes allows you to easily cycle through any combination of Sublime Text 2 preferences. The obvious use is for changing color schemes, themes, and fonts simultaneously, but any of the ST2 preferences are available.

### Git

#### SideBarGit

Add git commands to sidebar. Textual port of komodin extension for sublime text.

#### GitGutter

A Sublime Text 2/3 plugin to see git diff in gutter

#### Gitignore

Gitignore plugin for Sublime Text

### Other essential and interesting Packages

#### SassBeautify

A Sublime Text plugin that beautifies Sass files.

#### LineEndings

On statusbar and on command palette.

#### JsFormat

Javascript formatting for Sublime Text

#### HTMLAttributes

HTML(5) attribute completions

#### FileDiffs

Shows diffs between the current file, or selection(s) in the current file, and clipboard, another file, or unsaved changes.

#### EditorConfig

helps developers define and maintain consistent coding styles between different editors and IDEs - Sublime plugin

#### Autoprefixer

Sublime plugin to prefix your CSS

#### sublimelint

Error highlighting in Sublime Text.

#### SyncedSideBar

Sublime Text plugin to sync project sidebar (folder view) with currently active file.

### More

For more you can check [package control's website](https://sublime.wbond.net/). It contains a list of popular, trending and new packages, it also gives you the ability to search by label or by text input.

---

## Settings

I won't go much for Settings right now (since I'm kinda off schedule) so for now you can check the settings I'm using by visiting [this link](https://github.com/varemenos/veSettingsST3)
