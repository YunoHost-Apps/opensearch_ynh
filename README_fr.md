<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# OpenSearch pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/opensearch.svg)](https://ci-apps.yunohost.org/ci/apps/opensearch/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/opensearch.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/opensearch.maintain.svg)

[![Installer OpenSearch avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opensearch)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer OpenSearch rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

OpenSearch makes it easy to ingest, search, visualize, and analyze your data.

### Features

OpenSearch is a scalable, flexible, and extensible open-source software suite for search, analytics, and observability applications licensed under Apache 2.0. Powered by Apache Lucene and driven by the OpenSearch Project community, OpenSearch offers a vendor-agnostic toolset you can use to build secure, high-performance, cost-efficient applications. Use OpenSearch as an end-to-end solution or connect it with your preferred open-source tools or partner projects.

### Limitations

- Currently the security is disabled
- Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
- Not scalable for now


**Version incluse :** 2.9.0~ynh3

**Démo :** <https://playground.opensearch.org/app/home>
## Documentations et ressources

- Site officiel de l’app : <https://opensearch.org>
- Documentation officielle de l’admin : <https://opensearch.org/docs/latest/>
- Dépôt de code officiel de l’app : <https://github.com/opensearch-project/OpenSearch>
- YunoHost Store : <https://apps.yunohost.org/app/opensearch>
- Signaler un bug : <https://github.com/YunoHost-Apps/opensearch_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
ou
sudo yunohost app upgrade opensearch -u https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
