# campusciff
Repositorio para ejercicios GitHub

##### 1. Crear un repositorio en vuestro GitHub llamado campusciff.

OK

##### 2. Clonar vuestro repositio en local.

$ git clone https://github.com/jaritgor/campusciff.git


##### 3. Crear (si no lo habéis creado ya) en vuestro repositorio local un documento README.md.

OK

##### 4. Añadir al README.md los comandos utilizados hasta ahora y hacer un coomit inicial con el mensaje commit inicial.

joseantonio@jaritgor MINGW64 ~/Desktop/BIG DATA/DATA_SCIENCE_TOOLKIT/campusciff (master)
$ cd campusciff

$ ls -a

$ vim README.md

$ git add .

$ git commit -m "Commit inicial"

##### 5. Subir los cambios al repositorio remoto.

$ git push origin master

##### 6. Crear en el repositorio local un fichero llamado privado.txt.

$ touch privado.txt

##### 7. Crear en el repositorio local una carpeta llamada privada.

$ mkdir privada

##### 8. Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git.

$ echo privado.txt > .gitignore

$ echo privada > .gitignore

##### 9. Añadir fichero 1.txt al repositorio local.

$ touch 1.txt

$ git add .

$ git status

$ git reset HEAD privado.txt

$ git status

$ git commit -m "añadido ficheros"

##### 10. Crear un tag v0.1.

$ git tag v0.1

##### 11. Subir los cambios al repositorio remoto.

$ git push --tags origin master

##### 12. Crear una rama v0.2.

$ git branch v0.2

##### 13. Posiciona tu carpeta de trabajo en esta rama.

$ git checkout v0.2

##### 14. Añadir un fichero 2.txt en la rama v0.2.

$ touch 2.txt

$ git add 2.txt

$ git commit -m "añadido fichero 2"

##### 15. Subir los cambios al reposiorio remoto.

$ git push origin v0.2

##### 16. Posicionarse en la rama master.

$ git checkout master

##### 17. Hacer un merge de la rama v0.2 en la rama master.

$ git merge v0.2

##### 18. En la rama master poner Hola en el fichero 1.txt y hacer commit.

$ echo "Hola" > 1.txt

$ git add 1.txt

$ git commit -m "anadido hola 1.txt"

##### 19. Posicionarse en la rama v0.2 y poner Adios en el fichero "1.txt" y hacer commit.

$ git checkout v0.2

$ git add 1.txt

$ git commit -m "añadido adios 1.txt"


##### 20. Posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2
+
##### 22. Arreglar el conflicto anterior y hacer un commit.

$ git checkout master

$ git merge v0.2

$ vim 1.txt

$ git add 1.txt

$ git commit -m "resuelto conflicto"

$ git merge v0.2

##### 21. Listar las ramas con merge y las ramas sin merge.

$ git log --oneline --decorate --graph --all

##### 23. Crear un tag v0.2

$ git tag v0.2

##### 24. Borrar la rama v0.2

$ git branch -d v0.2

##### 25. Listar los distintos commits con sus ramas y sus tags.

$ git log --oneline --decorate --graph --all

##### 26. Poner una foto en vuestro perfil de GitHub.

OK

##### 27. Poner el doble factor de autentificación en vuestra cuenta de GitHub.

OK

##### 28. Añadir (si no lo habéis hecho ya) la clave pública que se corresponde a tu ordenador.

OK

##### 29. Preguntar los nombres de usuario de GitHub de tus compañeros de clase, búscalos, y sigueles.

OK

##### 30. Seguir los repositorios campusciff del resto de tus compañeros.

OK

##### 31. Añadir una estrella a los repositorios campusciff del resto de tus compañeros.

OK

##### 32. Crear una tabla de este estilo en el fichero README.md con la información de varios de tus compañeros de clase.

| Usuario | Enlace |
| ------ | ------- | 
| plopez76 | https://github.com/plopez76/campusciff.git |
| crisrodfra | https://github.com/crisrodfra/campusciff.git |

##### 33. Poner a como colaborador del repositorio campusciff.

OK - Adolfo Sanz De Diego - asanzdiego

##### 34. Crear una organización llamada campuscifftunombredeusuariodegithub

OK - https://github.com/organizations/campusciffjaritgor/

##### 35. Crear 2 equipos en la organización campuscifftunombredeusuariodegithub, uno llamado administradores con más permisos y otro colaboradores con menos permisos.

OK - Administradores: privilegios de ADMIN sobre el reposiorio privilegio
Colaboradores: privilegios de READ sobre el reposiorio privilegio

##### 36. Meter a y a 2 de vuestros compañeros de clase en el equipo administradores.

OK

##### 37. Meter a y a otros 2 de vuestros compañeros de clase en el equipo colaboradores.

OK
##### 38. Crear un index.html que se pueda ver como página web en la organización.

$ git clone https://github.com/jaritgor/GitHub_prueba.git

$ cd GitHub_prueba

$ git checkout --orphan gh-pages

$ git rm -rf

$ echo "My GitHub Page" > index.html

$ git add .

$ git commit -a -m "Primera página commit"

$ git push origin gh-pages

##### 39. Hacer 2 forks de 2 repositorios campuscifftunombredeusuariodegithub. github.io de 2 organizaciones de las que no seais ni administradiores ni colaboradores.

jaritgor/campusciff-1
forked from plopez76/campusciff

jaritgor/testbigdata
forked from Eduardociff/testbigdata

##### 40. Crearos una rama en cada fork.

This branch is even with plopez76:master.

This branch is even with Eduardociff:master.

##### 41. En cada rama modificar el fichero index.html añadiendo vuestro nombre.

Al no existir fichero index.html modifico readme - Añadido nombre jaritgor 

##### 42. Con cada rama hacer un pull-request.

Update README.md #1 Open	jaritgor  wants to merge 1 commit into plopez76:master from jaritgor:master

##### 43. Aceptar los pull-request que lleguen a los repositorios de tu organización.

Esperando para aceptar pull-request
