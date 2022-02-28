# Devio Biamp SNMP template for Zabbix

Devio Biamp - hardware hub solution for conference rooms. We use it with Huddle cam, TV and Mac mini and some good audio + Devio mics

Original web interface is not useful, and I wanted to store call history and some amplify parameters

SNMP codes from [official site](https://support.biamp.com/Devio/Configuration/Using_SNMP_with_Devio)

Maybe, next will be monitoring via SSH (SNMP have unprotected RW rows)

## how-to use
Just add template, add SNMP host with SNMPv2 and credentials

## Watch
Only main parameters from specs

## Triggers:
- From "ICMP ping template": high loss, high response time, unavailable by ping;
- Microphone line fault;
- Firmware has changed.

Maybe add more in future. 


Tested on Devio Biamp SCR-25 (don't have any other).
