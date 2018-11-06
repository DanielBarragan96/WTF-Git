# WTF-Git
GitHub Workshop
This is a GitHub Workspace

git config --global user.name "someone"

git config --global user.email "someone@someplace.com"

git init

git remote add origin <link del repositorio>

git fetch origin master

git pull origin master

git status

git add *

git commit -m "some init msg"

git push origin <branch>

Change branch: $ git checkout <branch>
	
Nueva branch:  $ git checkout -b  <branch>
	
Git commits: $ git log


--------------------------WTF is Git

//	https://github.com/a-rmz/wtf-git 
//	https://education.github.com/
//	https://www.digitalocean.com/
//	https://github.com/github/gitignore  

git commit 		//editor del commit
		:q		 //ingresar para salir del editor
		:x		//cerrar y guardar los cambios del editor
		
git log			//Datos del Git actual
		-p		//más detalles
		
cat filename		//show content of file

echo "I am the first file" > file1		//Crear nuevo archivo

git diff			//Mostrar cambiios de la version actual con la base de datos

git status		//Estado del Git

vim .git/hooks/pre-commit	//crear script para ejecutar en bash antes del commit

vim .gitignore	//archivos a ignorar
		bin/		//ignorar todos los archivos dentro de bin/
		*.o		//ignorar todos los archivos con terminación .o

mkdir bin		//crear directorio bin

touch bin/algo.o bin/algo.c	//crear dos archivos dentro de bin

cmd //c tree		//Tree del Git

Remote
*Fetch: guardar archivos sin modificar tus archivos
*Pull: hace un fetch y los combina con tu código
*Push: tomar hasta el último commit y va a subirlos al remote indicado
Fork
*es una copia de un proyecto
*pull request: pedir permiso para subir tus cambios
*merge request: solicitar combinar tu branch con la del dueño del repo

git remote -v		//Git origin status

git push -u branch_X		//set-up upstream branch
