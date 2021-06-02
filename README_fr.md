# Matterbridge pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/matterbridge.svg)](https://dash.yunohost.org/appci/app/matterbridge) ![](https://ci-apps.yunohost.org/ci/badges/matterbridge.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/matterbridge.maintain.svg)  
[![Installer Matterbridge avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matterbridge)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Matterbridge rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Connecteur entre une série de protocoles de discussion

**Version incluse :** 1.22.2~ynh1



## Avertissements / informations importantes

## Configuration

Comment configurer cette application : un fichier brut en SSH `/opt/yunohost/matterbridge/matterbridge.toml`. Vous pouvez suivre cette [documentation](https://github.com/42wim/matterbridge/wiki/How-to-create-your-config) sur la façon de créer votre config. 

## Documentations et ressources

* Documentation YunoHost pour cette app : https://yunohost.org/app_matterbridge
* Signaler un bug : https://github.com/YunoHost-Apps/matterbridge_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing --debug
ou
sudo yunohost app upgrade matterbridge -u https://github.com/YunoHost-Apps/matterbridge_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps