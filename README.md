# SVBLIME · Web nueva

- `publicar/`: la web lista para ser la página principal (sin contraseña, visible para Google).
- `rediseno/`: la misma web con contraseña (**svblime**), para revisiones privadas en svblime.cl/rediseno/.

## Publicar como página principal

1. En GitHub: botón verde **Code** → **Download ZIP** y descomprimir.
2. En FileZilla, entrar a `public_html` (la raíz de svblime.cl).
3. Abrir la carpeta `publicar` del ZIP, seleccionar **todo lo que hay adentro** y arrastrarlo a `public_html`.
   Cuando pregunte, elegir **Sobrescribir** y marcar "usar siempre esta acción".
4. **No borrar nada** del hosting: las propuestas (`propuesta`, `propuestasuv`, `backtojungle`) y el `.htaccess` se quedan como están.
5. Abrir https://svblime.cl y recargar con Ctrl+Shift+R (en Mac: Cmd+Shift+R).
