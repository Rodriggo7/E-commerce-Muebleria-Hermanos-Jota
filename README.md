# 🪑 E-commerce Mueblería Hermanos Jota

Este proyecto es la fachada completa y la experiencia interactiva de un e-commerce de muebles, desarrollado exclusivamente con tecnologías del lado del cliente (Client-Side). Se construyó simulando una experiencia de compra fluida y asíncrona sin necesidad de un backend real.

## 🚀 Despliegue
**Sitio en Producción:** https://rodriggo7.github.io/E-commerce-Muebleria-Hermanos-Jota/

## 🛠️ Tecnologías Utilizadas
* **HTML5:** Estructura semántica.
* **CSS3:** Diseño 100% responsivo (Mobile First), uso de Flexbox, Modelo de Cajas y un sistema de variables (Custom Properties) para mantener la consistencia en la UI/UX.
* **JavaScript (Vanilla JS):** Lógica modular, manipulación dinámica del DOM, Promesas (async/await) y Fetch API.
* **JSON:** Almacenamiento local estructurado del catálogo de productos.

## ✨ Funcionalidades Principales
1. **Catálogo Dinámico:** Los productos se cargan de forma asíncrona desde un archivo `productos.json` local utilizando `fetch`.
2. **Carrito de Compras Simulado:** Contador interactivo en el header que reacciona a los eventos de los botones "Añadir al Carrito" con feedback visual.
3. **Buscador en Tiempo Real:** Filtro de productos por nombre o categoría dentro del catálogo.
4. **Validación de Formularios:** Validación estricta del lado del cliente (longitud de campos y formato de email) con manipulación del DOM para mostrar mensajes de error o éxito.
5. **Sistema de Temas:** Paleta de colores extraída del logo vectorial (SVG) e implementada mediante variables CSS para una interfaz moderna y coherente.

## 👥 Integrantes del Equipo (Sprint 2)
* [Tu Nombre / Rodrigo Rivera] - *Rol/Tareas (ej. Lógica JS y Fetch API)*
* [Nombre Integrante 2] - *Rol/Tareas (ej. Maquetación HTML y JSON)*
* [Nombre Integrante 3] - *Rol/Tareas (ej. Estilos CSS y Responsividad)*
* [Nombre Integrante 4] - *Rol/Tareas (ej. Documentación y Pruebas)*

## ⚙️ Instalación y Uso Local
Si deseas clonar este proyecto y correrlo en tu máquina local:
1. Clona el repositorio: `git clone https://github.com/Rodriggo7/E-commerce-Muebleria-Hermanos-Jota.git`
2. Abre la carpeta del proyecto.
3. Para que la API `fetch` funcione correctamente con archivos locales, abre el proyecto utilizando una extensión como **Live Server** en VS Code (abrir el archivo `index.html` directamente en el navegador con un doble clic puede bloquear la petición por políticas de CORS).