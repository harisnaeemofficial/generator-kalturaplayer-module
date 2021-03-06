# generator-kalturaplayer-module

> [Yeoman](http://yeoman.io) generator for creating [Kaltura Player](https://github.com/kaltura/mwEmbed/) modules and plugins - lets you quickly set up a project following best practices.


## Getting Started

* Install Yeoman as super user [root or Administrator], run:

```bash
npm install -g yo
```
* Install generator-kalturaplayer-module as super user [root or Administrator], run:

```bash
npm install -g generator-kalturaplayer-module
```
* Clone [Kaltura Player](https://github.com/kaltura/mwEmbed/) to your machine

```bash
git clone https://github.com/kaltura/mwEmbed/
```

* Change working dir to the modules dir

```bash
cd mwEmbed/modules
```

* Finally, initiate the generator and follow the steps:

```bash
yo kalturaplayer-module
```

## Generators

Available generators:

* App(Module + optional plugins)
    - [kalturaPlayer-module](#app) (aka [kalturaPlayer-module:app](#app))
* Plugin
    - [kalturaPlayer-module:plugin](#plugin)

### App
Sets up a module, generating all the boilerplate you need to get started.

Example:
```bash
yo kalturaplayer-module
```

### Plugin
Generates a new plugin in an existibng module.

Example:
```bash
yo kalturaplayer-module:plugin myPluginName
```
>Plugin must be initiated from inside a module directory

## License

All code in this project is released under the AGPLv3 license unless a different license for a particular library is specified in the applicable library path.

Copyright © Kaltura Inc. All rights reserved.
