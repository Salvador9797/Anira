# Anira 0.6.2

## Correcciones

- Cambiar SUB/DUB sustituye automáticamente la reproducción tras haberla iniciado, sin volver a pulsar Reproducir. Captura la posición y pausa actuales y conserva pantalla completa y orientación. La fuente anterior se detiene y se descartan sus callbacks pendientes. También se puede cambiar el idioma desde las preferencias del reproductor.
- Acceso OP/ED siempre visible al mostrar los controles. Durante un segmento compatible pasa a «Saltar introducción» o «Saltar créditos», sin segundos. Fuera de esos intervalos explica la disponibilidad de tiempos y permite reintentar si corresponde.
- Los fallos de consulta ya no borran marcas válidas. Caché independiente por episodio, idioma y duración; resultados parciales se combinan y las consultas fallidas se reintentan hasta dos veces. Las respuestas de sesiones anteriores se descartan. Se conserva la comprobación conservadora de duración para no inventar saltos.

Mismo paquete y firma; versión 0.6.2, código 16. Instala encima de la anterior para conservar datos.

Verificación: compilación, firma v2/v3, flujo original y minificado, regresión SUB/DUB, identidad del episodio y conservación de intervalos. No se dispuso de Android físico para comprobar las transiciones reales. La disponibilidad y exactitud de los tiempos comunitarios y de las fuentes externas puede variar. Las capturas existentes son de 0.5.0.
