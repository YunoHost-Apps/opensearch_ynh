<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 的 OpenSearch

[![集成程度](https://dash.yunohost.org/integration/opensearch.svg)](https://dash.yunohost.org/appci/app/opensearch) ![工作状态](https://ci-apps.yunohost.org/ci/badges/opensearch.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/opensearch.maintain.svg)

[![使用 YunoHost 安装 OpenSearch](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opensearch)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 OpenSearch。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

OpenSearch makes it easy to ingest, search, visualize, and analyze your data.

### Features

OpenSearch is a scalable, flexible, and extensible open-source software suite for search, analytics, and observability applications licensed under Apache 2.0. Powered by Apache Lucene and driven by the OpenSearch Project community, OpenSearch offers a vendor-agnostic toolset you can use to build secure, high-performance, cost-efficient applications. Use OpenSearch as an end-to-end solution or connect it with your preferred open-source tools or partner projects.

### Limitations

- Currently the security is disabled
- Therefore, the package is configured to remain not public for now (i.e. not accessible through the web, the apps depending on it should be installed on the same server)
- Not scalable for now


**分发版本：** 2.9.0~ynh2

**演示：** <https://playground.opensearch.org/app/home>
## 文档与资源

- 官方应用网站： <https://opensearch.org>
- 官方管理文档： <https://opensearch.org/docs/latest/>
- 上游应用代码库： <https://github.com/opensearch-project/OpenSearch>
- YunoHost 商店： <https://apps.yunohost.org/app/opensearch>
- 报告 bug： <https://github.com/YunoHost-Apps/opensearch_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
或
sudo yunohost app upgrade opensearch -u https://github.com/YunoHost-Apps/opensearch_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
