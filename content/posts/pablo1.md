---
title: Revalorización del WIP Real S/4HANA
subtitle: Controlling
category:
  - CO-PC
author: Pablo
date: 2021-02-27T16:01:00.433Z
featureImage: /uploads/gaelle-marcel-9dzy0mo98xu-unsplash.jpg
---

1. [Seccion 1](#Seccion%20principal)

# Seccion principal

# ¿Qué es el trabajo en curso (WIP)?

Si no estas familiarizado con el concepto de trabajo en curso, el WIP son los costes de materiales y actividades consumidos durante el proceso de fabricación, además de aquellos costes imputados en una orden de fabricación, pero sin haber una entrega o alta en stock del producto terminado al final del periodo.

_Representan aquellos costes de producción de las ordenes incompletas al final del periodo._

## Revalorización del trabajo en curso

Mediante la función de revalorización del WIP podrás distribuir las diferencias calculadas en la ejecución del coste real del material ledger a los productos entregados en el almacén y al trabajo en curso (WIP) en proporción a las cantidades. Al activar la revalorización del trabajo en curso las diferencias pertenecientes al WIP serán valoradas a precios reales.

Se puede determinar el WIP de dos maneras:

<h1>Daniel</h1>

1.         Wip a coste real.

La diferencia entre el coste real cargado en una orden (Consumo) y el coste real abonado en la orden (Alta o Entrada)

2.         Wip a coste teórico.

La valoración de la cantidad real confirmada hasta la fecha para cada notificación, menos el rechazo relevante.

Si NO hay una revaluación WIP pueden producirse los siguientes problemas reales de absorción de costes:

Para la entrega parcial de la orden de producción, todas las desviaciones de materiales y clases de actividad se transfieren al nivel superior sólo a la cantidad entregada parcialmente. Esto puede provocar una distorsión del coste real del producto.

Si no se entrega ningún producto en el período, las desviaciones no se pueden implosionar y no se asignan en el material ledger. En este escenario, las diferencias permanecen en las cuentas de diferencias de precio de material y en los centros de coste de las clases de actividad. Por lo tanto, no existe una absorción de diferencias completa.

<!--\\\\\\\[if !supportLists]-->⁻      <!--\\\\\\\[endif]-->La cuenta WIP se valora según los precios estándar de los materiales y actividades consumidos.
