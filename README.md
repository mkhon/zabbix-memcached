This memcached template is based on https://github.com/vicendominguez/memcached-zabbix-template
but uses preprocessing and dependent items so it does not require any scripts.

# Installation

1. Copy userparameter_memcached.zabbix_agentd.conf to /etc/zabbix/zabbix_agentd.conf.d/userparameter_memcached.conf

2. Import zabbix-memcached.xml template. The template uses "Agent (active)" type to get raw values -
change the type to "Agent" if you use passive agents.
