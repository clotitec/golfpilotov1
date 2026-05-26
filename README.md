# ⛳ Golf Piloto v1 — Campo de Golf Municipal de Llanes

Demo interactiva del campo de golf de Llanes (18 hoyos, par 72) sobre mapa satélite.
Proyecto **independiente y autocontenido**: HTML estático, sin backend.

## Contenido

| Archivo | Qué es |
|---|---|
| `index.html` | **Plano del campo** (solo lectura): los 18 hoyos superpuestos sobre satélite, numerados, con tee🚩→green⛳, distancias y leyenda con nombre y par. Datos incrustados. |
| `editor.html` | **Editor**: dibuja el área de cada hoyo, marca tee y green, autoguardado en el navegador, exporta `holes.json`. Carga `holes.json` para seguir editando. |
| `holes.json` | Datos maestros de los 18 hoyos: número, par, HCP, nombre, polígono, tee, green. |
| `cartel_llanes_2026.pdf` | Plano oficial del campo (recorrido reorganizado 2026), referencia visual. |

## Uso

- **Ver el campo:** abre `index.html` (o la URL desplegada).
- **Editar la geometría:** abre `editor.html`, pulsa *Cargar holes.json*, ajusta y exporta.

El mapa usa teselas de satélite Esri World Imagery (requieren conexión); todo lo demás
funciona en local con doble clic (`file://`).

## Datos del recorrido

18 hoyos · Par 72 · Campo de Golf Municipal de Llanes (rasa entre Andrín y Cué).
Nombres y par extraídos del cartel oficial 2026; geometría (áreas/tee/green) trazada
sobre satélite.

---
Clotitec · demo piloto reutilizable (base para los campos de golf de Murcia).
