# Landing Page — Nuevo Cliente
# Template: Premium | OCTech Services

## Contexto
Esta carpeta es un scaffold generado desde el template premium de OCTech Services.
El archivo `client.json` contiene los datos del cliente provistos en el cuestionario de diagnóstico.

## Tu tarea al abrir esta sesión
1. Leer `client.json` — ahí están todos los datos del cliente
2. Leer `index.html` — identificar todos los tokens `[TOKEN]`
3. Reemplazar cada token con el dato correspondiente de `client.json`
4. Actualizar `og-image.html` con el nombre y colores del cliente si los hay
5. Confirmar que no quede ningún `[TOKEN]` sin reemplazar en `index.html`

## Reglas
- No modificar `styles.css`, `sections.css`, `app.js`, `assets/image-slot.js` — son el framework compartido
- No cambiar la estructura HTML — solo el contenido dentro de los tokens
- El `og-image.html` se regenera con Chrome headless después (ver checklist)
- Las fotos ya deben estar en `assets/ph/` antes de hacer el preview local

## Referencia de tokens
Ver `delivery/client-swap-checklist.md` en el repo padre para la tabla completa de tokens y el flujo de deployment.

## Stack
- HTML estático + CSS (Hanken Grotesk, design system propio)
- Deployed en Vercel via GitHub (repo público, Hobby plan)
- No hay backend, no hay base de datos, no hay secrets
