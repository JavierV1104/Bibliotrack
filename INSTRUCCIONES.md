# Cómo instalar Bibliotrack en iPhone o iPad

## Opción 1 — Publicar con GitHub Pages (gratis, recomendado)

1. Crea una cuenta gratuita en https://github.com
2. Crea un repositorio nuevo llamado `bibliotrack`
3. Sube los archivos: `index.html`, `manifest.json`, `icon-192.svg`, `icon-512.svg`
4. Ve a Settings → Pages → Branch: main → Save
5. Tu app estará en: `https://TU-USUARIO.github.io/bibliotrack`
6. Abre esa URL en Safari desde el iPhone/iPad
7. Toca el botón compartir (□↑) → "Añadir a pantalla de inicio"
8. ¡Listo! Bibliotrack aparecerá como app nativa 🎉

## Opción 2 — Servidor local (para probar en casa)

Si tienes Python instalado en tu Mac/PC:
```
cd carpeta-bibliotrack
python3 -m http.server 8080
```
Luego en el iPhone/iPad (misma red WiFi): `http://IP-DE-TU-COMPU:8080`

## Notas importantes

- Los datos se guardan en el dispositivo (localStorage del navegador Safari)
- La búsqueda de libros requiere conexión a internet (usa Open Library)
- Para no perder los datos, no borres los datos del sitio en Safari
- Funciona offline una vez instalada (sin búsqueda, que necesita internet)
