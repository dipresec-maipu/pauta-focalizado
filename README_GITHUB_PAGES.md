# Pauta focalizada PCSP

ID pauta: `PF_PCSP_20260406_20260503`

## Archivos para publicar en GitHub Pages

- `index.html`: visor movil de pauta focalizada.
- `nomina.csv`: nomina local leida por el visor. Debe estar junto al `index.html`.
- `pauta_focalizada_pcsp.docx`: informe Word generado desde plantilla institucional.
- `pauta_focalizada_pcsp.pdf`: version PDF del informe.
- `pauta_focalizada_pcsp.xlsx`: respaldo tabular.
- `puntos_focalizados_pcsp.geojson`: puntos operativos.
- `celdas_criticas_pcsp.geojson`: grilla metodologica.
- `cuadrantes_focalizados_pcsp.geojson`: cuadrantes focalizados.
- `cuadrantes_todos_pcsp.geojson`: todos los cuadrantes con asignacion.
- `mapa_pauta_focalizada_pcsp.png`: mapa usado en el informe.
- `.nojekyll`: evita procesamiento Jekyll en GitHub Pages.

El visor intenta leer primero `nomina.csv` desde este mismo repositorio. Si no puede cargarlo, intenta como respaldo la URL de ArcGIS Online configurada en el script.

El script Python y los insumos brutos no son necesarios para publicar el visor; deben mantenerse en la carpeta de trabajo local/VSC.
