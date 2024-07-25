Sistema de Registro de Ventas
Este proyecto es un sistema de registro de ventas desarrollado en PHP y SQLite. Permite gestionar artículos, clientes y generar facturas de manera eficiente. Además, incluye la visualización de estadísticas relacionadas con las ventas.

Estructura del Proyecto:
articulo.php: Gestión de artículos.
cliente.php: Gestión de clientes.
css/: Archivos de estilos CSS.
estilos.css: Archivo principal de estilos.
db/: Base de datos y archivos relacionados.
DBfacturacion.sqlite: Base de datos SQLite.
db.php: Conexión y gestión de la base de datos.
estadisticas.php: Visualización de estadísticas.
factura.php: Generación de facturas.
img/: Imágenes utilizadas en el proyecto.
index.php: Archivo principal.
js/: Archivos JavaScript.
script.js: Archivo principal de scripts.
libx/: Librerías adicionales.

Requisitos:
Servidor web (por ejemplo, El servidor integrado de PHP o Apache).
PHP 7.4 o superior.
SQLite.

Instalación:
Clonar el repositorio en el servidor web:

bash
Copiar código: "git clone <URL_DEL_REPOSITORIO>"
Asegurarse de que el servidor web tenga permisos de escritura en el directorio db/ para que SQLite pueda crear y modificar la base de datos.
Configurar el servidor web para apuntar al directorio del proyecto.

Uso:
Acceder a la URL del proyecto en el navegador web.
Utilizar las diferentes funcionalidades del sistema:
Gestión de artículos: Crear, editar y eliminar artículos.
Gestión de clientes: Crear, editar y eliminar clientes.
Generación de facturas: Crear y ver facturas.
Visualización de estadísticas: Consultar estadísticas de ventas.

Detalles de los Archivos:
articulo.php
Este archivo gestiona las operaciones relacionadas con los artículos, como la creación, edición y eliminación de artículos en la base de datos.

cliente.php
Este archivo maneja las operaciones relacionadas con los clientes, permitiendo la creación, edición y eliminación de clientes.

db.php
Este archivo contiene las funciones para la conexión a la base de datos SQLite y las operaciones básicas de CRUD (Crear, Leer, Actualizar, Eliminar).

factura.php
Este archivo se encarga de la generación de facturas, incluyendo la creación de nuevas facturas y la visualización de facturas existentes.

estadisticas.php
Este archivo proporciona una interfaz para visualizar estadísticas relacionadas con las ventas, como el total de ventas por período y otros datos relevantes.

index.php
Este es el archivo principal del proyecto que sirve como punto de entrada para la aplicación. Desde aquí se puede acceder a las diferentes secciones del sistema.

Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para mejorar este proyecto.

Cómo Contribuir:
Haz un fork del proyecto.
Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
Realiza los cambios necesarios y haz commits (git commit -am 'Añadir nueva funcionalidad').
Sube los cambios a tu repositorio (git push origin feature/nueva-funcionalidad).
Abre un pull request en el repositorio original.

Licencia:
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

Créditos:
Desarrollado por [Isaias Marrero Burgos (2022-1777)].
