# Material de marketing — Jaimez Grocery

Piezas de publicidad impresa para la tienda. Diseño cálido de mercado mexicano
(verde / rojo / blanco), bilingüe ES/EN, con las fotos reales del negocio y un
código QR que abre **https://jaimezgrocery.com/**.

## Archivos listos para imprimir (PDF)

| Archivo | Qué es | Tamaño | Para Staples |
|---|---|---|---|
| `Jaimez-Triptico.pdf` | Tríptico, 2 páginas (exterior + interior) | **11 × 8.5"** | "Brochures" · Full Bleed · **Gloss** |
| `Jaimez-Tarjeta-IMPRIMIR.pdf` | Tarjeta, 2 páginas (frente + reverso) | **3.5 × 2"** | "Business Cards" · 14 pt · doble cara |
| `Jaimez-Tarjeta-FRENTE.png` | Solo el frente (verde con logo), 1344×768 px (~384 DPI) | **3.5 × 2"** | Subir a la pestaña **Front** |
| `Jaimez-Tarjeta-REVERSO.png` | Solo el reverso (crema con QR), 1344×768 px (~384 DPI) | **3.5 × 2"** | Subir a la pestaña **Back** |
| `Jaimez-Tarjeta-PROOF.pdf` | Vista de referencia (las 2 caras juntas) | Carta | — (solo revisar) |

> El editor "Upload Your Own" de Staples pide **frente y reverso como imágenes
> separadas**. Usa los PNG `-FRENTE` y `-REVERSO` (uno por pestaña). El PDF
> `-IMPRIMIR` sirve para procesos que aceptan un solo archivo de 2 páginas.

## Especificaciones de pedido sugeridas

- **Trípticos:** 11×8.5", Full Bleed, **Gloss**, a color doble cara, tri-fold. Mín. 25.
- **Tarjetas:** 3.5×2", 14 pt, doble cara. Mín. 250 (Staples no vende menos).
- Entrega a domicilio gratis en órdenes de $59.99+.

## Fuentes editables

- `triptico.html` — tríptico (fuente).
- `tarjeta.html` — tarjeta con vista previa y notas (fuente).
- `tarjeta-print.html` — tarjeta a sangre completa 3.5×2 (genera el PDF de impresión).
- `tarjeta-frente.html` / `tarjeta-reverso.html` — cada cara por separado (generan los PNG).
- `assets/` — fotos optimizadas usadas en las piezas.
- `qr-jaimez-black.svg` / `.png` / `qr-jaimez-green.svg` — código QR a jaimezgrocery.com.

Para regenerar los PDF: abrir el `.html` en Chrome → Imprimir → Guardar como PDF
(respetando el tamaño de página definido en cada archivo).

---
Desarrollado por **Medenezer LLC / Imperio Digital 365**.
