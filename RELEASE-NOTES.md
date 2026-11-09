# Anira 0.13.30

## 0.13.30 — Reproducción más robusta y Android TV

- Mejora la recuperación del reproductor cuando una fuente tarda en preparar el video o no llega a emitir los primeros fotogramas.
- Evita interrumpir una fuente que ya está preparada mientras se comprueba una alternativa.
- Amplía el margen de preparación y añade vigilancia para detectar reproducciones preparadas que no llegan a mostrar imagen.
- Incluye ajustes de navegación y compatibilidad de interfaz para Android TV.
- Conserva el paquete Android y el certificado de firma para actualizar instalaciones existentes.
- Versión Android: 0.13.30 (versionCode 72).

## Historial anterior

# Anira 0.13.12

## 0.13.12 — Actualizaciones dentro de Anira

- Añade una tarjeta integrada para avisar cuando exista una nueva versión estable publicada en el repositorio oficial.
- Comprueba la disponibilidad de nuevas versiones al iniciar y reanudar la aplicación, con intervalo de comprobación de seis horas.
- La tarjeta permite abrir la descarga oficial o posponer el aviso sin bloquear la navegación.
- Evita mostrar el aviso encima del reproductor, el lector inmersivo y el editor de avatar.
- Valida que la descarga proceda de las publicaciones oficiales de Salvador9797/Anira.
- Actualiza la versión Android a 0.13.12 (versionCode 54).
- Conserva el paquete y el certificado de firma para permitir la actualización sobre instalaciones existentes.

Esta entrega reúne las mejoras publicadas desde 0.8.10 y añade la corrección del seguimiento de lectura de manhwa.

## 0.13.4 — Corrección de capítulos leídos

- Corrige el momento en que se registra un capítulo como leído: ahora se marca cuando la última página cargada entra en la zona visible de lectura.
- Comprueba que la marca se haya guardado antes de evitar nuevos intentos.
- Añade una prueba de regresión para verificar el registro y la recuperación del estado.
- No modifica el reproductor de anime.

## 0.13.3 — Progreso y navegación del lector

- «Seguir leyendo» se presenta en un carrusel horizontal.
- Cada capítulo conserva su estado de leído por manhwa y perfil.
- La marca de lectura se registra al alcanzar la última página.
- El lector permite ir al capítulo anterior y al siguiente, respetando los límites de la serie.
- El progreso y las marcas se incluyen en la biblioteca y en los respaldos compatibles.

## 0.13.2 — Biblioteca de anime y manhwa

- Biblioteca incorpora un selector independiente Anime/Manhwa.
- Distingue títulos guardados de lecturas recientes.
- La búsqueda de Biblioteca filtra los registros locales sin cargar el catálogo remoto.
- La navegación desde una ficha o el lector conserva el origen y regresa a Biblioteca.
- La preferencia de tipo de biblioteca se guarda por perfil y se incluye en los respaldos.
- Quitar un manhwa de guardados no elimina su progreso de lectura.

## 0.13.1 — Catálogo y lector de manhwa

- Índice de manhwa ampliado con opción para mostrar más resultados.
- Búsqueda por palabras y sin distinguir tildes sobre los títulos cargados.
- Secciones de Continuar leyendo, capítulos recientes, manhwa recientes, recomendaciones y populares cuando la fuente aporta esos datos.
- Fichas con títulos y portadas canónicos.
- Capítulos y páginas consultados desde las respuestas públicas de la fuente, incluidos números decimales.
- Se descartan rutas de relleno y se informa de bloqueos del CDN sin marcar falsamente una lectura como completada.

## 0.13.0 — Primera versión del lector

- Nueva sección Leer, con navegación entre descubrimiento, ficha y capítulos.
- Lector vertical con restauración de página y posición.
- Progreso por perfil y controles de lectura ocultables.
- Biblioteca de lecturas y respaldo de datos.
- La integración con Olympus consulta únicamente páginas públicas; no evade CAPTCHA ni restricciones de acceso.

## 0.12.2 — Navegación, perfiles, reproducción y respaldos

- Barra inferior y cabecera reorganizadas, con mejor respuesta táctil y navegación de regreso.
- Ajustes reorganizados y conservación de búsqueda y desplazamiento entre pestañas ya cargadas.
- Mejoras en tarjetas, portadas, miniaturas, accesibilidad, foco y reducción de movimiento.
- Nueve avatares y selección de foto, con encuadre y almacenamiento privado.
- Cuatro colores de acento por perfil y acceso al grupo de Telegram.
- Correcciones de posición de reproducción, transición al siguiente episodio y modo imagen en imagen.
- Mejor almacenamiento y conciliación del progreso por perfil.
- Caché del catálogo, menos solicitudes duplicadas y cancelación de consultas innecesarias.
- Estados de carga, error, vacío y reintento más claros.
- Exportación e importación de todos los perfiles, con nombres, avatares, fotos, listas, progreso, preferencias y subtítulos.
- Protección opcional de respaldos mediante contraseña.
- Validaciones adicionales de conexiones, redirecciones, respuestas externas y operaciones entre perfiles.

## 0.8.10 — Catálogo y reproducción

- Catálogo unificado de AnimeAV1 y TioAnime, con deduplicación y prioridad de AnimeAV1.
- Selección automática de proveedores y recuerdo del servidor por anime e idioma.
- Reproducción de enlaces HLS sin extensión y respaldo automático conservando el progreso.
- Carruseles de animes recientes, recomendaciones y títulos con doblaje confirmado.
- Consulta automática de temporadas y continuidad.
- Consulta del siguiente episodio cerca del final, sin descargar el video.
- Correcciones para conservar la posición al volver de segundo plano y evitar controles superpuestos.
- Portadas verticales completas sin recortar personajes.
- El siguiente episodio se inicia en horizontal y a pantalla completa.

## Identificación y compatibilidad

- Nombre: Anira.
- Paquete Android: `app.anira.anime`.
- Versión: `0.13.12`.
- Código: `54`.
- Android mínimo: 8.0 (API 26).

Instala la actualización encima de la versión anterior para conservar los datos locales. No desinstales Anira antes de actualizar.

## Verificación y límites

La validación automatizada cubre pruebas de lógica, frontend, código nativo y empaquetado Android. La APK distribuida debe corresponder a esta versión y conservar el certificado de firma anterior. El funcionamiento visual y la disponibilidad de catálogo, imágenes, capítulos, idiomas y reproducción también dependen de las fuentes externas y del dispositivo; no se garantiza disponibilidad universal.

