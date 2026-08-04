# Roberto Contino | Estilistas

Este es el repositorio oficial para el sitio web institucional de **Roberto Contino Estilistas**. El sitio es una página web estática, responsiva e interactiva diseñada para presentar la trayectoria, servicios, el equipo de estilistas y permitir la reserva ágil de turnos vía WhatsApp.

## 🚀 Despliegue Automático

El proyecto está configurado para desplegarse de manera automática en **GitHub Pages** mediante GitHub Actions cada vez que se realiza un push a la rama `main`.

### Requisitos en GitHub para activar el despliegue automático:
1. Ve a la pestaña **Settings** (Configuración) de este repositorio en GitHub.
2. En el menú de la izquierda, selecciona **Pages**.
3. En la sección **Build and deployment**, bajo **Source**, selecciona **GitHub Actions** en lugar de "Deploy from a branch".
4. ¡Listo! El workflow se encargará de compilar y publicar el sitio automáticamente con cada cambio en la rama `main`.

Una vez activado, el sitio estará disponible en la URL proporcionada por GitHub (generalmente `https://francocontino.github.io/robercon/`).

## 🛠️ Tecnologías Utilizadas

- **HTML5** & **Vanilla JavaScript** para la estructura y comportamiento dinámico.
- **Tailwind CSS** (vía CDN) para un diseño elegante, moderno y adaptado a todo tipo de pantallas (responsive).
- **Google Fonts** (Montserrat y Playfair Display) para una tipografía de alta calidad.
- **Font Awesome** para los íconos de redes sociales y elementos interactivos.
- **GitHub Actions** para el flujo continuo de integración y despliegue (CI/CD).

## 📂 Estructura del Proyecto

- `index.html`: El archivo principal que contiene la maquetación y la lógica del sitio.
- `*.jpg`, `*.png`, `*.webp`: Imágenes optimizadas utilizadas en el diseño del salón y perfiles del equipo.
- `.github/workflows/deploy.yml`: Configuración del workflow de despliegue automático.
- `.gitignore`: Archivos del sistema y configuraciones locales excluidos del control de versiones.
