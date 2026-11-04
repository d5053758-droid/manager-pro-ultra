# Manager Pro Ultra – PES 2014 (V1.2)

Aplicación web instalable (PWA) para Android. Organiza nuestra Liga Máster localmente en el navegador.

## Funciones
- Biblioteca de capturas con selección y menú Compartir de Android.
- Organización de capturas por partido.
- Historial de encuentros con rival, fecha, resultado, formación, estilo e informe táctico.
- Plantilla editable con dorsal, edad, posición, media y observaciones.
- Balance de victorias, empates, derrotas y diferencia de gol.
- Exportación y restauración de copia JSON, incluyendo imágenes.
- Caché de recursos para uso sin conexión después de la primera carga.
- Iconos PWA optimizados en SVG para tamaños de 192 y 512 px, además del icono vectorial adaptable.

## Publicar e instalar en Android
Los archivos ya están cargados en la raíz de este repositorio. No hace falta subirlos otra vez.

1. Abre el repositorio y entra en **Settings → Pages**.
2. En **Build and deployment**, elige **Deploy from a branch** como fuente.
3. Selecciona la rama **main** y la carpeta **/ (root)**; pulsa **Save**.
4. Espera a que GitHub Pages muestre la dirección del sitio. Normalmente será `https://d5053758-droid.github.io/manager-pro-ultra/`.
5. Abre esa dirección en Chrome para Android, toca el menú `⋮` y elige **Instalar aplicación** o **Añadir a pantalla principal**.

Esta es una PWA, no un APK nativo. La instalación crea un icono y abre la app en modo independiente.

## Uso
1. En **Partidos**, registra el próximo encuentro.
2. En **Plantilla**, introduce los datos de los jugadores de PES 2014.
3. En **Capturas**, selecciona el partido activo e importa imágenes desde la galería.
4. Selecciona capturas y compártelas con ChatGPT desde el menú de Android para pedir el análisis táctico.
5. En Inicio, exporta un respaldo periódicamente.

## Privacidad y límites
- No requiere cuenta y no envía los datos a un servidor.
- Partidos, jugadores e imágenes se guardan en IndexedDB local del navegador.
- Compartir imágenes requiere que el usuario elija ChatGPT u otra aplicación desde el menú de Android.
- No se conecta automáticamente a PPSSPP ni analiza el partido por sí sola.
- Borrar los datos del sitio o del navegador puede eliminar el progreso. Usa **Exportar copia** para conservarlo.
- El archivo de respaldo puede ser grande si guardas muchas capturas.
