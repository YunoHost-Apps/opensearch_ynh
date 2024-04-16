<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# OpenSearch para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/opensearch.svg)](https://dash.yunohost.org/appci/app/opensearch) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/opensearch.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/opensearch.maintain.svg)

[![Instalar OpenSearch con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opensearch)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar OpenSearch de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

OpenSearch makes it easy to ingest, search, visualize, and analyze your data.

### Features

OpenSearch is a scalable, flexible, and extensible open-source software suite for search, analytics, and observability applications licensed under Apache 2.0. Powered by Apache Lucene and driven by the OpenSearch Project community, OpenSearch offers a vendor-agnostic toolset you can use to build secure, high-performance, cost-efficient applications. Use OpenSearch as an end-to-end solution or connect it with your preferred open-source tools or partner projects.

### Limitations

- Currently the security is disabled
- Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
- Not scalable for now


**Versión proporcionada:** 2.9.0~ynh2

**Demo:** <https://playground.opensearch.org/app/home>
## Documentación e recursos

- Web oficial da app: <https://opensearch.org>
- Documentación oficial para admin: <https://opensearch.org/docs/latest/>
- Repositorio de orixe do código: <https://github.com/opensearch-project/OpenSearch>
- Tenda YunoHost: <https://apps.yunohost.org/app/opensearch>
- Informar dun problema: <https://github.com/YunoHost-Apps/opensearch_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
ou
sudo yunohost app upgrade opensearch -u https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
