# Sabores Urbanos - Pedidos de Comida

Una aplicación web moderna para un local de comidas, diseñada para permitir a los clientes explorar el menú y realizar pedidos fácilmente. La interfaz es limpia, rápida y completamente adaptada para dispositivos móviles.

![Sabores Urbanos Screenshot](https://i.imgur.com/k9b6t7I.png)

## 🚀 Cómo ejecutar el proyecto

Este es un proyecto de frontend estático (HTML, CSS, y JavaScript con React a través de ESM). No requiere un proceso de compilación complejo como `create-react-app` para ejecutarse localmente.

### Opción 1: Usando un servidor local simple (Recomendado)

1.  Asegúrate de tener [Node.js](https://nodejs.org/) instalado en tu sistema.
2.  Abre una terminal o línea de comandos en la carpeta raíz del proyecto.
3.  Instala `serve`, un servidor estático muy popular:
    ```bash
    npm install -g serve
    ```
4.  Una vez instalado, ejecuta el servidor con el siguiente comando:
    ```bash
    serve -s .
    ```
    El flag `-s` es importante porque le indica al servidor que redirija todas las peticiones al `index.html`, lo cual es necesario para que las aplicaciones de página única (SPA) como esta funcionen correctamente.
5.  Abre tu navegador y ve a la dirección que te indica la terminal (generalmente `http://localhost:3000`).

### Opción 2: Usando la extensión "Live Server" en VS Code

1.  Si usas Visual Studio Code como editor de código, puedes instalar la extensión [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).
2.  Una vez instalada, haz clic derecho sobre el archivo `index.html` en el explorador de archivos de VS Code.
3.  Selecciona la opción "Open with Live Server".
4.  Esto abrirá la aplicación en tu navegador predeterminado automáticamente.

## ✨ Características

*   **Menú Interactivo:** Explora diferentes categorías de comida (Promos, Pizzas, Hamburguesas, etc.).
*   **Vista Detallada:** Haz clic en cualquier plato para ver sus ingredientes, descripción y precio.
*   **Acciones Rápidas:** Botones directos para realizar pedidos por llamada telefónica o WhatsApp.
*   **Diseño Responsivo (Mobile-First):** Se ve y funciona de manera excelente en cualquier tamaño de pantalla.
*   **Información Clave:** Acceso rápido a la ubicación del local en Google Maps, horarios y costos de envío.
*   **Cero Compilación:** Construido con tecnologías modernas que no requieren un paso de `build`, facilitando su despliegue.

## 🛠️ Tecnologías Utilizadas

*   **React 19:** Cargado directamente en el navegador a través de `importmap` y ESM, sin necesidad de Webpack o Vite.
*   **TypeScript:** Para un código más robusto y mantenible.
*   **Tailwind CSS:** Utilizado a través de su CDN para un diseño rápido y personalizable.
*   **HTML5 y CSS3**
*   **ESM (ECMAScript Modules):** Permite usar `import` y `export` de JavaScript directamente en el navegador.

## 📦 Despliegue en Internet

Para publicar esta aplicación y que sea accesible para todo el mundo, puedes usar cualquiera de los siguientes servicios de alojamiento estático gratuitos:

*   **Vercel:** Ideal para proyectos de frontend modernos. Simplemente conecta tu repositorio de GitHub y Vercel se encargará del resto.
*   **Netlify:** Muy similar a Vercel, ofrece una integración y despliegue automáticos muy sencillos desde GitHub.
*   **GitHub Pages:** Una opción gratuita y directa si tu código ya está alojado en un repositorio de GitHub.

El proceso es simple: sube todos los archivos de tu proyecto a un repositorio de GitHub y luego conecta ese repositorio a uno de estos servicios. Ellos detectarán automáticamente que es un sitio estático y lo desplegarán sin necesidad de ninguna configuración de `build` de tu parte.
# pedidos
