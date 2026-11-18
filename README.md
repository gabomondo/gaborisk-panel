# GaboRisk Panel

Panel gratuito para el Chart Trader de NinjaTrader 8: riesgo y profit fijos en dólares, SL y TP automáticos, break-even, trailing y límite diario.

Parte de [gabomondo](https://gabomondo.com) · Trading sin humo.

## Descarga

👉 **[gabomondo.com/gaborisk](https://gabomondo.com/gaborisk/)** — ahí está el manual en PDF, capturas y las instrucciones de instalación.

O directo desde este repo: [Releases](https://github.com/gabomondo/gaborisk-panel/releases) → `GaboRisk-v2.0-NT8.zip`.

## Qué incluye

- `GaboRiskPanelV2.cs` — el AddOn (panel): riesgo/profit en USD, break-even, trailing, límite diario.
- `GaboRiskLines.cs` — el indicador: dibuja las zonas roja y verde, y permite arrastrarlas.

## Instalación

**Opción recomendada:** descargá el `.zip` del último [Release](https://github.com/gabomondo/gaborisk-panel/releases) y en NinjaTrader: `Tools > Import > NinjaScript Add-On` (en español, Herramientas > Importar).

**Manual:** copiá el código de cada `.cs` en `New > NinjaScript Editor` (AddOn para el panel, Indicator para las líneas) y compilá con F5.

Detalle completo, campo por campo, en el manual (PDF) de [gabomondo.com/gaborisk](https://gabomondo.com/gaborisk/).

## Aviso

Herramienta de gestión personal, con fines educativos. No da señales ni dice cuándo entrar. No constituye asesoramiento financiero ni de inversión y se ofrece "tal cual", sin garantías. Operar futuros implica riesgo de pérdida. Probado en NinjaTrader 8.1.9 (64 bits) con MNQ en cuenta de simulación; no probado con cuentas reales ni en otras versiones.

## Licencia

Código fuente abierto, de uso libre. Sin garantías (ver aviso arriba).
