# Resultados — cifras clave por estudio

Estas son las cifras que aparecen en el libro, reunidas aquí para que se puedan
cruzar de un vistazo. Cada una procede de un estudio medido, no de una
estimación.

---

## Los cuatro tipos de resultado

No todos los «no» valen lo mismo. El libro los separa en cuatro clases, y esta
distinción es la tesis central:

- **Sin ventaja (medido):** se midió el efecto y no lo hay, o es adverso.
  Veredicto definitivo.
- **No medible:** el estudio murió antes de generar operaciones evaluables (por
  falta de muestra). No es un «no hay», es un «no se pudo saber con datos gratis».
- **Positivo insuficiente:** el efecto existe y es positivo, pero no supera el
  listón que uno mismo se fijó.
- **Herramienta / control:** no era una apuesta, sino una pieza de medición.

---

## Parte I · Criptomonedas

| # | Idea | Qué pasó | Tipo |
|---|---|---|---|
| 1 | Cascada de liquidaciones | −4,7 %/año (con sizing prudente) | sin ventaja |
| 2 | Ignición (momentum) | moneda al aire; 0 de las casillas confirman fuera de muestra | sin ventaja |
| 3 | Funding → dirección | negativa en las 24 variantes | sin ventaja |
| 4 | Rejilla v4 (ciclos) | 0 de 720 combinaciones sobreviven | sin ventaja |
| 5 | Whitelist (pares) | 0 de 911 sobreviven al filtro | sin ventaja |
| 6 | Posicionamiento continuo | −0,25 %/día operado; 0 de 6 señales aportan | sin ventaja |
| 7 | Carry delta-neutral | +6,5 %/año, por debajo del listón del 12 % | positivo insuficiente |
| 8 | Agotamiento (BTC/ETH) | 49 casos, hacían falta 242 | no medible |
| 9 | Agotamiento (12 monedas) | 174 casos, hacían falta 1.262 | no medible |
| 10 | Capitulación | 288 casos, hacían falta 821 | no medible |
| 11 | Triple extremo | 240 casos, hacían falta 1.496 | no medible |
| 12 | Ignición (variante horaria) | tampoco confirma fuera de muestra | sin ventaja |
| 13 | Modelo de coste v2 | validado (0,27 %) | herramienta |
| 14 | Control solo-precio | base de medición | control |
| 15 | «Domingo bajista» | era la marea, no habilidad | sin ventaja (beta) |

**Detalle de la cascada de liquidaciones (el estudio mejor documentado):**
- Rebote bruto medido: +0,034 %
- Coste de operar (ida y vuelta): ~0,15 %
- Resultado real, operado un año: −4,7 % (sizing prudente) / ruina (sizing pleno)
- Operaciones ganadoras: 24,4 % — un buen ejemplo de que acertar ≠ ganar
- Casos medidos: 2.778.649 filas de datos · más de 4.000 cascadas
- Coste en datos de pago: 0 €

---

## Parte II · Bolsa — tres épocas, más de veinte estudios

El programa de bolsa recorrió tres épocas, en las que el método fue madurando.
En total, más de veinte estudios. Ninguno con ventaja que sobreviviera al coste.
Nueve de ellos con contrato y firma digital verificables; los de la primera
época, medidos pero sin ese sello (se indica cuáles pesan más).

### Época 1 — la búsqueda a ciegas (sin sello, pre-método)

| Estudio | El número que lo cerró | Veredicto |
|---|---|---|
| Halt-resume | factor de beneficio real 1,04 (el 12,6 era espejismo por mirar el futuro) | sin edge |
| 21.384 pausas de mercado | mejor acierto 0,58 (azar: 0,50) | sin edge |
| Gap-up limpio | 1 de 20 aciertos aparente; ilusión | muere |
| Reversión del gap | −1.404 puntos por operación | muere |
| Pre-market (gappers) | acierto 53 % vs 42 % del azar | sin señal |
| Mercados del mundo (7 bolsas) | 0 reglas operables | explorado |
| Contagio de sector | 3,2 puntos, coste 10: no llega | muere |

### Época 2 — el método infalsificable (contrato + firma)

| Familia | El número que la mató | Firma |
|---|---|---|
| A · Coste real | herramienta de medida (spread ~6 al abrir) | — |
| B · Flujo agresor | señal −3,5; el placebo la iguala | sí |
| C · Momentum tardío | el «edge» era la marea de un solo día | sí |
| D · Amplitud | relación real: 0,6 % | sí |
| E · Tras resultados | −73 puntos frente al control | sí |
| F · Entrar al índice | 96 % del efecto era momentum | sí |
| G · Fin de mes | placebo +20 gana a la señal +18 | sí |
| I · Seguir tendencia | 81 frente a 117 de no hacer nada | sí |
| J · Microcaps | −256 puntos; el margen no da | sí |

### Época 3 — a varios días (contrato + firma)

| Familia | El número que la mató | Firma |
|---|---|---|
| K · Régimen (media 200) | cede 4,6 puntos al año; no compensa | sí |
| R · Detector de régimen | 1,9 falsas alarmas al año (máximo: 1) | sí |

**Dos venenos se repiten en casi todas:** lo que «parecía» ventaja, al limpiarlo,
era momentum disfrazado (la marea) o la ilusión de un único caso extremo que
inflaba la media.

**La factura:** ~2.000 € en cinco meses. Cero euros ganados.

**Nota de fiabilidad:** los estudios de las épocas 2 y 3 tienen contrato con firma
digital reproducible. Los de la época 1 están medidos pero preceden al método
infalsificable, y se tratan como «medidos, no sellados».

---

## El marcador, entre los dos mercados

Decenas de ideas medidas, cero reglas con ventaja desplegable, y todas las vetas
gratuitas exploradas. No es un fracaso: es un hallazgo, y uno más honesto que
cualquier «sistema» que se venda sin enseñar sus pérdidas.
