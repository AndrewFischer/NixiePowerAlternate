# NixiePowerAlternate
A general purpose power supply for devices with a Nixie tube display.  

Changes (TBD) for Rev 0.1
Improve HV boost regulator. 
Replace linear 5.0 regulator with a TPS5430 buck regulator.  Power the 3.3V regulator from the 5V supply. 
This allows Vin to have a much wider input range.  Within reason an unregulated Vin will work.

The TPS543 is an inexpensive basic part at JLCPCB with a 500kHz switching frequency and reasonable external parts count.  The '5430 is somewhat sensitive to choice of output capacitor. See the datasheet and application notes if you stray from the BOM.  There are newer parts with better specs. Most are currently unavailable or beyond my ability to solder.  

