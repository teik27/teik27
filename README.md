# IPTV Netflix — Android / Android TV

Proyecto Android que empaqueta la interfaz IPTV original y delega la reproducción en Android Media3 (ExoPlayer).

## Compilar

1. Sube el contenido de esta carpeta a la raíz de un repositorio GitHub (incluida la carpeta `.github`).
2. Abre **Actions → Compilar IPTV Netflix APK → Run workflow**.
3. Descarga `app-debug.apk` desde el artefacto `IPTV-Netflix-APK` o desde la Release `latest`.

## Reproducción

- Android usa Media3/ExoPlayer para HLS (`.m3u8`) y streams MPEG-TS/progresivos.
- Reintenta automáticamente hasta cinco veces ante errores del reproductor.
- El botón VLC de la interfaz sigue disponible como alternativa externa.
- Las listas y preferencias siguen guardándose localmente en el dispositivo.

La estabilidad también depende del servidor IPTV, la red, el formato de emisión y los límites del proveedor. El proyecto no incluye ni almacena credenciales ni listas IPTV.
