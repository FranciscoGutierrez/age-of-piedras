# Age of Piedras 🏰⚔️
Juego RTS HTML5/Canvas, versión **2.7**.

- Juego en `index.html` con pantalla de inicio, opción **Español / English**, mejoras en el Hub de Centro, Herrería y Universidad.\n- Menú principal y menú de pausa para volver al inicio o cambiar idioma. La preferencia se guarda en el dispositivo.
- `manifest.webmanifest`: instalable como PWA.
- `sw.js`: cachea recursos para jugar sin internet después de la primera carga.
- `icons/`: íconos para iPhone, Android y navegador.

## Publicar gratis con GitHub Pages
En GitHub entra a **Settings → Pages**, elige **Deploy from a branch**, rama **main**, carpeta **/(root)** y pulsa **Save**.

La URL pública es: **https://franciscogutierrez.github.io/age-of-piedras/**

Abre la URL con **Safari** en un iPhone, pulsa **Compartir → Agregar a inicio** y después abre el juego desde su ícono.

Al actualizar el juego, cambia el valor `CACHE` de `sw.js` para que los dispositivos renueven los archivos offline.

## Notas
- GitHub Pages requiere que esté habilitado desde Settings.
- El juego utiliza HTML y JavaScript sin dependencias externas.
- Para publicar futuras versiones sustituye `index.html` y actualiza la versión del caché.
