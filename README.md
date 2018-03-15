# STM32L4-Discovery-UartRamAnalyzer-Project

This is a Simple project where an Hex value (0xAAAAAAAA) == (bx 1010 1010 1010 1010 1010 1010 1010 1010) is written once (at the startup) in the ram memory of the Microcontroller and continuously checked in cycles to ensure (or check) the modifications on those bits caused by Radiation.

The Device will comunicate the check status through a virtual com port -
-BaudRate =115200
-The communication is optimized for:
--->1 Termite
--->2 the Arduino IDE Com visualizer
it might need some modifications in order to be properly displayed on Putty.

This project was made using ST Software and Keil uVision5
