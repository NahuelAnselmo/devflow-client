🛒 E-Commerce Frontend
📌 Descripción

E-Commerce Frontend es la interfaz de usuario para el sistema de tienda online La Old School 23. Está diseñado con React + Vite, ofreciendo un entorno rápido, modular y fácil de escalar.

Este proyecto consume la API del backend 👉 Repositorio Backend: https://github.com/NahuelAnselmo/devflow-server

🚀 Características Principales

Autenticación de usuarios (login / registro).

Listado de productos dinámico consumido desde la API.

Carrito de compras con persistencia local.

Checkout de pedidos conectado al backend.

Gestión de usuarios (perfil, historial de pedidos).

Responsive Design para PC, tablet y mobile.

Componentes reutilizables con enfoque modular.

🛠️ Tecnologías

React + Vite (base del proyecto).

React Router (navegación).

Axios / Fetch (consumo de API).

TailwindCSS (estilos rápidos y modernos).

Context API o Redux (gestión de estado global).

Framer Motion (animaciones).

## 📂 Estructura del Proyecto

```bash
📦 ecommerce-frontend
 ┣ 📂 public        # Archivos estáticos (imágenes, favicon, etc.)
 ┣ 📂 src
 ┃ ┣ 📂 assets      # Recursos estáticos (CSS, imágenes locales)
 ┃ ┣ 📂 components  # Componentes reutilizables (botones, cards, etc.)
 ┃ ┣ 📂 hooks       # Custom Hooks
 ┃ ┣ 📂 pages       # Páginas de la aplicación (Home, Login, Products, etc.)
 ┃ ┣ 📂 routes      # Configuración de rutas con React Router
 ┃ ┣ 📂 services    # Llamadas a la API (fetch/axios)
 ┃ ┣ 📂 store       # Estado global (Redux/Zustand/Context)
 ┃ ┣ 📂 utils       # Funciones auxiliares
 ┃ ┣ 📜 App.jsx     # Componente raíz
 ┃ ┗ 📜 main.jsx    # Punto de entrada de React
 ┣ 📜 .env.example  # Variables de entorno de ejemplo
 ┣ 📜 index.html    # HTML base
 ┣ 📜 package.json
 ┗ 📜 README.md


⚙️ Requisitos Previos

Antes de instalar y ejecutar el proyecto, asegurate de tener:

Node.js (v16 o superior).

Git instalado.

Visual Studio Code u otro editor.

📥 Instalación

Clonar el repositorio:

git clone https://github.com/NahuelAnselmo/devflow-client.git
cd TU_REPO_FRONT


Instalar dependencias:

npm install


Crear archivo .env en la raíz del proyecto con la URL del backend:

VITE_API_URL=http://localhost:3000/api


Iniciar el servidor en modo desarrollo:

npm run dev

📡 Rutas principales

/ → Home con listado de productos.

/login → Iniciar sesión.

/register → Crear cuenta.

/cart → Carrito de compras.

/checkout → Finalizar compra.

/profile → Perfil del usuario.

🧪 Testing

Para testear la app recomendamos:

Jest + React Testing Library (unit tests).

Cypress (tests end-to-end).

🚀 Despliegue

El frontend puede desplegarse en:

Vercel

Netlify

GitHub Pages

Asegúrate de configurar VITE_API_URL con la URL de producción del backend.

📜 Licencia

Este proyecto está bajo licencia MIT.

👥 Equipo

Desarrollado por:

° Nahuel Anselmo
```
