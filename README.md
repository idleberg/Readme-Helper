# Readme Helper

[![GitHub release](https://img.shields.io/github/release/idleberg/Readme-Helper.svg?style=flat-square)](https://github.com/idleberg/Readme-Helper/releases)
[![Travis](https://img.shields.io/travis/idle/Readme-Helper.svg?style=flat-square)](https://travis-ci.org/idle/Readme-Helper)

Snippets for [Sublime Text](http://www.sublimetext.com/) to speed up the process of writing Readme files, supporting [Markdown](http://daringfireball.net/projects/markdown/), [reStructuredText](http://docutils.sourceforge.net/rst.html) and [Textile](http://txstyle.org/).

## Installation

### Package Control

1. Make sure you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed
2. Choose *Install Package* from the Command Palette (`Ctrl+Shift+P` on Windows/Linux, `⇧⌘P` on OS X)
3. Select *Readme Helper* and press `Enter`

### GitHub

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/Readme-Helper.git`

### Manual installation

1. Download the files using the GitHub [.zip](https://github.com/idleberg/Readme-Helper/archive/master.zip) download option
2. Unzip the files to your Sublime Text `Packages` directory

## Usage

By default, command completion should be enabled in all Sublime Text versions. If the completion popup doesn't show while typing one of the following commands, you can force showing it using `Ctrl+Space` or by adding the right scope to your user settings under `auto_complete_selector`.

All command completions are prefixed with `rm`. Thanks to Sublime Text fuzzy search, you can use shortcuts such as `rmppl` to trigger `rm:paypal` or `rmsf` to trigger `rm:sourceforge`.

See below for a full list of available commands.

### Scaffolding

`rm:scaffold_sublimetext`
instructions for Sublime Text Package Control

`rm:scaffold_grunt`
instructions for a Grunt package

`rm:scaffold_node`
(very basic) instructions for the Node Package Manager

`rm:scaffold_node`
a [readme](https://wordpress.org/plugins/about/readme.txt) for a Wordpress plugin

### Snippets

#### Licenses

Trigger         | License
----------------|--------
`rm:apache`     | [Apache License, Version 2.0](http://opensource.org/licenses/Apache-2.0)
`rm:bsd2`       | [BSD 2-Clause License](http://opensource.org/licenses/BSD-2-Clause)  
`rm:bsd3`       | [BSD 3-Clause License](http://opensource.org/licenses/BSD-3-Clause)
`rm:ccby3`      | [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/)
`rm:cc0`        | [Creative Commons CC0 1.0 Universal](http://creativecommons.org/publicdomain/zero/1.0/legalcode)
`rm:ccby4`      | [Creative Commons Attribution 4.0 Unported License](http://creativecommons.org/licenses/by/4.0/)
`rm:ccbync3`    | [Creative Commons Attribution-NonCommercial 3.0 Unported License](http://creativecommons.org/licenses/by-nc/3.0/)
`rm:ccbync4`    | [Creative Commons Attribution-NonCommercial 4.0 Unported License](http://creativecommons.org/licenses/by-nc/4.0/)
`rm:ccbyncnd3`  | [Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License](http://creativecommons.org/licenses/by-nc-nd/3.0/)
`rm:ccbyncnd4`  | [Creative Commons Attribution-NonCommercial-NoDerivs 4.0 Unported License](http://creativecommons.org/licenses/by-nc-nd/4.0/)
`rm:ccbyncsa3`  | [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-nc-sa/3.0/)
`rm:ccbyncsa4`  | [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 Unported License](http://creativecommons.org/licenses/by-nc-sa/4.0/)
`rm:ccbynd3`    | [Creative Commons Attribution-NoDerivs 3.0 Unported License](http://creativecommons.org/licenses/by-nd/3.0/)
`rm:ccbynd4`    | [Creative Commons Attribution-NoDerivs 4.0 Unported License](http://creativecommons.org/licenses/by-nd/4.0/)
`rm:ccbysa3`    | [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/)
`rm:ccbysa4`    | [Creative Commons Attribution-ShareAlike 4.0 Unported License](http://creativecommons.org/licenses/by-sa/4.0/)
`rm:afferogpl3` | [GNU Affero General Public License 3.0](http://opensource.org/licenses/AGPL-3.0)
`rm:gpl2`       | [GNU General Public License 2.0](http://opensource.org/licenses/GPL-2.0)
`rm:gpl3`       | [GNU General Public License 3.0](http://opensource.org/licenses/GPL-3.0)
`rm:lgpl2`      | [GNU Lesser General Public License 2.1](http://opensource.org/licenses/LGPL-2.1)
`rm:mit`        | [The MIT License](http://opensource.org/licenses/MIT)
`rm:zlib`       | [The zlib/libpng License](http://opensource.org/licenses/Zlib)

#### Badges

Trigger                       | Badge                                           | Example
------------------------------|-------------------------------------------------|--------
`rm:cocoapod_version`         | [CocoaPod](http://badge.fury.io/for/co)         | ![Pod version](https://badge.fury.io/co/Promises.svg)
`rm:codeclimate`              | [Code Climate](https://coveralls.io/)           | n/a
`rm:coveralls`                | [Coverage](https://coveralls.io/)               | ![Coverage](https://s3.amazonaws.com/assets.coveralls.io/badges/coveralls_100.png)
`rm:cpan_version`             | [Perl](http://badge.fury.io/for/pl)             | ![CPAN version](https://badge.fury.io/pl/perl.svg)
`rm:bitdeli`                  | [BitDeli](https://bitdeli.com/)                 | ![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/idleberg/readme-helper/trend.png)
`rm:bower_version`            | [Bower](http://badge.fury.io/for/bo)            | ![Bower package](https://badge.fury.io/bo/jquery.svg)
`rm:david`                    | [Depencies](https://david-dm.org/)              | [![devDependencies](https://david-dm.org/idleberg/Readme-Helper.svg)](https://david-dm.org/idleberg/Readme-Helper#info=devDependencies)
`rm:david_dev`                | [devDepencies](https://david-dm.org/)           | [![devDependencies](https://david-dm.org/idleberg/Readme-Helper/dev-status.svg)](https://david-dm.org/idleberg/Readme-Helper#info=devDependencies)
`rm:flattr`                   | [Flattr](http://flattr.com/) (badge)            | ![Flattr this](https://api.flattr.com/button/flattr-badge-large.png)
`rm:flattr_icon`              | [Flattr](http://flattr.com/) (icon)             | ![Flattr this](https://flattr.com/_img/icons/flattr_logo_16.png)
`rm:gem_version`              | [gem version](http://badge.fury.io/for/rb)      | ![gem version](https://badge.fury.io/rb/gem.svg)
`rm:grunt`                    | [Grunt](http://gruntjs.com/)                    | ![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)
`rm:github_follow`            | [GitHub](http://ghbtns.com/) (follow button)    | <iframe src="http://ghbtns.com/github-btn.html?user=idleberg&type=follow" allowtransparency="true" frameborder="0" scrolling="0" width="132" height="20"></iframe>
`rm:github_follow_count`     | [GitHub](http://ghbtns.com/) (follow count)      | <iframe src="http://ghbtns.com/github-btn.html?user=idleberg&type=follow&count=true" allowtransparency="true" frameborder="0" scrolling="0" width="165" height="20"></iframe>
`rm:github_fork`              | [GitHub](http://ghbtns.com/) (fork)             | <iframe src="http://ghbtns.com/github-btn.html?user=idleberg&repo=Readme-Helper&type=fork" allowtransparency="true" frameborder="0" scrolling="0" width="53" height="20"></iframe>
`rm:github_fork_count`        | [GitHub](http://ghbtns.com/) (fork count)       | <iframe src="http://ghbtns.com/github-btn.html?user=idleberg&repo=Readme-Helper&type=fork&count=true" allowtransparency="true" frameborder="0" scrolling="0" width="95" height="20"></iframe>
`rm:github_star`              | [GitHub](http://ghbtns.com/) (star)             | <iframe src="http://ghbtns.com/github-btn.html?user=idleberg&repo=github-buttons&type=watch" allowtransparency="true" frameborder="0" scrolling="0" width="62" height="20"></iframe>
`rm:github_star_count`        | [GitHub](http://ghbtns.com/) (star count)       | <iframe src="http://ghbtns.com/github-btn.html?user=idleberg&repo=Readme-Helper&type=watch&count=true" allowtransparency="true" frameborder="0" scrolling="0" width="110" height="20"></iframe>
`rm:github_star_large_count`  | [GitHub](http://ghbtns.com/) (large star count) | <iframe src="http://ghbtns.com/github-btn.html?user=idleberg&repo=Readme-Helper&type=watch&count=true&size=large" allowtransparency="true" frameborder="0" scrolling="0" width="170" height="30"></iframe>
`rm:github_version`           | [GitHub](http://badge.fury.io/for/gh)           | ![GitHub version](https://badge.fury.io/gh/idleberg%2FBootstrap-Listr.svg)
`rm:gitter`                   | [Gitter](https://gitter.im)                     | [![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/gitterHQ/gitter)
`rm:landscape`                | [Landscape](https://landscape.io)               | n/a
`rm:nuget_version`            | [NuGet](http://badge.fury.io/for/nu)            | ![NuGet version](https://badge.fury.io/nu/jquery.svg)
`rm:paypal`                   | [Paypal](http://paypal.com/)                    | ![Donate](https://www.paypalobjects.com/WEBSCR-640-20110429-1/en_US/i/btn/btn_donate_SM.gif)
`rm:pypi_version`             | [PyPI](http://badge.fury.io/for/py)             | ![PyPI version](https://badge.fury.io/py/pypi.svg)
`rm:php_version`              | [PHP](http://badge.fury.io/for/ph)              | ![PHP version](https://badge.fury.io/ph/simplepie%2Fsimplepie.svg)
`rm:npm_version`              | [npm module](https://www.npmjs.org/)            | ![npm module](https://badge.fury.io/js/npm.svg)
`rm:travis`                   | [Travis](http://travis-ci.org/)                 | ![Travis](https://secure.travis-ci.org/idleberg/Readme-Helper.svg)

#### URLs

Trigger                  | Target                   | Example
-------------------------|--------------------------|--------
`rm:bitbucket_repo`      | Bitbucket repository     | https://bitbucket.org/user/repository
`rm:github_repo`         | GitHub repository        | https://github.com/user/repository
`rm:github_user`         | GitHub user profile      | https://github.com/user
`rm:github_webpage`      | GitHub web page          | https://user.github.io/repository
`rm:gitorious_repo`      | Gitorious repository     | https://gitorious.org/user/repository
`rm:googlecode`          | Google Code project      | https://code.google.com/p/project
`rm:heroku_webpage`      | Heroku web page          | http://example.herokuapp.com
`rm:sourceforge`         | SourceForge project page | https://sourceforge.net/projects/example
`rm:sourceforge_webpage` | SourceForge web page     | http://example.sourceforge.net

## Contributions

If you'd like to contribute to this project, feel invited to commit to this repository!

## License

The MIT License (MIT)

Copyright (c) 2013 Jan T. Sott

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/Readme-Helper) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`