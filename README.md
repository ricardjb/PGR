# PGR: Plan de Gestion de Residuos
## Herramienta de Visualizacion y Analisis de Reportes

**Introducción**

En la actualidad, la sostenibilidad se ha vuelto una prioridad en el ámbito de la construcción. En este sentido, el reciclaje de los residuos generados es un punto de gran importancia. El ordenamiento y clasificación de residuos sólidos es una de las medidas más eficaces para lograr el desvío de vertederos y alcanzar altos porcentajes de reciclaje. Aún más eficaz, es una herramienta que permita recopilar y observar de forma cómoda los resultados de la gestión de residuos. 

Se plantea la necesidad de una herramienta que reciba las planillas confeccionadas en obra, las procese de forma sencilla y permita la visualización interactiva de los datos.

**Preguntas**

1. ¿Qué cantidad de residuos de generan en la obra en estudio?
2. ¿Cuál es la cantida de resiudos contabilizados por categoría?
3. ¿Cómo es la distribución de los resiudos al inicio y al final de la obra?
4. ¿Qué porcentaje de lo recolectado es reciclable?

**Metodología**

 - Lectura y procesamiento de los datos de planillas mediante Pandas.
 - Visualización de datos mediante Plotly Express, Graph Objects y Subplots.
 - Se exportan los gráficos en formato HTML.
 - Guardado de resultado en planilla de cálculo mediante Pandas.


**Caso de Estudio**

La planilla analizada pertenece a la obra NWT, cuya construcción inició en 2023 y finalizó en 2025.

**Análsis de Resultados**

Las preguntas planteadas al inicio, fueron respondidas por el código propuesto, para el caso de estudio presentado.

1. ¿Qué cantidad de residuos de generan en la obra en estudio?
2. ¿Cuál es la cantida de resiudos contabilizados por categoría?
3. ¿Cómo es la distribución de los resiudos al inicio y al final de la obra?
4. ¿Qué porcentaje de lo recolectado es reciclable?

Se presentan 3 gráficas en formato HTML para indicar totales, totales anuales y porcentaje de reciclaje, respectivamente.

Junto a esto, se genera una planilla con las informaciones mencionadas en cada pestaña.