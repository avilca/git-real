Curso GIT

1) COMANDOS DE CONFIGURACION DE USUARIO:

	git config --global user.name "Andres Vilca"
	git config --globa user.email avilca@gmail.com
	git config --global color.ui true


2)CREAMOS UN DIRECTORIO:
	mkdir curso  --> crea directorio
	cd curso ---> ingresamos al directorio creado

3)CONVERTIMOS EL DIRECTORIO "CURSO" en un REPOSITORIO GIT:
	git init --> inicia el directorio git



4)COMANDOS:

	git add   ---> anadir archivo
	git commit -m"mensaje personalizado" --> guarda modificacion con mensaje


	4.1)COMANDOS DE apoyo:

		git status

		git log 
		git add --all   --> agrega todas modificacione de los archivos y si hubieran files nuevos tambien los agrega
		git add *.txt   --> agrega todos los archivos con extension .txt del directorio git
		git add docs/   --> agrega todo lo que esta dentro del dicectorio docs
		git add "*.txt" --> agrega los txt del proyecto
		git reset HEAD nombre_de_archivo  --> Saca el archivo de la zona de espera
        git checkout -- LICENCIA.txt    --> regresa el archivo a su forma original 
