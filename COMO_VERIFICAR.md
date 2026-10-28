# How to verify this (no programming needed)

You don't need to be technical to understand what this repository proves. Here it is, in plain language.

## 1. What a sha256 signature is

Imagine a machine that takes any document and returns a code of 64 letters and numbers: always the same for the same document, and completely different if you change a single comma. That code is the "sha256 signature".

A real example from this book: `85d42b5e25c4df893cc44eb7759226ff591a5781e115e8316484e99d033601a2`

You can't go backwards (the code doesn't give you the document), and you can't forge it (finding two documents with the same signature is, in practice, impossible).

## 2. Why that proves honesty

The most common trap in trading is to look at the data, find a pretty pattern by chance, and then say "this was my strategy". It's drawing the target around the arrow.

To avoid that, every study in this book was done like this:

1. The hypothesis was written down: what would be looked for, and in which direction.
2. Its sha256 signature was computed and saved, before looking at a single data point.
3. Only then was the data examined and the result measured.

Because the signature was recorded first, it's impossible to change the hypothesis afterwards to fit what came out. The signature wouldn't match.

## 3. What you can check

- `SELLOS.md` lists the signatures of each study, with their dates.
- `RESULTADOS.md` lists the figures that came out.
- If the original documents are published in the future (sanitized, with no private data), anyone with a computer will be able to recompute each signature and check that it matches the one published here. There are free tools for this on every operating system (the `sha256sum` command, for example).

## 4. The honesty of "after-the-fact" seals

Not all seals carry the same weight, and the book doesn't hide it. In cryptocurrencies and in some families of equity rules, the rule was signed before touching the result: that is a prediction put to the test.

In one part of the equities work ("The hunt that followed the sun"), the seal came after the data had been seen. It serves to keep history from being rewritten, not to pretend nobody had looked. A late seal doesn't turn a finding into a prediction; it turns a file into a file that can no longer be touched up.

Saying so is part of the honesty. Hiding it would be exactly the trap this book teaches you to spot.

## In short

This repository doesn't ask for faith. It gives you the signatures and the figures so you can check for yourself that behind every number there was a real measurement, and that the question it said it would answer is exactly the one it answered.


# Cómo verificar esto (sin saber programar)

No necesitas ser técnico para entender qué prueba este repositorio. Aquí va, en lenguaje sencillo.

## 1. Qué es una firma sha256

Imagina una máquina que coge cualquier documento y devuelve un código de 64 letras y números: siempre el mismo para el mismo documento, y completamente distinto si cambias una sola coma. Ese código es la «firma sha256».

Ejemplo real de este libro: `85d42b5e25c4df893cc44eb7759226ff591a5781e115e8316484e99d033601a2`

No se puede ir hacia atrás (del código no sacas el documento), y no se puede falsificar (encontrar dos documentos con la misma firma es, en la práctica, imposible).

## 2. Por qué eso demuestra honestidad

La trampa más común en el trading es mirar los datos, encontrar un patrón bonito por casualidad y luego decir «esta era mi estrategia». Es hacer la diana alrededor de la flecha.

Para no caer en eso, cada estudio de este libro se hizo así:

1. Se escribió la hipótesis: qué se iba a buscar y en qué dirección.
2. Se calculó su firma sha256 y se guardó, antes de mirar un solo dato.
3. Solo entonces se miraron los datos y se midió el resultado.

Como la firma quedó registrada antes, es imposible cambiar la hipótesis después para que cuadre con lo que salió. La firma no coincidiría.

## 3. Qué puedes comprobar tú

- En `SELLOS.md` están las firmas de cada estudio, con su fecha.
- En `RESULTADOS.md` están las cifras que salieron.
- Si en el futuro se publican los documentos originales (sanitizados, sin datos privados), cualquiera con un ordenador podrá recalcular la firma de cada uno y comprobar que coincide con la publicada aquí. Hay herramientas gratuitas para ello en cualquier sistema operativo (el comando `sha256sum`, por ejemplo).

## 4. La honestidad de los sellos «a posteriori»

No todos los sellos pesan igual, y el libro no lo esconde. En las criptomonedas y en algunas familias de reglas de bolsa, la regla se firmó antes de tocar el resultado: eso es una predicción puesta a prueba.

En una parte de la bolsa («La cacería que seguía al sol»), el sello llegó después de haber visto los datos. Sirve para no reescribir la historia, no para pretender que no se había mirado. Un sello tardío no convierte un hallazgo en una predicción; convierte un archivo en un archivo que ya no se puede maquillar.

Decirlo es parte de la honestidad. Ocultarlo sería justo la trampa que este libro enseña a detectar.

## En resumen

Este repositorio no te pide fe. Te da las firmas y las cifras para que compruebes, tú mismo, que detrás de cada número hubo una medición de verdad, y que la pregunta que se dijo que se iba a responder es exactamente la que se respondió.
