# 028 INCH 8 DIGIT (2 LINES X 4 DIGIT) 7 SEGMENT SERIALLY CONTROLLED LED DISPLAY 

Open source 7 segment serially controlled led display that fits inside a generic 45x26mm panel mount plastic enclosure. Based on [MAX7219](assets/pdf/MAX7219-MAX7221.pdf) chip. This IC is controlled by a serial SPI bus.

![METERON](/028-inch-8-digit/assets/img/meteron.jpg)


PCB FRONT                                     | PCB BACK
----------------------------------------------|----------------------------------------------
![](/028-inch-8-digit/assets/img/pcbfront.jpg) |![](/028-inch-8-digit/assets/img/pcbback.jpg) 


The display can be now controlled by Arduino (or any other) boards via serial bus, using a library written for led display modules based on MAX7219 chip.

## Panelized PCB
![](/028-inch-8-digit/assets/img/pcbpanel.jpg)

## How to use this repository

The PCB was developed in KiCad V5.1,

## Directory structure

* The root folder contains template KiCad files: project, schematic and PCB 
* /library folder contains additional symbols needed to edit printed schematic
* /modules folder contains additional footprints needed to edit printed circuit board
* /gerber folder contains ready to manufacture files.
* /assets folder contains support files for reade.md
