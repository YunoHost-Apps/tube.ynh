<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Tube pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/tube)](https://ci-apps.yunohost.org/ci/apps/tube/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/tube)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/tube)

[![Installer Tube avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tube)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Tube rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Tube est une application de partage de vidéos de type Youtube (sans censure ni fonctionnalités dont vous n'avez pas besoin !) écrite en Go qui prend également en charge le transcodage automatique en MP4 H.265 AAC, plusieurs collections et le flux RSS.

### Caractéristiques

- Facile à ajouter des vidéos (il suffit de déplacer un fichier dans le dossier)
- Facile à télécharger des vidéos (il suffit d'utiliser le téléchargeur intégré et le transcodeur automatique !)
- Transcodeur intégré basé sur ffmpeg qui convertit automatiquement votre contenu téléchargé en MP4 H.264 / AAC
- Générateur de vignettes automatique intégré
- Pas de base de données (informations vidéo extraites des métadonnées du fichier)
- Pas de JavaScript (l'interface utilisateur du lecteur est entièrement en HTML, à l'exception de l'uploader qui se dégrade !)
- Modèle CSS et HTML facile à personnaliser
- Génère automatiquement un flux RSS (à /feed.xml)
- Interface utilisateur propre, simple et familière

**Version incluse :** 1.2.0~ynh3

## Captures d’écran

![Capture d’écran de Tube](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://git.mills.io/prologic/tube>
- YunoHost Store : <https://apps.yunohost.org/app/tube>
- Signaler un bug : <https://github.com/YunoHost-Apps/tube_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/tube_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
ou
sudo yunohost app upgrade tube -u https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
