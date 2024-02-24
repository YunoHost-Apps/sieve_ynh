# Packaging an app, starting from this example

* Copy this app before working on it, using the ['Use this template'](https://github.com/YunoHost/example_ynh/generate) button on the Github repo.
* Edit the `manifest.json` with app specific info.
* Edit the `install`, `upgrade`, `remove`, `backup`, and `restore` scripts, and any relevant conf files in `conf/`.
  * Using the [script helpers documentation.](https://yunohost.org/packaging_apps_helpers)
* Add a `LICENSE` file for the package.
* Edit `doc/DISCLAIMER*.md`
* The `README.md` files are to be automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator

---
<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Example app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/example.svg)](https://dash.yunohost.org/appci/app/example) ![Working status](https://ci-apps.yunohost.org/ci/badges/example.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/example.maintain.svg)

[![Install Example app with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Example app quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

This is a dummy description of this app features


**Shipped version:** 1.0~ynh1

**Demo:** https://demo.example.com

## Screenshots

![Screenshot of Example app](./doc/screenshots/example.jpg)

## Documentation and resources

* Official app website: <https://example.com>
* Official user documentation: <https://yunohost.org/apps>
* Official admin documentation: <https://yunohost.org/packaging_apps>
* Upstream app code repository: <https://some.forge.com/example/example>
* YunoHost Store: <https://apps.yunohost.org/app/example>
* Report a bug: <https://github.com/YunoHost-Apps/example_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
or
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>