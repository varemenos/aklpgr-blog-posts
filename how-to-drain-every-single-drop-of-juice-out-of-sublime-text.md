# How to drain every single drop of juice out of Sublime Text
- Adonis K.
- varemenos
- 2013/09/30
- General
- published

<a name="Prologue"></a>
<h2><a href="#Prologue">Prologue</a></h2>

Countless frontend developer use Sublime Text and I'm no exception. This piece of software is so awesome, functional and customizable that forces you to love it.

Anyway, in this blog post I will share some of the packages and settings I'm using daily and since they make my day so much easier (This post will focus on Sublime Text 3 since I've switched to it about a month ago).

---

<a name="Package-Control"></a>
<h2><a href="#Package-Control">Package Control</a></h2>

Before we dig deep into the package world of Sublime Text, let me first quote a description of what Package Control is.

> A Sublime Text 2/3 package manager for easily discovering, installing, upgrading and removing packages. Also includes an automatic updater and package creation tool. Packages can be installed from GitHub, BitBucket or custom package repositories. The plugin uses a channel and repository system to allow users to find new packages over time without any work. It also supports working with packages that were manually installed.

<a name="Installation"></a>
<h3><a href="#Installation">Installation</a></h3>

There are different instructions depending on the version of Sublime Text you are using:

