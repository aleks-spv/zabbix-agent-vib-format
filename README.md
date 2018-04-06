

Агент zabbix для установки на Vmware Esxi. Проверено на EsXi 6.0

Команды для установки:

esxcli software acceptance set --level=CommunitySupported
esxcli software vib install -v /full/path/to/zabbix-agent.vib -f


Agent zabbix for installation on Vmware Esxi. Tested on EsXi 6.0

Commands to install:

esxcli software acceptance set --level=CommunitySupported
esxcli software vib install -v /full/path/to/zabbix-agent.vib -f
