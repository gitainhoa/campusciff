# campusciff-2016
Repositorio para las prácticas del módulo Data Science ToolKit
### Comandos utilizados y descripción

1. Creo desde github un repositorio llamado campusciff. Marco la opción para crear automáticamente un README.md.

2. Inicializo el repositorio.
```sh
	$ git init
	```	
3. Clono el repositorio remoto (se trae el README.md)
	```sh
	$ git clone git@github.com:gitainhoa/campusciff.git
	```
4. Subo al stage
	```shgit 
	$ git add .
	```

5. Commit inicial
	```sh
	$ git commit -m "commit inicial"
	```
6. Creo archivo y carpeta privada	
```sh
$ echo "I love Mahler" > privado.txt
	$ mkdir privada
	```

7. Creo gitignore 
	```sh
	$ touch .gitignore
	```
8. Incluyo el fichero privado.text y el directorio privada en gitignore: privado.txt
privada\

9. Creo 1.txt
	```sh
	$ echo "One" > 1.txt
	```

8. Subo .gitignore y 1.txt
	```sh
	$ git add .
	$ git commit -m "añadido .gitignore"
	```
9. Actualizo README.md (Esto se hará recurrentemente, según vaya actualizando la documentación)
	```sh
	$ git add .
	$ git commit -m "actulizado README.md"
	```
10. Creo y subo etiquetas
	```sh
	$ git tag v0.1
	$ git push --tag origin master
	``` 
