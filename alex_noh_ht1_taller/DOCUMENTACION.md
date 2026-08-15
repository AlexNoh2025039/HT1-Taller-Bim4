Documentación del Proyecto: Tiendita la Bendición
Proyecto: Hoja de Trabajo 1 - Taller

Estudiante: Alexander Noh González
Carné: 2025039

--------------------------------------------------------------------

Descripción General
Tiendita la Bendición es una aplicación web, la interfaz está dividida en 7 componentes principales, permitiendo mostrar toda la información de la tienda de forma clara y organizada en la pantalla, además de dejar configurada la base para la conexión con el servidor.




--------------------------------------------------------------------

Estructura del Proyecto
El código está organizado usando la convenciones estándar de Angular, manteniendo una separación clara entre componentes, servicios y configuraciones:

--------------------------------------------------------------------
src/
├── app/                        
│   ├── components/             
│   │   ├── header/            # Encabezado de la tienda
│   │   ├── footer/            # Pie de página
│   │   ├── body/              # Contenedor principal
│   │   ├── inicio/            # Bienvenida
│   │   ├── productos/         # Catálogo
│   │   ├── producto-detalle/  # Ficha técnica del producto
│   │   └── usuarios/          # Listado de usuarios
│   ├── services/                
│   │   └── api.service.ts     # Servicio para consumo de API
│   ├── app.module.ts          # Módulo principal
│   ├── app.component.ts       # Componente raíz
│   └── app-routing.module.ts  # Configuración de rutas
├── environments/               
│   ├── environment.ts         # Entorno de desarrollo
│   └── environment.prod.ts    # Entorno de producción
├── index.html                 
├── main.ts                    
└── styles.scss  




--------------------------------------------------------------------
Componentes del Sistema

HeaderComponent: Esta en la barra superior con el branding, título de Tiendita la Bendición.

--------------------------------------------------------------------

FooterComponent: este esta hasta el abajo de la pagina
y sirve para dar un poco de información de la pagina como
un numero de contacto.

--------------------------------------------------------------------

BodyComponent: Funciona como un contenedor que distribuye los 
componentes de usuario, productos y sus detalles.

--------------------------------------------------------------------

InicioComponent: Vista de bienvenida para los clientes.

--------------------------------------------------------------------

ProductosComponent: Tabla de datos de los diferentes productos.

--------------------------------------------------------------------

UsuariosComponent: Muestra los datos de los usuarios.

--------------------------------------------------------------------

ProductoDetalleComponent: muestra los detalles de cada producto.






--------------------------------------------------------------------

Servicio de API (ApiService)
El ApiService funciona como el intermediario de comunicación con el backend, se encarga de enviar y recibir la información, y toma la URL base directamente desde las variables de entorno.

Tiene los siguientes métodos preparados:

getProductos(): Consulta la lista completa de productos del catálogo.

getUsuarios(): Obtiene la información de los usuarios.

getProductoById(id): Busca y devuelve los detalles de un producto específico mediante su ID.

Ejecución en Entorno Local
Para levantar el servidor de desarrollo y previsualizar la aplicación:

Ejecuta el comando en la terminal dentro de la carpeta del proyecto:

Bash
ng serve
Una vez completada la compilación, abre tu navegador e ingresa a:
http://localhost:4200

🛠️ Tecnologías Utilizadas
Framework: Angular 22.1.1

Lenguaje: TypeScript 6.0.2

Enrutamiento: Angular Router

Estilos: SCSS / CSS Grid & Flexbox