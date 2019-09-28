<div align = "center">
    <img src = "imagenes/logo_python.jpeg" />
</div>

# Tutorial Python.

*Tutorial Python* es una guía de referencias para la instalación e introducción rápida al lenguaje [*Python*](https://www.python.org/).


<img src="https://img.shields.io/badge/License-MIT-green" /> <img src="https://img.shields.io/badge/Markdown-1.0.1%20-blue" />

## Desarrolladores.

* [Ing. Edgard Decena.](mailto:edecena@gmail.com)
* [Ing. Luís Acevedo.](mailto:laar19@protonmail.com)

<a name = "indice"></a>

## Índice.

<pre>
1. <a href = "#python">Python y el Cálculo Científico.</a>
2. <a href = "#instalacion">Instalación.</a>
3. <a href = "#modos">Modos de uso.</a>
4. <a href = "#caracteristicas">Características fundamentales.</a>
5. <a href = "#libros">Libros de aprendizaje.</a>
    5.1 <a href = "#python-crach-course">Python Crash Course.</a>
    5.2 <a href = "#learning-python">Learning Python.</a>
    5.3 <a href = "#fluent-python">Fluent Python.</a>
    5.4 <a href = "#learning-python-the-hard-way">Learn Python: the hard way.</a>
    5.5 <a href = "#python-cookbook">Python Cookbook.</a>
    5.6 <a href = "#python-para-todos">Python para todos.</a>
6. <a href = "#trucos">Trucos y consejos.</a>
    6.1 <a href = "creando_un_entorno_virtual.md">Creando un entorno virtual Python.</a>
    6.2 <a href = "estructura_script_python.md">Estructura de un script en Python.</a>
    6.3 <a href = "guia_estilo_pep8.md">Guía de estilo PEP8.</a>
7. <a href = "#codigos">Códigos Python.</a>
    7.1 <a href = "codigos/hola_mundo.py">Hola Mundo Python!</a>
</pre>

<a name = "python"></a>

## 1. Python y el Cálculo Científico.

Históricamente la ciencia se ha dividido en **disciplinas experimentales** y **disciplinas teóricas** (o *empirismo* y *racionalismo*). Consecuentemente, un gran número de estudios en filosofía de la ciencia (*epistemología*) se han dedicado al estudio de la interelación de estos dos modos de hacer ciencia. Durante las últimas décadas la **computación** ha emergido como un componente importante del quehacer científico, y al hacerlo ha desestabilizado esta visión binaria de la ciencia. Dicho de una forma simple, es posible ahora usar las computadoras para resolver problemas científicos de forma más rápida y menos engorrosa; **pero sobre todo, resolver problemas que antes no podían ser resueltos analíticamente**.

Para la solución de estos problemas científicos, dentro del software libre ha surgido en los últimos años el lenguaje de programación [**Python**](https://www.python.org), que últimamente ha tenido una mejora sustancial con la inclusión de potentes y versátiles librerías de cálculo simbólico (*SymPy*), numérico (*NumPy* y *SciPy*) y gráfico (*PyPlot* y *Matplotlib*). *Python* ha tenido una vertiginosa evolución y expansión a nivel mundial, no sólo en el ámbito académico, sino también en el ámbito científico e industrial.

<a href = "#indice">[IR AL ÍNDICE]</a>

<a name = "instalacion"></a>

## 2. Instalación.

Según el sistema operativo, *Python* puede ser instalado de 3 maneras:
* **Windows**: puede ser descargado directamente desde la [página principal](https://www.python.org/downloads/windows/) de *Python*.
* **Mac OS X**: Aunque la mayoría de las versiones de *MacOsX* vienen con *Python* pre instalado, puede en algunos casos instalarse desde la [página principal](https://www.python.org/downloads/mac-osx/) de *Python*. 
* **Linux**: Todas las versiones de Linux vienen instaladas con *Python*. podrás ver la versión que tienes instalada abriendo la terminal y escribiendo `python`.

<a href = "#indice">[IR AL ÍNDICE]</a>

<a name = "modos"></a>

## 3. Modos de uso.

En *Python*, se suele usar el código de 3 modos relacionados:

* **Interactivo**: Esto es común en tareas exploratorias, cuando aún no tenemos del todo definido el problema. Por ejemplo, tenemos un conjunto de datos en uno o más archivos y necesitamos saber qué información contienen, quizás hacer algún gráfico o buscar palabras claves. Los modos interactivos de *Python* pueden habilitarse al usarlo directamente en la terminal a través del intérprete del lenguaje, mediante *Jupyter Notebooks*, compiladores online, etc.

* **Scripts**: Los scripts (del inglés guión) se refiere a pequeños programas que se usan para tareas sencillas, generalmente cuando queremos automatizar tareas como hacer una copia de respaldo (backup) semanal, o descargar alguna información de una página web cada vez que esta actualice cierta información. A veces también estos scripts se usan como "pegamento" para concatenar programas, generalmente cuando estos programas son complejos o no tenemos acceso al código fuente (o no entendemos el código fuente).

* **Paquetes o librerías**: Esto es más o menos lo que uno tiene en mente cuando piensa en un programa, como una hoja de cálculo, o una aplicación de para el celular. Es decir, son varios bloques de códigos organizados para realizar diversas tareas. En general, un usuario de *Python* NO escribe librerías, sino que hace uso de ellas. Escribir librerías requiere de ciertos principios de ingeniería de software, de lo contrario el código tendrá altas probabilidades de ser ineficiente, difícil de mantener, propenso a errores, etc.

<a href = "#indice">[IR AL ÍNDICE]</a>

<a name = "caracteristicas"></a>

## 4. Características fundamentales.

El lenguaje *Python* es:
* Un lenguaje de programación **orientado a objetos**.
* De **propósito general**, es suficientemente bueno para casi todo.
* **Multiparadigma**, es posible programar usando distintos estilos de programación o incluso combinándolos.
* De **alto nivel**, es decir cercano al lenguaje humano y lejos del lenguaje máquina.
* **Interpretado**, es decir no es necesario compilarlo antes de correr un script Python.
* **Multiplataforma**, corre en diversos sistemas operativos.
* Un lenguaje **simple**, el código es simple de leer, de escribir y de mantener.
* **Gratuito** y es una herramienta de **código abierto**.
* Está muy **bien documentado**.
* Es ampliamente usado en la mayoría de las disciplinas científicas.
* Tiene una gran comunidad de usuarios (no todos científicos), por lo que es fácil encontrar ayuda, tutoriales, foros, blogs, etc.
* Buena performance. Aunque estrictamente es un lenguaje lento (el costo de la simplicidad). Existen formas de acelerarlo.
* Posee un extenso ecosistema de librerías:

<p align = "center">
    <a href = "https://www.youtube.com/watch?v=5GlNDD7qbP4">
        <img src = "imagenes/python_librerias.png"/>
    </a>
</p>

<a href = "#indice">[IR AL ÍNDICE]</a>

<a name = "libros"></a>

## 5. Libros de aprendizaje.

*Python* es un lenguaje con una curva de aprendizaje interesante. Muchos autores han decidido volcar sus conocimientos para apoyar a los aprendices en la construcción de programas y conocimiento estructurado. Hay libros especializados en temas puntuales o en tópicos importantes; como por ejemplo el desarrollo web o el análisis de datos.

La correcta elección de un libro implica muchos factores, pero es bastante útil de primera mano buscar referencias que nos puedan dar un panorama más claro del autor o título, para así tener la seguridad antes de leer un libro sobre *Python*.

Aquí te presentamos los principales libros sobre el lenguaje, los más destacados a elección de los profesionales del sector.

<a name = "python-crach-course"></a>

### 5.1 Python Crash Course.

[*Python Crash Course*](https://www.amazon.com/Python-Crash-Course-Hands-Project-Based/dp/1593276036) es un curso sorprendente, orientado a personas que quieren aprender a programar por cuenta propia.  Es una introducción amena a la programación y particularmente, como es lógico, al lenguaje *Python*. A través del libro se tienen distintos desafíos entre los cuales destaca el escribir programas, resolver problemas y consolidar los conceptos básicos previos a código de mayor nivel.

El libro enseña conceptos bastante populares en la actualidad, como el uso de librerías, la respuesta a eventos de mouse y teclado, visualización de datos e incluso creación de juegos en 2D.

<a name = "learning-python"></a>

### 5.2 Learning Python.

[*Learning Python*](https://www.amazon.com/Learning-Python-5th-Mark-Lutz/dp/1449355730) es uno de los libros más populares, dado que es el resumen del curso de entrenamiento en *Python* de su autor, Mark Lutz. Es un libro que mejora constantemente, presentando una quinta edición bastante robusta que introduce conceptos y buenas prácticas.

Tiene muchas bondades, entre ellas desafíos que permiten escribir código de forma rápida, eficiente y de alta calidad. Está indicado para personas con pocos conocimientos, aunque obviamente es útil también para programadores con mayor experiencia.

De primera mano permite explorar los tipos de objeto por defecto que vienen con el lenguaje, como la sintaxis elemental. Una de sus principales características es que todos los conocimientos están orientados en la programación orientada a objetos.

<a name = "fluent-python"></a>

### 5.3 Fluent Python.

[*Fluent Python*](https://www.amazon.com/Fluent-Python-Concise-Effective-Programming/dp/1491946008) es un libro distinto, está diseñado para volverse productivo en el desarrollo con *Python* de forma rápida, dado que es un libro “hands-on” que básicamente prioriza las actividades a la teoría.

Este libro se concentra en aspectos importantes como modelos y estructuras de datos, funciones y flujos de control. Además tiene una sección muy interesante relacionada a la metaprogramación, un concepto más avanzado pero inherente a grandes proyectos.

<a name = "learning-python-the-hard-way"></a>

### 5.4 Learn Python: the hard way.

[*Learn Python: the hard way*](https://learnpythonthehardway.org/book/) es un libro que por el título puede pensarse está orientado a programadores experimentados o que buscan un desafío en su aprendizaje. Sin embargo, es un libro eminentemente para principiantes, de una elevada calidad. El término “Hard way” se refiere al deseo del autor de afianzar algunos conceptos como base para avanzar en el libro.

El libro tiene niveles iniciales con temas elementales (como el primer Hola mundo o la construcción de variables) pero poco a poco ahonda y permite tener una visión sólida del lenguaje *Python* de cara a la programación orientada a objetos.

<a name = "python-cookbook"></a>

### 5.5 Python Cookbook.

[*Python Cookbook*](https://www.amazon.com/Python-Cookbook-Third-David-Beazley/dp/1449340377) es uno de los libros más amenos para el aprendizaje de *Python*. Se puede encontrar las indicaciones para el desarrollo de programas a manera de recetas. Hay una serie de temas interesantes para desarrolladores experimentados y novatos que se pueden explorar. Entre ellos están los algoritmos y estructuras de datos, las cadenas de texto y números, los tipos de operadores, las clases y objetos, la programación web y los principales errores en el desarrollo de un programa.

<a name = "python-para-todos"></a>

### 5.6 Python para todos.

[*Python para todos*](documentos/libro_python_para_todos.pdf) se trata de un libro gratuito, que empieza tratando sobre conceptos básicos pero ahonda hasta el uso de bases de datos. Está distribuido bajo una licencia de *Creative Commons* y se puede realizar su descarga en formato PDF directamente desde su misma página web.

Estos fueron algunos títulos únicamente del gran universo bibliográfico que gira en torno a *Python*. Como hemos podido ver, la mayoría de ellos están escritos en inglés, pero inclusive si no tienes el idioma a la perfección muchos de los conceptos son entendibles.

Siéntete en la libertad de usar libros para aprender *Python* cuando desees, porque si bien es cierto que para programar se necesita escribir código a diario, un libro puede ser el aliado perfecto al momento de diagnosticar un error o resolver un bug.

<a href = "#indice">[IR AL ÍNDICE]</a>

<a name = "trucos"></a>

## 6. Trucos y consejos.


