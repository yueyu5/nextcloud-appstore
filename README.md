# Nextcloud AppStroe 镜像
[![GitHub Repo Size](https://img.shields.io/github/repo-size/yueyu5/nextcloud-appstore)](https://github.com/yueyu5/nextcloud-appstore)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/yueyu5/nextcloud-appstore)](https://github.com/yueyu5/nextcloud-appstore/commits/master)
## 简介
因Nextcloud AppStroe访问慢，在此每日定时更新https://apps.nextcloud.com/api/v1/。

## 使用方法
**nextcloud中`config.php`加入**
  ```php
  'appstoreurl' => 'https://github.com/yueyu5/nextcloud-appstore/blob/master/api/v1/',
  ```
或加速
  ```php
  'appstoreurl' => 'https://v6.gh-proxy.org/https://github.com/yueyu5/nextcloud-appstore/blob/master/api/v1/',
  ```


