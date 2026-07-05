# 📝 Mis Notas — Notas privadas 100% locales

Aplicación de notas tipo editor de texto (estilo Word) contenida en **un único archivo HTML**. Sin instalación, sin servidor, sin cuenta, sin nube.

## ¿Para qué sirve?

Para escribir y organizar notas con texto enriquecido, imágenes pegadas desde el portapapeles y grabaciones de audio, todo desde el navegador. Descarga `notas.html`, ábrelo con doble clic y empieza a escribir.

## 🔒 Seguridad y privacidad por diseño

La premisa central del proyecto es que **tus notas no salen de tu ordenador**:

- **Cero conexiones**: la aplicación no realiza ninguna petición de red. No hay analítica, ni rastreadores, ni CDNs, ni telemetría. Puedes usarla sin conexión a internet.
- **Almacenamiento local**: todo se guarda en IndexedDB, dentro del perfil de tu navegador, en tu propio disco. Nadie más puede leerlo.
- **Sin cuentas ni contraseñas**: no hay registro, por lo que no hay credenciales que robar ni servidores que puedan sufrir filtraciones.
- **Código auditable**: es un solo archivo HTML legible. Puedes abrirlo con cualquier editor y comprobar exactamente qué hace.

## 🗽 Autonomía: tus datos son tuyos

- **Sin dependencia de terceros**: ninguna empresa puede cerrar el servicio, cambiar el precio o dejarte sin acceso. El archivo es tuyo para siempre.
- **Sin formatos propietarios**: las notas se exportan a JSON abierto y legible. Migrar a otra herramienta siempre será posible.
- **Copias de seguridad bajo tu control**: el botón *Exportar* descarga todas tus notas en un archivo que guardas donde decidas (USB, disco externo, tu propia nube cifrada).
- **Funciona en cualquier sitio**: cualquier navegador moderno, en escritorio, tablet o móvil, con o sin internet.

## ✨ Funcionalidades

- Editor enriquecido: negrita, cursiva, subrayado, títulos, listas, citas
- Pegar imágenes con Ctrl+V o arrastrarlas (compresión automática)
- Grabación de audio con el micrófono, con reproductor integrado
- Guardado automático mientras escribes
- Múltiples notas con búsqueda y panel lateral
- Exportar / importar copia de seguridad en JSON
- Diseño responsive (móvil, tablet y escritorio)

## 🚀 Uso

1. Descarga `notas.html`
2. Ábrelo con doble clic en tu navegador
3. Escribe. Se guarda solo.

## ⚠️ Advertencias

- Las notas viven en el almacenamiento del navegador: si borras los *datos de navegación* de ese navegador, se pierden. **Exporta copias de seguridad periódicamente.**
- Los datos son independientes por navegador y por dispositivo (Chrome y Firefox no comparten notas).
- El micrófono requiere conceder permiso al navegador la primera vez.

## Licencia

MIT — úsalo, modifícalo y compártelo libremente.
