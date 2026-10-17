# ConectaMap — proyecto Android de prueba

Este proyecto contiene una interfaz Android mínima y un flujo de GitHub Actions para producir una APK debug.

## Estado real
- Interfaz local instalable: sí, cuando la compilación termine correctamente.
- Búsqueda de personas / cuentas: todavía no conectada.
- Solicitudes de amistad: todavía no conectadas.
- Firebase / servidor: todavía no conectado.
- GPS / ubicación compartida: no implementado; la app no solicita permisos de ubicación.

## Cómo obtener la APK desde un teléfono
1. Crea un repositorio nuevo en GitHub llamado `ConectaMap-Android`.
2. Sube el contenido completo de esta carpeta a la rama `main`, manteniendo las carpetas y archivos.
3. Abre la pestaña **Actions** del repositorio.
4. Abre el flujo **Crear APK de ConectaMap** y pulsa **Run workflow** si no empezó automáticamente.
5. Espera a que el trabajo termine con marca verde. En la parte inferior de la ejecución, descarga el artefacto `ConectaMap-apk-debug`.
6. Descomprime el ZIP descargado y abre `app-debug.apk` en cada teléfono. Android puede pedir permiso para instalar desde el navegador/gestor de archivos.

No compartas esta APK como una app de ubicación real. Es solo una primera prueba de interfaz.
