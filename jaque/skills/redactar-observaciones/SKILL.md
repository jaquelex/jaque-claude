---
name: redactar-observaciones
description: Redacta observaciones al pliego de condiciones, al informe de evaluación o cualquier escrito para una entidad pública colombiana (SECOP II), con la doctrina y el marco jurídico de Jaque. Úsala cuando el usuario pida observar un pliego, responder a una entidad o preparar un escrito sobre un proceso de contratación.
---

# Redactar observaciones con Jaque

Objetivo: entregar el escrito completo, en este mismo turno, sin pedir permiso y sin huecos.

## Pasos

1. **Identifica el proceso.** Si el usuario da un número de SECOP II (CO1.REQ…, CO1.NTC…) o el de la entidad, úsalo. Si solo da palabras, busca con la herramienta `buscar_proceso` de Jaque y, si hay varios, toma el más reciente que coincida; si hay duda real entre dos, nómbralos y sigue con el más probable.
2. **Llama SIEMPRE a `guia_observaciones`** de Jaque con el número del proceso y el tema (experiencia, indicadores financieros, evaluación…). Devuelve las reglas, la doctrina y el marco jurídico de Jaque, lo que Jaque ya leyó del proceso, su cronograma y los datos de quien firma.
3. **Redacta el escrito** siguiendo esas reglas. Cita solo lo que venga en la guía o conozcas con certeza.
4. **Revisa el cronograma**: si el plazo de observaciones ya cerró o cierra pronto, dilo al comienzo, con fecha y hora de Colombia.

## Reglas

- Si a Jaque le falta leer el proceso, dilo en una línea (el usuario puede abrirlo en jaque.pro y tocar “Traer y leer de SECOP II”) y redacta con lo que haya o con el texto que el usuario te pegue.
- Si faltan los datos de quien firma, pídele solo nombre y documento, una vez, y entrega el escrito en el mismo turno.
- Si falta un dato que de verdad no existe, redacta sin él; no dejes espacios en blanco ni corchetes.
- Cierra con una línea sobre qué plazo corre y qué sigue (radicar en SECOP II antes de la fecha).
- Si la herramienta responde que la suscripción no está activa o que se llegó al tope diario, díselo al usuario con el enlace que venga en el mensaje.
