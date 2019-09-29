<div align = "center">
    <img src = "imagenes/logo_python.jpeg" />
</div>

# Creando un entorno virtual Python.

Cuando se está desarrollando software en *Python*, es común utilizar diferentes versiones de un mismo paquete. Un *virtualenv*, o entorno virtual de *Python*, es un ambiente creado con el objetivo de aislar recursos como librerías y entornos de ejecución del sistema principal o de otros entornos virtuales. Esto significa que en el mismo sistema, computadora, es posible tener instaladas múltiples versiones de una misma librería sin crear ningún tipo de conflicto.

Para crear y utilizar un entorno virtual debe instalarse `virtualenv`; pero antes debe instalarse el [manejador de paquetes](instalador_paquetes_pip.md) de *Python* `pip`:
```bash
$ sudo apt-get install python3-pip
```
Luego instalamos `virtualenv`:
```bash
$ sudo pip3 install virtualenv
```

## Creando un entorno virtual.

Para crear el entorno virtual debes dirigirte a la carpeta donde lo deseas crear. Se crea con el comando `virtualenv` seguido del nombre que le quieras poner, como lo indica el siguiente ejemplo:
```bash
$ virtualenv nombre_de_tu_entorno -p python3 --no-site-packages
```
Esto creará una nueva carpeta dentro del directorio que hayamos escogido, allí se instalarán todos los paquetes que desees utilizar.

## Activar / Desactivar entorno virtual.

Para **activar** el entorno virtual debes dirigirte a la nueva carpeta anteriormente creada y ejecuta:
```bash
$ source nombre_entorno_virtual/bin/activate
```
Para **desactivar** el entorno virtual simplemente ejecuta:
```bash
$ deactivate
```
<a href = "https://github.com/ejdecena/tutorial_python">[IR AL ÍNDICE]</a>