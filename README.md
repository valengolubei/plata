# 💚 PLATA

App personal de gastos en dos monedas (UYU · ARS · USD), con comparador de precios de supermercados.

- **Sin servidores, sin costos**: un solo archivo HTML. Los datos viven en el dispositivo y, opcionalmente, se sincronizan con una planilla privada de Google Sheets.
- **Instalable en el celular**: abrí la URL y usá "Agregar a pantalla de inicio". Funciona offline.
- **Privada**: este repositorio no contiene datos, tokens ni URLs personales. La configuración de sincronización se hace dentro de la app y queda solo en cada dispositivo.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | La app completa |
| `sw.js` | Service worker (funcionamiento offline) |
| `manifest.webmanifest` | Manifiesto PWA (ícono, nombre, pantalla completa) |
