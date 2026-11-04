# Manager Pro Ultra – PES 2014 (V1.1)

Aplicación web instalable (PWA) para Android. Organiza la Liga Máster localmente en el navegador.

## Funciones de V1.1
- Biblioteca de capturas con selección múltiple y menú Compartir de Android.
- Organización de capturas por partido.
- Historial de partidos con rival, fecha, resultado, formación, estilo e informe táctico.
- Plantilla editable con dorsal, edad, posición, media y observaciones.
- Balance de victorias, empates, derrotas y diferencia de gol.
- Exportación y restauración de respaldo JSON, incluyendo capturas.
- Caché de recursos para uso offline después de la primera carga.

## Instalación en Android
Esta es una PWA, no un APK. Para instalarla como aplicación debe estar publicada en un origen HTTPS.

1. Sube el contenido de esta carpeta a la raíz de un repositorio nuevo de GitHub.
2. En el repositorio abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**, elige `main` y `/ (root)`, y guarda.
4. Cuando GitHub Pages publique el sitio, abre la URL HTTPS en Chrome para Android.
5. Usa el menú `⋮` y selecciona **Instalar aplicación** o **Añadir a pantalla principal**. Los nombres pueden variar según la versión del navegador.

## Uso
1. En **Partidos**, registra el encuentro o la próxima jornada.
2. En **Plantilla**, registra los jugadores según los datos que muestra PES 2014.
3. En **Capturas**, importa imágenes mientras tienes un partido activo.
4. Selecciona capturas y comparte con ChatGPT desde el menú de Android para pedir el análisis.
5. En Inicio, exporta un respaldo periódicamente.

## Privacidad y límites
- La aplicación no requiere cuenta ni envía los datos a ningún servidor.
- Partidos, jugadores e imágenes se guardan en IndexedDB local del navegador.
- Compartir imágenes requiere que el usuario elija una aplicación en el menú de Android.
- La app no se conecta automáticamente a PPSSPP ni analiza el partido por sí sola.
- Si borras los datos del sitio o del navegador, puedes perder la información local. Usa **Exportar copia** para conservarla.
- El respaldo JSON puede ser grande si acumulas muchas capturas.
