<p align = "center">
    <img src = "imagenes/logo_python.jpeg" />
</p>

# 6.1 Instalador de paquetes Pip.

[*Pip*](https://es.wikipedia.org/wiki/Pip_(administrador_de_paquetes)) es un acrónimo recursivo que se puede interpretar como *Pip Instalador de Paquetes* o *Pip Instalador Python*. *Pip* es un sistema de gestión de paquetes sencillo utilizado por *Python* para la **instalación** y **administración** de paquetes del [*Python Package Index (PyPI)*](https://es.wikipedia.org/wiki/Python_Package_Index).

## 6.1.1 Instalación.

*Pip* no viene instalado con *Python*, por lo tanto debemos instalarlo. En un sistema operativo *Linux*, con paquetería *apt* (*Debian*, *Ubuntu*, *Linux Mint*, etc), debemos abrir una terminal (`Ctrl + Alt + T`) y ejecutar:
```bash
$ sudo apt-get install python3-pip
```

## 6.1.2 Actualizar PIP.

Si el gestor de paquetes *Pip* ya está instalado, podemos actualizarlo usando la siguiente instrucción en la terminal:
```bash
$ pip install -U pip
```

## 6.1.3 Administrar paquetes Python.

Para ver la lista de todos los comandos posibles con *Pip* y sus opciones más generales, solo tenemos que ejecutar:
```bash
$ pip
```

Para conocer más sobre un comando en particular, ejecutamos:
```bash
$ pip [comando] --help
```

## 6.1.4 Buscar paquetes.

Para buscar un determinado paquete en el *PyPI*, simplemente intruducimos una cadena de búsqueda en la siguiente instrucción en una terminal: 
```bash
$ pip search [cadena de búsqueda]
```

## 6.1.5 Información de paquetes.

Una vez localizado un paquete con la instrucción `pip search`, podemos solicitar a *Pip* que nos muestre información adicional sobre el paquete ejecutando desde la terminal:
```bash
$ pip show [paquete]
```

## 6.1.6 Instalar paquete.

Para instalar un paquete en nuestro sistema, basta con ejecutar en la terminal:
```bash
$ pip install [paquete]
```

## 6.1.7 Descargar paquete.

Para **descargar** un paquete con todas las dependencias pero **sin instalarlo**, ejecutamos desde la terminal:
```bash
$ pip download [paquete]
```

## 6.1.8 Enumerar paquetes instalados.

Para saber qué paquetes tenemos instalados, podemos ejecutar:
```bash
$ pip list
```
O bien también podemos ejecutar:
```bash
$ pip freeze
```

## 6.1.9 Actualizar paquetes.

Para actualizar un paquete desactualizado, ejecutamos desde una terminal:
```bash
$ pip install --upgrade [paquete]
```
o bien,
```bash
$ pip install -U [paquete]
```

## 6.1.10 Desinstalar paquetes.

Para desinstalar/eliminar un paquete instalado, ejecutamos:
```bash
$ pip uninstall [paquete]
```
Para desinstalar varios paquetes tendremos que escribirlos con un espacio entre ellos.

<a href = "https://github.com/ejdecena/tutorial_python">[IR AL ÍNDICE]</a>