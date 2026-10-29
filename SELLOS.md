# Seals / Sellos — Digital signatures by study / Firmas digitales de cada estudio

A sha256 signature is a mathematical fingerprint of a document: change a single comma and the signature changes completely. It proves that a document has not changed since it was signed. On its own, it does not prove when it was signed.

Not every study in the book was sealed before looking at the data. The method matured along the way, and this list says so study by study. The "type" column uses five labels:

- in advance: the contract was signed and sealed before looking at the data. This is a prediction put to the test.
- after the fact: sealed after the ground had been explored. It stops anyone from rewriting afterwards what was done, but it is not a prediction.
- contract, no seal record: the contract exists, but its signature was not recorded at the time. It is published so the text can be checked, but there is no way to prove it was sealed before looking.
- no contract: there is no signed contract.
- no seal (pre-method): measured and written down before the sealing system existed.

---

## Before everything, forex (August 2025) and Part III (December 2025 – June 2026)

No seal. None of the forex tests was sealed before looking: there was no signed contract and no criterion fixed in advance to discard them. They are exploratory. The "APPROVED" verdict of the weekly selection was given after seeing the result.

---

## Part I · Cryptocurrencies (CryptoLyrus)

Seven of the fifteen tests were signed before looking at the data. Signatures are shown abbreviated to their first characters.

| Study | Signature (sha256) | Type | Verdict |
|---|---|---|---|
| Liquidation cascade (rebound after cascades) | `779f8a80…` | in advance (27 Aug 2026) | doesn't work |
| Carry | `6919e2e1…` | in advance | works, not enough: +6.5 %/year, below the 12 % bar |
| Exhaustion (12 coins) | `a87ebb59…` | in advance | couldn't be measured (too few cases) |
| Capitulation | `20ce7fd9…` | in advance | couldn't be measured (too few cases) |
| Triple extreme | `43de91e0…` | in advance | couldn't be measured (too few cases) |
| Price-only control | `790e24cf…` | in advance | control (not a hypothesis) |
| Continuous positioning | `85d42b5e…` | in advance (4 Sep 2026) | doesn't work: 0 of 6 signals add anything |

Full signature of continuous positioning:
`85d42b5e25c4df893cc44eb7759226ff591a5781e115e8316484e99d033601a2`

The other eight (ignition and its hourly variant, funding, the grid, the whitelist, the first exhaustion test, the cost model and "bearish Sunday") were done before the sealing system existed, or were tools: measured with the same care, but no seal (pre-method).

---

## Part II · Equities (Stock Agent)

Full signatures (sha256 of each contract as it was stored).

### First era: measured, not yet sealed

| Study | Type | Verdict |
|---|---|---|
| Rebound after a trading halt (halt-resume) | no seal (pre-method) | no edge: real profit factor 1.04; the 12.6 was a mirage |
| 21,384 trading halts | no seal (pre-method) | no edge: best AUC 0.58 |
| Clean gap-up | no seal (pre-method) | dies |
| Gap reversal | no seal (pre-method) | dies: −1.40 % per trade (median) |
| World markets (the pattern outside the US) | no seal (pre-method) | explored: 0 tradable rules in 7 exchanges |
| Sector contagion | no seal (pre-method) | dies: the signal does not cover the cost |
| The hunt that followed the sun (pre-market gappers) | after the fact | no signal: 53 % against a 42 % base |

The hunt that followed the sun was documented and sealed after seeing the ground. It is an honest closure, not a fulfilled prediction. Signature of the status document that holds its counts:
`947f1372390bcb7ce16f8fcc4ccc8f763fba0048e14e58d1ae8dfcb2bb15e281`

Its three veins were closed at the end with the same sealing system (signatures as given in the book):

| Vein | Signature (sha256) | Type | Verdict |
|---|---|---|---|
| Intraday: does the morning peak keep rising? | `10db83e5…` | sealed at closure | dies: −0.35 % per trade |
| Structure: do age, splits or type separate them? | `26faef16…` | sealed at closure | dies: −0.13 % |
| Short pressure | `5d38cc71…` | sealed at closure | dies: it was liquidity, −0.18 % |

