# 056 INCH 3 DIGIT 7 SEGMENT SERIALLY CONTROLLED LED DISPLAY 

Open source 7 segment serially controlled led display that fits inside a generic 45x26mm panel mount plastic enclosure. Based on [TM1637](assets/pdf/TM1637.pdf) chip. This IC is controlled by a serial two wire bus similar, but not exactly to i2c.

![METERON](/056-inch-3-digit/assets/img/meteron.jpg)


PCB FRONT                                     | PCB BACK
----------------------------------------------|----------------------------------------------
![](/056-inch-3-digit/assets/img/pcbfront.jpg) |![](/056-inch-3-digit/assets/img/pcbback.jpg) 


The display can be now controlled by Arduino (or any other) boards via serial bus, using a library written for led display modules based on TM1637 chip.

## Panelized PCB
![](/056-inch-3-digit/assets/img/pcbpanel.jpg)

## How to use this repository

The PCB was developed in KiCad V5.1,

## Directory structure

* The root folder contains template KiCad files: project, schematic and PCB 
* /library folder contains additional symbols needed to edit printed schematic
* /modules folder contains additional footprints needed to edit printed circuit board
* /gerber folder contains ready to manufacture files.
* /assets folder contains support files for reade.md
