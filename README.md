
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

# Disclaimer

You are free to:

Share — copy and redistribute the material in any medium or format

Adapt — remix, transform, and build upon the material

________________________________________

Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

NonCommercial — You may not use the material for commercial purposes.

___________________________________________

THE HARDWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE HARDWARE OR THE USE OR OTHER DEALINGS IN THE HARDWARE.

_____________________________________________

# Overview

This repo contains both the CAD for the 3D printed cover for the Pocket Operator and the PCB schematic for the adapter. PCB is created using KiCad. Software can be found [here](https://github.com/PO-MIDI-Adapter/midi-adapter-sofware)

[![PO-MA](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-hardware/master/photos/title.jpg)](https://www.youtube.com/watch?v=iIQ18DAJAU0 "PO-MA")


# BOM

1. 1 x PCB board
2. 1 x 3D printed cover (Found in the cad folder)
3. 1 x Holder Left (Found in the cad folder)
4. 1 x Holder right (Found in the cad folder)
5. 25 x P75-B1 pogo pins [ebay](https://www.ebay.ca/itm/50pcs-P75-B1-Dia-1-02mm-100g-Cusp-Spear-Spring-Loaded-Test-Probes-Pogo-Pin/191960357788?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2060353.m2749.l2648)
6. 1 x USB-Host breakout [ebay](https://www.ebay.com/itm/USB-Female-Power-Module-USB-Type-A-Female-Breakout-Converter-Board-Breadboard/272351358553?hash=item3f6967ee59:g:LB8AAOSw~y9ZAxTT)
In addition, you would need the following electronics (bom.csv)

|Manufacturer Part Number|Manufacturer               |Digi-Key Part Number|Quantity|Description                    |
|------------------------|---------------------------|--------------------|--------|-------------------------------|
|SN74HC125N              |Texas Instruments          |296-1572-5-ND       |1       |IC BUFFER NON-INVERT 6V 14DIP  |
|A 14-LC-TT              |Assmann WSW Components     |AE9989-ND           |1       |CONN IC DIP SOCKET 14POS TIN   |
|OS102011MS2QN1          |C&K                        |CKN9565-ND          |1       |SWITCH SLIDE SPDT 100MA 12V    |
|SDS-50J                 |CUI Inc.                   |CP-2350-ND          |1       |CONN RCPT FMALE DIN 5POS SOLDER|
|DEV-14057               |SparkFun Electronics       |1568-1442-ND        |1       |TEENSY 3.6 W/OUT HDRS K66 EVAL |
|SJ1-3533NG              |CUI Inc.                   |CP1-3533NG-ND       |2       |CONN JACK STEREO 3.5MM R/A     |
|CF14JT220R              |Stackpole Electronics Inc  |CF14JT220RCT-ND     |2       |RES 220 OHM 1/4W 5% AXIAL      |
|CF14JT10K0              |Stackpole Electronics Inc  |CF14JT10K0CT-ND     |1       |RES 10K OHM 1/4W 5% AXIAL      |
|PPTC241LFBN-RC          |Sullins Connector Solutions|S7022-ND            |2       |CONN HDR 24POS 0.1 TIN PCB     |
|PRPC028SACN-RC          |Sullins Connector Solutions|S1131EC-28-ND       |2       |CONN HEADER VERT 28POS 2.54MM  |

# Photos

![With volca and beatstep](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-hardware/master/photos/volca%2Bbeatstep.jpg "Setup")

![Standalone](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-hardware/master/photos/adapter.jpg)

![Cover](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-hardware/master/photos/cover.jpg)

![Pins](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-hardware/master/photos/pins.jpg)

![Layout](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-hardware/master/photos/layout.PNG)
