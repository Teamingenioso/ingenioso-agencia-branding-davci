# DAVCI · Manual de uso de marca 2026

Manual de marca de DAVCI Grupo (Oil Services · Construcciones · Logística) en una sola página web.
Hecho por Ingenioso.

## Qué hay aquí

| Archivo | Para qué sirve |
|---|---|
| `index.html` | El manual completo. Un solo archivo, sin dependencias, ~410 KB. |
| `DAVCI-manual-de-marca-vista-previa.pdf` | Vista previa en PDF, 86 láminas 16:9. |
| `FOTOS.md` | Lista de las 33 fotos pendientes, con medidas. |
| `robots.txt` y `noindex` | El manual no se indexa en buscadores. |
| `.nojekyll` | Le dice a GitHub Pages que sirva el archivo tal cual. |

## Publicar con GitHub Pages

1. Crea el repositorio y sube estos archivos:

   ```bash
   git init -b main
   git add .
   git commit -m "Manual de marca DAVCI 2026"
   gh repo create Teamingenioso/davci-manual-de-marca --public --source=. --push
   ```

2. En GitHub: **Settings → Pages → Build and deployment**.
   Source: **Deploy from a branch**. Branch: **main**, carpeta **/ (root)**. Guarda.
3. En uno o dos minutos queda en:
   `https://teamingenioso.github.io/davci-manual-de-marca/`

Notas:

- Pages gratis solo funciona con repositorio **público**. Para dejarlo privado hace falta un plan de pago de GitHub.
- El enlace sigue siendo público para quien lo tenga, aunque no salga en buscadores.
- Para que sí lo indexen, borra `robots.txt` y la línea `<meta name="robots" ...>` de `index.html`.

## Actualizar

Cambia `index.html`, haz commit y push. Pages se actualiza solo.

## Notas del contenido

- Los nombres de usuario, cifras y URLs de los mockups son ejemplos. La app es un concepto.
- Akira Expanded se usa con licencia demo. Antes de producir, comprar la licencia: https://typologic.gumroad.com/l/akiraexpanded
- Neue Helvetica: https://myfonts.com/fonts/linotype/neue-helvetica
- La misión, la visión y el perfil de persona son borradores. Hugo debe validarlos.
