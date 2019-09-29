<div align = "center">
    <img src = "imagenes/logo_python.jpeg" />
</div>

# 6.3 Estructura de un script en Python.

La estructura básica por **convención** de un programa *Python* se presenta en el siguiente fragmento de código:

```python
1 #!/usr/bin/env python3
2 
3 
4 if __name__ == "__main__":
5    pass
6
```

La **línea 1** se conoce como *shebang*, se reconoce al iniciar con los caracteres `#!` cuando están al principio de la primera o segunda línea de un archivo de texto. Indica que el archivo es un *script* y le dice al sistema operativo qué intérprete ha de usarse para ejecutarlo. Los sistemas operativos *Linux* (y otros sistemas *Unix-like*) soportan de forma nativa esta característica.

Entre los ejemplos de *shebang* tenemos:

* `#!/usr/bin/python3` -> Usar el ejecutable *Python* localizado en `/usr/bin`
* `#!/usr/bin/env python3` -> Usa `env` para buscar la variable de entorno "python3" en el PATH para ejecutar el script con ese programa.

Los sistemas operativos *Windows* no tienen soporte nativo para *shebang*. En cambio, usan la *extensión* del archivo para asociarlo al ejecutable de turno. Por lo tanto, la línea de *shebang* sería completamente ignorada en el caso de los sistemas Windows.

La **línea 4** está asociada al modo de funcionamiento del intérprete *Python*. Cuando el intérprete lee un archivo de código, **ejecuta todo el código que se encuentra en él**. Todo módulo (archivo de código) en *Python* tiene un atributo especial llamado `__name__` que define el *espacio de nombres* en el que se está ejecutando el archivo. Este atributo es usado para identificar de forma única un módulo en el sistema de importaciones.

Por su parte `__main__` es el nombre del *ámbito* en el que se ejecuta el código de nivel superior (tu programa principal).

El intérprete pasa el valor del atributo a `"__main__"` si el módulo se está ejecutando como programa principal (cuando lo ejecutas llamando al intérptrete en la terminal con `python my_modulo.py`, haciendo doble click en él, ejecutandolo en el intérprete interactivo, etc ).

Si el módulo NO es llamado como programa principal, sino que es **importado** desde otro módulo, el atributo `__name__` pasa a contener el **nombre del archivo** en sí.

Es decir, si tienes un archivo llamado `mi_modulo.py`, si lo ejecutamos como programa principal el atributo `__name__` será `"__main__"`, si lo usamos importándolo desde otro módulo (`import mi_modulo`) el atributo `__name__` será igual a `"mi_modulo"`.

En resúmen, básicamente lo que haces usando `if __name__ == "__main__":` es ver si el módulo ha sido importado o no. Si no se ha importado (se ha ejecutado como programa principal) ejecuta el código dentro del condicional.

Una de las razones para hacerlo es que, a veces, se escribe un módulo (un archivo *.py*) que se puede ejecutar directamente, pero que alternativamente, también se puede importar y reutilizar sus funciones, clases, métodos, etc. en otro módulo. Con esto conseguimos que la ejecución sea diferente al ejecutar el módulo directamente que al importarlo desde otro programa.

<a href = "https://github.com/ejdecena/tutorial_python">[IR AL ÍNDICE]</a>