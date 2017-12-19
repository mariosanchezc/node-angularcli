## CONSTRUCCIÓN DE LA IMAGEN
	- docker-compose build

##### Ejecutar un contenedor para crear por primera vez el proyecto
	- docker-compose run frontend ng new name_project
    	* frontend: nombre del servicio
    	* name_project: Nombre del proyecto Angular

##### Antes de Construir:
    - Dentro del archivo docker-compose.yml se encuentra la sección command
    - Aquí se debe poner el mismo nombre del creado anteriormente (name_project)

## Ejecución del Proyecto angular
	- docker-compose build
	- docker-compose up

##### Paso Final
	Dirigirse a su navegador a la dirección:
	- con docker-machine (por defecto) : http://192.168.99.100:4200
	- sin docker-machine : http://localhost:4200