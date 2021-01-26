# Matterbridge for YunoHost

[![Integration level](https://dash.yunohost.org/integration/matterbridge.svg)](https://dash.yunohost.org/appci/app/matterbridge) ![](https://ci-apps.yunohost.org/ci/badges/matterbridge.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/matterbridge.maintain.svg)  
[![Install matterbridge with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matterbridge)

matterbridge Server

**Shipped version:** 1.17.4

- [Yunohost project](https://yunohost.org)
- [matterbridge website](https://github.com/42wim/matterbridge)

![](https://raw.githubusercontent.com/42wim/matterbridge/master/img/matterbridge-notext.gif)


[![Install matterbridge with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=matterbridge)

### Installing guide

 App can be installed by YunoHost **admin web-interface** or by **running following command**:

         $ sudo yunohost app install https://github.com/YunoHost-Apps/matterbridge_ynh
         
         After install :
 
        1. need to edit file /opt/matterbridge/matterbridge.toml
        2. restart service systemctl restart matterbridge

 
### Upgrade this package:

        $ sudo yunohost app upgrade matterbridge -u https://github.com/YunoHost-Apps/matterbridge_ynh

