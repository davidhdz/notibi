NotiBi
======
Sistema de Notificaciones Bicentenarias.

----
<br>

|Tabla de Contenidos|
|-------------------|
|[Sinopsis](#sinopsis)|
|[Requisitos](#requisistos)|
|[Uso](#uso)|
|[Compatibilidad](#compatibilidad)|
|[Descargas](#descargas)|
|[Capturas](#capturas)|
|[Información](#informacion)|

<br><br>

Sinopsis {#sinopsis}
--------
Sistema de notificaciones con mensajes alusivos a la campaña bicentenaria de Venezuela. Realizado para la Fundación Centro Nacional de Desarrollo e Investigaciones en Tecnologías Libres.
<br><br>
NotiBi es un sistema que despliega en pantalla mensajes con contenidos que relatan de forma resumida acontecimientos sucedidos durante la gesta independentista de Venezuela. 
<br><br>
NotiBi está hecho en python y despliega los mensajes a través del sistema de notificaciones de `gnome (>= 3.x)`. 


Requisitos {#requisitos}
----------
NotiBi requiere los siguientes paquetes:

 * `python >= 2.6`
 * `python-notify >= 0.1.1`


Uso {#uso}
---
    notibi [-t segundos] [-m /ruta/archivo.csv] [-g /ruta/directorio_iconos]

    opciones:
      --version      muestra el número de versión del programa
      -h, --help     muestra este mensaje de ayuda
      -t segundos    establece el tiempo en segundos entre cada notificación
      -m archivo     establece la ubicación y nombre del archivo de mensajes formato csv
      -g directorio  establece la ubicación y nombre de la carpeta de iconos


Compatibilidad {#compatibilidad}
--------------
Probado en distribuciones con entorno Gnome 3
 * Debian Wheezy
 * Caribay 4.0 
 * Canaima 4.x
 * Ubuntu 14.04*

*Nota: Ubuntu 14.04 despliega los mensajes, pero como el entorno no cuenta con área de notificación, los mensajes no se almacenan en ésta como en otras distribuciones que usan Gnome 3.


Descargas {#descargas}
---------
Versión 0.1 para Debian y derivados: [notibi_0.1_all.deb](http://fsl.cenditel.gob.ve/frs/download.php/467/notibi_0.1_all.deb)

Capturas {#capturas}
--------
**Despliegue**
![Despliegue](screenshots/1.png "Despliegue")

<br/>
**Área de notificaciones**
![Área de notificaciones](screenshots/2.png "Área de notificaciones")

<br/>
**Detalle**
![Detalle](screenshots/3.png "Detalle")
<br/>


Información {#informacion}
-----------
**Proyecto bicentenario**: http://bicentenario.cenditel.gob.ve<br>
**Repositorio**: http://github.com/davidhdz/notibi<br>
**Repositorio institucional**: http://fsl.cenditel.gob.ve/frs/?group_id=73&release_id=246

