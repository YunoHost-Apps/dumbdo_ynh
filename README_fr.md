<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# DumbDo pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/dumbdo)](https://ci-apps.yunohost.org/ci/apps/dumbdo/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/dumbdo)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/dumbdo)

[![Installer DumbDo avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbdo)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer DumbDo rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Une application de liste de tâches stupidement simple qui fonctionne tout simplement. Pas de base de données complexe, pas de fonctionnalités inutiles - juste des choses à faire.

### Caractéristiques

- Interface propre et minimale
- Mode sombre/lumineux avec détection des préférences du système
- Stockage sur fichier - les todos persistent entre les sessions
- Conception entièrement réactive
- Rapide et léger
- Protection par code PIN (4-10 chiffres si activé)


**Version incluse :** 1.0.0~ynh2

## Captures d’écran

![Capture d’écran de DumbDo](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.dumbware.io/>
- Dépôt de code officiel de l’app : <https://github.com/DumbWareio/DumbDo>
- YunoHost Store : <https://apps.yunohost.org/app/dumbdo>
- Signaler un bug : <https://github.com/YunoHost-Apps/dumbdo_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/dumbdo_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbdo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dumbdo -u https://github.com/YunoHost-Apps/dumbdo_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
