# zbx-wdmycloudex4
Zabbix SNMP Template for (Western Digital) WD My Cloud EX4

In WD My Cloud EX4 is simple (MIBs here http://downloads.wdc.com/nas/WDMYCLOUDEX4-MIB.txt). 

Because some OID return not-clear-byte values (150.3G, 2.3T) - in items used "regex-magic". Loosing some
precision (i try to beat this problem), for flexiable data:
![alt_text](https://github.com/GOID1989/zbx-wdmycloudex4/raw/master/zabbix_preproccessing.PNG)

## Prerequisites:
 - Enable SNMP on WD My Cloud EX4
 - Zabbix 3.4+ with preproccessing support for regex-magic on item

## Notice:
In my env this NAS is "lazy" and have problems with BULK SNMP queries from Zabbix.
Template uses vars set on host-level:
 - {$SNMP_PORT}
 - {$SNMP_COMMUNITY}


