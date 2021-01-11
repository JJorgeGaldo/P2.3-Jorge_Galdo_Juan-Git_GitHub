# P2.3-Jorge_Galdo_Juan-Git_GitHub
Creación de un repositorio para la práctica de la asignatura CODE (esto lo estoy creando desde el portatil linux directamente en GitHub). En el momento de la creación ya selecciono la opción "Add a README file"
Este comentario está hecho desde la terminal del portátil con linux

Acabo de tener un problema con el commit anterior. Me daba error al no detectar quién era yo. Es un error extraño porque había configurado git con el comando "git config --global user.mail y user.name", pero no me lo reconocía.
Para solucionarlo hice:
1) comprobar que tenía bien el archivo de configuración de git: git config --list. Efectivamente estaba correcto
2) intenté volver a comitear, pero me volvió a dar el mismo error "who you are"
3) sobreescribí la info volviendo a ejecutar los comandos git config --global user.name // user.mail
4) al volver a ejecutar el commit lo hizo sin ningún error

Ahora voy a probar a hacer este commmit a ver qué pasa, pero espero que esté solucionado.

El anterior commit no mme ha dado problemas. Ahora estoy editando el archivo con el mac y en principio todo está correcto. Los pasos que seguí para editr este archivo fueron:
1) Accedí a GitHub desde este equipo y copié el enlace de SSH del repositorio
2) usando la terminal me moví al directorio donde quería clonar el repositorio de GitHub
3) ejecuté: git clone (pegué el código copiado)
4) entré en la carpeta y edité el archivo con el editor nano
5) ahora saldré guardando cambios e intentaré hacer un commit con el atajo commit -am "mensaje", añadiendo al staging area los cambios justo antes de comitear sin necesidad de ejecutar el git add

