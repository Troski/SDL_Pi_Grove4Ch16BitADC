

Grove 4Ch/16BitADC Board Drivers

SwitchDoc Labs, Novemeber 2017 Version 1.1

Raspberry Pi Pure Python Software

The Grove 4Ch/16BitADC Board contains Grove Connectors and an ADS1115 ADC.

These drivers are adapted from the Adafruit ADS1x15 Drivers.  

Modifications: 
Version 1.0	
	- Made them local directory drivers
 	- Added a rawMode channel reading routine
	- Made modifications to delays and then removed them - neeeded in ESP8266 systems but not in the Raspberry Pi	

Version 1.1
	- Fixed an import clash error.  Something to do with the latest versions of the Raspberry Pi OS.  No clue where it came from.

