# UNI GYM

copia una breve descripcion del trabjo que tengas en el informe  

* likn  del  viedo : valen toca poner el link que va a mandar pablo 

# Este repositorio contiene:

* Código fuente
* Archivos de información
* Script de desarrollo

# Repositorio de  hardwre:

* Modulo Relé :https://www.vistronica.com/potencia/modulo-rele-de-2-canales-detail.html?gclid=Cj0KCQiAiNnuBRD3ARIsAM8KmlvKu1OsLLj2f1v3_M37RQ9z3bZeedvF-MK_U-YOIhiK0kF-tS2quo4aAoY4EALw_wcB
* arduino :https://www.dynamoelectronics.com/tienda/arduino-uno-r3/?gclid=Cj0KCQiAiNnuBRD3ARIsAM8KmltRdE1reLVw2Ld-6UQwaSnY2RHy3PdUPfCBtxLXO9i95YUO0hzpWVwaAh-HEALw_wcB
* Cerradura Inteligente Turbolock Seguridad Avanzada, Acceso: https://articulo.mercadolibre.com.co/MCO-494151729-cerradura-inteligente-turbolock-seguridad-avanzada-acceso-_JM?matt_tool=24497864&matt_word&gclid=Cj0KCQiAiNnuBRD3ARIsAM8Kmlu89j6uHJSS8UtjVS4zwD6Bxrcboct044f2XQ9sE-nejcqtR0aBroYaAmkkEALw_wcB&quantity=1
*Lector / Escaner Usb Código De Barras Alta Velocidad X-718 :https://articulo.mercadolibre.com.co/MCO-514614632-lector-escaner-usb-codigo-de-barras-alta-velocidad-x-718-_JM?matt_tool=44486125&matt_word&gclid=Cj0KCQiAiNnuBRD3ARIsAM8KmlsBTu21omypiCNl9cqqWR33P5Lns1k10o5mqfF4WjsOqQ4UOGTiZfUaAg6pEALw_wcB&quantity=1

# *Requisitos de Software:*

* Ubuntu 16.04
* Python 2.7 bibliotecas necesarias (mqtt, flask, xlrd)
* IDE Arduino

# *Cómo instalar* 

Es necesario instalar las bibliotecas de la siguiente manera

* Para instalar pandas:
 ```sh
pip install pandas
pip3 install pandas
```
Esta biblioteca es necesaria porque mediante ella podemos astraer la informcaion en la base de datos.

* Para instalar fask:
 ```sh
pip install flask
pip3 install flask
```
Esta biblioteca es la que se encarga de general la pagina.

* Para instalar serial :
```sh 
python -m pip install pyserial
```
Esta bibloteca es la responsable de comunicar la pagina con el Arduino

# no se como ponerle pero es donde esplico los codigos

* doc_exportar.pyc

En este codigo podremos encontrar cada una de las funciones que se encargan de abilitar las opciones de la pagina 
las culaes se van a esportar a la codigo principal,se implementa este metodo para poder llevar un orden a la hora de programar.

```sh
* login
* calificacion
* promedio
* correo
* guardar
```

* PromedioSemana.py

En este codigo se encarga de general la grafica vista en la opcion de horarios .

* Codigo_Paralelo.py

Es el encargado de leer la informacion del lector de  barrar y permitir mediante el arduino que el estudiante ingre al gym, este debe estar ejecutandose al mismo tiempo que el de la pagina 

* Flask1.py

codigo principal es el encargado que general la pagina wed es a que donde se llaman las funciones de doc_exportar.pyc y tdos los codigos (html,css) de las carpetas de templates y static 

# ejecucion no estoy seguro 

* Codigo_Paralelo.py
* Flask1.py

# Universidad de Ibague 

Programa de Ingeniería Electrónica
Electrónica Digital III 2019B

Autores:

 * Johan Steven Avila Paramo
 * Juan Pablo Ocampo
 * vale no me se todo tu nombre 
  

Tutor:

 * Harold F. Murcia

