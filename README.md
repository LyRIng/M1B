## M1B Vac/Iac Signal Input Module
(original version 2011 - updated 09.2022)

### Introduction
The M1B board from [L&R Ingeniería](https://www.lyringenieria.com.ar/language/es/) (designed by N.Cortez and R.Oliva) is an auxiliary peripheral board designed to isolate and true-rms convert line AC voltages (VAC 220 V rms nominal) and currents (IAC up to 20 A rms)  to a range readable from two 0- 5 Vdc A/D converter channels. It also provides two 0-10 Vdc outputs proportional to VAC and IAC. It uses a LEM VL-20P Hall effect sensor for line voltage sensing, and a bidirectional ACS712/4 Allegro sensor for AC current. It uses twin [AD736 True RMS-to-DC Converter ICs](https://www.analog.com/en/products/ad736.html). It works from an unregulated 14.4 Vdc supply and generates its own bipolar voltages for correct operation. 

In the **/schem** directory a schematic of the circuit is described. The board is available with or without a DIN-R416 plastic cabinet, contact L&R Ing. for details. 


