#### Creando un entorno virtual.

Para crear el entorno virtual debes dirigirte a la carpeta donde lo deseas crear. Se crea con el comando `virtualenv` seguido del nombre que le quieras poner, como lo indica el siguiente ejemplo:
```bash
$ virtualenv nombre_de_tu_entorno -p python3
```
Esto creará una nueva carpeta dentro del directorio que hayamos escogido, allí se instalarán todos los paquetes que desees utilizar.

#### Activar / Desactivar entorno virtual.
Para **activar** el entorno virtual debes dirigirte a la nueva carpeta anteriormente creada y ejecuta:
```bash
$ source nombre_entorno_virtual/bin/activate
```
Para **desactivar** el entorno virtual simplemente ejecuta:
```bash
$ deactivate
```
<a href = "#indice">[IR AL ÍNDICE]</a>