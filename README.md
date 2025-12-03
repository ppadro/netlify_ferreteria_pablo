
# Ferretería Pablo 🛠️

Aplicación web desarrollada con **React + Vite** para la gestión de productos de una ferretería.  
Incluye funcionalidades de carrito, autenticación, panel de administración y visualización de productos.

---

## 🚀 Tecnologías utilizadas
- [React](https://react.dev/) – Librería para construir interfaces de usuario.
- [Vite](https://vitejs.dev/) – Herramienta de build rápida y moderna.
- [Bootstrap](https://getbootstrap.com/) – Estilos y componentes responsivos.
- Context API – Manejo de estado global (Auth, Cart, Products).
- Vercel – Hosting y despliegue automático.

---

## 📂 Estructura del proyecto
```
src/
 ├── assets/          # Recursos estáticos (logos, íconos)
 ├── components/      # Componentes reutilizables (Navbar, FormularioProducto, etc.)
 ├── context/         # Contextos globales (AuthContext, CartContext, ProductsContext)
 ├── pages/           # Páginas principales (Inicio, Productos, Carrito, Dashboard, etc.)
 ├── video/           # Videos utilizados en la app
 ├── App.jsx          # Componente raíz
 ├── index.css        # Estilos globales
 └── main.jsx         # Punto de entrada
```

---

## ⚙️ Instalación y ejecución

1. Clonar el repositorio:
   
   git clone https://github.com/ppadro/ferreteria-pablo.git
   cd ferreteria-pablo
   

2. Instalar dependencias:
    npm install
  

1. Ejecutar en desarrollo:
   npm run dev
   

4. Generar build de producción:
   npm run build
   

---

## 🌐 Deploy en Vercel
El proyecto está configurado para desplegarse en [Vercel](https://vercel.com).  
- **Build Command:** `npm run build`  
- **Output Directory:** `dist`  
- Configuración adicional en `vercel.json`.

---

## 📌 Funcionalidades
- Catálogo de productos con imágenes y descripciones.
- Carrito de compras.
- Autenticación de usuarios.
- Panel de administración con edición y eliminación de productos.
- Diseño responsivo.

---

## 👨‍💻 Autor
Proyecto desarrollado por **Pablo Padró**.
Readme generado por Copilot
