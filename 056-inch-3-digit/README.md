# 056 INCH 3 DIGIT 7 SEGMENT SERIALLY CONTROLED LED DISPLAY 

Open source 7 segment serially controlled led display that fits inside a generic 45x26mm panel mount plastic enclosure. Based on [TM1637](assets/pdf/TM1637.pdf) chip. This IC is controlled by a serial two wire bus similar, but not exactly to i2c.

![METERON](/056-inch-3-digit/assets/img/meteron.jpg)


PCB FRONT                                     | PCB BACK
----------------------------------------------|----------------------------------------------
![](/056-inch-3-digit/assets/img/pcbfront.jpg) |![](/056-inch-3-digit/assets/img/pcbback.jpg) 
![](/assets/img/voltmeterpcbfront.jpg)        |![](/036-inch-5-digit/assets/img/pcbfront.jpg) 
![](/assets/img/voltmeterpcbback.jpg)         |![](/036-inch-5-digit/assets/img/pcbback.jpg) 


The display can be now controlled by Arduino (or any other) boards via serial bus, to display numbers, letters, or individual segments.

## Versions

There are several board versions, each one with different personalities


| HINT                               | CONTROLLER CHIP | LINK                                     
|------------------------------------|-----------------|--------------------------------------
| 056 INCH 3 DIGIT                   | TM1637          | [056 INCH 3 DIGIT](/056-inch-3-digit)  
| 036 INCH 5 DIGIT                   | TM1637          | [036 INCH 5 DIGIT](/036-inch-5-digit)  
| 028 INCH 8 DIGIT (2 Lines x 4Digit)| MAX7219         | [028 INCH 8 DIGIT](/028-inch-8-digit)
