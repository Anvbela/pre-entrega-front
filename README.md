# AnimurA Store ❀ - Pre-entrega

¡Bienvenidos a **AnimurA**! Este proyecto es el desarrollo de una tienda online dedicada a la exhibición y venta de piezas artesanales únicas y personalizadas hechas a mano, con base de retiro en la ciudad de La Plata.

---

## 📝 Descripción del Proyecto
El sitio web está diseñado de forma estática utilizando **HTML5** y **CSS3**. Cuenta con una estética cálida y artesanal que refleja la identidad de la marca. Esta pre-entrega incluye la página principal, catálogo de productos, sección de registro y la estructura base de navegación de la tienda.

---

## 🚀 Funcionalidades e Interfaces Incluidas

El proyecto está estructurado a través de múltiples páginas interconectadas de manera dinámica:

* **Página de Inicio (`index.html`):** Presenta la marca con una marquesina animada de bienvenida, banner principal, sección de reseñas de clientes y un pie de página detallado con la ubicación del taller mediante mapas interactivos.
* **Catálogo de Decoración/Productos (`pages/decoracion.html`):** Sección donde se listan las piezas artesanales (Plato cabrita, Ensaladera Jinx, Tazas payaso, etc.) distribuidas mediante un sistema de grillas dinámicas.
* **Formulario de Registro (`pages/Registrate.html`):** Formulario para que los usuarios se registren, vinculado directamente a un sistema de recepción de correos (**Formspree**).
* **Secciones Maquetadas en Navegación:** Estructura de links lista para las páginas de productos personalizados, procesos y el carrito de compras.

---

## 🛠️ Tecnologías y Recursos Utilizados

* **HTML5:** Estructuración semántica de todas las páginas del sitio.
* **CSS3:** Estilos personalizados utilizando:
    * **CSS Grid:** Para la distribución alineada y limpia de las tarjetas de productos.
    * **Flexbox:** Para la alineación adaptativa de la barra de navegación (Header) y las columnas de información del Footer.
    * **CSS Animations (@keyframes):** Animación de texto fluido en la marquesina de introducción.
* **FontAwesome (v6.5.1):** Kit de iconos vectoriales para las redes sociales, menú y carrito de compras.
* **Google Maps Embed:** Integración de mapa interactivo en el footer de la web.

---

## 📂 Estructura del Proyecto

El repositorio está organizado de la siguiente manera:

```text
├── index.html              # Página de inicio principal
├── style.css               # Hoja de estilos generales y responsive del sitio
├── img/                    # Carpeta contenedora de imágenes, logos y banners
└── pages/                  # Vistas secundarias de la aplicación
    ├── decoracion.html     # Galería y catálogo de productos
    ├── Registrate.html     # Formulario de registro de usuarios
    ├── Personalizados.html # (Próxima entrega)
    ├── procesos.html       # (Próxima entrega)
    └── carrito.html        # (Próxima entrega)
