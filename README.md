# employee-segmentation-unsupervised
Proyecto de segmentación de empleados con K-Means. Se probaron distintos métodos (codo, Silhouette, Calinski-Harabasz) y se eligió k=4. Se generaron perfiles de empleados para analizar la deserción y proponer estrategias de retención y desarrollo.

⚙️ Metodología

Preprocesamiento de datos: imputación de valores nulos, codificación ordinal de variables categóricas y estandarización.

Selección de número de clusters: comparación de métodos (Elbow, Silhouette y Calinski-Harabasz).

Modelado: aplicación de K-Means con k=4 (número óptimo seleccionado).

Perfilado de clusters: generación de una tabla con promedios y modas de variables por cluster.

Análisis de resultados: identificación de perfiles de empleados (jóvenes en etapa inicial, veteranos estables, empleados de mediana carrera, etc.) y conclusiones para la toma de decisiones en recursos humanos.

📊 Resultados

Se identificaron 4 clusters de empleados con perfiles distintos.

Se evidenció que los grupos de empleados jóvenes presentan mayor riesgo de deserción.

Los empleados veteranos mostraron mayor estabilidad y lealtad a la empresa.

Se proponen estrategias diferenciadas de retención y desarrollo de carrera para cada cluster.

🛠️ Tecnologías

Python, Pandas, Scikit-learn, Matplotlib, Seaborn
