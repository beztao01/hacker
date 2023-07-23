---
layout: default
---

## Comandos de GIT

Git es un sistema de control de versiones.

El primer comando que vamos a conocer es:

```bash
    $ git init 
```

Este comando inicializa un repositorio, es una base de datos donde se van a guardar todos los cambios que realices.

```bash
    $ git add texto.txt
```

Con este comando agregamos el archivo a la base de datos. y lo mandas al stage.

```bash
$ git commit -m "Este es el primer commit"
```

Este comando le manda el ultimo cambio a git, es decir que el archivo esta listo. 
```bash
$ git add .
```

Este comando le indica a git que agregue todos los archivos que sufrieron cambio. (hay que validar esta info)
```bash
$ git status
```

Este comando nos muestra que archivos tienen cambios.
```bash
$ git show
```

Este comando nos muestra de manera visual todos los cambios de manera histórica, cuando se hicieron y quienes lo hicieron.
```bash
$ git log texto.txt
```

Este comando nos permite ver los cambios historiocos de un archivo

_Beztao_

[back](./)