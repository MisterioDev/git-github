# CURSO DE _GIT_ Y _GITHUB_

Git es un sistema de control de versiones de código, mientras que GitHub es una plataforma en línea que utiliza Git para alojar repositorios de código.

Git es una herramienta de línea de comandos que permite a los desarrolladores controlar y rastrear los cambios en sus proyectos de software. Con Git, los desarrolladores pueden crear repositorios locales en sus computadoras y realizar operaciones como confirmar cambios, crear ramas y fusionar cambios.

Por otro lado, GitHub es un servicio en línea que proporciona un alojamiento para repositorios de Git. Es una plataforma colaborativa que permite a los desarrolladores alojar sus proyectos de software en un servidor remoto y colaborar con otros desarrolladores en el mismo proyecto. A través de GitHub, los desarrolladores pueden crear repositorios públicos o privados, y también pueden contribuir a los repositorios de otros desarrolladores.

## FLUJO DE GIT Y GITHUB

El flujo básico de Git se refiere a los pasos que se siguen para trabajar con un repositorio de Git.

![Flujo Git y GitHub](https://jonmircha.com/img/blog/git-flow.png)

El área de trabajo es donde se realizan los cambios en los archivos del proyecto. Puedes hacer cambios, agregar nuevos archivos, etc. Para GIT las carpetas seran llamadas repsitorios, la carpeta local donde ejecutamos el comando "git init" es nuestro directorio de trabajo.

Una vez que se han realizado cambios en el área de trabajo, se deben agregar al área de preparación. Esto se hace con el comando "git add". El área de preparación es una especie de "zona intermedia" donde se almacenan los cambios antes de ser confirmados.

Los cambios en el área de preparación se confirman con el comando "git commit". Al hacerlo, se registran los cambios en el repositorio y se les asigna un mensaje que explica los cambios realizados.

Los cambios registrados en el repositorio se pueden verificar en cualquier momento utilizando el comando "git log".

Si quieres compartir tus cambios con otros desarrolladores o almacenarlos en un repositorio remoto, puedes usar el comando "git push" para enviarlos a un repositorio remoto, como GitHub. Para traer cambios de otros desarrolladores o repositorios remotos, puedes usar el comando "git pull" para descargar los cambios a tu repositorio local.

##COMANDOS:

**mkdir (+nombre de carpeta)** Crea carpeta. **cd (+nombre de carpeta)** Ingresa a carpeta. **touch (+nombre de archivo)** Crea archivos. **touch .gitignore** Todas las rutas en el, son ignoradas. **ls** Muestra los archivos dentro de la carpeta. **ls -a** Muestra todos los archivos, incluido los ocultos.

**git init** Inicializa un nuevo repositorio de Git en la carpeta actual. **git add (+nombre de archivo)** Agregar los cambios de un archivo al staged. **git add .** Agregar todos los cambios de todos los archivos al staged. **git commit -m "mensaje descriptivo del cambio"** Confirma cambios y agrega comentario.
