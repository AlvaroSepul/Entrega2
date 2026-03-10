# Telecom X - Análisis de Evasión de Clientes (Churn)

## Descripción
Este proyecto tiene como objetivo analizar la evasión de clientes (Churn) en Telecom X a partir de una base de datos en formato JSON.

Se trabajó en:
- carga y limpieza de datos,
- transformación y estandarización de variables,
- creación de una nueva columna llamada `Cuentas_Diarias`,
- análisis descriptivo,
- análisis exploratorio con gráficos para identificar patrones de evasión.

## Objetivo
Entender mejor qué características podrían estar relacionadas con la cancelación del servicio por parte de los clientes, para apoyar futuras decisiones de retención.

## Estructura del proyecto
- `TelecomX_Data.json`: base de datos original.
- `TelecomX_LATAM.ipynb` o notebook principal: desarrollo completo del análisis.
- `README.md`: descripción general del proyecto.

## Herramientas utilizadas
- Python
- Pandas
- Matplotlib
- JSON

## Principales análisis realizados
- Limpieza y tratamiento de datos.
- Conversión de variables numéricas.
- Revisión de valores nulos y duplicados.
- Creación de la variable `Cuentas_Diarias`.
- Análisis descriptivo de variables numéricas.
- Visualización de la distribución de churn.
- Comparación de churn según variables categóricas.
- Comparación de churn según variables numéricas.

## Principales hallazgos
A partir del análisis exploratorio, se identificaron diferencias entre los clientes que permanecen y los que cancelan el servicio. Algunas variables categóricas y numéricas muestran patrones que podrían estar asociados a una mayor evasión, lo que puede servir como base para futuras estrategias de retención.
