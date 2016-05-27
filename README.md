# campusciff-2016
Repositorio para las prácticas del módulo Data Science ToolKit
### Comandos utilizados y descripción

1. Creo desde github un repositorio llamado campusciff. Marco la opción para crear automáticamente un README.md.

2. Inicializo el repositorio.

	$ git init
	
3. Clono el repositorio remoto (se trae el README.md)

	$ git clone git@github.com:gitainhoa/campusciff.git
	
4. Subo al stage

	$ git add .

5. Commit inicial

	$ git commit -m "commit inicial"

6. Creo archivo y carpeta privada	

$ echo "I love Mahler" > privado.txt
	$ mkdir privada

7. Creo gitignore 

	$ touch .gitignore

8. Incluyo el fichero privado.text y el directorio privada en gitignore: privado.txt
privada\

9. Creo 1.txt

	$ echo "One" > 1.txt

8. Subo .gitignore y 1.txt

	$ git add .
	$ git commit -m "añadido .gitignore"

9. Actualizo README.md (Esto se hará recurrentemente, según vaya actualizando la documentación)

	$ git add .
	$ git commit -m "actulizado README.md"

10. Creo y subo etiquetas

	$ git tag v0.1
	$ git push --tag origin master

11. Creo rama v0.2 y me posiciono en ella.

	$ git branch v0.2
	$ git checkout v0.2

12. Compruebo que el head apunta a mi nueva rama. Creo fichero 2.txt y lo subo

	$ git log --oneline --decorate --graph --all
	
	* 30aca77 (HEAD -> v0.2, tag: v0.1, origin/master, origin/HEAD, master) 	actualizado README.md
	* e69d3e9 añadido .gitignore
	* 218a340 Initial commit

13. Creo fichero 2.txt

	$ echo "dos" > 2.txt
	$ git add .
	$ git commit -m "Añadido 2.txt "
	$ git push origin v0.2

14. Me posiciono de nuevo en master y hago merge con v0.2
	
	$ git checkout master
	$ git merge v0.2

15. Creo etiqueta v0.2

	$ git tag v0.2

15. Elimino rama v0.2 (en local, para remoto habría que usar además git push alias-repositorio-remoto --delete nombre-rama-remota)

  -m 	$ git branch -d v0.2

16. Listo los distintos commits

  $ git log --oneline --decorate --graph --all

17. Pongo foto en el perfil. Desde la opción de profile.

18. Fijo doble factor de autenticación. Eligo sms. Github envía un código para validar.
Activado el doble factor de seguridad
	
19. Clave pública. Ya estaba añadida
