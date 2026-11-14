# SVBLIME · Web completa

- `public_html/`: **todo el sitio svblime.cl listo para subir**: la web nueva (sin contraseña, visible para Google),
  sus páginas de servicio, preguntas frecuentes y contacto, más las propuestas `propuesta`, `propuestasuv` y `backtojungle`
  (con sus contraseñas de siempre), el ícono y el `robots.txt`.
- `rediseno/`: la misma web con contraseña (**svblime**), solo para revisiones privadas.

## Subirla al hosting

1. En GitHub: botón verde **Code** → **Download ZIP** y descomprimir.
2. En FileZilla, entrar a `public_html` en el servidor.
3. Abrir la carpeta `public_html` del ZIP, seleccionar **todo lo que hay adentro** y arrastrarlo al `public_html` del servidor.
   Elegir **Sobrescribir** y marcar "usar siempre esta acción".
4. No borrar el `.htaccess` del servidor (este paquete no lo trae a propósito).
5. Abrir https://svblime.cl y recargar con Ctrl+Shift+R (en Mac: Cmd+Shift+R).

Archivos de la web antigua que quedan en el servidor y ya no se usan (se pueden borrar después de revisar que todo funciona):
`styles.css`, `hero.mp4`, `hero-poster.jpg`, `assets/`, `brands/`, `team/`, `tokens/`, `vendor/`, `work/`, `js/app.min.js`, `servicios/pagina.css`.
