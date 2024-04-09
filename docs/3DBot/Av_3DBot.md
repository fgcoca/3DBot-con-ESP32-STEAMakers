# <FONT COLOR=#8B008B>Actividades 3DBot</font>

<center>

![Robot 3DBot](../img/3DBot/actividades/act_3dbot_1.png)  
*Robot 3DBot*  

</center>

Se recomienda revisar los contenidos en [actividades avanzadas con la placa Imagina 3DBot](../Imagina/avanzadas_imagina.md) antes de afrontar esta actividad con el robot.

## <FONT COLOR=#007575>**Telegram. Movimientos 3DBot**</font>
Ejemplo basado en el tutorial de Pedro Ruiz [Ejemplos 3DBot + ESP32 STEAMakers](https://pedroruizf.github.io/ejemplos_3dbot/index.html).

Lo que haremos será controlar los movimientos del robot mediante un bot de Telegram.

Comenzamos por configurar la conexión WiFi y el API Token de Telegram.

<center>

![Telegram. Movimientos 3DBot](../img/3DBot/actividades/act_3dbot_2.png)  
*Telegram. Movimientos 3DBot*  

</center>

Definimos las siguientes funciones con paso de valor desde una variable:

<center>

![Telegram. Movimientos 3DBot](../img/3DBot/actividades/act_3dbot_3.png)  
*Telegram. Movimientos 3DBot*  

</center>

Finalmente configuramos el evento de Telegram 'Nuevo mensaje recibido' y ya podemos subir el programa a la placa.

<center>

![Telegram. Movimientos 3DBot](../img/3DBot/actividades/act_3dbot_4.svg)  
*Telegram. Movimientos 3DBot*  
Clic sobre la imagen para ampliarla  
[Acceder al programa](http://www.arduinoblocks.com/web/project/1715586)

</center>

## <FONT COLOR=#007575>**Telegram. Movimientos y control de consumo 3DBot**</font>
Ejemplo basado en el tutorial de Pedro Ruiz [Ejemplos 3DBot + ESP32 STEAMakers](https://pedroruizf.github.io/ejemplos_3dbot/index.html).

Lo que haremos será controlar los movimientos del robot y consultar los datos de sus sensores tanto internos como e la placa Imagina 3DBot mediante un bot de Telegram.

Partimos del ejemplo anterior y comenzamos por configurar la conexión WiFi y el API Token de Telegram.

<center>

![Telegram. Movimientos 3DBot](../img/3DBot/actividades/act_3dbot_2.png)  
*Telegram. Movimientos 3DBot*  

</center>

Las funciones y bloques del ejemplo anterior los dejamos como están.

Modificamos el mensaje de ayuda para que tenga estos textos:

>
/ayuda o /help: ordenes disponibles; /adelante /atras /izda /dcha /Rizda para rotar a la izquierda /Rdcha para rotar a la derecha  /Gizda para giro atras izquierda /Gdcha para giro atras derecha /internos para consultar valores de sensores internos /distancia da la distancia a objeto /luz da el valor de luminosidad /ambiente da la temperatura ambiente

Añadir la función y bloques que vemos seguidamente.

<center>

![Telegram. Movimientos y control de consumo 3DBot](../img/3DBot/actividades/act_3dbot_5.png)  
*Telegram. Movimientos y control de consumo 3DBot*  
[Acceder al programa](http://www.arduinoblocks.com/web/project/1715595)

</center>

## <FONT COLOR=#007575>**IoT con ThingSpeak**</font>

