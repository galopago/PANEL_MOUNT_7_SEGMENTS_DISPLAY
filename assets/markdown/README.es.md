# DISPLAY DE 7 SEGMENTOS PARA MONTAJE EN PANEL CONTROLADO SERIALMENTE

Display de 7 segmentos Open Source para montaje en panel, controlado serialmente que encaja en un bisel generico para montaje en panel de 45x26mm. So podra actualizar en medidor de panel de uso especifico, simplemente cambiando el PCB por uno nuevo, el cual puede ser comandado por un microcontrolador.

![METERON](/036-inch-5-digit/assets/img/meteron.jpg)

Lea esto en otros idiomas: [English](../../README.md)

Actualizando el PCB del voltimetro de 5 digitos por uno que se puede controlar serialmente.

0.36 Pulgadas 5 Digitos voltimetro     | 0.36 Pulgadas 5 Digitos controlable serialmente     
---------------------------------------|----------------------------------------------
![](/assets/img/voltmeterback.jpg)     |![](/036-inch-5-digit/assets/img/meterback.jpg) 
![](/assets/img/voltmeterpcbfront.jpg) |![](/036-inch-5-digit/assets/img/pcbfront.jpg) 
![](/assets/img/voltmeterpcbback.jpg)  |![](/036-inch-5-digit/assets/img/pcbback.jpg) 

El display ahora puede ser controlado mediante una tarjeta Arduino (con otras tambien!) mediante un bus serial. Se podran mostrar numeros, caracteres o segmentos individuales.

## Versiones

Existen varias versiones de la tarjeta, cada una tiene su propia personalidad

| DESCRIPCION                                  | CHIP CONTROLADOR| ENLACE                               
|----------------------------------------------|-----------------|--------------------------------------
| 056 PULGADAS 3 DIGITOS                       | TM1637          | [056 INCH 3 DIGIT](/056-inch-3-digit)  
| 036 PULGADAS 5 DIGITOS                       | TM1637          | [036 INCH 5 DIGIT](/036-inch-5-digit)  
| 028 PULGADAS 8 DIGITOS (2 Lineas x 4 Digitos)| MAX7219         | [028 INCH 8 DIGIT](/028-inch-8-digit)
