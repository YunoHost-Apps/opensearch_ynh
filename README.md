<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# OpenSearch for YunoHost

[![Integration level](https://dash.yunohost.org/integration/opensearch.svg)](https://ci-apps.yunohost.org/ci/apps/opensearch/) ![Working status](https://ci-apps.yunohost.org/ci/badges/opensearch.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/opensearch.maintain.svg)

[![Install OpenSearch with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opensearch)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install OpenSearch quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

OpenSearch makes it easy to ingest, search, visualize, and analyze your data.

### Features

OpenSearch is a scalable, flexible, and extensible open-source software suite for search, analytics, and observability applications licensed under Apache 2.0. Powered by Apache Lucene and driven by the OpenSearch Project community, OpenSearch offers a vendor-agnostic toolset you can use to build secure, high-performance, cost-efficient applications. Use OpenSearch as an end-to-end solution or connect it with your preferred open-source tools or partner projects.

### Limitations

- Currently the security is disabled
- Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
- Not scalable for now


**Shipped version:** 2.9.0~ynh3

**Demo:** <https://playground.opensearch.org/app/home>
## Documentation and resources

- Official app website: <https://opensearch.org>
- Official admin documentation: <https://opensearch.org/docs/latest/>
- Upstream app code repository: <https://github.com/opensearch-project/OpenSearch>
- YunoHost Store: <https://apps.yunohost.org/app/opensearch>
- Report a bug: <https://github.com/YunoHost-Apps/opensearch_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
or
sudo yunohost app upgrade opensearch -u https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
