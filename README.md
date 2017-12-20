# Versión 1 IMAGEN Angular CLI 

## CONSTRUCCIÓN DE LA IMAGEN
	- docker-compose build

##### Ejecutar un contenedor para crear por primera vez el proyecto
	- docker-compose run frontend ng new name_project
    	* frontend: nombre del servicio
    	* name_project: Nombre del proyecto Angular
	- Nota: Si falla la instalación se puede correr el comando:
		* docker-compose run frontend npm install --prefix name_project

##### Antes de Construir:
    - Dentro del archivo docker-compose.yml se encuentra la sección command
    - Aquí se debe poner el mismo nombre del creado anteriormente (name_project)
	- Ir al docker-compose y descomentar la línea del working_dir y colocar el nombre del proyecto
		Ejemplo: /frontend/<name_project>
## Ejecución del Proyecto angular
	
	- docker-compose build
	- docker-compose up

##### Paso Final
	Verificar los puertos que esten expuestos en el host y el contenedor