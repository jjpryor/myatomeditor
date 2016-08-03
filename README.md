# My Atom Editor settings

In the screenshot below, atom is using `puppet-lint` and `puppet parser validate`
to indicate errors and warnings in sample pupept code.

![Image of Shell](https://github.com/jjpryor/myatomeditor/raw/master/atomsyntaxcheck.png)
## Installation
For Red Hat Family of OSs we will get the RPM for the Atom editor from a COPR:

https://copr.fedorainfracloud.org/coprs/mosquito/atom/

For other OSs, you can also get it directly from: https://atom.io

### For RHEL7 / Cento7:
```shell
yum install https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
cd /etc/yum.repos.d/
wget https://copr.fedorainfracloud.org/coprs/mosquito/atom/repo/epel-7/mosquito-atom-epel-7.repo
yum install atom
```

### For Fedora:
```shell
dnf copr enable mosquito/atom
dnf install atom
```

----------

## Community Packages (add-ons/plugins) that make Atom awesome
### My Must-Have for Puppet coding:
+ file-icons: https://atom.io/packages/file-icons
+ git-log: https://atom.io/packages/git-log
+ git-plus: https://atom.io/packages/git-plus
+ language-puppet: https://atom.io/packages/language-puppet
+ linter: https://atom.io/packages/linter
+ linter-puppet-parser: https://atom.io/packages/linter-puppet-parser
  + https://github.com/asquelt/linter-puppet-parser
     + Allows you to pass args to puppet `'puppetArguments': '--parser future'`
+ linter-puppet-lint: https://atom.io/packages/linter-puppet-lint
+ minimap: https://atom.io/packages/minimap


### Nice to have for puppet &amp; ruby:
+ autocomplete-ruby:https://atom.io/packages/autocomplete-ruby
+ erb-helper: https://atom.io/packages/erb-helper
+ linter-erb: https://atom.io/packages/linter-erb
+ linter-ruby: https://atom.io/packages/linter-ruby
+ ruby-block-converter: https://atom.io/themes/ruby-block-converter


### Nice to have for other languages:
+ atom-beautify: https://atom.io/packages/atom-beautify
+ atom-notifier: https://atom.io/packages/atom-notifier
+ browser-plus: https://atom.io/packages/browser-plus
+ open-in-browsers: https://atom.io/packages/open-in-browsers
+ open-terminal-here: https://atom.io/packages/open-terminal-here
+ language-ansible: https://atom.io/packages/language-ansible
+ linter-ansible-linting: https://atom.io/packages/linter-ansible-linting
+ linter-shellcheck: https://atom.io/packages/linter-shellcheck

---------

## My fav UI Theme &amp; Syntax Theme
+ atom-material-ui: https://atom.io/themes/atom-material-ui
+ seti-syntax: https://atom.io/themes/seti-syntax
