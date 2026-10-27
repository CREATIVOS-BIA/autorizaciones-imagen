# Autorizaciones de imagen — página de firma

Página pública donde talento, colaboradores y clientes firman la autorización de uso de imagen de Bia:
https://creativos-bia.github.io/autorizaciones-imagen/

Con `?proyecto=Nombre%20del%20proyecto` al final, el proyecto sale ya escrito.

Esta página solo muestra la carta y envía la firma. Todo lo demás lo hace el Apps Script
"Autorizaciones de Imagen - Bia" (copia del código en Drive: `AUV/25. Autorizaciones de Imagen/04_Registro/Automatizacion`):
el texto de la carta (plantilla en Google Docs), el PDF membreteado, la carpeta en Drive, el registro y el aviso en Slack.

Está fuera de Google para que abra con cualquier cuenta: las páginas de Apps Script fallan
("No se pudo abrir el archivo en este momento") cuando la persona tiene varias cuentas de Google abiertas.

- Cambiar el texto de la carta: en el Google Doc de la plantilla, no aquí.
- Cambiar el membrete de la página: reemplazar las imágenes de `img/`.
- Si se cambia la implementación del Apps Script, actualizar `API` en `index.html`.
