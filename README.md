# elsalvador-migration-ide

Infraestructura de Datos Espaciales y visualizador WebSIG para el análisis de migración interna y emigración internacional en El Salvador.

Este proyecto se creó con QGIS y `qgis2web` para generar un visor web cartográfico interactivo, apoyado en datos territoriales y socioeconómicos relacionados con el Censo 2024 del Banco Central de Reserva de El Salvador (BCR).

## Estructura del proyecto

- `index.html` — página principal del visor web.
- `layers/` — datos geoespaciales exportados en formato JavaScript.
- `resources/` — bibliotecas de cliente, estilos y utilidades usadas por el mapa.
- `styles/` — reglas de estilo generadas para cada capa del mapa.
- `images/` — iconos y recursos gráficos usados en la aplicación.
- `webfonts/` — fuentes web necesarias para la presentación.

## Cómo usar

1. Abre `index.html` en un navegador web moderno.
2. Asegúrate de que los archivos `layers/`, `resources/`, `styles/` y `webfonts/` estén presentes en el mismo directorio que `index.html`.
3. El visor debería cargarse localmente sin necesidad de servidor adicional, aunque para algunas configuraciones puede ser preferible usar un servidor estático local.

## Requisitos

- Navegador web compatible con JavaScript.
- No se requiere compilación adicional si los archivos ya están generados.

## URL

- https://davidparrillas.github.io/elsalvador-migration-ide/

## Licencia

Proyecto con licencia según el archivo `LICENSE`.
