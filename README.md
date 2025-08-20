Informe Final — Análisis Exploratorio de Evasión de Clientes (Churn) en Telecom X

1. Propósito del análisis

El objetivo principal de este proyecto fue detectar los factores que influyen en la evasión de clientes (churn) en la empresa Telecom X.  
La meta es comprender qué variables están más asociadas a la pérdida de clientes, para que la compañía pueda anticiparse a la cancelación de servicios y diseñar estrategias de retención efectivas.  

2. Estructura del proyecto

El trabajo se organizó en los siguientes recursos:

- Notebook principal: `TelecomX_parte1.ipynb`  
  Contiene todo el flujo del proyecto (ETL, análisis exploratorio y conclusiones).
  
- Datos originales: 
  - `TelecomX_Data.json` (fuente inicial de datos desde API simulada).  
  - `TelecomX_diccionario.md` (diccionario de variables).  

- Datos tratados: 
  - `telecomx_churn_clean.csv` (versión limpia y estructurada de los datos, con la nueva columna `Cuentas_Diarias`).  

3. Ejemplos de gráficos e insights obtenidos

Durante el análisis exploratorio de datos (EDA) se generaron visualizaciones estratégicas:

- Distribución de clientes según churn: mostró el porcentaje de clientes que permanecen activos vs. los que cancelaron.  
- Boxplot de cargos mensuales vs churn: evidenció que clientes con cargos más altos tienden a cancelar con mayor frecuencia.  
- Gráfico de barras del tipo de contrato: clientes con contratos mes a mes presentan mayor tasa de cancelación en comparación con los de contrato anual.  
- Relación entre antigüedad (tenure) y churn: los clientes con poca permanencia son más propensos a darse de baja.  

Principales insights:
- Los clientes nuevos, con contrato mes a mes y cargos elevados son el segmento de mayor riesgo de cancelación.  
- La implementación de contratos de mayor permanencia podría reducir significativamente el churn.  

4. Instrucciones para ejecutar el notebook

4.1 Requisitos
Este proyecto fue desarrollado en Python 3.x con las siguientes bibliotecas principales:  

4.2 Ejecución

1. Abrir el archivo TelecomX_parte1.ipynb en Google Colab.

2. Ejecutar las celdas secuencialmente para reproducir:

Proceso ETL (extracción desde JSON, transformación y carga a DataFrame).

Limpieza y enriquecimiento de datos.






