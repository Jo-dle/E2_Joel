### Parte 1:

##### 1. Acceder al repositorio original
<a href="https://github.com/calderin21/ecommerce">Repositorio Original</a>

 	
##### 2. Clonarlo en mi equipo: 

 	- git clone https://github.com/calderin21/ecommerce
	
##### 3. Entra en una carpeta y abre el archivo README.md:

	- cd ecommerce
	- cat README.md

##### 4. Únete a una rama del repositorio:

	 - git checkout Jo-dle

### Parte 2:

#### 1. Crea un nuevo repositorio con tu nombre y apellido:

	- mkdir Joel_Ramos_E2
	- cd Joel_Ramos_E2
	- git init
	
#### 2. Crea una carpeta vacía y vincúlala con tu repositorio remoto:

	- cd /c/xampp/htdocs/Joel_Ramos_E2
	- mkdir E2_parte2
	- git commit -m "Creación de la carpeta E2_parte2"
	- git remote add origin https://github.com/Jo-dle/E2_Joel.git
	- git push

#### 3. Crear un archivo README.md y escribir una breve descripción
	
	- nano README.md 

### Parte 3:

#### 1. Crea una carpeta llamada documentación y un archivo md llamado historia donde documentes todo lo realizado en el examen
 
	- cd /c/xampp/htdocs/Joel_Ramos_E2
 	- mkdir documentación
	- cd documentación
	- nano historia.md

#### 2. Haz add,commit y push de los archivos

	- git add .
	- git commit -m "Parte 3 apartado 2"

#### 3. Crea un archivo de datos.xml

	- nano datos.xml 
	- git commit -m "Creamos datos.xml"
 	- git push
  
#### 4. Modifica el archivo README.md y añade una sección autor

	-nano README.md
 
#### 5. Elimina el archivo datos.xml y actualiza el repositorio

	-rm datos.xml 
 	-git commit -m "Borramos datos.xml y actualizamos README.md"
  	-git push
	
	