* For v2 you can find there [here](https://sublime.wbond.net/installation#st2)
* For v3 you can find there [here](https://sublime.wbond.net/installation#st3)

<a name="How-to-install-a-Package-via-Package-Control"></a>
<h3><a href="#How-to-install-a-Package-via-Package-Control">How to install a Package via Package Control</a></h3>

To install a package via Package Control you first have to display the Package Control palette which you can do by either using the shortcut `Ctrl` + `Shift` + `P` or by using the menu and going to `Preferences` -> `Package Control`. You will now be presented with the Package Control palette which offers you some options, one of them is `Package Control: Install Package`. Once you select it, the palette will display a list of available packages you can choose to install. Once you choose a package for installation, a message will appear in the status bar indicating the installation process, at the end of which you might need to restart Sublime Text so that the package can be initiated.

---

<a name="Packages"></a>
<h2><a href="#Packages">Packages</a></h2>

Most of Sublime Text's functionality comes from the Packages you decide to install. What I mean by functionality? Thats:

* build systems
* system highlighting
* themes and color schemes
* text handling functions and shortcuts + more
* Sublime Text UI enhancers
* more

__note #1__: To install these all you have to do is type the name you in the title of the package you like in the `Package Control: Install Package` feature.
__note #2__: All of these packages are supported by Sublime Text 3, and most should be supported by Sublime Text 2 as well.

<a name="Must-have-packages"></a>
<h3><a href="#Must-have-packages">Must have packages</a></h3>

<a name="BracketHighlighter"></a>
<h4><a href="#BracketHighlighter">BracketHighlighter</a></h4>

It's a bracket and tag highlighter for Sublime Text

<a name="SideBarEnhancements"></a>
<h4><a href="#SideBarEnhancements">SideBarEnhancements</a></h4>

Enhancements to Sublime Text sidebar. Files and folders.

<a name="Package-Syncing"></a>
<h4><a href="#Package-Syncing">Package Syncing</a></h4>

Keep your different Sublime Test installations synchronized across different machines. The package is using a different attempt rather than just build a link. It is basically syncing your user folder and you can define which files you would like to include in the sync. On the other hand you can also exclude files from the sync for example for platform depending settings or packages.

<a name="HTML5"></a>
<h4><a href="#HTML5">HTML5</a></h4>

HTML5 bundle for Sublime Text forked by Textmate's HTML5 bundle

<a name="Emmet"></a>
<h4><a href="#Emmet">Emmet</a></h4>

 the essential toolkit for web-developers. Emmet takes the snippets idea to a whole new level: you can type CSS-like expressions that can be dynamically parsed, and produce output depending on what you type in the abbreviation. Emmet is developed and optimized for web-developers whose workflow depends on HTML/XML and CSS, but can be used with programming languages too.

<a name="Emmet-CSS-Snippets"></a>
<h4><a href="#Emmet-CSS-Snippets">Emmet CSS Snippets</a></h4>

Emmet CSS snippets for Sublime Text. Works with CSS, LESS, SCSS and Sass.

<a name="Dictionaries"></a>
<h4><a href="#Dictionaries">Dictionaries</a></h4>

Hunspell UTF8 dictionaries for Sublime Text. [Spell check]

<a name="SublimeCodeIntel"></a>
<h4><a href="#SublimeCodeIntel">SublimeCodeIntel</a></h4>

Full-featured code intelligence and smart autocomplete engine

<a name="Custom-Syntax-Highlighters"></a>
<h3><a href="#Custom-Syntax-Highlighters">Custom Syntax Highlighters</a></h3>

<a name="SCSS"></a>
<h4><a href="#SCSS">SCSS</a></h4>

The TextMate SCSS Official Bundle. Now Compatible with SublimeText

<a name="ApacheConf"></a>
<h4><a href="#ApacheConf">ApacheConf.tmLanguage</a></h4>

You can now get your .htaccess files with syntax highlighting

<a name="GitConfig"></a>
<h4><a href="#GitConfig">Git Config</a></h4>

syntax highlighting for git files

<a name="INI"></a>
<h4><a href="#INI">INI</a></h4>

syntax highlighting for .ini files

<a name="JavaScriptNext-ES6-Syntax"></a>
<h4><a href="#JavaScriptNext-ES6-Syntax">JavaScriptNext - ES6 Syntax</a></h4>

Better JavaScript language definition for SublimeText. This builds on the language files commonly used and adds more fine grained matching and also includes new features from ECMAScript 6 like modules, succinct methods, arrow functions, classes, and accessors (ES5).

<a name="Themes-and-Schemes"></a>
<h4><a href="#Themes-and-Schemes">Themes and Schemes</a></h4>

<a name="Theme - Soda"></a>
<h4><a href="#Theme - Soda">Theme - Soda</a></h4>

This is by far the most used theme of Sublime Text

Dark and light custom UI themes for Sublime Text 2 and Sublime Text 3.

<a name="Tomorrow-Color-Schemes"></a>
<h4><a href="#Tomorrow-Color-Schemes">Tomorrow Color Schemes</a></h4>

I'm always switching between Tomorrow or Tomorrow Night when writing code, it's just so easy on my eyes.

<a name="TextMate-Kuroir-Theme"></a>
<h4><a href="#TextMate-Kuroir-Theme">TextMate-Kuroir-Theme</a></h4>

I use this quite a lot when writing blog posts in markdown. This you can't find to Package Control but you can add by opening the Package Control panel, selecting `Package Control: Add Repository` and then inserting this url: `https://github.com/MarioRicalde/TextMate-Kuroir-Theme.git`. After that you can install it just like any other package listed in Package Control.

<a name="Dayle-Rees-Color-Schemes"></a>
<h4><a href="#Dayle-Rees-Color-Schemes">Dayle Rees Color Schemes</a></h4>

A ton of awesome color schemes

Sublime Text 2 Themes (textmate) created by Dayle Rees.

<a name="QuickThemes"></a>
<h4><a href="#QuickThemes">QuickThemes</a></h4>

QuickThemes allows you to easily cycle through any combination of Sublime Text 2 preferences. The obvious use is for changing color schemes, themes, and fonts simultaneously, but any of the ST2 preferences are available.

<a name="Git"></a>
<h3><a href="#Git">Git</a></h3>

<a name="SidebarGit"></a>
<h4><a href="#SidebarGit">SidebarGit</a></h4>

Add git commands to sidebar. Textual port of komodin extension for sublime text.

<a name="GitGutter"></a>
<h4><a href="#GitGutter">GitGutter</a></h4>

A Sublime Text 2/3 plugin to see git diff in gutter

<a name="GitIgnore"></a>
<h4><a href="#GitIgnore">GitIgnore</a></h4>

Gitignore plugin for Sublime Text

<a name="Other-essential-and-interesting-Packages"></a>
<h3><a href="#Other-essential-and-interesting-Packages">Other essential and interesting Packages</a></h3>

<a name="SassBeautify"></a>
<h4><a href="#SassBeautify">SassBeautify</a></h4>

A Sublime Text plugin that beautifies Sass files.

<a name="LineEndings"></a>
<h4><a href="#LineEndings">LineEndings</a></h4>

On statusbar and on command palette.

<a name="JsFormat"></a>
<h4><a href="#JsFormat">JsFormat</a></h4>

Javascript formatting for Sublime Text

<a name="HTMLAttributes"></a>
<h4><a href="#HTMLAttributes">HTMLAttributes</a></h4>

HTML(5) attribute completions

<a name="FileDiffs"></a>
<h4><a href="#FileDiffs">FileDiffs</a></h4>

Shows diffs between the current file, or selection(s) in the current file, and clipboard, another file, or unsaved changes.

<a name="EditorConfig"></a>
<h4><a href="#EditorConfig">EditorConfig</a></h4>

helps developers define and maintain consistent coding styles between different editors and IDEs - Sublime plugin

<a name="Autoprefixer"></a>
<h4><a href="#Autoprefixer">Autoprefixer</a></h4>

Sublime plugin to prefix your CSS

<a name="sublimelint"></a>
<h4><a href="#sublimelint">sublimelint</a></h4>

Error highlighting in Sublime Text.

<a name="SyncedSidebar"></a>
<h4><a href="#SyncedSidebar">SyncedSidebar</a></h4>

Sublime Text plugin to sync project sidebar (folder view) with currently active file.

<a name="More"></a>
<h3><a href="#More">More</a></h3>

For more you can check [package control's website](https://sublime.wbond.net/). It contains a list of popular, trending and new packages, it also gives you the ability to search by label or by text input.

---

<a name="Settings"></a>
<h2><a href="#Settings">Settings</a></h2>

I won't go much for Settings right now (since I'm kinda off schedule) so for now you can check the settings I'm using by visiting [this link](https://github.com/varemenos/veSettingsST3)
