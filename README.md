<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Plume for YunoHost

[![Integration level](https://dash.yunohost.org/integration/plume.svg)](https://dash.yunohost.org/appci/app/plume) ![Working status](https://ci-apps.yunohost.org/ci/badges/plume.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/plume.maintain.svg)

[![Install Plume with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plume)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Plume quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database.


**Shipped version:** 0.7.2~ynh1

**Demo:** https://joinplu.me/#instances

## Screenshots

![Screenshot of Plume](./doc/screenshots/screenshot.png)

## Disclaimers / important information

**Warning:** The package can take **15 to 30 minutes** to complete depending on your system configuration. **Don't intrupt the installation process while installing.**

## Important points to read before installing
1. **Plume** is still in **pre-release** stage and undergoing heavy development, so there can be **bugs**.
1. **Plume** requires a dedicated **root domain**, eg. plume.domain.tld
1. **Plume** requires a valid **certificate** installed on the domain. YunoHost can **install a Let's Encrypt certificate** on the domain from **admin web-interface** or through **command-line**.
1. This package is **multi-instance** that means you can run **multiple Plume instances** on a **single server**.

#### Multi-user support

LDAP is activated but HTTP auth is not supported

## Documentation and resources

* Official app website: <https://joinplu.me/>
* Official admin documentation: <https://docs.joinplu.me/>
* Upstream app code repository: <https://github.com/Plume-org/Plume>
* YunoHost documentation for this app: <https://yunohost.org/app_plume>
* Report a bug: <https://github.com/YunoHost-Apps/plume_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
or
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
