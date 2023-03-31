# NixiePowerAlternate
A regulated power supply for devices with a Nixie tube display.  
Vin is 9 to 14VDC.  Maximum input voltage is 16.5V. 
Outputs are 175VDC, 5VDC and 3.3VDC.<br>
MAX1771 maximum input is 16.5V which sets the upper limit on Vin.
TPS5430 and MAX1771 are inexpensive parts with reasonable performace. There are newer parts with better specs. Most are currently unavailable or beyond my ability to solder.
The TPS5430 is sensitive to choice of output capacitor. See the datasheet and application notes if you stray from the BOM.
#### Rev 0.1 Changes
* Improve HV boost regulator circuit.
* Correct footprint errors in Rev. 0. 
* Replace linear 5.0V regulator with a TPS5430 buck regulator.  Power the 3.3V regulator from the 5V supply. 

### Disclaimers and warnings
:exclamation: Danger of electric shock. 175Volts DC is present on this board.<br>
The files embodied in this repository are provided to you "as-is" and without warranty of any kind, express, implied or otherwise, including without limitation, any warranty of fitness for a particular purpose. See section 5 of the license.<br>
**This project is untested**.<br>
### License
[cc-by-nc 4.0](LICENSE.md)

