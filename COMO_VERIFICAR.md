# Cómo verificar esto (sin saber programar)

No necesitas ser técnico para entender qué prueba este repositorio. Aquí va, en
cristiano.

---

## 1. Qué es una firma sha256

Imagina una máquina que coge cualquier documento y devuelve un código de 64
letras y números —siempre el mismo para el mismo documento, y completamente
distinto si cambias una sola coma—. Ese código es la «firma sha256».

Ejemplo real de este libro:
`85d42b5e25c4df893cc44eb7759226ff591a5781e115e8316484e99d033601a2`

No se puede ir hacia atrás (del código no sacas el documento), y no se puede
falsificar (encontrar dos documentos con la misma firma es, en la práctica,
imposible).

---

## 2. Por qué eso demuestra honestidad

La trampa más común en el trading es mirar los datos, encontrar un patrón bonito
por casualidad, y luego decir «esta era mi estrategia». Es hacer la diana
alrededor de la flecha.

Para no caer en eso, cada estudio de este libro se hizo así:
1. Se escribió la hipótesis —qué se iba a buscar, en qué dirección.
2. Se calculó su firma sha256 y se guardó. **Antes de mirar un solo dato.**
3. Solo entonces se miraron los datos y se midió el resultado.

Como la firma quedó registrada antes, es imposible cambiar la hipótesis después
para que cuadre con lo que salió. La firma no coincidiría.

---

## 3. Qué puedes comprobar tú

- En **`SELLOS.md`** están las firmas de cada estudio, con su fecha.
- En **`RESULTADOS.md`** están las cifras que salieron.
- Cuando se publiquen los documentos originales (sanitizados, sin datos
  privados), cualquiera con un ordenador podrá recalcular la firma de cada uno
  y comprobar que coincide con la publicada aquí. Hay herramientas gratuitas
  para ello en cualquier sistema operativo (el comando `sha256sum`, por
  ejemplo).

---

## 4. La honestidad de los sellos «a posteriori»

No todos los sellos pesan igual, y el libro no lo esconde. En las criptomonedas
y en las familias K y R de bolsa, la regla se firmó **antes** de tocar el
resultado: eso es una predicción puesta a prueba.

En una parte de la bolsa (la «cacería del sol»), el sello llegó **después** de
haber visto los datos. Sirve para no reescribir la historia, no para pretender
que no se había mirado. Un sello tardío no convierte un hallazgo en una
predicción; convierte un archivo en un archivo que ya no se puede maquillar.

Decirlo es parte de la honestidad. Ocultarlo sería justo la trampa que este
libro enseña a detectar.

---

## En resumen

Este repositorio no te pide fe. Te da las firmas y las cifras para que
compruebes, tú mismo, que detrás de cada número hubo una medición de verdad —y
que la pregunta que se dijo que se iba a responder es exactamente la que se
respondió.
