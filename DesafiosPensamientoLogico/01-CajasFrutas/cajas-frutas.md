# Descripción del reto
> Tengo 3 cajas, cada una contiene un tipo de fruta diferente (peras, manzanas y naranjas). El problema es que todas las cajas tienen las etiquetas de las frutas incorrectas. ¿Cuántas cajas necesito abrir para saber colocar todas las etiquetas correctamente?

- 🍐 Peras
- 🍎 Manzanas
- 🍊 Naranjas

## ¿Qué esperamos de ti?
Se requiere dar solución al desafío de más arriba, toma en cuenta que este es un tipo de ejercicio **<u>totalmente lógico</u>, razón por la que nos olvidaremos del código en este desafío.**

Para completarlo aplica los siguientes pasos:

1. *Identifica posibles soluciones:* piensa en como solucionarías este problema, en ocasiones puedes tener más de una solución, por lo que te invito a que no te limites y desarrolles todas las soluciones que identifiques.

2. *Socializa tus hallazgos con la comunidad:* te invito a que compartas en la zona de comentario todas las soluciones identificadas.

3. *Toma el Quiz:* en el quiz encontrarás las posibles respuestas a este problema, entre ellas la respuesta correcta, recuerda que después del quiz encontrarás una nueva clase con la explicación del problema y su solución.

<br>

---

<br>

## **<u>Solución:</u>**

No hay ninguna de las tres cajas que esté bien etiquetada. Sabiendo esto, al abrir la primera caja, supongamos que es la etiquetada como _"Naranjas"_, me encontraría o con las **manzanas** o con las **peras**. _**Supongamos que son las manzanas.**_

Entonces ya sabría que en la caja que dice _"Naranjas"_, hay efectivamente **manzanas**.

- _"Naranjas"_ => **manzanas**

Como **todas las cajas están mal etiquetadas**, eso ya me indica que las **peras** no se pueden encontrar en la caja etiquetada como _"Peras"_. Por lo tanto, sin abrir ninguna otra caja, la única opción restante es la caja etiquetada como _"Manzanas"_.

- _"Manazanas"_ = **peras**

Y finalmente solo nos queda la caja etiquetada como _"Peras"_, en la cual sólo se pueden encontrar las **naranjas**.

- _"Peras"_ = **naranjas**

Sin importar el orden a elegir de las cajas, la logica es la misma.