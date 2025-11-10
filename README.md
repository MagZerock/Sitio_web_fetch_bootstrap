# Sitio_web_fetch_bootstrap
Proyecto: Tienda Online Dinámica (SPA)
Este proyecto implementa una Tienda Online de una sola página (SPA) utilizando HTML, CSS (Bootstrap 5) y JavaScript, con énfasis en el uso de Fetch API para cargar contenido dinámico (productos y secciones de la página) y el manejo de componentes de Bootstrap.

Características Destacadas
Arquitectura SPA: La navegación entre Home, Nosotros y Contacto se realiza sin recargar la página gracias a la función cargarPagina() y la Fetch API.

Carga de Productos Dinámica: Los ítems de la tienda se obtienen de un archivo datos.json mediante fetch() y se renderizan como tarjetas de Bootstrap en la página de inicio.

Requisitos Técnicos Cumplidos:

✅ Uso de Bootstrap 5 (Diseño y Componentes).

✅ Implementación de Fetch API (Para vistas y datos).

✅ Elementos Multimedia (<video>, <audio>).

✅ Elemento Tabla (<thead>, <tbody>, <tfoot>).

✅ Formulario Completo con validaciones HTML5.

✅ Componentes de Bootstrap (Carrusel, Navbar, Cards, etc.).

Instalación y Ejecución
Dado que el proyecto utiliza la Fetch API para cargar archivos locales, necesita un servidor web local para funcionar correctamente (evitando errores de CORS o file://):

Clonar/Descargar el Repositorio.

Iniciar un Servidor Web Local: Utiliza extensiones como "Live Server" en VS Code o inicia un servidor simple de Python (python -m http.server) en la raíz del proyecto.

Abrir index.html a través de la dirección local (ej: http://127.0.0.1:5500/index.html)
