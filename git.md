# Conceptos básicos de Git.
## Introducción.
Es un sistema manejador de versiones diseñado por Linus Torvalds, enfocado a la gestión de los diversos cambios que se realizan en los elementos del proyecto, coordinando el trabajo que varias personas realizan al trabajo.

Git se encuentra dividido por 3 “arboles”, el primero el directorio de trabajo quien contiene los archivos, el segundo el index que hace el rol de zona intermedia, de último lugar se encuentra el HEAD apuntado al último commit.

---
## Características:
* Gestión eficiente de grandes proyectos.
* Realmacenamiento periódico en paquetes.
* Cambios importados como ramas adicionales.
* La mayoría de cada una de las operaciones son locales.

---
## Conceptos básicos.
Merge: fusionar la rama en la que se esta trabajando con la original.
Push: sube los cambios hechos a una rama de trabajo tuya y/o de tu equipo remota.
Pull request: solicitud que se hace al propietario del proyecto para realizar un cambio.
Pull: actualizar su rama HEAD actual con los últimos cambios desde el servidor remoto.
Fetch: descarga datos nuevos de un repositorio remoto, pero no integra ninguno de estos nuevos datos en tus archivos de trabajo.
Commit: identifica los cambios hechos.

---
## Repositorios remotos.
Son versiones del proyecto que se encuentran almacenados en internet o en algún espacio de la red.

---
## Comandos básicos para utilizar Git:
### Configurar Git:
* git config –global user.name «nombre» : Configuramos el nombre con el que nos verán.
* git config –-global user.email johndoe@example.com :Configuramos el correo con el que nos contactan.
### Git init: nuevo repositorio.
* git init
### Clonar un repositorio remoto.
* git clone https://github.com/#####/########.git
### Añadir el documento (o carpeta) en el área de espera («stage»):
* git add nombre_archivo.txt
* git add . : Agrega todos los documentos
* git add –all : Añade los archivos excepto los nuevos
### Hacer un commit.
* git commit –m «mensaje del commit«
### Realizar un push.
* git push origin <nombre de la rama>
### Cambiar de rama.
* git checkout <nombre de la rama>
### Ramas:
* git branch <nombre de la rama> :crea una rama
* git branch :realiza un listado de todas las ramas
* git branch –d <nombre de la rama> :elimina la rama y lo une al master
### Ver el estado actual del repositorio con lista de archivos modificados o agregados.
* git status
### Unir la rama actual con la especificada.
* git merge <nombre de la rama>
### Unir la rama actual con la master.
* git rebase











