# boda-fiesta

Invitación digital de boda (HTML + CSS + JS) desplegada en Netlify, con integración de Google Apps Script para RSVP y sugerencias de canciones.

## Nota sobre links personalizados desde Google Sheets

Para soportar nombres con `&` (por ejemplo, `Mica & Jorge`) en el parámetro `nombre`, generá la URL codificando ese valor como `%26`.

Ejemplo sugerido en Google Sheets:

```gs
="https://TU-SITIO.netlify.app/?nombre=" & ENCODEURL(A2) & "&personas=" & B2
```

De esta forma el nombre llega correctamente en la URL y evita cortes por el separador `&` de query params.
