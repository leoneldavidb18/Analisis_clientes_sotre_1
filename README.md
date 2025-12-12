# Store 1 — Customer Data Cleaning & Customer Insights (Python)

## Descripción
Proyecto de análisis en Python basado en un caso de negocio simulado: **Store 1** almacena información de clientes en una estructura tipo tabla (listas anidadas).  
El objetivo es **limpiar, estandarizar y consultar datos de clientes**, además de calcular métricas simples (ingresos) y construir funciones reutilizables para filtrar y extraer información.

## Objetivos
- Estandarizar nombres de clientes (formato, espacios, guiones bajos y mayúsculas/minúsculas).
- Convertir tipos de datos (edad a entero).
- Normalizar categorías de compra (minúsculas).
- Calcular ingresos totales a partir de listas de gastos.
- Crear funciones para **consultas filtradas por categoría** y selección de clientes.

## Dataset / Estructura de datos
Los datos se almacenan como una lista de usuarios con el siguiente esquema:

- `user_id` (str)
- `user_name` (str → luego se transforma a lista: [nombre, apellido])
- `user_age` (float → luego int)
- `fav_categories` (list[str])
- `total_spendings` (list[int])

Ejemplo:
```python
['32415', ' mike_reed ', 32.0, ['ELECTRONICS', 'SPORT', 'BOOKS'], [894, 213, 173]]
git clone https://github.com/tuusuario/tu-repositorio.git
