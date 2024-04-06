---
layout: default
---

## Comandos de GIT

Git es un sistema de control de versiones.

El primer comando que vamos a conocer es:

```bash:
    $ git init 
```

Este comando inicializa un repositorio, es una base de datos donde se van a guardar todos los cambios que realices.

```bash:
    $ git add texto.txt
```

Con este comando agregamos el archivo a la base de datos. y lo mandas al stage.

```bash:
    $ git commit -m "Este es el primer commit"
```

Este comando le manda el último cambio a git, es decir que el archivo esta listo. 
```bash:
    $ git add .
```

Este comando le indica a git que agregue todos los archivos que sufrieron cambio. 
```bash:
    $ git status
```

Este comando nos muestra que archivos tienen cambios.
```bash:
    $ git show
```

Este comando nos muestra de manera visual todos los cambios de manera histórica, cuando se hicieron y quienes lo hicieron.

```bash:
    $ git log texto.txt
```

Este comando nos permite ver los cambios historicos de un archivo.

```bash:
    $ git checkout
```

Cambiar ramas o restaurar archivos del árbol de trabajo

```bash:
    $ git diff numero de commit numero de commit
```

Este comando te permite comparar un commit con otro commit

_FSL_

[back](./)