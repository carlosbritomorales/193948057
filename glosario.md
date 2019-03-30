Glosario

Git es un software de control de versiones (SCV) distribuido, libre y de c�digo abierto. Facilita el manejo de c�digo fuente con equipos de desarrollo distribuidos. La principal diferencia con SCV previos es la habilidad para hacer operaciones comunes (branching, committing, etc.) en el equipo de desarrollo local, sin tener que modificar el repositorio master o tener de acceso de escritura a �l. 

a. Control de versiones (VC)

El control de versiones es un sistema que permite almacenar un registro de cambios realizados en diferentes archivos a lo largo del tiempo, logrando as� organizar diferentes versiones de un determinado documento para acceder a versiones espec�ficas de los mismos.
Cabe destacar que a pesar de que est� pensado  para registro de c�digos tambi�n se puede llevar un control de versiones de cualquier archivo que se encuentre en un ordenador.

https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones

b. Control de versiones distribuido (DVC) 

El control de versiones es un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo, de modo que puedas recuperar versiones espec�ficas m�s adelante. Adem�s, el control de versiones distribuido permite a muchos desarrolladores de software trabajar en un proyecto com�n sin necesidad de compartir una misma red. Las revisiones son almacenadas en un sistema de control de versiones distribuido (DVCS, por sus siglas en ingl�s).

https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones 

c. Repositorio remoto y Repositorio local 

(RAE) Repositorio: Almac�n o lugar donde se guardan ciertas cosas.

Un repositorio local se pueden entender como la carpeta de un proyecto. Este contiene todos los archivos del proyecto, incluyendo la documentaci�n, adem�s almacena la historia de revisiones. 
Los repositorios remotos son versiones de tu proyecto que se encuentran alojados en Internet o en alg�n punto de la red, los repositorios remotos pueden tener m�ltiples colaboradores y pueden ser p�blicos o privados.

https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos 
d. Copia de trabajo / Working Copy 

Se le llama copia de trabajo al �repositorio� completo y localizado que debe tener cada usuario al momento de trabajar en un proyecto distribuido. Esta es la mayor novedad que brinda GIT con respecto a los dem�s SCV, puesto que, cualquier usuario con los permisos necesarios puede trabajar en �l, incluso sin conexi�n e independiente de un servidor central.

https://www.thomas-krenn.com/en/wiki/Git_Basic_Terms 

e. �rea de Preparaci�n / Staging Area 

Repositorio intermedio usado para carga temporal de datos en un proceso ETL. Suele contener datos solo durante el proceso de carga del datawarehouse. El �rea de preparaci�n es un sencillo archivo, generalmente contenido en tu directorio de Git, que almacena informaci�n acerca de lo que va a ir en tu pr�xima confirmaci�n. A veces se le denomina �ndice, pero se est� convirtiendo en est�ndar el referirse a ella como el �rea de preparaci�n.

https://git-scm.com/book/es/v1/Empezando-Fundamentos-de-Git 
http://enfoquepractico.com/glosario/

f. Preparar Cambios / Stage Changes 

Corresponde a la fase siguiente de la modificaci�n de un archivo en un repositorio. Es decir, luego de editar nuestro archivo necesitamos preparar los cambios para concluir de manera efectiva el proceso de guardado de modificaciones. Para esto es fundamental el uso del comando �git add�, y para corroborar que los cambios se encuentran �preparados�, podemos ejecutar el comando �git status�.

https://git-scm.com/book/es/v1/Fundamentos-de-Git-Guardando-cambios-en-el-repositorio 

g. Confirmar cambios / Commit Changes 

Corresponde a la fase siguiente de la preparaci�n de un archivo en un repositorio. Es decir, luego de preparar nuestro archivo necesitamos confirmar los cambios para concluir de manera efectiva el proceso de guardado de modificaciones. Para esto es fundamental el uso del comando �git commit�. 

https://git-scm.com/book/es/v1/Fundamentos-de-Git-Guardando-cambios-en-el-repositorio 

h. Commit

El comando commit es usado para cambiar a la cabecera. Ten en cuenta que cualquier cambio comprometido no afectar� al repertorio remoto. Usa el comando:
git commit �m �Message to go with the commit here�

https://git-scm.com/docs/git-commit 

