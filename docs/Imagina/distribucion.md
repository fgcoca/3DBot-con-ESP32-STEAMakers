# <FONT COLOR=#8B008B>Asociación de pines y componentes</font>

## <FONT COLOR=#007575>**Imagina 3DBot**</font>
La asociación de pines analógicos de entrada/salida con componentes es la siguiente:

* A0 / GPIO02 --> Zumbador
* A1 / GPIO04 --> Cualquier sensor o actuador
* A2 / GPIO35 --> Sensor de luz (LDR)
* A3 / GPIO34 --> Sensor de temperatura (NTC)
* A4 --> Bus I2C
* A5 --> Bus I2C

La asociación de pines digitales de entrada/salida con componentes es la siguiente:

* D0 / RX0 --> Bluetooth RX
* D1 / TX0 --> Bluetooth TX
* D2 / GPIO26 --> Sensor de ultrasonidos (ECHO), pulsador
* D3 / GPIO25 --> <FONT COLOR=#00C800><b>LED verde</b></font>, <u><b>emisor infrarrojos</u></b>
* D4 / GPIO17 --> Sensor de ultrasonidos (TRIG)
* D5 / GPIO16 --> <FONT COLOR=#FFC855><b>LED amarillo</b></font>, <u><b>sensor de línea izquierdo</u></b>
* D6 / GPIO27 --> <FONT COLOR=#FF0000><b>LED rojo</b></font>, <u><b>sensor de línea derecho</u></b>
* D7 / GPIO14 --> Motor A (izquierdo)
* D8 / GPIO12 --> Motor A
* D9 / GPIO13 --> Motor A
* D10 / GPIO05 --> Motor B (derecho)
* D11 / GPIO23 --> Receptor de infrarrojos
* D12 / GPIO19 --> Motor B
* D13 / GPIO18 --> Motor B

## <FONT COLOR=#007575>**Pines Imagina 3DBot - ESP32 STEAMakers**</font>
El grupo de pines D0 a D13 tienen la siguiente correspondencia entre las dos placas:

<center>

![Pines D0 a D13](../img/imagina/Ima_05.png)  

</center>

El grupo de pines A0 a A5, SDA y SCL tienen la siguiente correspondencia entre las dos placas:

<center>

![Pines A0 a A5, SDA y SCL](../img/imagina/Ima_06.png)  

</center>

El resto de pines tienen la siguiente correspondencia entre las dos placas:

<center>

![Resto de pines](../img/imagina/Ima_07.png)  

</center>
