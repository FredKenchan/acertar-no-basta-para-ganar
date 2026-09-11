# Sellos — firmas digitales de cada estudio

Cada firma sha256 se calculó **antes de mirar los datos** del estudio
correspondiente. Es la prueba de que la hipótesis no se modificó a posteriori.

Un sello «de antemano» es una predicción puesta a prueba. Un sello «a
posteriori» ordena lo que ya pasó, pero no pretende ser una predicción — en el
libro esa distinción se explica con claridad, y aquí se marca en la columna
«tipo».

---

## Parte I · Criptomonedas (CryptoLyrus)

| Estudio | Firma (sha256, abreviada) | Tipo | Veredicto |
|---|---|---|---|
| Reversión tras cascadas (A1-D0) | `779f8a80…` | antemano | sin ventaja |
| Carry delta-neutral (B1a) | `6919e2e1…` | antemano | positivo, no supera hurdle |
| Agotamiento short-covering (C1-multi) | `a87ebb59…` | antemano | no medible (muestra) |
| Capitulación (C2-multi) | `20ce7fd9…` | antemano | no medible (muestra) |
| Triple extremo (C3-multi) | `43de91e0…` | antemano | no medible (muestra) |
| Control solo-precio (C0) | `790e24cf…` | antemano | infraestructura (no hipótesis) |
| Posicionamiento continuo (H-POS1) | `85d42b5e…` | antemano | sin ventaja, con potencia |

**Nota sobre H-POS1** — hash del cuerpo canónico (vinculante):
`85d42b5e25c4df893cc44eb7759226ff591a5781e115e8316484e99d033601a2`
· sellado 2026-09-04 · fichero de sobre: `10f42bc7…d4ec4f5`

---

## Parte II · Bolsa (Sistema D)

| Estudio | Firma (sha256, abreviada) | Tipo | Veredicto |
|---|---|---|---|
| Separador pre-market (cacería del sol) | contrato retroactivo | **a posteriori** | cerrado con evidencia negativa / parcialmente no concluyente |
| Familia R (detector de régimen) | `1a997cd9…` | antemano | muere |
| Familia K (regímenes MA200) | contrato v1.5 | antemano | (ver libro) |

**Nota sobre el separador pre-market** — su contrato se firmó *después* de
haber ejecutado el estudio, con una declaración de anterioridad explícita. No es
un pre-registro: es un inventario honesto de lo que se hizo. El libro lo cuenta
como una confesión, no como una predicción cumplida. Documento fuente de los
recuentos: `ESTADO_PREMKT_v1.md`, sha256
`947f1372390bcb7ce16f8fcc4ccc8f763fba0048e14e58d1ae8dfcb2bb15e281`.

---

## Cómo se leen estas firmas

Una firma sha256 es un resumen matemático de un contenido: si cambias una sola
coma del documento original, la firma cambia por completo. Por eso, si el
documento sellado que respalda cada estudio coincide con la firma aquí
publicada, queda demostrado que no se tocó después de sellarlo.

Las firmas se muestran abreviadas por legibilidad. Las completas están en los
ficheros de la carpeta `sellos/` cuando se publiquen los documentos originales
sanitizados.
