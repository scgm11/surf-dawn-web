# surf-dawn-web

La web de **Surf Dawn** en [surfdawn.app](https://surfdawn.app/): la portada (`index.html`, en español,
inglés y portugués con `?lang=`), Soporte, Privacidad y la página de testers de Android. GitHub Pages
la publica desde `main`: un push es la web en un minuto.

- Las imágenes van en `web/`; las arma `tools/web_images.py` del repo de las apps
  (`python3 tools/web_images.py ../surf-dawn-web/web …`).
- Los manuales en PDF siguen en [`surf-dawn-data/manual/`](https://github.com/scgm11/surf-dawn-data/tree/main/manual),
  donde se publican con cada versión de las apps; la web los enlaza ahí.
- Los datos que bajan las apps (picos, mareas, normales) siguen en
  [`scgm11/surf-dawn-data`](https://github.com/scgm11/surf-dawn-data) y en `scgm11.github.io/surf-dawn-data/`.
  **El dominio va solo en este repo**: puesto en surf-dawn-data o en un sitio `scgm11.github.io`, GitHub
  redirigiría también los datos de los relojes.
- Las páginas viejas de `scgm11.github.io/surf-dawn-data/` redirigen acá (con el idioma y la sección).
- Al cambiar la web, `lastmod` en `sitemap.xml`. Search Console tiene la propiedad de dominio `surfdawn.app` (registro TXT en GoDaddy) y Bing la verifica con `BingSiteAuth.xml`: no borrar ninguno de los dos.
