<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Matterbridge for YunoHost

[![Integration level](https://dash.yunohost.org/integration/matterbridge.svg)](https://dash.yunohost.org/appci/app/matterbridge) ![Working status](https://ci-apps.yunohost.org/ci/badges/matterbridge.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/matterbridge.maintain.svg)  
[![Install Matterbridge with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matterbridge)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Matterbridge quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Multi-protocols bridge for online communications

**Shipped version:** 1.25.2~ynh2
## Disclaimers / important information

## Configuration

How to configure this app: a plain file with SSH `/opt/yunohost/matterbridge/matterbridge.toml`. You can follow this [doc](https://github.com/42wim/matterbridge/wiki/How-to-create-your-config) on how to create your config.

## Documentation and resources

* Official admin documentation: <https://github.com/42wim/matterbridge/wiki>
* Upstream app code repository: <https://github.com/42wim/matterbridge>
* YunoHost documentation for this app: <https://yunohost.org/app_matterbridge>
* Report a bug: <https://github.com/YunoHost-Apps/matterbridge_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing --debug
or
sudo yunohost app upgrade matterbridge -u https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
