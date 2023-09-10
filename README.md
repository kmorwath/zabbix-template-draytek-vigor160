# zabbix-template-draytek-vigor160
Zabbix Template for Vigor 160

Inspired by https://github.com/seangordon/Zabbix-Template-Draytek-130

Tested on a Vigor 165 with firmware 4.2.3. Should work on the 166 too.

Features:

WAN1, WAN3, WAN4 and WAN5 status and Rx/Tx data are retrieved.
WAN1 is the physical xDSL port, WAN3-5 are virtual ports.

LAN1 and LAN2 ports status and Rx/Tx data are retrieved separately.

Attenuation and SNR for both directions.

Attainable and actual dowload/upload speeds - using firmware 4.2.5 or later. Firmware 4.2.3 didn't report upload speeds.

Graphs for WAN1, LAN1 and LAN2 Rx/Tx, SNR, attenuation and RX
attainable/actual speed.