### Second era: the contract signed before looking

| Family | Signature (sha256) | Type | Verdict |
|---|---|---|---|
| A · Real cost | — | no contract (tool) | tool: median spread 0.06 % |
| B · Aggressor flow | — | no contract | dies: signal ~0.01 % against cost ~0.06 % |
| C · Late momentum | `05e40fab46954de14172bf607d486e67a3772cce11966ea6ee964a9353bd52b7` | contract, no seal record | dies: the gain came from a single day |
| D · Breadth | `f6869e06dc88e1582e0351670aeb5045be16b125ab4f8965b19fe420ad9062ef` | contract, no seal record | dies: explains 0.6 % of the move |
| E · After earnings | `6b7fb67c05d2cd3c8987c93d495877e29c024f753add569f3137c91b42098dcc` | in advance | dies: −0.73 % against the control |
| F · Entering the index | `067851cab1f45b27f1c651a167e6d70329e235543ae93aa2db435f7137590174` | in advance | dies: 96 % of the effect was momentum |
| G · Turn of the month | `ea4b23e126ad12a95fa49900edaaa0c2ef09ba7b5d93ee9833d40804e013ae94` | in advance | dies: the placebo wins |
| G · Turn of the month (re-study, 2 and 5 days) | `de1c6f23a37d461c19b4a805cbc643dad8d6f9c1bc6183ca37bd048e3f119864` | in advance | dies: signal +0.17 %, placebo +0.19 % |
| I · Trend following | `b5d1226a32c75c992138ce0c60553fda2b41367cfcce89c465932cfc56194318` | in advance | dies: +0.81 % a month against +1.17 % for buy and hold |
| J · Microcaps | `a19a367e8aea4d669509ef8075d44ed34629ef24a84c0fc8a73c426a1f01201d` | in advance | dies: median −2.56 % per trade, with measured cost |
| Microcap cost map | `2d30a9e6571cc53a72d50d04db80da5a04c9c16e56827b50cbbbab7f357ada47` | in advance | tool (not a hypothesis) |

Note on C and D: their contracts exist, but their signature was not recorded in any seal at the time. They are published so the text can be checked, without being able to prove they were sealed before looking at the data.

### Third era: the last attempt, over several days

| Family | Signature (sha256) | Type | Verdict |
|---|---|---|---|
| K · Regime (200-day average): contract | `1f08a7c61ebfca07af1194dea6a9232a8d567f5282d45bd07299c4471549ab69` | in advance | dies: gives up 4.6 points a year; not worth it |
| K · amendment 1 | `0b56bf7a5dd85438b63d1adf20cc8e3266d964de98c3a51cad245bd9a43c1368` | in advance | — |
| K · amendment 2 | `9a5469939a65a2b52b89ab000b112b6b3fe2326c54f79b0edb8816771518ecb7` | in advance | — |
| K · amendment 3 | `ffe84093c6a9e114e44c936b14d6ca18a20b4e0f5fdd894ad1d6af23c24984b5` | in advance | — |
| R · Regime detector | `0ef47abc03dcc9333d83b3d27939ad39ae5222c74717ffd6e44b5ccbe03dce42` | in advance | dies: 1.9 false alarms a year (maximum: 1) |

---

## How to check a signature

Compute the sha256 of the original document and compare it with the signature above:

```
sha256sum document.md
```

If the two match, the document has not changed by a single comma since it was signed. The original documents are not published today. If sanitized versions are published in the future, anyone will be able to recompute these signatures over them.

---

🇪🇸 Versión en español más abajo · *Spanish version below.*

---

# Sellos — Firmas digitales de cada estudio

Una firma sha256 es una huella matemática de un documento: si cambias una sola coma, la firma cambia por completo. Prueba que un documento no ha cambiado desde que se firmó. No prueba, por sí sola, cuándo se firmó.

No todos los estudios del libro se sellaron antes de mirar los datos. El método fue madurando a medida que avanzaba, y esta lista lo dice estudio por estudio. La columna «tipo» usa cinco etiquetas:

