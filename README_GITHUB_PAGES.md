# Pauta Focalizada PCSP - Publicación en GitHub Pages

## Archivo principal

GitHub Pages debe encontrar un archivo llamado `index.html` en la raíz del repositorio o carpeta de publicación.

Este paquete ya contiene:

- `index.html`: visor móvil de la pauta focalizada.
- `.nojekyll`: evita que GitHub Pages intente procesar el sitio con Jekyll.

## Pasos resumidos

1. Crear un repositorio en GitHub, por ejemplo: `pauta-focalizada-pcsp`.
2. Subir `index.html` y `.nojekyll` a la raíz del repositorio.
3. Entrar a `Settings` > `Pages`.
4. En `Build and deployment`, elegir `Deploy from a branch`.
5. Seleccionar rama `main` y carpeta `/root`.
6. Guardar.
7. Esperar algunos minutos y abrir el enlace publicado.

## Actualización de la pauta

Cada vez que generes una nueva pauta:

1. Ejecuta `generar_pauta_focalizada_pcsp.py`.
2. Copia el nuevo `salida_pauta/index.html`.
3. Reemplaza el `index.html` del repositorio.
4. Haz commit / upload.
5. GitHub Pages actualizará el sitio.

## Precaución

Si el repositorio es público, el visor también queda público en internet. No publicar datos sensibles o información operativa que no deba difundirse.
