# Matterbridge pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/matterbridge.svg)](https://dash.yunohost.org/appci/app/matterbridge) ![](https://ci-apps.yunohost.org/ci/badges/matterbridge.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/matterbridge.maintain.svg)  
[![Installer Matterbridge avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matterbridge)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Matterbridge rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Matterbridge est un pont entre une série de protocoles de discussion et propose une REST-API. Les protocoles pris en charge sont entre autres IRC, XMPP, Gitter, Mattermost, Slack, Discord, Telegram, Rocket.Chat, Hipchat (via xmpp), Matrix, Steam, ssh-chat et Zulip.

**Version incluse :** 1.22.1

## Configuration

Comment configurer cette application : un fichier brut en SSH `/opt/yunohost/matterbridge/matterbridge.toml`. Vous pouvez suivre cette [documentation](https://github.com/42wim/matterbridge/wiki/How-to-create-your-config) sur la façon de créer votre config. 

## Documentation

 * Documentation officielle : https://github.com/42wim/matterbridge/wiki
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Non**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/matterbridge.svg)](https://ci-apps.yunohost.org/ci/apps/matterbridge/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/matterbridge.svg)](https://ci-apps-arm.yunohost.org/ci/apps/matterbridge/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Links

 * Signaler un bug : https://github.com/YunoHost-Apps/matterbridge_ynh/issues
 * Dépôt de l'application principale : https://github.com/42wim/matterbridge
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing --debug
ou
sudo yunohost app upgrade matterbridge -u https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing --debug
```
