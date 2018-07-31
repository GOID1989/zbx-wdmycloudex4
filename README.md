# zbx-wdmycloudex4
Zabbix SNMP Template for (Western Digital) WD My Cloud EX4

In WD My Cloud EX4 is simple (MIBs here http://downloads.wdc.com/nas/WDMYCLOUDEX4-MIB.txt). 

## Prerequisites:
 - Enable SNMP on WD My Cloud EX4
 - Zabbix 3.4+ with preproccessing support for regex-magic on item

## Notice:
In my env this NAS is "lazy" and have problems with BULK SNMP queries from Zabbix.
Template uses vars set to your env:
 - {$SNMP_PORT}
 - {$SNMP_COMMUNITY}


