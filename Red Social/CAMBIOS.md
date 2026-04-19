# Bitácora de Cambios - InstaTube

Este documento registra las modificaciones realizadas en el proyecto de la Red Social.

## Cambios Realizados

### 1. Cambio de Marca (Branding)
- Se ha renombrado la aplicación de **LifeInvader** a **InstaTube**.
- Se actualizaron los títulos de las páginas en todos los archivos HTML (`index.html`, `login.html`, `registro.html`, `perfil.html`, `editar.html`).
- Se actualizó el encabezado (header) principal en todas las páginas.
- Se actualizó la clave de `localStorage` de `lifeInvaderUsers` a `instaTubeUsers` para mantener la consistencia en el almacenamiento de datos.
- Se actualizaron las referencias dinámicas en `app.js`.

### 2. Corrección de Estilos (CSS)
- Se restauraron los estilos base, variables de color y el diseño responsivo en `styles.css`.
- Se aplicó una **temática verde** sólida para un aspecto más sencillo y minimalista, eliminando degradados y sombras complejas en el banner.
- Se simplificó la navegación y el tamaño de la tipografía para un diseño más limpio.
- Se definieron los estilos para el feed de publicaciones, la barra lateral de contactos y la vista de perfil.
- Se corrigió el problema de las variables no definidas que impedía que el CSS se aplicara correctamente.

### 3. Eliminación de JavaScript (Mockup Estático)
- Se han eliminado todas las referencias a `app.js` y los scripts inline en los archivos HTML.
- El archivo `app.js` ha sido borrado del proyecto.
- Las secciones que antes eran dinámicas (lista de contactos, perfil de usuario) ahora contienen datos estáticos integrados directamente en el HTML.
- Se rellenaron los formularios con valores predeterminados para mantener la visualización del diseño.

### 4. Perfiles Estáticos y Contactos
- Se ha actualizado el perfil principal a **David Lopez** (México, Campeche).
- Se agregaron las fotos de perfil locales desde la carpeta `img/Foto de perfil/` para David y todos los contactos.
- Se recreó el feed de publicaciones en `index.html` utilizando las imágenes locales de `img/Foto de publicacion/`, asignando cada imagen a su respectivo autor.
- La publicación superior en el feed es de **David Lopez**, simulando ser la actualización más reciente.
- Se crearon 6 archivos HTML adicionales para simular perfiles de contactos reales con sus respectivas fotos locales:
    - `perfil_ana.html`
    - `perfil_carlos.html`
    - `perfil_maria.html`
    - `perfil_pedro.html`
    - `perfil_laura.html`
    - `perfil_juan.html`
- Se actualizó la lista de contactos en `index.html` y en todos los perfiles para incluir las miniaturas de las fotos de perfil locales.

## Estructura del Proyecto
- `index.html`: Feed principal con publicaciones y contactos con fotos locales.
- `perfil.html`: Perfil de David Lopez con foto local.
- `perfil_*.html`: Perfiles individuales de los contactos con fotos locales.
- `editar.html`: Formulario de edición estático.
- `styles.css`: Estilos verdes simplificados.
- `img/`: Carpeta que contiene todas las imágenes locales (perfil y publicaciones).