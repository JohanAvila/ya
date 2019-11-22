# UNI GYM

copia una breve descripcion del trabjo que tengas en el informe  

* likn  del  viedo : valen toca poner el link que va a mandar pablo 

# Este repositorio contiene:

* Código fuente
* Archivos de información
* Script de desarrollo

# *Requisitos de Software:*

* Ubuntu 16.04
* Python 2.7 bibliotecas necesarias (mqtt, flask, xlrd)
* IDE Arduino
# *Cómo instalar*

Es necesario instalar las bibliotecas de la siguiente manera

* Para instalar mqtt:
 sh
sudo apt install -y mosquitto mosquitto-clients

Esta biblioteca es necesaria porque es un protocolo de red abierto liviano que generalmente se ejecuta en tcp / ip que permite enviar y recibir datos a través de Wi-Fi y es perfecto para aplicaciones IoT.

* para instalar paho-mqtt
 sh
pip install paho-mqtt

esa biblioteca ayuda a implementar las versiones 3.1 y 3.1.1 del protocolo MQTT.
* para instalar fask:
 sh
matraz de instalación de sudo pip

Esta biblioteca es donde puede usar el rasberry pi 3 para alojar el sitio web, es decir, el servidor al que irá toda la información.

* para instalar xlrd:
 sh
pip install xlrd "

Con esta biblioteca, podrá vincular los documentos de Excel con el sitio web y, por lo tanto, podrá leer los archivos de información que se ejecutarán.

# Conexión entre el rasberry pi a la pantalla táctil de 3.5 "

Por lo general, cuando usa el rasberry pi, conecta la forma a hdmi con un monitor. En este caso, utiliza una pantalla táctil de 3.5 "que se conecta directamente al pinout de frambuesa, por lo que debe colocar algunos comandos:
 sh
sudo rm -rf LCD-show

git clone https://github.com/goodtft/LCD-show.git

chmod -R 755 pantalla LCD

cd LCD-show /

sudo ./LCD35-show

En la última línea, este 35 indica el tamaño de la pantalla táctil que es tan importante porque si va a trabajar con otra pantalla táctil, necesitará otros comandos.

Si desea volver a trabajar desde el monitor, solo necesita poner los siguientes comandos en el terminal.

 sh
chmod -R 755 pantalla LCD

cd LCD-show /


sudo ./LCD-hdmi

# Programación de Nodemcu ESP8266
En primer lugar, necesita instalar una biblioteca en arduino IDE

se abre el archivo, luego las preferencias e ingrese
 sh
https://arduino.esp8266.com/stable/package_esp8266com_index.json

en el campo URL de Board Manager adicionales. Puede agregar varias URL, separándolas con comas.
luego, vaya al administrador de tarjetas y al motor de búsqueda, escriba "esp8266" y seleccione "comunidad esp0266", luego placa de herramientas y seleccione el módulo esp8266 genérico, el tamaño del flash se establece en "4M (1M SPIFFS)" y "velocidad de carga: 115200" y El puerto serie está configurado.

# * Universidad de Ibague *
Programa de Ingeniería Electrónica
Electrónica Digital III 2019B
Autores
  - Julian David Alcala Forero
  - Jhon Faver Mendoza
  - Juan Camilo Leon Martinez
  
  Tutor:
  Harold F. Murcia
Enviar comentarios
Historial
Guardadas
Comunidad
