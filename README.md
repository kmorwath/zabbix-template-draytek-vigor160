# zabbix-template-draytek-vigor160
Zabbix Template for Vigor 160

Inspired by https://github.com/seangordon/Zabbix-Template-Draytek-130

Features:

WAN1, WAN3, WAN4 and WAN5 status and Rx/Tx data are retrieved.
WAN1 is the physical xDSL port, WAN3-5 are virtual ports.

LAN1 and LAN2 ports status and Rx/Tx data are retrieved separately.

Attenuation and SNR for both directions.

Attainable and actual dowload speed

Actual upload speed only. As of firmware 4.2.3
ADSL-LINE-MIB::adslAtucCurrAttainableRate.4 is always 0 and
ADSL-LINE-MIB::adslAturCurrAttainableRate.4 reports the dowload
speed instead.

Graphs for WAN1, LAN1 and LAN2 Rx/Tx, SNR, attenuation and RX
attainable/actual speed.
