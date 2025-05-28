# Proyecto-Spa-Header

Proyecto Spa and Beauty - Glow Queen
Descripción
Este es un proyecto web frontend para un spa y centro de belleza llamado "Glow Queen". Se trata de una landing page moderna y elegante que presenta los servicios de tratamientos de belleza y cuidado de la piel.
Características principales
Diseño y Estilo

Diseño responsivo con una paleta de colores profesional
Colores principales: Azul marino (#264065), Cian suave (#a9d6cb), Gris (#909090) y tonos blancos
Tipografía: Poppins de Google Fonts
Layout moderno con elementos flotantes y efectos visuales

Secciones incluidas

Header navegable

Logo de Glow Queen
Menú de navegación (Home, About, Services, Facilities, More)
Iconos de búsqueda y carrito
Botones de Sign In y Sign Up


Sección Hero

Título principal: "Bring back the beauty and glow of your skin"
Descripción de servicios
Botones de llamada a la acción (Book Now, Watch Video)
Imagen principal de una mujer con elementos decorativos


Sección de Servicios

Estadísticas destacadas:

15+ Tratamientos especiales
25+ Terapeutas profesionales
100% Fórmulas herbales


Iconos representativos para cada servicio


Sección de Reviews

Testimonios de clientes (Sophia Princeton y Tamara Jules)
Diseño de tarjetas flotantes
Comillas decorativas



Estructura de archivos
proyecto-spa/
├── index.html          # Archivo principal HTML
├── css/
│   └── style.css      # Hoja de estilos CSS
└── img/               # Carpeta de imágenes (requerida)
    ├── logo-glowqueen.png
    ├── beauty-woman.png
    ├── lotus-marca-de-agua.png
    ├── face-icon.png
    ├── lotus-icon.png
    ├── mortar-icon.png
    ├── comillas-icon.png
    ├── play-icon.svg
    ├── arrow-down.svg
    ├── search-icon.png
    └── bag-icon.png
Cómo visualizar el proyecto
Opción 1: Visualización local simple

Descargar los archivos: Asegúrate de tener index.html y css/style.css
Crear carpeta de imágenes: Crea una carpeta llamada img/ en el directorio raíz
Añadir imágenes: Coloca todas las imágenes requeridas en la carpeta img/
Abrir en navegador: Haz doble clic en index.html o abre el archivo desde tu navegador

Opción 2: Servidor local (recomendado)
Para una mejor experiencia y evitar problemas de CORS:
bash# Con Python 3
python -m http.server 8000

# Con Node.js (si tienes http-server instalado)
npx http-server

# Con PHP
php -S localhost:8000
Luego visita http://localhost:8000 en tu navegador.
Opción 3: Live Server (VS Code)
Si usas Visual Studio Code:

Instala la extensión "Live Server"
Haz clic derecho en index.html
Selecciona "Open with Live Server"

Requisitos

Navegador moderno (Chrome, Firefox, Safari, Edge)
Conexión a internet (para cargar las fuentes de Google Fonts)
Imágenes requeridas (ver lista en estructura de archivos)

Notas técnicas

El diseño utiliza Flexbox para el layout
Implementa posicionamiento absoluto para elementos decorativos
Incluye efectos de sombra y border-radius para un aspecto moderno
La tipografía se carga desde Google Fonts
El CSS utiliza variables CSS para mantener consistencia en los colores

Navegadores compatibles

Chrome 60+
Firefox 55+
Safari 12+
Edge 79+

Estado del proyecto
Este es un proyecto estático de frontend que presenta el diseño y la estructura básica de una landing page para un spa. Para funcionalidad completa, sería necesario agregar:

JavaScript para interactividad
Backend para formularios y reservas
Base de datos para gestión de citas
Sistema de autenticación para Sign In/Sign Up


Nota: Asegúrate de tener todas las imágenes requeridas para que el sitio se visualice correctamente. Las imágenes faltantes aparecerán como enlaces rotos en el navegador.
