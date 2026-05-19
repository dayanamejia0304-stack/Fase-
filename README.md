# Fase 3 - Fundamentos de Programación (UNAD)

## Problema 3: Auditoría de Inventario (Matriz)

Este proyecto corresponde a la **Fase 3** del curso **Fundamentos de Programación** de la Universidad Nacional Abierta y a Distancia (UNAD).

El programa fue desarrollado en **Python** y tiene como objetivo auditar un inventario utilizando una **matriz**, para determinar qué productos necesitan ser reabastecidos.

---

## Descripción del Problema

La información del inventario se almacena en una matriz con el siguiente formato:

[Código, Nombre, Stock Actual, Stock Mínimo]

El programa analiza cada artículo y calcula la cantidad exacta que se debe solicitar si el stock actual está por debajo del mínimo requerido.

---

## Lógica de Negocio

- Si el **Stock Actual** es menor al **Stock Mínimo**, entonces:
  Cantidad a pedir = Stock Mínimo - Stock Actual

- Si el **Stock Actual** es mayor o igual al mínimo, entonces:
  Cantidad a pedir = 0

---

## Funcionalidades del Programa

- Se crea una matriz con al menos 5 artículos.
- Se utiliza una función para calcular la cantidad a pedir.
- Se imprime un informe final con el nombre del artículo y la cantidad necesaria.

---

## Archivos del Proyecto

- `Problema3.py` → Código fuente del programa.

---

## Ejecución del Programa

Para ejecutar el programa desde la terminal:

```bash
python Problema3.py
