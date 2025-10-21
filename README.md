# Pizzería Mamá Mía 🍕 — Hito 6

Bienvenido/a al repositorio de la Pizzería Mamá Mía. Esta aplicación es el Hito 6 del bootcamp Desafío Latam y está desarrollada con React y Vite.

La app simula la experiencia de una pizzería: listado de pizzas, autenticación básica, carrito de compras y flujo de compra.

## Estado actual (Hito 6)

- Código fuente en `src/` (componentes, páginas, contexto y utilidades).
- Build de producción generado en `docs/` (configurado en `vite.config.js`).
- ESLint configurado y actualizado para ignorar la carpeta `docs/` (evita lintear archivos compilados).
- Dependencias principales: React, React DOM, React Router.

## Características principales

- Autenticación (login / registro) — interfaz y flujo básico.
- Listado de pizzas con imágenes, precios e ingredientes.
- Añadir pizzas al carrito y modificar cantidades.
- Carrito con total y opción de pagar (vacía el carrito al confirmar).
- Rutas de navegación (React Router v6): Home, Pizza, Cart, Login, Register, Profile, NotFound.
- Contexto para gestionar el carrito (`src/context/CartContext.jsx`).
- Componentes reutilizables: `Header`, `Footer`, `Navbar`, `CardPizza`, etc.

## Estructura del proyecto (resumen)

```
├── public/
├── docs/                # Salida de build (producción)
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   ├── styles.css
│   ├── components/
│   │   ├── CardPizza.jsx
│   │   ├── Footer.jsx
│   │   ├── Header.jsx
│   │   └── Navbar.jsx
│   ├── context/
│   │   ├── CartContext.jsx
│   │   ├── CartProvider.jsx
│   │   └── useCart.jsx
│   └── pages/
│       ├── Home.jsx
│       ├── Pizza.jsx
│       ├── Cart.jsx
│       ├── Login.jsx
│       ├── Register.jsx
│       └── Profile.jsx
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
└── README.md
```


Abrir en el navegador:

[http://localhost:5173](http://localhost:5173)


## Autor

- Johanna Barrientos
- Desafío Latam — Hito 6





