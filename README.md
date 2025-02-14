ADX - Arduino Digital Modes Transceiver UPDATE (20 December 2022):

- ADX Build Manual V1.2 Released.

- Calibration Procedure Changed to protect EEPROM from R/W wear out during calibration.  

- Caution Note on SI5351 Library.

- ZENER DIODE PA MOSFET PROTECTION to protect PA Mosfets from excessive SWR conditions.

- ADX_QUAD_V1.2 Firmware relaese with new calibration procedure and 10m/28Mhz band addition.

IMPORTANT NOTE ON NT7S SI5351 LIBRARY VERSIONS   

Please install SI5351 Library that is in ADX Github under ADX Firmware! 
Or use Etherkit SI5351 Library Version 2.1.3. 
ADX firmware is compatible with only Etherkit SI5351 Library version 2.1.3.
____________________________________________________________________________

ADX is an Arduino based Digital Modes Transceiver.

- ADX - is abbreviation for Arduino Digital Xceiver.

- ADX is a mono band (actually quad band) digital modes optimized HF transceiver that can cover four pre-programmed bands one band at a time by swapping Band LPF Modules. 
It can work on 80m, 40m, 30m,20m, 17m, 15m and 10m bands and can operate on four of the most popular digital modes, FT8, FT4, JS8call and WSPR. 

My goal with this project is to design a simple HF Transceiver optimized for operating on Digital modes:
-	Simple to procure – meaning not effected by chip shortage
-	Simple to build – 2 modules, 2 IC’s and 4 Mosfets!
-	Simple to setup and tune – One simple calibration procedure is all needed.
-	Simple to operate – Plug in ADX MIC to soundcard MIC input and ADX SPK to PC soundcard speaker input and we are good to go with any digital modes Software.
-	Dirt Cheap – Costs less than 25$ to get all parts and PCB if we exclude ridiculous shipping costs!

- For ease of following which parts to solder while building Main board of ADX, Interactive BOM File - ibom_ADX.html file is a great help. Just run that file on Microsoft edge and follow each highlighted component and solder one by one. This interactive BOM was prepared by Gilles DELPECH - F1BFU. Thank you Gilles!

If you like my designs and would like to support my work:
https://www.buymeacoffee.com/wb2cba

