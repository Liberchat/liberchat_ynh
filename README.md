# Package YunoHost pour Liberchat

[![Integration level](https://dash.yunohost.org/integration/liberchat.svg)](https://dash.yunohost.org/appci/app/liberchat) ![Working status](https://ci-apps.yunohost.org/ci/badges/liberchat.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/liberchat.maintain.svg)

[![Installer Liberchat avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=liberchat)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d'installer Liberchat rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n'avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Liberchat est une application de chat en temps réel chiffrée de bout en bout, conçue pour les communes numériques. Elle offre :

- **Chat en temps réel** avec Socket.IO
- **Chiffrement de bout en bout** pour tous les messages
- **Messages vocaux chiffrés** 
- **Partage d'images chiffrées**
- **Réactions emoji chiffrées**
- **Interface moderne** avec thème sombre/clair
- **Progressive Web App (PWA)**
- **Aucune collecte de données**

**Version incluse :** 6.1.18~ynh1

## Captures d'écran

![Capture d'écran de Liberchat](./doc/screenshots/liberchat-screenshot.png)

## Documentation et ressources

- Site officiel de l'app : <https://github.com/AnARCHIS12/Liberchat>
- Dépôt de code officiel de l'app : <https://github.com/AnARCHIS12/Liberchat>
- YunoHost Store : <https://apps.yunohost.org/app/liberchat>
- Signaler un bug : <https://github.com/YunoHost-Apps/liberchat_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/liberchat_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/liberchat_ynh/tree/testing --debug
ou
sudo yunohost app upgrade liberchat -u https://github.com/YunoHost-Apps/liberchat_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** <https://yunohost.org/packaging_apps>