- antemano: el contrato se firmó y se selló antes de mirar los datos. Es una predicción puesta a prueba.
- a posteriori: se selló después de haber explorado el terreno. Impide que nadie reescriba después lo que se hizo, pero no es una predicción.
- contrato sin registro de sello: el contrato existe, pero su firma no quedó registrada en su momento. Se publica para que el texto sea verificable, sin poder probar que se selló antes de mirar.
- sin contrato: no hay contrato firmado.
- sin sello (pre-método): se midió y se anotó antes de que existiera el sistema de sellado.

---

## Antes de todo, las divisas (agosto de 2025) y la Parte III (diciembre de 2025 – junio de 2026)

Sin sello. Ninguna de las pruebas de divisas se selló antes de mirar: no hubo contrato firmado ni un criterio fijado de antemano para descartarlas. Son exploratorias. El veredicto «APROBADO» de la selección semanal se puso después de ver el resultado.

---

## Parte I · Criptomonedas (CryptoLyrus)

Siete de las quince pruebas se firmaron antes de mirar los datos. Las firmas se muestran abreviadas a sus primeros caracteres.

| Estudio | Firma (sha256) | Tipo | Veredicto |
|---|---|---|---|
| Cascada de liquidaciones (rebote tras cascadas) | `779f8a80…` | antemano (27 ago 2026) | no funciona |
| Carry | `6919e2e1…` | antemano | funciona, no basta: +6,5 %/año, bajo el listón del 12 % |
| Agotamiento (12 monedas) | `a87ebb59…` | antemano | no se pudo medir (pocos casos) |
| Capitulación | `20ce7fd9…` | antemano | no se pudo medir (pocos casos) |
| Triple extremo | `43de91e0…` | antemano | no se pudo medir (pocos casos) |
| Control solo-precio | `790e24cf…` | antemano | control (no es hipótesis) |
| Posicionamiento continuo | `85d42b5e…` | antemano (4 sep 2026) | no funciona: 0 de 6 señales aportan |

Firma completa del posicionamiento continuo:
`85d42b5e25c4df893cc44eb7759226ff591a5781e115e8316484e99d033601a2`

Las otras ocho (la ignición y su variante horaria, el funding, la rejilla, la whitelist, el primer agotamiento, el modelo de coste y el «domingo bajista») se hicieron antes de montar el sistema de sellado, o eran herramientas: se midieron con el mismo cuidado, pero sin sello (pre-método).

---

## Parte II · Bolsa (Stock Agent)

Firmas completas (sha256 de cada contrato tal como quedó guardado).

### Primera época: medidas, aún sin sello

| Estudio | Tipo | Veredicto |
|---|---|---|
| Rebote tras una pausa técnica (halt-resume) | sin sello (pre-método) | sin ventaja: factor de beneficio real 1,04; el 12,6 era un espejismo |
| 21.384 pausas de mercado | sin sello (pre-método) | sin ventaja: mejor AUC 0,58 |
| Gap-up limpio | sin sello (pre-método) | muere |
| Reversión del gap | sin sello (pre-método) | muere: −1,40 % por operación (mediana) |
| Mercados del mundo (el patrón fuera de EE. UU.) | sin sello (pre-método) | explorado: 0 reglas operables en 7 bolsas |
| Contagio de sector | sin sello (pre-método) | muere: la señal no cubre el coste |
| La cacería que seguía al sol (premercado, gappers) | a posteriori | sin señal: 53 % frente a una base del 42 % |

La cacería que seguía al sol se documentó y se selló después de haber visto el terreno. Es un cierre honesto, no una predicción cumplida. Firma del documento de estado que recoge sus recuentos:
`947f1372390bcb7ce16f8fcc4ccc8f763fba0048e14e58d1ae8dfcb2bb15e281`

Sus tres vetas se cerraron al final con el mismo sistema de sellado (firmas tal como las da el libro):

