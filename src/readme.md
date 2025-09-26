# GitHub #

Git –version 

Git config –global user.name "Javier Seguel" --> configurar nombre 

git config user.email --> configuracion de email 

Git config –global –list --> ver configuracion global de usuario en el equipo 

Git config –global –e --> entra a ver la configuración de global --> :q! Para salir :wq para editar cambios 

git config user.email 

 

Git init --> para inicializar git en el proyecto 

Git status --> hacer seguimiento al proyecto (que es lo que se modifico y en que rama, que archivo) 

Git add . --> los sube al stage 

Git commit –m "mensaje" 

Git commit –am "mensaje" --> esto es un comnado abreviado para agrear al stage y luego commit 

Git reset nombreArchivo  --> esto es para regresara Untrack 

Git add *.html --> toma todos los archivos con .html para luego poder enviarlos al stage 

Git log --> para mirar todos los commit que tiene el proyecto 

 

Git checkout -- .  --> restaurar ultimo commit 

 

Git branch --> ver ramas por defecto master principal 

 

Git branch –m master main --> cambiar el nombre de la rama principal a main 

Git config –global init.defaultBranch main  --> init con rama principal de nombre main 

 

Letras en VSCode para GitHub 

U --> Untrack 

M --> Modificado 

D --> Eliminado 

A --> preparado stage 

Atajo para entrar a Source Control --> ctrl + shif + g 

 

Acortar alias 

Git status –short --> muestra de forma más simplificada la modificacion o cambios realizados en el proyecto 

git config --global alias.s "status --short" --> creando un alias acortando status –short con Git s 

git log –oneline --> muestra un log mas ordenado 

 

git config --global alias.gl "log --graph --decorate --pretty=format:'%C(yellow)%h%Creset %Cgreen(%ad)%Creset %C(cyan)<%an>%Creset %s' --date=format-local:'%Y-%m-%d %H:%M'" 

 gl = log --graph --decorate --pretty=format:'%C(yellow)%h%Creset%C(auto)%d%Creset %Cgreen(%ad)%Creset %C(cyan)<%an>%Creset 
%s' --date=format-local:'%Y-%m-%d %H:%M'

 

Actualizar commit y revisar cambios  

Git diff --> permite ver los cambios en git, pero para comprobar antes revisar en VSCode 

 

git commit --amend -m "Se agrega Notas" --> comando para actualizar un commit  en el caso que este mal escrito o renombrar dentro de la rama 