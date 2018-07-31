# zbx-wdmycloudex4
Zabbix SNMP Template for (Western Digital) WD My Cloud EX4

In WD My Cloud EX4 is simple (MIBs here http://downloads.wdc.com/nas/WDMYCLOUDEX4-MIB.txt). 

Prerequisites:
1) Enable SNMP on WD My Cloud EX4
2) Zabbix 3.4+ with preproccessing support for regex-magic on item

Notice:
In my env this NAS is "lazy" and have problems with BULK SNMP queries from Zabbix.

