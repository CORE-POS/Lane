# Lane
[![travis-ci](https://travis-ci.org/CORE-POS/Lane.svg?branch=master)](https://travis-ci.org/CORE-POS/Lane)

Standalone lane repo

# Install
The lane require [composer](https://getcomposer.org/). Install it then run:
`composer install`

Next browse the pos/is4c-nf/install folder. You may be prompted to create pos/is4c-nf/ini.json and give the webserver write permission to it.

# Plugins
Plugins can be installed from [plugins.core-pos.com](https://plugins.core-pos.com) using `composer require`. You can also install plugins in `pos/is4c-nf/plugins/` by simply using `git clone` or even just editing locally. Plugins are considered separate entities from this repository and will be ignored regardless of how they're installed.
