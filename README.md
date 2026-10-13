# Etiqueta Scanner V3 NYX

- Pantalla principal: listado de registros SQLite y exportación CSV.
- Escáner en pantalla secundaria, interfaz vertical fija.
- Pitido de éxito al insertar HU nuevo, tono distinto si HU duplicado y tono de error.
- Consulta inmediata de HU duplicado, con fecha de registro.
- OCR nativo y respaldo de luminancia con contraste cada 4 fotogramas insuficientes.
- No elimina ni migra la BD previa: usa `etiquetas_v1.db` y el mismo applicationId.
- `main.yml` incluido.

Subir **el contenido** de este ZIP a la raíz de un repositorio nuevo.
No mezclar archivos de versiones anteriores.

**Nota:** sin prueba física en NYX no se garantiza el rendimiento del OCR; la rotación de interfaz queda fija y ML Kit recibe la rotación de CameraX.
