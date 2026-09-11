# La Ecuación Mágica — Registro de verificación

Este repositorio es la **prueba material** del libro *La Ecuación Mágica*
(Frédéric Briet). Contiene las firmas digitales (sha256) de cada hipótesis
probada y las cifras clave de cada estudio, para que cualquier lector pueda
comprobar que los números del libro son reales y que ninguna regla se ajustó
después de mirar los datos.

No te pido que me creas. Te doy con qué comprobarme.

---

## Qué encontrarás aquí

- **`SELLOS.md`** — la lista de firmas digitales de cada estudio, con su fecha.
  Cada firma es un código sha256 único que se calculó **antes de mirar los
  datos**. Si el estudio se hubiera modificado después, la firma no coincidiría.
- **`RESULTADOS.md`** — las cifras clave de cada hipótesis (qué se midió, qué
  salió, cuál fue el veredicto), tal como aparecen en el libro.
- **`COMO_VERIFICAR.md`** — guía sencilla para entender qué prueba cada cosa,
  sin necesidad de saber programar.

---

## La idea en una frase

Un sello (una firma sha256) es como lacrar un sobre antes de abrirlo. Se escribe
la hipótesis —qué se va a buscar, en qué dirección, con qué horizonte—, se
sella, y solo entonces se miran los datos. Como el sello no se puede cambiar
después sin que cambie por completo, es la prueba de que la pregunta que se dijo
que se iba a responder es exactamente la que se respondió.

Esa disciplina —**primero dices, luego miras, nunca al revés**— es lo que
separa una investigación honesta de un backtest ajustado a posteriori. Es la
«Cerradura 1» del libro, y este repositorio es su prueba.

---

## Aviso

Todos los datos proceden de fuentes públicas o gratuitas donde las había, y de
suscripciones de pago donde hizo falta (detallado en el libro). Este repositorio
**no contiene** credenciales, claves, datos de cuentas ni información privada:
solo las firmas y las cifras que respaldan el relato.

Nada de lo aquí publicado es asesoramiento financiero. Ver el aviso legal del
libro.
