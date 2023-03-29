Crear un repositorio y configura el directorio para poder consolidar las versiones 
git init
                            
Subir un archivo al repositorio
git add <archivo>

Subir todos los archivos
git add .

Subir los archivos de la versión y sirve para luego hacer un push
git commit -m "Mensaje"     

Muestra las diferencias entre un archivo en el repositorio 
git diff <archivo>          
git diff <hash><archivo>

Hash es el numero de identificación del commit
Head, es el ultimo commit

Ver cambios que se han agregado al Staging
git status

Para crear un nuevo branch
git branch <Nombre>         

Se utiliza para entrar al branch
git checkout <Nombre>       

git merge <Nombre>
Es el punto de una historia que estoy uniendo con otra          
el merge es automático siempre y cuando los cambios entre las ramas no interfieran entre si, es decir que no causen conflictos
el merge fusiona uno o más ramas dentro de la rama que tienes activa

git checkout -b <Nombre>
Se crea un branch desde done estas

git revert <ID>
Revert al id del commit es estilo un reset --soft

git reset
Va devuelta al head del branch 
--soft o --hard
Soft: guarda los cambios y reset a el branch
Hard: va al branch y elimina todos los cambios hechos


git config --global user.email "you@example.com"
para referir un correo al momento de realizar un commit
git config --global user.name "Your Name"
para referir un usuario al momento de realizar un commit

pull request (petición de cambios) proceso administrativo para validar que los cambios realizados son correctos con la operativa

para vincular el repositorio local con alguno remoto
git remote add labrepo https://github.com/caldgalv/labrepo.git

para sincronizar el repositorio local con el remoto
git remote add origin https://github.com/caldgalv/labrepo.git
git branch -M main
git branch main lab/01
git checkout -b lab/01
git push -u origin lab/01
