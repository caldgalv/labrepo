git init                    Crear un repositorio
                                Configura el directoria para poder consolidar las versiones 
git add <archivo>           Subir un archivo al repositorio
git add .                   Subir todos los archivos
git commit -m "Mensaje"     Subir los archivos de la versión
                                Sirve para luego hacer un push
git diff <archivo>          Muestra las diferencias entre un archivo en el repositorio 
git diff <hash><archivo>    Hash es el numero de identificación del commit
                                Head, es el ultimo commit
git status                  Ver cambios que se han agregado al Staging
git branch <Nombre>         Para crear un nuevo branch
git checkout <Nombre>       Se utiliza para entrar al branch
git merge <Nombre>          Es el punto de una historia que estoy uniendo con otra
git checkout -b <Nombre>    Se crea un branch desde done estas
git revert <ID>             Revert al id del commit es estilo un reset --soft
git reset                   Va devuelta al head del branch 
                                --soft o --hard
                                    Soft: guarda los cambias y reset a el branch
                                    Hard: va al branch y elimina todos los cambios hechos
