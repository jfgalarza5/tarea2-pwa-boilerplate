# Tarea 2 - La Forja del Desarrollador PWA

Este proyecto es una plantilla base para iniciar aplicaciones web progresivas (PWA) con Material Design Lite, lista para desarrollo profesional y colaborativo.

## Scripts de NPM

| Script           | Descripcion                                                                 |
|------------------|------------------------------------------------------------------------------|
| `npm run dev`    | Inicia el servidor de desarrollo con recarga en vivo.                       |
| `npm run lint`   | Analiza el codigo con ESLint para detectar errores y malas practicas.       |
| `npm run format` | Formatea el codigo con Prettier segun las reglas definidas.                 |
| `npm run serve`  | Simula un servidor de produccion, desactivando el cache del navegador. Ideal para probar Service Workers. |

## Estructura del Proyecto

- `index.html`: Estructura base con Material Design Lite.
- `manifest.json`: Manifesto basico para PWA.
- `sw.js`: Service Worker inicial.
- `css/`, `js/`, `assets/`: Archivos de estilos, scripts y recursos.

## Requisitos

- Node.js v16+
- Navegador moderno

## ¿Por que se usa live-server para desarrollo en lugar de http-server?
Se usa live-server en desarrollo porque recarga el navegador automaticamente cada vez que haces un cambio, lo que hace el trabajo mucho mas rapido. En cambio, http-server solo muestra los archivos pero no se actualiza solo.

##  ¿Por que es crucial deshabilitar el cache de http-server al probar un Service Worker?

Los Service Workers usan cache. Para evitar que el navegador sirva versiones antiguas, se desactiva el cache de archivos con `-c-1`.

---

Clona este repo con `git clone https://github.com/jfgalarza5/tarea2-pwa-boilerplate.git` y empieza tu proxima PWA muy facil y sencillo.
