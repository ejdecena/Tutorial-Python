<div align = "center">
    <img src = "imagenes/logo_python.jpeg" />
</div>

# Guía de estilo PEP8.

En la organización *Python* existen lo que se llaman *PEP's* o [*Python Enhancement Proposals*](http://www.python.org/dev/peps/pep-0001/#what-is-a-pep), los cuales son documentos que proveen información a la comunidad de *Python* o describen nuevas características del lenguaje, su proceso de desarrollo o su entorno. Uno de estos *PEP's* es el *PEP8*, el cual está dedicado a la recopilación de los **estándares de estilo** seguidos por los desarrolladores de *Python* a la hora de escribir código para la librería estandar. Un listado completo de los *PEP's* se puede encontrar [aquí](http://www.peps.io/), mientras que una versión en castellano del *PEP8* se puede descargar de [aquí](documentos/guia_pep8_es.pdf) en este repositorio.

Algunas las principales convenciones de estilo para escribir código *Python* son las siguientes:

* Usar 4 espacios para indentar.
* Es posible usar solo tabulaciones u ocho espacios para código antiguo que haya sido escrito así. Por ningún motivo se han de mezclar espacios y tabulaciones.
* Limitar los tamaños de línea a 79 caracteres como máximo, si bien se puede continuar líneas largas con el símbolo `\`, es recomendable el uso de paréntesis.
* Se deben separ las funciones de nivel superior y las clases con dos líneas en blanco, mientras que los métodos dentro de clases los podemos separar con una sola línea. También se pueden usar líneas en blanco dentro de las funciones para separ bloques que guardan cierta correlación lógica.
* Las sentencias de `import` deben estar generalmente separadas una en cada línea.
* Las sentencias import deben de estar siempre en la parte superior del archivo agrupadas de la siguiente manera:
    * Librería estándar.
    * Librerías de terceros.
    * import's de la aplicación local.
* Usar espacios alrededor de los operadores aritméticos.
* No usar espacios alrededor del signo igual cuando se encuentre en un listado de argumentos de una función.
* Los comentarios que contradicen al código son peores que cuando no existen comentarios.
* No se deben de realizar comentarios obvios.
* No se deben comparar booleanos mediante ==

<a href = "README.md#indice">[IR AL ÍNDICE]</a>