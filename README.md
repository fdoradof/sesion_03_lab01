# Sesion_03_lab01
Laboratorio de Inventarios en ansible

# Enunciado del Ejercicio
- Crearemos un Proyecto en GitHub con el nombre sesion_03_lab01 y lo clonaremos en nuestro equipo (Windows)
- Desde VsCode, crearemos un archivo "inventory" dentro del proyecto
- Dentro del inventario crearemos los 6 siguientes grupos:
	- America
	- Asia
	- Europa
	- Africa
	- Oceania
	- Antartida

- Si os fijáis bien, los grupos creados anteriormente son los continentes del Planeta, por lo que ahora dentro de cada uno de estos grupos crearemos otros tres grupos con el nombre de tres países de estos continentes (Los países que queramos).

- Posteriormente declararemos 10 nodos por país con los siguientes formatos:
	- Primer país --> NOMBRE_PAIS-NUMERO_NODO.dominio.es
	- Segundo país --> NOMBRE_PAIS-LETRA_NODO.dominio.es
	- Tercer país --> LETRA_NODO-NOMBRE_PAIS-NUMERO_NODO.dominio.es

- Por ultimo crearemos un grupo global llamado "MUNDO“ el cual será el padre de todos los anteriores.
