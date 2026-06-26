# ⚡ ElecCAD — Editor Web de Tableros Eléctricos

Editor CAD fotorrealista para esquemas eléctricos de baja tensión (BT). Standalone HTML, sin instalación, doble-clic para abrir.

## 🚀 Demo rápida

Abre `eleccad.html` en cualquier navegador moderno.

## ✨ Características

- **Editor drag & drop** — arrastra componentes al lienzo, conecta con cables
- **Componentes fotorrealistas** con gradientes SVG multicapa, sombras y tornillos metalizados
- **4 marcas industriales**: Schneider (verde), ABB (negro), CHINT (azul), TYMF (rojo)
- **Estándar IEC/REBT** — colores de cable: L1 rojo, N azul, PE verde, L2 marrón, L3 gris
- **Export PNG 2×** resolución alta
- **Sin dependencias** — solo Konva.js 9.3.6 via CDN

## 🧰 Componentes incluidos

| Categoría | Componentes |
|---|---|
| MCBs | Schneider 1/2/3P · ABB 1/2/3P · CHINT 1/2/3P · TYMF 1/2/3P |
| Protecciones | Diferencial 2P/4P · ICP General · SPD sobretensión |
| Panel | Carril DIN · Carril Omega · Peine monofásico · Módulo ciego |
| Bus bars | L1 morado · Neutro azul · PE verde (columna) |
| Terminales | Regleta fase (verde/azul/amarillo) · Regleta PE |
| Control | Piloto verde/rojo · LIGA/DESL · Parada emergencia |
| Cableado | Canaleta corrugada negra |
| Cables | L1 rojo · N azul · PE verde · L2 marrón · L3 gris · negro |

## ⌨️ Atajos de teclado

| Tecla | Acción |
|---|---|
| `S` | Herramienta Seleccionar |
| `W` | Herramienta Cable |
| `D` | Herramienta Borrar |
| `G` | Toggle grid |
| `ESC` | Cancelar / Deseleccionar |
| `DEL` | Eliminar seleccionado |
| Doble-clic | Finalizar cable |
| Clic derecho | Cancelar cable |

## 📐 Arquitectura

```
eleccad.html          # App completa (standalone, ~700 líneas)
BIBLIOTECA.md         # Catálogo de componentes + fuentes libres
```

Tecnologías: HTML5 Canvas · [Konva.js 9.3.6](https://konvajs.org) · SVG inline

## 🗺️ Roadmap

- [ ] Guardar/cargar proyecto (JSON)
- [ ] Snap a carril DIN
- [ ] Zoom/pan con rueda del ratón
- [ ] MCCB caja moldeada grande
- [ ] Medidor digital con display
- [ ] Motor eléctrico 3F
- [ ] Cam switch 0-1-2
- [ ] Tablero cabinet completo

## 📚 Biblioteca Canva

Los componentes visuales están basados en el pack [teslamatic.education](https://canva.link/d7z5gau2d8bi8ln) — 14 páginas con componentes reales de Schneider, ABB, CHINT, TYMF + ejemplos de tableros completos. Ver `BIBLIOTECA.md`.

## 🪪 Licencia

MIT — libre para uso comercial y educativo.
