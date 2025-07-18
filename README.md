# Repostería Catalina - Sitio Web y Formulario de Contacto

Este proyecto es el sitio web para **"Repostería Catalina", un emprendimiento real de pastelería**. Fue desarrollado como parte de dos evaluaciones de desarrollo front-end, utilizando imágenes y contenido auténtico del negocio.

El sitio presenta los productos y servicios de la repostería e incluye un formulario de contacto avanzado con funcionalidades dinámicas.

## Características Principales

* **Sitio Web Estático:** Múltiples páginas (Inicio, Servicios, Nosotros, Contacto) construidas con HTML y CSS.
* **Diseño Responsivo:** Adaptable a diferentes tamaños de pantalla utilizando el framework Bootstrap.
* **Formulario de Contacto Dinámico:**
    * **Validación de Campos:** Verificación en tiempo real para asegurar que los campos no estén vacíos, que el email tenga un formato válido y que el teléfono corresponda a un número móvil chileno (9 dígitos comenzando con 9).
    * **Límite de Caracteres:** Control en el campo de mensaje con un contador visible para el usuario.
    * **Integración de API Externa:** Carga una lista de países desde la API de `restcountries.com` para poblar un menú desplegable.
    * **Persistencia de Datos con `localStorage`:**
        * **Crear (Create):** Guarda nuevos contactos en el almacenamiento local del navegador.
        * **Leer (Read):** Muestra una lista de todos los contactos guardados directamente en la página.
        * **Actualizar (Update):** Permite editar la información de un contacto existente.
        * **Eliminar (Delete):** Permite borrar un contacto de la lista, solicitando una confirmación previa.

## Tecnologías Utilizadas

* **HTML5**
* **CSS3** (con variables y diseño responsivo)
* **JavaScript**
* **jQuery 3.5.1** (para manipulación del DOM, eventos y peticiones AJAX)
* **Bootstrap 4.6.2** (para el layout y componentes de la interfaz)
* **Google Fonts**
* **Bootstrap Icons**
