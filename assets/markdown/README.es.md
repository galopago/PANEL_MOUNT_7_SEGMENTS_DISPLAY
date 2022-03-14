# DISPLAY DE 7 SEGMENTOS PARA MONTAJE EN PANEL CONTROLADO SERIALMENTE

Display de 7 segmentos Open Source para montaje en panel, controlado serialmente que encaja en un bisel generico para montaje en panel de 45x26mm. So podra actualizar en medidor de panel de uso especifico, simplemente cambiando el PCB por uno nuevo, el cual puede ser comandado por un microcontrolador.

![METERON](/036-inch-5-digit/assets/img/meteron.jpg)

Lea esto en otros idiomas: [English](/assets/markdown/README.md)

Upgrading a 5 digit voltmeter PCB with a 5 digit serially controllable display

0.36 Inch 5 Digits voltmeter           | 0.36 Inch 5 Digits serially controllable     
---------------------------------------|----------------------------------------------
![](/assets/img/voltmeterback.jpg)     |![](/036-inch-5-digit/assets/img/meterback.jpg) 
![](/assets/img/voltmeterpcbfront.jpg) |![](/036-inch-5-digit/assets/img/pcbfront.jpg) 
![](/assets/img/voltmeterpcbback.jpg)  |![](/036-inch-5-digit/assets/img/pcbback.jpg) 

The display can be now controlled by Arduino (or any other) boards via serial bus, to display numbers, letters, or individual segments.

## Versions

There are several board versions, each one with different personalities

| HINT                               | CONTROLLER CHIP | LINK                                     
|------------------------------------|-----------------|--------------------------------------
| 056 INCH 3 DIGIT                   | TM1637          | [056 INCH 3 DIGIT](/056-inch-3-digit)  
| 036 INCH 5 DIGIT                   | TM1637          | [036 INCH 5 DIGIT](/036-inch-5-digit)  
| 028 INCH 8 DIGIT (2 Lines x 4Digit)| MAX7219         | [028 INCH 8 DIGIT](/028-inch-8-digit)
