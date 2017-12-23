# zabbix_template_ntpd

NTP Client Template for Zabbix ~> 3.4.

Necessary "Dependent Item". Put userparameter_ntp.conf in Include-UserParameter's Directory.

- ZABBIX 3.4用 NTPDクライアントのテンプレートです。
- UserParameterのワインライナーでntpq -pをJSON化して、依存アイテムで各値を入れてます。
- NTPのためだけにAgentにEnableRemoteCommandsとか設定することは不要です。
- FreeBSD11/CentOS7.1以上で動きます。

このテンプレートはMIT Licenseです。
