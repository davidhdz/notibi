NotiBi
======
Sistema de Notificaciones Bicentenarias.

----

Sinopsis
--------
Sistema de notificaciones con mensajes alusivos a la campaña bicentenaria de Venezuela. 
Realizado para la Fundación Centro Nacional de Desarrollo e Investigaciones en Tecnologías Libres.
<br><br>
NotiBi es un sistema que despliega en pantalla mensajes con contenidos que relatan de forma resumida acontecimientos sucedidos durante la gesta independentista de Venezuela. 
<br><br>
NotiBi está hecho en python y despliega los mensajes a través del sistema de notificaciones de `gnome (>= 3.x)`. 


Requisitos
----------
NotiBi requiere los siguientes paquetes:

 * `python >= 2.6`
 * `python-notify >= 0.1.1`


Uso
---
```bash
  notibi [-t segundos] [-m /ruta/archivo.csv] [-g /ruta/directorio_iconos]

  opciones:
    --version      show program's version number and exit
    -h, --help     muestra este mensaje de ayuda
    -t segundos    tiempo en segundos entre cada notificación
    -m archivo     ubicación y nombre del archivo de mensajes formato csv
    -g directorio  ubicación y nombre de la carpeta de iconos
```

Información
-----------

* **Proyecto bicentenario:** http://bicentenario.cenditel.gob.ve
* **Repositorio:** http://github.com/davidhdz/notibi
* **Repositorio institucional:** https://canaima.cenditel.gob.ve/trac/browser/bicentenario/notificaciones


Capturas
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
