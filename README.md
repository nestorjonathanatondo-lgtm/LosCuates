LOS CUATES TAMALES - PREPARAR APK EN GITHUB
============================================

ARCHIVOS ZIP LISTOS:
1. los-cuates-GITHUB-APK-JONES-3X.zip (6.9 MB) - Con cambios Jones:
   - Logo JM inicio 3x mÃ¡s grande (30vh)
   - Logo Los Cuates en ticket PDF superior
   - Logo JM footer 3x mÃ¡s grande + "design"
   - Mapa "tamales los cuates" esquina Candela y Chihuahua
   - Eliminado content://...

2. los-cuates-GITHUB-APK-FINAL-ENVIO-30KM.zip (6.9 MB) - TODO LO ANTERIOR + EnvÃ­o $30/km

PASOS PARA GENERAR APK:

1. Ve a github.com y crea nuevo repositorio (ej: los-cuates-tamales)
2. NO marques "Add README", dÃ©jalo vacÃ­o
3. Descomprime el ZIP FINAL-ENVIO-30KM en tu computadora
4. Sube TODOS los archivos a GitHub:
   - index.html
   - los_cuates_final_redondo.png
   - jm_transparent.png
   - sarape.webp
   - manifest.json
   - capacitor.config.json
   - package.json
   - .github/workflows/build-apk.yml
5. Ve a la pestaÃ±a "Actions" en GitHub
6. VerÃ¡s "Build APK Los Cuates" -> click "Run workflow" -> "Run workflow"
7. Espera 3-5 minutos
8. Descarga el APK en "Artifacts" -> Los-Cuates-Tamales-APK

El APK estarÃ¡ en android/app/build/outputs/apk/debug/app-debug.apk

Para instalar en Android, activa "Instalar apps desconocidas" en tu celular.

ENVIO $30/KM:
- Al abrir la app, da click en "Mi ubicaciÃ³n"
- Calcula distancia desde Candela esq Chihuahua hasta ti
- Muestra: EnvÃ­o $90 (3.0 km x $30/km)
- Checkbox "Recoger en tienda" pone envÃ­o $0
