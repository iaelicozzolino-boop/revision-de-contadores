# Revisión de contadores

App de un solo `index.html`, sin build. Se publica con GitHub Pages desde `main`: https://iaelicozzolino-boop.github.io/revision-de-contadores/

- Modo recepción (`#recepcion`) y modo marinero. Datos en `localStorage` (`recepcion_<fecha>`, `revision_<fecha>`, `revision_mailTo`), solo en cada navegador.
- La recepción envía la lista por WhatsApp o Gmail como enlace `?lista=<fecha>-<amarres>`. Se siguen aceptando los enlaces antiguos `#r-...`.
- PDF con jsPDF y jspdf-autotable desde jsDelivr.
- La versión visible está en `.app-version` (ahora v1.6). Subirla en cada cambio.
- Enlazada desde el repo MarinaIbizaApps.
