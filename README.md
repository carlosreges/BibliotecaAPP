# BibliotecaAPP
Aplicación para administrar una biblioteca

##Clase Libro:

Atributos:
titulo: Almacena el título del libro.
disponible: Indica si el libro está disponible para ser alquilado.
Constructor:
El constructor toma el título del libro y lo marca como disponible.

Métodos:
getTitulo(): Devuelve el título del libro.
isDisponible(): Verifica si el libro está disponible.
setDisponible(boolean disponible): Establece la disponibilidad del libro.

##Clase Usuario:
Atributos:
nombreUsuario: Almacena el nombre del usuario.
librosAlquilados: Lista de libros que el usuario ha alquilado.
Constructor:
El constructor toma el nombre del usuario y crea una lista vacía de libros alquilados.

Métodos:
getNombreUsuario(): Devuelve el nombre del usuario.
getLibrosAlquilados(): Devuelve la lista de libros alquilados por el usuario.
alquilarLibro(Libro libro): Agrega un libro a la lista de libros alquilados por el usuario.

##Clase Biblioteca:
Atributos:
libros: Lista de libros en la biblioteca.
Constructor:
El constructor inicializa la lista de libros.

Métodos:
agregarLibro(Libro libro): Agrega un libro a la biblioteca.
buscarLibro(String titulo): Busca un libro por título y verifica si está disponible.
getLibros(): Devuelve la lista de libros en la biblioteca.

##Programa Principal (Main):

Creación de la Biblioteca y Agregado de Libros:
Se crea una instancia de la biblioteca.
Se agregan algunos libros a la biblioteca.

Creación de un Usuario y Alquiler de Libro:
Se crea un usuario.
Se busca un libro en la biblioteca por título.
Si se encuentra y está disponible, el usuario alquila el libro.
Listado de Libros en la Biblioteca:

Se muestra un listado de todos los libros en la biblioteca.
Listado de Libros Alquilados por el Usuario:

Se muestra un listado de los libros alquilados por el usuario.
Lógica de Validación:

Nombre y Apellido:
Se asume que el nombre y el apellido no pueden estar en blanco. Esta validación debería realizarse antes de crear un usuario.

DNI (Documento Nacional de Identidad):
Se valida el DNI con el formato del DNI de 8 cifras.
