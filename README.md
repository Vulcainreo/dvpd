# Damn Vulnerable Peripheral Device (DVPD)

	Damn Vulnerable Peripheral Device (DVPD) for Bluetooth LE Hacking learning and practice.
	DVPD is a nodejs tool designed to understand and learn more about Bluetooth LE devices 
	hacking without the need of actual hardware device

## Pre-requisites

	1. [Nodejs Bleno Package] (https://github.com/sandeepmistry/bleno#prerequisites)
	2. Bluetooth LE 4.0 Adapter

## Installation

	git clone https://github.com/ji2kumar/dvpd.git

## Run

	sudo node dvpd.js

## Troubleshooting

	1. if script not running, check Bluetooth adapter state.
	       > hciconfig
	         if "DOWN" then run following command:
	             > hciconfig hci0 up   [e.g. hci0, might be different for you so put which is in use for you]
