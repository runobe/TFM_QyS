# TFM_QyS
Trabajo Fin de Master. Modelo de tópicos Quejas y Sugerencias
## Contenidos
[01_Analisis_Exploratorio](01_Analisis_Exploratorio.ipynb): Obtener datos, analizar valores vacíos, estadísticos sobre palabras, distribución de palabras.
### Preprocesado
[02_01_Preprocesado_pruebas](02_01_Preprocesado_pruebas.ipynb):Pruebas para evaluar que libreria utilizar nltk o Spacy.
[02_02_Preprocesado_definitivo](02_02_Preprocesado_definitivo.ipynb):Preprocesado realizado: Eliminar documentos con menos de dos palabras, tokenizado, lematización, signos de puntuación, tokens numéricos, stopwords..
### Evaluación
#### Evaluación Cuantitativa
[03_01_evaluacion_cuantitativa](03_01_evaluacion_cuantitativa.ipynb): Construir los modelos utilizando (LDA,GSDMM, BERTopic, Kmeans con (TF-IDF y con Word2Vec) y Aglomerativo con (TF-IDF y con Word2Vec) y métricas de validación externa (ARI NMI, BCubed).
[03_02_evaluacion_cuantitativa_bigramas](03_02_evaluacion_cuantitativa_bigramas.ipynb): Construir los modelos utilizando (LDA,GSDMM, BERTopic, Kmeans con (TF-IDF y con Word2Vec) y Aglomerativo con (TF-IDF y con Word2Vec) y métricas de validación externa (ARI NMI, BCubed).
#### Evaluación Cualitativa
**Exportación de palabras y documentos** Necesaria para preparar los cuestionarios
[04_01_LDA](04_01_evaluacion_cualitativa_exportacion_lda.ipynb)
[04_02_GSDMM](04_02_evaluacion_cuantitativa_exportacion_GSDMM.ipynb)
[04_03_BERTopics](04_03_evaluacion_cualitativa_exportacion_bertopic.ipynb)
[04_04_Kmeans](04_04_evaluacion_cualitativa_exportacion_kmeans.ipynb)
[04_05_Aglomerativo](04_05_evaluacion_cualitativa_exportacion_agglomerative.ipynb)
**Fiabilidad encuestadores**
[05_fiabilidad_evaluadores](05_evaluacion_cualitativa_fiabilidad_evaluadores.ipynb)
#### Combinación de evaluaciones
[06_evaluacion_combinada_modelos](06_evaluacion_combinada_modelos.ipynb)
### Post-clustering
[07_Post_clustering](07_Post_clustering.ipynb): Utilizar HDBSCAN para reducir el número de clústeres debido a solapamiento semático y dificultad para visualizar: Dendogramas del proceso.
### Visualización
[08_Visualizacion_treemap](08_Visualizacion_treemap.ipynb): Generar el html necesario para construir una visualización basada en treemap. Calcular términos y documentos más representativos del clúster.
