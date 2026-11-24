---
name: verificar-contratista
description: Verifica una empresa o persona por NIT o cédula (registro mercantil, multas y sanciones en SECOP, listas OFAC y ONU) y muestra con qué entidades ha contratado. Úsala para debida diligencia de un contratista, un posible socio de consorcio o un competidor.
---

# Verificar un contratista con Jaque

1. Con el NIT o la cédula, llama a `verificar_empresa` de Jaque. Si el usuario solo da el nombre, usa `contratos_de_contratista` con el comienzo del nombre y de ahí toma el NIT.
2. Llama a `contratos_de_contratista` para ver sus entidades, años, contratos más grandes y recientes y los consorcios en que figura.
3. Entrega: **resultado de la verificación** primero (limpio o con alertas, en una frase), luego **historial de contratación** (entidades, valores, años) y **banderas** (multas, sanciones, concentración en una sola entidad).
4. Aclara una sola vez los límites: no cubre responsables fiscales ni antecedentes disciplinarios y judiciales, y los datos abiertos llegan con 2 a 4 días de retraso. No concluyas más de lo que muestran los datos.
