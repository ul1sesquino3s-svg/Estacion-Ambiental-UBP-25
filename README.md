# Estacion-Ambiental-UBP-25

Repositorio del proyecto de Lab-I con Arduino UNO: Estación Ambiental Inteligente con sensores y módulos

Integrantes del proyecto: Ignacio Alzabé, Donato Doebbeling, Ulises Carlos Quiñones, Juan Manuel Servadei

Profesores:

Teórico: Ing. Martín Salamero

Práctico: Prof. Aguero y Prof. Escudero



## **Cosas Importantes**

**Lectura de los archivos CSV**
Cada linea tiene la fecha y la hora, y los números que hay corresponden a la temperatura, humedad del aire, luminosidad y humedad

de la tierra, respectivamente.

**App Bluetooth**

Se abre la app, debe elegirse el módulo previamente emparejado llamada *GORDATO*, luego se presiona "Conectar" y se espera un minuto

hasta que se envien por primera vez los datos en el módulo.

**LCD I2C**

Todos los sensores mostrarán 0 en sus lecturas durante el primer minuto; esto forma parte del funcionamiento esperado, ya que

los datos se actualizan cuando se cargan en el archivo csv, que ocurre cada 60 segundos.

**Contenido del Repositorio**

Presentación utilizada durante la exposición

Archivo CSV del día 22 de octubre, uno de los días los cuales se hizo la prueba de 48hs.

Informe completo del proyecto

Bitácoras de todo el progreso del proyecto

Código en .ino del proyecto y backup en .txt

Archivo STL de la carcasa creada para el proyecto

README

