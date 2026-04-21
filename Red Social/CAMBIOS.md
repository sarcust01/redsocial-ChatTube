# Integrantes
- Lopez Gonzalez David Concepcion
- Hernández Lira José Enrique



# Documentación del Proyecto - InstaTube

Este documento detalla la estructura y características actuales de la Red Social **InstaTube**, un prototipo estático desarrollado con HTML y CSS.

## Descripción General
**InstaTube** es una plataforma de red social minimalista que permite a los usuarios visualizar un feed de publicaciones, perfiles de contactos y gestionar su propia información de perfil. El proyecto destaca por su diseño limpio con una temática verde sólida y una interfaz intuitiva.

## Características Principales

### 1. Feed de Publicaciones (`index.html`)
- Muestra una lista de publicaciones de diversos usuarios.
- **Estructura de Publicación Mejorada**:
    - Descripción y hashtags ahora aparecen en la parte superior.
    - Fotografía central (almacenada localmente).
    - **Sección de Comentarios Enriquecida**: Incluye comentarios estáticos con el avatar (foto de perfil) del autor del comentario para una apariencia más real.
    - Formulario de simulación para nuevos comentarios.
- **Banner Publicitario**: Se integró un banner de publicidad simulado en la parte superior del feed y de cada perfil.

### 2. Gestión de Perfiles
- **Perfil Principal (`perfil.html`)**: Muestra la información de David Lopez (México, Campeche), incluyendo su biografía, foto de perfil local y banner publicitario.
- **Perfiles de Contactos (`perfil_*.html`)**: Existen 6 perfiles individuales (Ana, Carlos, Maria, Pedro, Laura y Juan) con información específica, fotos locales y banners temáticos.
- **Edición de Perfil (`editar.html`)**: Formulario estático para simular la modificación de datos personales.

### 3. Autenticación Simulada
- **Login (`login.html`)**: Interfaz de acceso directo. Al presionar el botón de inicio de sesión, el usuario es redirigido automáticamente al feed principal (`index.html`) sin necesidad de validación, agilizando la navegación en el prototipo.
- **Registro (`registro.html`)**: Interfaz para simular la creación de una nueva cuenta.

### 4. Diseño y Estilos (`styles.css`)
- **Temática Visual**: Uso de colores verdes sólidos (`#4CAF50`) para una apariencia profesional y sencilla.
- **Responsividad**: Diseño adaptado para dispositivos móviles y escritorio mediante el uso de CSS Grid y Media Queries.
- **Componentes**: Estilos definidos para banners, tarjetas de publicación, barras laterales de contactos y formularios.

## Estructura de Archivos
- `index.html`: Página principal con el feed.
- `login.html` / `registro.html`: Páginas de acceso.
- `perfil.html`: Perfil del usuario logueado.
- `perfil_ana.html`, `perfil_carlos.html`, etc.: Perfiles de la red de contactos.
- `editar.html`: Formulario de edición.
- `styles.css`: Hoja de estilos global.
- `img/`: Directorio de recursos visuales (fotos de perfil y publicaciones).
