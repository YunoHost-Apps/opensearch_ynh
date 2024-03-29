<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# OpenSearch per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/opensearch.svg)](https://dash.yunohost.org/appci/app/opensearch) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/opensearch.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/opensearch.maintain.svg)

[![Installa OpenSearch con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opensearch)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare OpenSearch su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

OpenSearch makes it easy to ingest, search, visualize, and analyze your data.

### Features

OpenSearch is a scalable, flexible, and extensible open-source software suite for search, analytics, and observability applications licensed under Apache 2.0. Powered by Apache Lucene and driven by the OpenSearch Project community, OpenSearch offers a vendor-agnostic toolset you can use to build secure, high-performance, cost-efficient applications. Use OpenSearch as an end-to-end solution or connect it with your preferred open-source tools or partner projects.

### Limitations

- Currently the security is disabled
- Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
- Not scalable for now


**Versione pubblicata:** 2.9.0~ynh1

**Prova:** <https://playground.opensearch.org/app/home>
## Documentazione e risorse

- Sito web ufficiale dell’app: <https://opensearch.org>
- Documentazione ufficiale per gli amministratori: <https://opensearch.org/docs/latest/>
- Repository upstream del codice dell’app: <https://github.com/opensearch-project/OpenSearch>
- Store di YunoHost: <https://apps.yunohost.org/app/opensearch>
- Segnala un problema: <https://github.com/YunoHost-Apps/opensearch_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
o
sudo yunohost app upgrade opensearch -u https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
