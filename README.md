# NixiePowerAlternate
A regulated power supply for devices with a Nixie tube display.  
Vin is 9 to 14VDC.  Maximum input voltage is 16.5V. 
Outputs are 175VDC, 5VDC and 3.3VDC. 

Rev 0.1 Changes
Improve MAX1771 HV boost regulator, correcting errors in Rev. 0.  (done)
(TBD) Replace linear 5.0 regulator with a TPS5430 buck regulator.  Power the 3.3V regulator from the 5V supply. 
MAX1771 maximum input is 16.5V and the upper limit on Vin.

The TPS5430 and MAX1771 are inexpensive basic part at JLCPCB with reasonable performace. There are newer parts with better specs. Most are currently unavailable or beyond my ability to solder.
The TPS5430 is sensitive to choice of output capacitor. See the datasheet and application notes if you stray from the BOM. 