i. clone: 

Comando que nos permite obtener una copia de un repositorio Git existente �por ejemplo, un proyecto en el que queremos contribuir. Por ejemplo, si quieres clonar la librer�a Ruby llamada Grit, har�as algo as�:

$ git clone git://github.com/schacon/grit.git

https://git-scm.com/book/es/v1/Fundamentos-de-Git-Obteniendo-un-repositorio-Git 

j. pull 

Comando que nos permite fusionar todos los cambios que se han hecho en el repositorio local en el cual estamos trabajando. Este comando te recuerda que si est�s en la rama maestra y ejecutas git pull, autom�ticamente unir� los cambios a la rama maestra del remoto despu�s de haber recuperado todas las referencias remotas. Tambi�n lista todas las referencias remotas que ha recibido.

https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos 

k. push 

Comando esencial que sirve para enviar los cambios que se han hecho en la rama principal de los repertorios remotos que est�n asociados con el directorio que est� trabajando. Por ejemplo: 
git push  origin master

https://www.hostinger.es/tutoriales/comandos-de-git#Comandos-basicos-de-GIT
https://wikis.fdi.ucm.es/ELP/Gu%C3%ADa_r%C3%A1pida_de_Github

l. fetch 

Este comando le permite al usuario buscar todos los objetos de un repositorio remoto que actualmente no reside en el directorio local que est� trabajando. Por ejemplo:
git fetch origin

https://git-scm.com/docs/git-fetch 

m. merge 

Este comando se usa para fusionar una rama con otra rama activa:
git merge <branch-name>

https://git-scm.com/book/es/v1/Ramificaciones-en-Git-Procedimientos-b%C3%A1sicos-para-ramificar-y-fusionar 

n. status 

Este comando muestra la lista de los archivos que se han cambiado junto con los archivos que est�n por ser a�adidos o comprometidos.
https://git-scm.com/docs/git-status 

o. log 

Ejecutar este comando muestra una lista de commits en una rama junto con todos los detalles. Por ejemplo:
commit 15f4b6c44b3c8344caasdac9e4be13246e21sadw

Author: Alex Hunter <alexh@gmail.com>

https://git-scm.com/docs/git-log 

p. checkout 

El comando checkout se puede usar para crear ramas o cambiar entre ellas. Por ejemplo, el siguiente comando crea una nueva y se cambia a ella:
command git checkout -b <banch-name>
Para cambiar de una rama a otra solo usa:
git checkout <branch-name>

https://git-scm.com/docs/git-checkout 

q. Rama / Branch 

Este comando se usa para listar, crear o borrar ramas. Para listar todas las ramas se usa:
git branch

para borrar la rama:

git branch -d <branch-name>

https://git-scm.com/book/es/v1/Ramificaciones-en-Git-Procedimientos-b%C3%A1sicos-para-ramificar-y-fusionar 

r. Etiqueta / Tag
 
 Esta funcionalidad se usa t�picamente para marcar versiones de lanzamiento (v1.0, por ejemplo).
Listar las etiquetas disponibles en Git es sencillo, Simplemente escribe git tag:
Crear una etiqueta anotada en Git es simple. La forma m�s f�cil es especificar -a al ejecutar el comando tag:
$ git tag
v0.1
v1.3
Este comando lista las etiquetas en orden alfab�tico; el orden en el que aparecen no tiene mayor importancia.
Git usa dos tipos principales de etiquetas: ligeras y anotadas. Una etiqueta ligera es muy parecida a una rama que no cambia �un puntero a una confirmaci�n espec�fica�. Sin embargo, las etiquetas anotadas son almacenadas como objetos completos en la base de datos de Git. Tienen suma de comprobaci�n; contienen el nombre del etiquetador, correo electr�nico y fecha; tienen mensaje de etiquetado; y pueden estar firmadas y verificadas con GNU Privacy Guard (GPG). Generalmente se recomienda crear etiquetas anotadas para disponer de toda esta informaci�n; pero si por alguna raz�n quieres una etiqueta temporal y no quieres almacenar el resto de informaci�n, tambi�n tiene disponibles las etiquetas ligeras.

https://git-scm.com/book/es/v1/Fundamentos-de-Git-Creando-etiquetas 
