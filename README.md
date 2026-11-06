# INKHAUS · Booking · Publicación estática

Demo ficticia de VYB con portfolio generado con IA y artistas ficticios. No se realizan reservas reales mientras falte la cuenta propia de Setmore. No hay contactos inventados. Ver RECURSOS.md para procedencia.

Extraer el ZIP. Abrir PowerShell en la carpeta extraída y ejecutar:

```powershell
py -m http.server 8099 --bind 127.0.0.1
```

Abrir http://127.0.0.1:8099/ y detener con Ctrl+C. No ejecutar desde dentro de la vista comprimida del ZIP.

Para GitHub Pages subir index.html, styles.css, app.js, config.js, assets/ y .nojekyll directamente a la raíz del repositorio. Settings → Pages → Deploy from a branch → rama correcta → / (root). Las rutas relativas admiten /nombre-repositorio/. No hay instalación npm ni compilación para este paquete.

No editar permanentemente esta salida: personalizar clients/<id>/client.json y regenerar desde el proyecto VYB_TATTOO_STUDIO.zip. Incluye allí guía completa para crear clientes, conectar Setmore y ejecutar pruebas. No se publicó ni modificó automáticamente ningún repositorio.
