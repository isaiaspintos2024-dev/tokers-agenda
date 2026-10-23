# Toker's Agenda 🧉

App de tareas hermana de **Toker's**: semáforo de estados (🟡 en proceso, 🟢 hecha, 🔴 no hecha), calendario, notas con dibujo y fotos, listas, resumen semanal, avisos y copia de seguridad.

## Cómo está armado

- `www/index.html` — toda la app (un solo archivo). También se puede abrir directo en el navegador.
- `assets/` — ícono y pantalla de inicio (el mate en círculo verde).
- `capacitor.config.json` — datos de la app para Android.
- `.github/workflows/build-apk.yml` — GitHub arma el APK solo cada vez que se sube un cambio.

## Dónde está el APK

Cada vez que se compila, el archivo `TokersAgenda.apk` queda en la rama **apk** de este repositorio
y también en la pestaña **Actions** → la última ejecución → *Artifacts*.

## Cambiar el logo

Reemplazá los archivos de `assets/` (por ejemplo, con el duende tomando mate) y subí el cambio:
GitHub vuelve a armar el APK con el ícono nuevo.
