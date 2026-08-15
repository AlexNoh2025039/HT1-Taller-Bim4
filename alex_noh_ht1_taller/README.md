# AlexNohHt1Taller

ACT1-B4
En el trabajo se utilizo ia para los ejemplos visuales,
de scss y una idea de conposición de componentes en el body,
para que se puediera almacenar dentro de la vista para 
poder centralizar la distribucion de las tablas en una sola.

Documentación
En el src esta todo el codigo del proyecto,
app es en donde estan y se ordenan todas las carpetas
de los componentes de la pagina,
core es el que almacena las partes de la pagina como lo son los componentes que forman parte de la estructura de la vista principal.

--
Components:
Aqui estan 7 partes de la vista de la pagina o aplicación.

header: que es el encabezado de la pagina.
footer: Este se uso para poder mostrar datos de contacto con los usuarios.
body: Aqui en ves de usar usuario, producto y detalles de forma individual
se usao el patron de composición de componentes, asi body hace el trabajo de 
contenedor principal de los otros 3 contenedores que agrupa y coordina a los 3
contenedores, asi se puede centralizar la distribución de las tablas en una sola
vista.
inicio: Aqui se hizo la bienvenida de el usuario a la aplicacion.
Producto: Muestra una tabla donde se encuentras algunos productos 
de la tienda.
ProductoDetalle: aqui en este muestra otra tabla con las caracteristicas un poco
mas detalladas de los productos.
Usuarios: aqui muestra a todos los usuarios registrados en una lista.
Environments: Este guarda datos de configuracion que cambian segun donde este corriendo el proyecto, este permite que la aplicación 
se use directamente en desarrollo
o producción, sin modificar codigo.
