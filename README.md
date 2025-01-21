# Challenge-Literatura

Este es una aplicación de consola de Java Spring Boot que proporciona una interfaz para administrar libros y autores.

## Características

* Buscar un libro por título
* Listar todos los libros registrados
* Listar todos los autores registrados
* Listar autores que vivieron en un año específico
* Listar libros por idioma

## Tecnologías utilizadas

* Java
* Spring Boot
* Maven
* PostgreSQL

## Configuración

1. Clona el repositorio
2. Actualiza el archivo `application.properties` con tus credenciales de base de datos
3. Ejecuta la aplicación utilizando tu IDE o a través de la línea de comandos con `mvn spring-boot:run`


## Autor

Mynor García

## Uso

La aplicación proporciona una interfaz de consola. Sigue las instrucciones para utilizar las diferentes características.

```
Menu de opciones:
1- Buscar libro por titulo
2- Listar libros registrados
3- Listar autores registrados
4- Listar autores vivos en un determinado año
5- Listar libros por idioma
0- Salir
Elija la opción a través de su número:

1
Ingrese el nombre del libro que desea buscar
"X Libro"
El libro ya existe en la base de datos
--------- LIBRO ---------
Titulo: "X Libro"
Autor: "Nombre de Autor"
Idioma: "Ïdioma"
Numero de descargas: "###"
-------------------------
