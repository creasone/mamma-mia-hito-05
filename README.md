# Pizzería Mamma Mía — Hito 5

Aplicación React + Vite que incorpora navegación cliente con React Router.

## Funcionalidades

- Rutas para Home, Registro, Login, Carrito, detalle `p001`, Perfil y 404.
- Navbar con `NavLink` y navegación sin recargas.
- `BrowserRouter` en desarrollo y `HashRouter` en producción para GitHub Pages.
- Catálogo y detalle consumidos desde la API académica, con respaldo local para la demo.

## Ejecutar

```bash
pnpm install --frozen-lockfile
pnpm dev
```

Compilar con `pnpm build`.

La API se obtiene desde `VITE_API_URL` o, por defecto, `http://localhost:5000`.
