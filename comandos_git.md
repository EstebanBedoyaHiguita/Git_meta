#Comfiguracion

comando para conocer la version  de github

- git -v
- git --verson

Comandos para configurar git por primera vez:

- git config --global user.name "EstebanBedoyaHiguita"
- git config --global user.email "estebanbedoyahiguita@gmail.com"

Comando para ver que usuario esta configurado o con que correo electronico

- git config --global user.name
- git config --global user.email
- git config --list

Comandos para inicializar git en un directorio

- git init
comando para ver el estado de los archivos
- git status

Comando para ver todas las versiones de mi proyecto
- git log
- git log --oneline

Pasos para crear una version de mi codigo
1. Agregar cambios
-git add . (si se quiere agregar solo un archivo git add *.js - homa.html)

2. comprometer los archivos
- git commit -m "Descripcion del commit"