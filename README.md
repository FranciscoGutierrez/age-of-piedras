# Tiny Kingdoms: Under Siege 🏰⚔️
**Little Kingdoms. Big Trouble.**

Juego RTS HTML5/Canvas, versión **2.15**.

- Juego en `index.html` con pantalla de inicio, opción **Español / English**, seis civilizaciones (Celtas, Franceses, Ingleses, Nórdicos, Italianos, Españoles) y seis dificultades (Muy fácil, Fácil, Estándar, Difícil, Muy difícil, Extremo).
- Cada civilización aplica bonificaciones y penalizaciones reales; cada dificultad ajusta HP, daño, número de invasores y temporizadores. **Estándar** conserva el balance de v2.7.
- Ya no existe el límite especial de 8 aldeanos: puedes entrenar tantos como permita la población disponible (máximo general de 80), ampliando con casitas.
- Los cuatro botones de entrenamiento muestran el número de unidades vivas por tipo en formato `Aldeano (12)` / `Villager (12)`; el conteo se actualiza al crear unidades, sufrir bajas y cambiar de idioma. Las unidades en cola se muestran por separado.
- ⚖️ **Balance v2.15:** recursos iniciales 260 🌾 / 160 🪙 (antes 320/200). Recolección base de 2 recursos cada 0.80 s (antes 0.55 s); a partir del quinto aldeano asignado al mismo recurso, rendimiento decreciente suave. Sin límite especial de aldeanos; las mejoras económicas siguen aumentando la producción.
- 🏹 Arqueros: daño 13 (antes 14), alcance 110 (antes 132), recarga 1.20 s (antes 1.05 s) y ventaja contra espadachines ×1.90 (antes ×2.25); costos intactos.
- Hub de Centro, Herrería y Universidad, con progreso de investigación instantáneo.
- El encabezado durante la partida muestra el emblema y nombre traducido de la civilización activa.
- Menú principal y menú de pausa para volver al inicio o cambiar idioma. La preferencia se guarda en el dispositivo.
- 🎶 Banda sonora medieval original generada con Web Audio: ambiente tranquilo durante la preparación, ritmo más intenso en las oleadas y música especial para el ogro. Control de sonido en el menú inicial, la barra de juego y el menú de pausa; elección guardada en el dispositivo. Funciona sin descargas ni conexión.
- 🔉 Efectos sintetizados mediante Web Audio (sin archivos externos): taps, selección de unidades, golpes de espada, lanzas, flechas, impactos al castillo y garrotazos. Rugido del Gran Ogro al aparecer y al bajar a la mitad de vida. Incluye fanfarria al ganar y melodía de derrota cuando cae el castillo. Efectos y música cuentan con controles independientes, disponibles en pausa y persistidos en el dispositivo.
- `manifest.webmanifest`: instalable como PWA.
- `sw.js`: cachea recursos para jugar sin internet después de la primera carga.
- `icons/`: íconos para iPhone, Android y navegador.

## Publicar gratis con GitHub Pages
En GitHub entra a **Settings → Pages**, elige **Deploy from a branch**, rama **main**, carpeta **/(root)** y pulsa **Save**.

Comparte este enlace para jugar: **https://franciscogutierrez.github.io/age-of-piedras/**

> El enlace conserva el nombre técnico anterior del repositorio para no romper vínculos ni instalaciones existentes; el título mostrado al jugador es **Tiny Kingdoms: Under Siege**.

Abre la URL con **Safari** en un iPhone, pulsa **Compartir → Agregar a inicio** y después abre el juego desde su ícono.

Al actualizar el juego, cambia el valor `CACHE` de `sw.js` para que los dispositivos renueven los archivos offline.

## Notas
- GitHub Pages requiere que esté habilitado desde Settings.
- El juego utiliza HTML y JavaScript sin dependencias externas.
- Para publicar futuras versiones sustituye `index.html` y actualiza la versión del caché.
