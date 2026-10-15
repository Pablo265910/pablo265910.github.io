# Mi Página para GitHub Pages

Página web básica lista para publicar con **GitHub Pages**.

## Archivos

- `index.html` — página principal (contenido y estructura).
- `style.css` — estilos de la página.
- `README.md` — este archivo.

## Cómo publicarla

1. Crea un repositorio en GitHub (por ejemplo `mi-pagina`).
2. Sube estos archivos a la rama `main`:
   ```bash
   git init
   git add .
   git commit -m "Primera versión de la página"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/mi-pagina.git
   git push -u origin main
   ```
3. En GitHub entra en **Settings → Pages**.
4. En *Source* selecciona **Deploy from a branch**.
5. Elige la rama **main** y la carpeta **/ (root)**, y guarda.
6. En unos minutos tu página estará en:
   `https://TU-USUARIO.github.io/mi-pagina/`

## Consejo

Si el repositorio se llama `TU-USUARIO.github.io`, la página se publica en
`https://TU-USUARIO.github.io/` (sin subcarpeta).
