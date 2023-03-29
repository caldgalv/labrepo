Primeras anotaciones del notebook
git init                    Crear un repositorio
                                Configura el directorio para poder consolidar las versiones 
git add <archivo>           Subir un archivo al repositorio
git add .                   Subir todos los archivos
git commit -m "Mensaje"     Subir los archivos de la versión
                                Sirve para luego hacer un push
git diff <archivo>          Muestra las diferencias entre un archivo en el repositorio 
git diff <hash><archivo>    Hash es el numero de identificación del commit
                                Head, es el ultimo commit
git status                  Ver cambios que se han agregado al Staging
git branch <Nombre>         Para crear un nuevo branch
git checkout <Nombre>       Se utiliza para entrar al branch
git merge <Nombre>          Es el punto de una historia que estoy uniendo con otra
git checkout -b <Nombre>    Se crea un branch desde done estas
git revert <ID>             Revert al id del commit es estilo un reset --soft
git reset                   Va devuelta al head del branch 
                                --soft o --hard
                                    Soft: guarda los cambios y reset a el branch
                                    Hard: va al branch y elimina todos los cambios hechos

git remote add <nombre del repositorio><URL del repositorio> para vincular el repositorio local con alguno remoto

git config --global user.email "you@example.com" para referir un correo al momento de realizar un commit
git config --global user.name "Your Name" para referir un usuario al momento de realizar un commit
pull request (petición de cambios) proceso administrativo para validar que los cambios realizados son correctos con la operativa

el merge es automático siempre y cuando los cambios entre las ramas no interfieran entre si, es decir que no causen conflictos
