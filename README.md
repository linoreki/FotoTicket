# FotoTicket

Prepara e imprime tus fotos en tickets de forma sencilla y accesible.

FotoTicket convierte tus fotos en blanco y negro listas para imprimir en papel térmico de 58 mm o 80 mm, directamente desde el navegador. Todo el procesamiento ocurre en tu ordenador: la foto nunca sale de tu dispositivo.

## Características

- 🖼️ Sube, arrastra o pega (Ctrl+V / ⌘+V) una foto
- ✨ Conversión automática a blanco y negro con dithering listo para impresoras térmicas
- ☀️ / 🌙 Ajustes de brillo (más clara / más oscura)
- 📏 Tamaños de ticket: Normal (58 mm) y Grande (80 mm)
- 🖨️ Impresión directa por el diálogo del sistema
- 💾 Descarga la imagen como PNG
- 🔒 Todo se procesa localmente, sin subir nada a ningún servidor
- ♿ Accesible: funciona con teclado y lectores de pantalla

## Uso

No requiere instalación ni servidor. Abre el archivo `index.html` directamente en tu navegador (Chrome, Edge, Firefox o Safari) y ya está.

También puedes hospedarlo en cualquier hosting estático de GitHub Pages, Netlify, Vercel, etc.

1. Elige tu foto
2. Ajusta el brillo si quieres
3. Imprime o guarda la imagen

> **Tip para imprimir**: usa una impresora térmica de tickets (58 mm o 80 mm). El diálogo de impresión del navegador eliminará los márgenes automáticamente.

## Desarrollo

El proyecto es un único archivo HTML sin dependencias de build. La única dependencia es Tailwind CSS vía CDN.

```bash
# No hay pasos de build. Para verlo en local:
start index.html   # Windows
open index.html    # macOS y Linux
```

## Tecnología

- HTML, CSS y JavaScript vanilla (ES6)
- Tailwind CSS (CDN)
- Canvas API para el procesamiento de imagen
- Dithering de Floyd-Steinberg para simular el rendimiento térmico

## Estructura

```
├── index.html    # Aplicación completa (HTML + CSS + JS)
├── README.md
└── LICENSE
```

## Licencia

Distribuido bajo la licencia [Apache 2.0](LICENSE).