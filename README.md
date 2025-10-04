# Repositorio Informático

Web personal de un profesor de ciclos de informática con estilo minimalista en texto plano.

Sitio construido con Jekyll y alojado en GitHub Pages.

## Estructura

- `_layouts/` - Plantillas HTML
- `_posts/` - Publicaciones en formato Markdown
- `index.html` - Página principal
- `archivo.html` - Listado completo de publicaciones

## Cómo añadir una nueva entrada

1. Clonar el repositorio:
   ```bash
   git clone git@github.com:repositorioinformatico/repositorioinformatico.github.io.git
   ```

2. Crear un nuevo archivo en `_posts/` con el formato `YYYY-MM-DD-titulo.md`:
   ```bash
   cd repositorioinformatico.github.io
   nano _posts/2025-10-04-mi-nueva-nota.md
   ```

3. Añadir el front matter y contenido:
   ```markdown
   ---
   layout: post
   title: "Título de mi nota"
   date: 2025-10-04
   ---

   Contenido de la nota en Markdown...
   ```

4. Guardar, hacer commit y push:
   ```bash
   git add _posts/2025-10-04-mi-nueva-nota.md
   git commit -m "Nueva entrada: mi nueva nota"
   git push
   ```

5. Esperar 1-2 minutos y la entrada aparecerá automáticamente en https://repositorioinformatico.github.io

## Probarlo localmente (opcional)

```bash
bundle install
bundle exec jekyll serve
```

Visitar http://localhost:4000
