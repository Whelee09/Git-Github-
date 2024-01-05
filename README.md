# Lista de comandos mas utilizados
- git innit. inicia el respositorio

- ls -al. muestra los archivos ocultos

- git status. para ver el estado actual
- git add. anade archivos al stagging

- git rm --cached (lo saca del stagging)
- git commit -m "texto".  envia los cambios al repo y el -m es para le mensaje

- git config. configurar git
- git config --list. configuracion por defecto
- git config --global user.name "name"

- git log "nombre del archivo.extension"

- git show nombreArchivo. muestra los cambios que han existido sobre un archivo

- como salir de vim? esc+shift+zz.. en realidad no nos salimos asi sino que se guarda el archivo
- como empezar a escribir en vim. ctrl + i (de insertar)

- git diff tag1 tag2

- git reset tag --hard. todo vuelve al estado anterior de ese commit  y "borra" los commit que se hicieron despues
- git reset tag --soft. lo que esta en stagging sigue ahi disponible para un nuevo commit 
- git diff. muestra los cambios del editor de codigo vs los que estan en stagging

- git log --stat. cambios especificos hechos en cada archivo(muestra la cantidad de bytes)

- git checkout (tagQueQUieroVer || master(para vlver)) nombreArchivo

- git commit -am.  hace el git add + el commit(solo funciona con archivos a los cuales le hemos hecho add anteriormente)

- git branch nombreNueva

- git show. muestra el ultimo camvio que hicimos y hacia donde apunta head

- git checkout nombreRamaADondeMeQuieroMover. Para moverme entre ramas  

- git merge [nombreRamaAUnir]. lo ejecuto desde la rama main o a la que  quiero llevar los cambios

- git remote add origin linkRepoGithub. anadimos una rama remota 

- git remote. devuelve el nombre de la rama remota
- g- it remote -v. 

- git push ramaRemota ramaDesdeSeQuiereEnviar. git envia a la rama remota la rama local

- git branch -m nombreRama.  cambiar de rama

- git pull ramaRemota ramaMainLocal. trae lo externo que haya a nuestro repo local

- git pull ramaRemota ramaMainLocal --allow-unrelated-histories. ya que no hay commits comun lo frozamos

- git log --all. muestra todos os logs independientemente de la rama en la que estemos
- git log --all --graph. 
- git log --all --graph --decorate --oneline. te muestra "graficamente" 
- toda la historia de tus versiones inluyenfo ramas y merges

- alias nombreNuevoSimple="comando".  le da otro nombre al mismo comando 

- git tag -a nombreTag -m "mensaje" hash. le poneoms un tag al hash
- git tag. muestra la lista de todos los tags
- git show-ref --tags. muestra el nombre del tag asociado a hash (x) comit
- git push nombreRamaRemota --tags. envia los tags el repo externo
- git tag -d nombreTagABorrar. borra un tag pero solo desde algo interno pero no en el repo de Github
- git push origin :refs/tags/nombreTagABorrar. borra la referencia a nuesta referencia (la borra de github)

- git show-branch. nos muestra las ramas y su historia
- git show-branch --all. lo mismo pero con mas datos
- gitk. intefaz grafica fina

### Recursos para el git ignore: 
se usa el mismo formato que el de la consola
(Ej: *.jpg . ignrora los archivos .jpg). 
https://www.toptal.com/developers/gitignore. facilita la creacion de gitignore
