# Tarea 

1.  	Definicion de las relaciones y 5 ejemplos de c/u (uno a uno / uno a muchos / muchos a muchos)
2.  	Investigar que es un SGBD (cuales son los mas famosos)
3.  	En que se diferencias las relacionales con las no relacionales

## 1º : 

Las relaciones indican como se van a relacionar dos tablas. Dentro de una base de datos existen 3 tipos de relacion, uno a uno, uno a muchos, muchos muchos. Por ejemplo una lista de precios puede tener varios articulos y cada articulo un grupo de caracteristicas y cada caracteristica estar relacionada a un grupo de articulos.

### Uno a uno : 
			Persona - DNI
			Producto - Marca
			Automovil - Patente
			Mascota - Altura
			Monedas - Cantidad

### Uno a muchos : 
			Marca - Productos
			Altura - Mascotas
			Pais - Ciudades
			Empresa - Empleados
			Carta - Platos

### Muchos a muchos : 
			Personas - Trabajos
			Paises - Ciudades
			Marcas - Productos
			Automoviles - Colores
			Mascotas - Razas

## 2º : 

Un SGBD (Sistema Gestor de Base de Datos) es un conjunto de programas que nos permiten gestionar bases de datos. Es decir, realiza las funciones de agregar, modificar, extraer y almacenar información de una base de datos, además de poseer herramientas con funciones de eliminar, modificar, analizar, etc… datos de estas. Realiza la función concreta de interfaz entre la base de datos y los usuarios finales o los programas correspondientes, organizando los datos y permitiendo su acceso.

### Ejemplos de SGBD: 

* Microsoft Access 
* Microsoft SQL Server 
* PostgreSQL
* MySQL 
* Oracle Database 


## 3º : 

1.  	Las bases de datos relacionales son aquellas que tienen tablas que se relacionan entre si mediante un identificador unico comun que sirve como nexto para esa relacion, la misma debe ser diseñada desde el principio y los datos se ingresaran a las tablas segun se diseño y son escalables en el tiempo.
2.  	Las bases no relacionales son aquellas que no tienen tablas realacionadas entre si como por ejemplo JSON y se caracterizan por su rapidez.

