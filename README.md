# surf-dawn-web

La web de **Surf Dawn** en [surfdawn.app](https://surfdawn.app/): la portada (`index.html`, en español,
inglés y portugués con `?lang=`), Soporte, Privacidad y la página de testers de Android. GitHub Pages
la publica desde `main`: un push es la web en un minuto.

- Las imágenes van en `web/`; las arma `tools/web_images.py` del repo de las apps
  (`python3 tools/web_images.py ../surf-dawn-web/web …`).
- Los videos van en `video/`: el lanzamiento (`lanzamiento_16x9_*` para pantallas anchas, `lanzamiento_9x16_*` en el teléfono) y un corto por plataforma (`corto_garmin|apple|android_*`), en es/en/pt, con su portada `.jpg`. Los arma `tienda-video/` del repo de las apps (`montaje.py`, y `montaje.py web` hace estas copias livianas); los másteres y las tomas de Runway quedan fuera de git, en `~/Desktop/SURFDAWN/SurfDawn-tienda/video/`.
- Los manuales en PDF siguen en [`surf-dawn-data/manual/`](https://github.com/scgm11/surf-dawn-data/tree/main/manual),
  donde se publican con cada versión de las apps; la web los enlaza ahí.
- Los datos que bajan las apps (picos, mareas, normales) siguen en
  [`scgm11/surf-dawn-data`](https://github.com/scgm11/surf-dawn-data) y en `scgm11.github.io/surf-dawn-data/`.
  **El dominio va solo en este repo**: puesto en surf-dawn-data o en un sitio `scgm11.github.io`, GitHub
  redirigiría también los datos de los relojes.
- Las páginas viejas de `scgm11.github.io/surf-dawn-data/` redirigen acá (con el idioma y la sección).
- Al cambiar la web, `lastmod` en `sitemap.xml`. Search Console tiene la propiedad de dominio `surfdawn.app` (registro TXT en GoDaddy) y Bing la verifica con `BingSiteAuth.xml`: no borrar ninguno de los dos.
