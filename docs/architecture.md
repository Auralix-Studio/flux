# Arquitectura · Flux

## Descubrimiento por etapas

El escáner prueba destinos conocidos, puertos habituales y después amplía la búsqueda sobre hosts activos. Valida respuestas de video y presenta candidatos con información de la emisión.

## Reproducción con media_kit

El motor basado en libmpv gestiona formatos, pistas de audio, subtítulos y búsqueda temporal. Flux añade controles y seguimiento de cambios en la emisión.

## Navegador y TV

El navegador detecta candidatos de video y los comprueba al seleccionarlos. Las integraciones de TV coordinan descubrimiento, autorización y solicitudes de apertura o reproducción.

## Límites de red

El descubrimiento de streams aplica controles de direcciones privadas. Esto no significa que el navegador integrado o una URL web seleccionada funcionen sin Internet. En Android TV, el receptor HTTP requiere la aplicación abierta.
