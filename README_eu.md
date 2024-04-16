<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# OpenSearch YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/opensearch.svg)](https://dash.yunohost.org/appci/app/opensearch) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/opensearch.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/opensearch.maintain.svg)

[![Instalatu OpenSearch YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opensearch)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek OpenSearch YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

OpenSearch makes it easy to ingest, search, visualize, and analyze your data.

### Features

OpenSearch is a scalable, flexible, and extensible open-source software suite for search, analytics, and observability applications licensed under Apache 2.0. Powered by Apache Lucene and driven by the OpenSearch Project community, OpenSearch offers a vendor-agnostic toolset you can use to build secure, high-performance, cost-efficient applications. Use OpenSearch as an end-to-end solution or connect it with your preferred open-source tools or partner projects.

### Limitations

- Currently the security is disabled
- Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
- Not scalable for now


**Paketatutako bertsioa:** 2.9.0~ynh2

**Demoa:** <https://playground.opensearch.org/app/home>
## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://opensearch.org>
- Administratzaileen dokumentazio ofiziala: <https://opensearch.org/docs/latest/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/opensearch-project/OpenSearch>
- YunoHost Denda: <https://apps.yunohost.org/app/opensearch>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/opensearch_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
edo
sudo yunohost app upgrade opensearch -u https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
