# Portafolio Data Analytics

Sitio estatico simple para publicar proyectos de Power BI, SQL y analitica de datos con GitHub Pages.

## Estructura

- `index.html`: portada del portafolio.
- `styles.css`: estilos generales.
- `projects/powerbi-dax-modelado.html`: primer caso documentado.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub, por ejemplo `data-analytics-portfolio`.
2. Sube el contenido de esta carpeta al repositorio.
3. En GitHub, entra a `Settings > Pages`.
4. En `Build and deployment`, selecciona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guarda los cambios.

GitHub publicara el sitio en una URL similar a:

```text
https://TU_USUARIO.github.io/data-analytics-portfolio/
```

## Antes de publicar

- Cambia `tu_correo@example.com` por tu correo real.
- Actualiza los enlaces de LinkedIn y GitHub.
- Reemplaza los placeholders de capturas con imagenes reales del reporte.
- Agrega enlaces de Power BI Publish to Web solo si los datos son publicos o ficticios.

## Agregar otro proyecto

1. Copia `projects/powerbi-dax-modelado.html`.
2. Cambia el nombre del archivo.
3. Edita titulo, descripcion, capturas, medidas y aprendizajes.
4. Agrega una nueva tarjeta en `index.html`.
