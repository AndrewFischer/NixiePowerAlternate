# NixiePowerAlternate
A regulated power supply for devices with a Nixie tube display.  
Vin is 9 to 14VDC.  Maximum input voltage is 16.5V. 
Outputs are 180VDC, 5VDC and 3.3VDC. 

Changes (TBD) for Rev 0.1
Improve MAX1771 HV boost regulator.
Replace linear 5.0 regulator with a TPS5430 buck regulator.  Power the 3.3V regulator from the 5V supply. 
This allows wider input range. Within reason an unregulated Vin will work. The MAX1771 maximum input is 16.5V, which sets the upper limit on Vin.

The TPS5430 is an inexpensive basic part at JLCPCB with a 500kHz switching frequency and reasonable external parts count. There are newer parts with better specs. Most are currently unavailable or beyond my ability to solder.
The '5430 is sensitive to choice of output capacitor. See the datasheet and application notes if you stray from the BOM. 

