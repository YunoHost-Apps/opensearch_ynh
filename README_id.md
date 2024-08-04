<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# OpenSearch untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/opensearch.svg)](https://ci-apps.yunohost.org/ci/apps/opensearch/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/opensearch.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/opensearch.maintain.svg)

[![Pasang OpenSearch dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opensearch)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang OpenSearch secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

OpenSearch makes it easy to ingest, search, visualize, and analyze your data.

### Features

OpenSearch is a scalable, flexible, and extensible open-source software suite for search, analytics, and observability applications licensed under Apache 2.0. Powered by Apache Lucene and driven by the OpenSearch Project community, OpenSearch offers a vendor-agnostic toolset you can use to build secure, high-performance, cost-efficient applications. Use OpenSearch as an end-to-end solution or connect it with your preferred open-source tools or partner projects.

### Limitations

- Currently the security is disabled
- Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
- Not scalable for now


**Versi terkirim:** 2.9.0~ynh3

**Demo:** <https://playground.opensearch.org/app/home>
## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://opensearch.org>
- Dokumentasi admin resmi: <https://opensearch.org/docs/latest/>
- Depot kode aplikasi hulu: <https://github.com/opensearch-project/OpenSearch>
- Gudang YunoHost: <https://apps.yunohost.org/app/opensearch>
- Laporkan bug: <https://github.com/YunoHost-Apps/opensearch_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
atau
sudo yunohost app upgrade opensearch -u https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
