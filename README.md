# Dashboard Transacciones Open Loop

Tablero web de transacciones Open Loop (STG), publicado con GitHub Pages.

- **Datos:** Google Sheets (hoja USOS), procesados por Google Apps Script.
- **Página:** `index.html` consulta la API de Apps Script configurada en `config.js`.
- **Funciones:** indicadores generales, tendencia mensual, comportamiento horario, consulta diaria por año y mes, y descarga en PDF.

## Archivos

| Archivo | Descripción |
|---|---|
| `index.html` | Página del tablero |
| `config.js` | URL de la Aplicación web de Apps Script (termina en `/exec`) |
| `logo.js` | Logo de STG en base64 |

## Actualizar la conexión

Edita `config.js` y reemplaza el valor de `API_URL` por la URL de la implementación de Apps Script.
