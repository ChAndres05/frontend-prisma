# Frontend Prisma

Frontend del sistema gastronómico **Sabor & Gestión**.

## Tecnologías
- React
- Vite
- React Router
- Axios

## Requisitos
- Node.js 18 o superior
- npm 9 o superior

## Instalación
- npm install
- Variables de entorno

## Crear un archivo .env.local basado en .env.example.

# Ejemplo:
```bash 
VITE_API_URL=http://localhost:3000
```
## Ejecución local
```bash
npm run dev
```

## Flujo de ramas:

- main: versión estable del proyecto
- develop: integración de cambios revisados
- feature/nombre-funcionalidad: trabajo individual por funcionalidad

# Ejemplos:

- feature/login
- feature/catalogo
- feature/mesas

## Reglas básicas de trabajo

- No trabajar directamente sobre main
- No subir node_modules
- No subir archivos .env.local
- Antes de hacer push, probar el proyecto con npm run dev
- Antes de integrar cambios, ejecutar npm run lint
- Calidad de código

## Para revisar el estilo y errores básicos del código:

```bash
npm run lint
```
## Estructura base

- src/pages: páginas principales
- src/components: componentes reutilizables
- src/services: conexión con backend
- src/context: autenticación y estado global
- src/router: rutas
- src/styles: estilos globales