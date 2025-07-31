# Liberchat pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/liberchat.svg)](https://dash.yunohost.org/appci/app/liberchat) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/liberchat.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/liberchat.maintain.svg)

[![Installer Liberchat avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=liberchat)

*[Read this README in english.](./README_en.md)*

> *Ce package vous permet d'installer Liberchat rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/install) pour apprendre comment l'installer.*

## Vue d'ensemble

🚩✊ **Liberchat — La Commune Numérique**

Un chat en temps réel, autogéré, horizontal, pour la Commune numérique. Application de chat chiffrée de bout en bout, conçue dans l'esprit anarcho-syndicaliste pour l'autogestion, la solidarité et la liberté numérique.

### Caractéristiques principales

- 💬 **Chat en temps réel** avec Socket.IO
- 🔒 **Chiffrement de bout en bout (E2EE)** pour tous les messages, images et vocaux
- 🎤 **Messages vocaux chiffrés** avec lecture universelle
- 🖼️ **Partage d'images chiffrées** sécurisé
- 😀 **Réactions emoji chiffrées** sur les messages
- 🌙 **Interface moderne** avec thème sombre/clair
- 📱 **Progressive Web App (PWA)** installable
- 🛡️ **Aucune collecte de données** - respect total de la vie privée
- ✏️ **Modification et suppression** des messages
- 🔗 **Aperçu des liens** avec métadonnées
- 👥 **Liste des utilisateurs** en temps réel

**Version livrée :** 6.1.18~ynh1

**Démo :** https://liberchat-3-0-1.onrender.com

## Captures d'écran

![Capture d'écran de Liberchat](./doc/screenshots/liberchat-screenshot.png)

## Installation

### Installation standard

```bash
sudo yunohost app install https://github.com/Liberchat/liberchat_ynh
```

### Installation en mode test

```bash
sudo yunohost app install https://github.com/Liberchat/liberchat_ynh/tree/testing --debug
```

## Configuration

### Après installation

1. **Définir la clé de chiffrement** : Tous les utilisateurs doivent utiliser la même clé pour communiquer
2. **Choisir un nom d'utilisateur** unique
3. **Commencer à chatter** en toute sécurité

### Fonctionnalités avancées

- **Mode clair/sombre** : Basculez dans les paramètres
- **Installation PWA** : Ajoutez l'app à votre écran d'accueil
- **Messages vocaux** : Cliquez sur le micro pour enregistrer
- **Partage d'images** : Glissez-déposez ou cliquez sur l'icône

## Philosophie

> « Pour l'autogestion, la solidarité et la liberté numérique. Un chat libre, par et pour le peuple. »

- **Aucune hiérarchie** : Tous les utilisateurs ont les mêmes droits
- **Respect de la vie privée** : Pas de tracking, pas de collecte
- **Code ouvert** : Transparent, modifiable, forkable
- **Solidarité** : Entraide technique et humaine
- **Décentralisation** : Hébergement autonome possible

## Documentation et ressources

- **Dépôt officiel** : https://github.com/AnARCHIS12/Liberchat
- **Documentation complète** : Voir le dossier `docs/` du projet principal
- **Signaler un bug** : https://github.com/Liberchat/liberchat_ynh/issues
- **YunoHost Store** : https://apps.yunohost.org/app/liberchat

## Informations pour les développeurs

### Structure du package

```
liberchat_ynh/
├── manifest.toml          # Métadonnées de l'application
├── scripts/
│   ├── install           # Installation
│   ├── remove            # Désinstallation  
│   ├── upgrade           # Mise à jour
│   ├── backup            # Sauvegarde
│   └── restore           # Restauration
├── conf/
│   ├── nginx.conf        # Configuration Nginx + WebSocket
│   ├── systemd.service   # Service systemd
│   └── .env              # Variables d'environnement
└── doc/
    └── screenshots/      # Captures d'écran
```

### Développement

```bash
# Cloner le dépôt
git clone https://github.com/Liberchat/liberchat_ynh
cd liberchat_ynh

# Tester l'installation
sudo yunohost app install . --debug

# Tester la mise à jour
sudo yunohost app upgrade liberchat --debug
```

### Contributions

Merci de faire vos pull requests sur la [branche `testing`](https://github.com/Liberchat/liberchat_ynh/tree/testing).

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps

---

**Fait par et pour la communauté, dans l'esprit de la Commune numérique.**

[![Anticapitaliste](https://img.shields.io/badge/Anticapitaliste-✊-red?style=for-the-badge)](#)
[![Logiciel Libre](https://img.shields.io/badge/Logiciel_Libre-100%25-black?style=for-the-badge)](#)
[![Anarcho-syndicaliste](https://img.shields.io/badge/Anarcho--syndicaliste-Noir_&_Rouge-black?style=for-the-badge&labelColor=ff2800)](#)# liberchat_ynh
