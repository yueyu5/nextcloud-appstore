# 说明
因Nextcloud appstore访问慢，在此定时更新https://apps.nextcloud.com/api/v1/apps.json。

nextcloud中config.php加入：

'appstoreurl' => 'https://raw.githubusercontent.com/yueyu5/nextcloud-appstore/master',

或加速
'appstoreurl' => 'https://raw.staticdn.net/yueyu5/nextcloud-appstore/master',

