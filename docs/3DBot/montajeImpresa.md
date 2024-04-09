# <FONT COLOR=#8B008B>Guía de montaje versión pieza impresa 3D</font>
La presente guía de montaje es la que aparece en el manual que acompaña al kit y que está disponible en la [Tienda - Innovad Ddactic](https://shop.innovadidactic.com/es/imagina-steam-y-makers/1598-kit-imagina-arduino-3dbot-esp32-steamakers-para-arduinoblocks.html)

En esta sección vamos a explicar el montaje a partir de la nueva versión del chasis 3DBot formado por una sola pieza.

## <FONT COLOR=#007575>**Material**</font>
El kit Imagina 3dBot incluye:

* 1 Chasis impreso en 3D compacto: 2 ruedas + 2 juntas tóricas y 1 bola de plástico
* 1 Placa de control ESP32 STEAMakers con cable USB
* 1 Shield Imagina 3DBot V4 Innova Didactic
* 2 Motores con placa + cables (Ref. ID_MOTOR_PLACA)
* 3 Sensores infrarrojo siguelíneas (Ref. RBL030120)
* 3 Cables M-M de 20 cms. para conectar los sensores de línea (Ref. RBLSENSOR-PP)
* 1 Power-Bank 5V/2200 mAh (Ref. VL2200PB001GR)
* 1 Sensor de ultrasonidos de 4 pins (Ref. HC-SR04)
* 1 Mando para control remoto (Ref. KS9002)
* 1 Juego de tornillería compuesto por:
    * 4 DIN7981 2,9*25mm
    * 7 DIN7981 2,9*6,5mm
    * 2 DIN7985 M3*12mm
    * 2 DIN934 M3

En la imagen vemos el contenido del kit.

<center>

![Material](../img/3DBot/chasis_3D/material.png)  
*Material*  

</center>

Las piezas impresas en 3D son las siguientes:

<center>

![Chasis 3DBot](../img/3DBot/chasis_3D/ch_1.png)  
*Chasis 3DBot*  
Disponible en: [Tienda - Innovad Ddactic](https://shop.innovadidactic.com/es/3dbot-robotica-con-arduino-o-scratch/1633-chasis-3dbot-nueva-version-cuerpo-de-una-sola-pieza.html)

</center>

Serán necesarias las ruedas también impresas en 3D:

<center>

![Rueda 3DBot](../img/3DBot/chasis_3D/ch_2.png)  
*Rueda 3DBot*  
Disponible en: [Tienda - Innovad Ddactic](https://shop.innovadidactic.com/es/3dbot-robotica-con-arduino-o-scratch/312-rueda-3dbot.html)

</center>

Las ruedas necesitan de neumáticos, que se consiguen a partir de una junta tórica:

<center>

![Tórica neumático](../img/3DBot/chasis_3D/ch_3.png)  
*Tórica neumático*  
Disponible en: [Tienda - Innovad Ddactic](https://shop.innovadidactic.com/es/3dbot-robotica-con-arduino-o-scratch/315-torica-neumatico.html)

</center>

Para funcionar con dos ruedas apoyamos el chasis en una rueda loca:

<center>

![Bola soporte chasis](../img/3DBot/chasis_3D/ch_4.png)  
*Bola soporte chasis*  
Disponible en: [Tienda - Innovad Ddactic](https://shop.innovadidactic.com/es/3dbot-robotica-con-arduino-o-scratch/316-bola-soporte-chasis.html)

</center>

## <FONT COLOR=#007575>**Montaje ESP32 STEAMakers e Imagina 3DBot**</font>
Montaremos la placa ESP32 STEAMakers en la caja de soporte de la placa con 3 tornillos de estrella de 2,9×6,5mm. Encima de esta, instalaremos el Shield Imagina 3DBot y ya podemos conectar la placa ESP32 STEAMakers al ordenador con el cable USB.

<center>

![Montaje ESP32 STEAMakers e Imagina 3DBot](../img/3DBot/chasis_3D/ch_5.png)  
*Montaje ESP32 STEAMakers e Imagina 3DBot*  

</center>

## <FONT COLOR=#007575>**Montaje y conexionado del robot 3DBot**</font>
Colocamos o verificamos que el chasis ya lleve puesta la rueda “loca” trasera.

<center>

![Rueda loca](../img/3DBot/chasis_3D/ch_6.png)  
*Rueda loca*  

</center>

Preparamos el motor izquierdo (motor A), que es el motor que lleva incorporado el sensor de línea fotoeléctrico que hace de “encoder”.

Hemos de poner el soporte para el sensor de línea tal y como se ve en la fotografía con un tornillo de 2,9×6,5mm.

<center>

![Motor izquierdo](../img/3DBot/chasis_3D/ch_7.png)  
*Motor izquierdo*  

</center>

Sujetamos al chasis los motores del robot apretándolos con dos tornillos de 2,9x25mm. 

<FONT COLOR=#FF0000><b></b>¡Importante!</b></font> No hay que apretar en exceso los tornillos para no aplastar la caja reductora y los engranajes de los motores.

Hemos de tener en cuenta que el motor A, que lleva el encoder, es el que se coloca a la izquierda.

<center>

![Motores](../img/3DBot/chasis_3D/ch_8.png)  
*Motores*  

</center>

Insertamos la batería Power Bank, en la parte inferior del chasis con el connector USB hacia la parte trasera.

<center>

![Power Bank](../img/3DBot/chasis_3D/ch_9.png)  
*Power Bank*  

</center>

Conectamos el motor izquierdo a motor A y el motor derecho a motor B en la placa.

<center>

![Conexionado de motores](../img/3DBot/chasis_3D/ch_10.png)  
*Conexionado de motores*  

</center>

Colocamos los sensores de línea fotoeléctricos, sujetándolos con tornillos de M3x12mm y tuercas de M3.

<center>

![Sensores de línea](../img/3DBot/chasis_3D/ch_11.png)  
*Sensores de línea*  

</center>

Una vez los tenemos montados, conectamos el sensor fotoeléctrico izquierdo a la entrada D5 o SL, y el sensor fotoeléctrico derecho a la entrada D6 o SR, con sus respectivos cables.

También conectamos a la entrada D15 el sensor de línea fotoeléctrico de la rueda izquierda (encoder).

<center>

![Conexionado sensores de línea y encoder](../img/3DBot/chasis_3D/ch_12.png)  
*Conexionado sensores de línea y encoder*  

</center>

Colocamos las juntas tóricas en las ruedas y a su vez colocamos estas en los ejes de los motores.

<center>

![Ruedas](../img/3DBot/chasis_3D/ch_13.png)  
*Ruedas*  

</center>

Conectamos el sensor de ultrasonidos a la placa Imagina 3DBot en su correspondiente zócalo, en la parte delantera de la placa.

<center>

![Ultrasonidos](../img/3DBot/chasis_3D/ch_14.png)  
*Ultrasonidos*  

</center>

El aspecto final del robot es:

<center>

![Robot 3DBot](../img/3DBot/chasis_3D/ch_15.png)  
*Robot 3DBot*  

</center>

Ya estamos listos para continuar con las actividades con el robot 3DBot.
