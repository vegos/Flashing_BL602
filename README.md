This will contain a howto flash a Smartwise T61 (eWeLink compatible) no-neutral touch wall switch with OpenBL602.  

Tool:  
Buffalo Lab Dev Cube: https://dev.bouffalolab.com/download  

Firmware:  
https://github.com/openshwprojects/OpenBK7231T_App/releases  
(OpenBL602_1.18.288.bin -> https://github.com/openshwprojects/OpenBK7231T_App/releases/download/1.18.288/OpenBL602_1.18.288.bin)  

  
Wiring (from https://www.elektroda.pl/):  

![Wiring](images/Wiring.jpg)  

EN to 3.3V via a 10kΩ resistor (to enter bootloader mode)  
Vcc to 3.3V on USB2TTL  
TX to RX on USB2TTL  
RX to TX on USB2TTL  
GND to GND on USB2TTL  

![Wiring](images/Wired.jpg)  


Software:  

![Flashing](images/BuffaloLabDevCube.png)  


First boot:

![First Boot[(images/FirstBoot.jpg)  

  
To be continued...  
