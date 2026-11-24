---
name: mercado-entidad
description: Quién le ha vendido más a una entidad pública colombiana: ranking de contratistas por contratos y valor, consorcios descompuestos. Úsala para conocer el mercado de una entidad antes de ofertar o para ver contra quién se compite.
---

# Mercado de una entidad con Jaque

1. Llama a `mayor_contratista` de Jaque con el nombre de la entidad (por ejemplo “Gobernación de Santander”) y, si el usuario lo pide, la ventana en meses (por defecto 36).
2. Entrega el ranking resumido (los primeros contratistas con número de contratos y valor), señala si hay **concentración** (uno o dos contratistas con la mayor parte) y los **consorcios** con sus integrantes.
3. Si el usuario quiere profundizar en un contratista, sigue con `contratos_de_contratista` o con la habilidad de verificar contratista.
4. Si la entidad es ambigua (varias con nombre parecido), nombra la que usaste y sigue.
