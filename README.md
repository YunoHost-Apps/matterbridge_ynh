# Matterbridge for YunoHost

[![Integration level](https://dash.yunohost.org/integration/matterbridge.svg)](https://dash.yunohost.org/appci/app/matterbridge) ![](https://ci-apps.yunohost.org/ci/badges/matterbridge.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/matterbridge.maintain.svg)  
[![Install matterbridge with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matterbridge)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Matterbridge quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Matterbridge is a bridge between a series of chat protocols and offers a REST-API. Supported protocols are among others IRC, XMPP, Gitter, Mattermost, Slack, Discord, Telegram, Rocket.Chat, Hipchat(via xmpp), Matrix, Steam, ssh-chat and Zulip.

**Shipped version:** 1.21.0

## Configuration

How to configure this app: a plain file with SSH `/opt/yunohost/matterbridge/matterbridge.toml`. You can follow this [doc](https://github.com/42wim/matterbridge/wiki/How-to-create-your-config) on how to create your config.

## Documentation

 * Official documentation: https://github.com/42wim/matterbridge/wiki
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported? **No**
 * Can the app be used by multiple users? **No**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/matterbridge%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/matterbridge/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/matterbridge%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/matterbridge/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/matterbridge_ynh/issues
 * Upstream app repository: https://github.com/42wim/matterbridge
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing --debug
or
sudo yunohost app upgrade matterbridge -u https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing --debug
```
