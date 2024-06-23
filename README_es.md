<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# OpenSearch para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/opensearch.svg)](https://dash.yunohost.org/appci/app/opensearch) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/opensearch.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/opensearch.maintain.svg)

[![Instalar OpenSearch con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opensearch)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarOpenSearch rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

OpenSearch makes it easy to ingest, search, visualize, and analyze your data.

### Features

OpenSearch is a scalable, flexible, and extensible open-source software suite for search, analytics, and observability applications licensed under Apache 2.0. Powered by Apache Lucene and driven by the OpenSearch Project community, OpenSearch offers a vendor-agnostic toolset you can use to build secure, high-performance, cost-efficient applications. Use OpenSearch as an end-to-end solution or connect it with your preferred open-source tools or partner projects.

### Limitations

- Currently the security is disabled
- Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
- Not scalable for now


**Versión actual:** 2.9.0~ynh2

**Demo:** <https://playground.opensearch.org/app/home>
## Documentaciones y recursos

- Sitio web oficial: <https://opensearch.org>
- Documentación administrador oficial: <https://opensearch.org/docs/latest/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/opensearch-project/OpenSearch>
- Catálogo YunoHost: <https://apps.yunohost.org/app/opensearch>
- Reportar un error: <https://github.com/YunoHost-Apps/opensearch_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
o
sudo yunohost app upgrade opensearch -u https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