| Veta | Firma (sha256) | Tipo | Veredicto |
|---|---|---|---|
| Intradía: ¿el pico de la mañana sigue subiendo? | `10db83e5…` | sellada al cierre | muere: −0,35 % por operación |
| Estructura: ¿edad, splits o tipo separan? | `26faef16…` | sellada al cierre | muere: −0,13 % |
| Presión bajista | `5d38cc71…` | sellada al cierre | muere: era liquidez, −0,18 % |

### Segunda época: el contrato firmado antes de mirar

| Familia | Firma (sha256) | Tipo | Veredicto |
|---|---|---|---|
| A · Coste real | — | sin contrato (herramienta) | herramienta: spread mediano 0,06 % |
| B · Flujo agresor | — | sin contrato | muere: señal ~0,01 % frente a coste ~0,06 % |
| C · Momentum tardío | `05e40fab46954de14172bf607d486e67a3772cce11966ea6ee964a9353bd52b7` | contrato sin registro de sello | muere: la ganancia salía de un solo día |
| D · Amplitud | `f6869e06dc88e1582e0351670aeb5045be16b125ab4f8965b19fe420ad9062ef` | contrato sin registro de sello | muere: explica el 0,6 % del movimiento |
| E · Tras resultados | `6b7fb67c05d2cd3c8987c93d495877e29c024f753add569f3137c91b42098dcc` | antemano | muere: −0,73 % frente al control |
| F · Entrar al índice | `067851cab1f45b27f1c651a167e6d70329e235543ae93aa2db435f7137590174` | antemano | muere: el 96 % del efecto era momentum |
| G · Fin de mes | `ea4b23e126ad12a95fa49900edaaa0c2ef09ba7b5d93ee9833d40804e013ae94` | antemano | muere: el placebo gana |
| G · Fin de mes (re-estudio, a 2 y 5 días) | `de1c6f23a37d461c19b4a805cbc643dad8d6f9c1bc6183ca37bd048e3f119864` | antemano | muere: señal +0,17 %, placebo +0,19 % |
| I · Seguir tendencia | `b5d1226a32c75c992138ce0c60553fda2b41367cfcce89c465932cfc56194318` | antemano | muere: +0,81 % al mes frente a +1,17 % de comprar y mantener |
| J · Microcaps | `a19a367e8aea4d669509ef8075d44ed34629ef24a84c0fc8a73c426a1f01201d` | antemano | muere: mediana −2,56 % por operación, con coste medido |
| Mapa de coste en microcaps | `2d30a9e6571cc53a72d50d04db80da5a04c9c16e56827b50cbbbab7f357ada47` | antemano | herramienta (no es hipótesis) |

Nota sobre C y D: sus contratos existen, pero su firma no quedó registrada en ningún sello en su momento. Se publican para que el texto sea verificable, sin poder probar que se sellaron antes de mirar los datos.

### Tercera época: el último intento, a varios días

| Familia | Firma (sha256) | Tipo | Veredicto |
|---|---|---|---|
| K · Régimen (media 200): contrato | `1f08a7c61ebfca07af1194dea6a9232a8d567f5282d45bd07299c4471549ab69` | antemano | muere: cede 4,6 puntos al año; no compensa |
| K · enmienda 1 | `0b56bf7a5dd85438b63d1adf20cc8e3266d964de98c3a51cad245bd9a43c1368` | antemano | — |
| K · enmienda 2 | `9a5469939a65a2b52b89ab000b112b6b3fe2326c54f79b0edb8816771518ecb7` | antemano | — |
| K · enmienda 3 | `ffe84093c6a9e114e44c936b14d6ca18a20b4e0f5fdd894ad1d6af23c24984b5` | antemano | — |
| R · Detector de régimen | `0ef47abc03dcc9333d83b3d27939ad39ae5222c74717ffd6e44b5ccbe03dce42` | antemano | muere: 1,9 falsas alarmas al año (máximo: 1) |

---

## Cómo comprobar una firma

Calcula el sha256 del documento original y compáralo con la firma de arriba:

```
sha256sum documento.md
```

Si coinciden, el documento no ha cambiado ni una coma desde que se firmó. Los documentos originales no están publicados hoy. Si en el futuro se publican versiones sanitizadas, cualquiera podrá recalcular estas firmas sobre ellas.
