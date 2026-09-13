# BlackoutUO — descargas

Este repositorio solo aloja lo que el launcher descarga. No tiene código.

## Instalar

1. Descarga el último `BlackoutLauncher.exe` de la release `launcher-v…` más reciente.
2. Windows mostrará «Windows protegió tu PC» porque el ejecutable no está firmado durante la
   Alpha. Pulsa **Más información** y luego **Ejecutar de todas formas**.
3. Elige la carpeta (o deja la que propone) y pulsa **Continuar**. El launcher descarga el cliente
   y los datos (~1,2 GB la primera vez) y a partir de ahí solo lo que cambie.
4. **Jugar.**

Si algo falla, pulsa **Abrir log** y adjunta `launcher.log` en el reporte.

## Para el administrador

`manifest.json` y `manifest.sig` en `main` son lo que el launcher lee; los assets de las releases
`data-vN`, `client-vX.Y.Z` y `launcher-vX.Y.Z` son inmutables. Se publican con `tools/Publish`
del repo `blackout-launcher`. Este repositorio **no se pone en privado**: dejaría fuera a todos los
launchers distribuidos.
