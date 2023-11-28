git help <cualquier_comando_git>
git config --global user.name "nombre de usuario" 
git config --global user.email email@email.com 
git config --global --unset user.name "nombre de usuario" 
git config --global --unset user.email email@email.com 
git config --list 
git branch nuevaBranch_nombre (crea una nueva branch). 
git checkout nuevaBranch_nombre (cambia a una branch existente). En este caso, el principal puntero HEAD está apuntando a la branch llamada nuevaBranch_nombre. 
git checkout -b nuevaBranch_nombre (crea una nueva branch y apunta a ella). 
git checkout master (vuelve a la branch principal-master-). 
git merge nuevaBranch_nombre (resuelve la unión (merge) entre las branches). Para realizar la unión (merge), debe estar en la branch que debe recibir los cambios. 
git branch -d nuevaBranch_nombre (apagando una branch). 
git branch (lista branches). 
git branch -v (lista branches con información de los últimos commits). 
git branch --merged (lista branches que ya se han unido (merged) con la master).
git branch --no-merged (listar branches que no se han unido (merged) con la master). 
git merge --abort o git reset --merge (cuando tenemos problemas con la unión (merge) y queremos deshacerla) 
git reset HEAD (cuando queremos volver a un commit anterior, si queremos volver a más de un commit, debemos poner el número de commits después de HEAD. Ejemplo: HEAD~2).
git commit --amend -m "Mi nuevo mensaje" (cambia los mensajes del commit).