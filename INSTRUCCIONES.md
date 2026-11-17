# Prototipo Zebra ZD421 – GitHub Pages (prueba)

**No requiere Python, Node.js ni PowerShell.**

IMPORTANTE: GitHub Pages publica una web visible en Internet. Usa solo datos ficticios. No incluyas archivos del inventario, IDs de productos reales, información de Codelco ni credenciales.

## Archivos
- `index.html` — Interfaz de prueba.
- `BrowserPrint.min.js` — **NO INCLUIDO**. Obtén esta biblioteca oficial desde la instalación de Zebra Browser Print o el sitio oficial de Zebra. Debe quedar en la misma carpeta que index.html. Antes de publicar la biblioteca en un repositorio público, verifica sus condiciones de licencia/distribución o consulta con TI.

## Publicar desde GitHub sin terminal
1. Inicia sesión en github.com con una cuenta personal autorizada.
2. Crea un repositorio nuevo, por ejemplo `zebra-etiquetas-demo`, de prueba; NO en una organización de trabajo sin permiso.
3. En el repositorio, elige **Add file → Upload files** y sube `index.html` y, solo si está autorizado, `BrowserPrint.min.js`. Confirma el commit.
4. En **Settings → Pages → Build and deployment**, selecciona **Deploy from a branch**, rama **main**, carpeta **/(root)**, y guarda.
5. Abre la URL publicada desde Edge en el computador donde Zebra Browser Print está instalado y funcionando.
6. Comprueba que Browser Print indique la impresora predeterminada. Si pide permiso, permite únicamente tu propio sitio.
7. Prueba primero con `PRODUCTO DE PRUEBA` y `1234567` y pulsa imprimir una vez.

## Si no puedes publicar la biblioteca
No cambies políticas de seguridad de Windows ni subas archivos propietarios a un repositorio público sin permiso. Solicita a TI un sitio de pruebas interno HTTPS donde se pueda alojar la página y la biblioteca oficial.

## Avisos
- Publicar una página en GitHub Pages no conecta con Excel Online ni SharePoint.
- La aplicación solo envía ZPL a la impresora local a través de Zebra Browser Print.
- La vista previa de barras es decorativa: el código real lo dibuja la Zebra con ZPL.
