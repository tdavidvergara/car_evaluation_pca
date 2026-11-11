
Tarea 3 - Reducción de Dimensionalidad con PCA sobre Car Evaluation Dataset
Descripción
Este proyecto corresponde a la Tarea 3 de la asignatura Aprendizaje Automático de la Universidad Autónoma de Occidente. El objetivo es aplicar técnicas de reducción de dimensionalidad mediante Análisis de Componentes Principales (PCA) sobre el conjunto de datos Car Evaluation Data Set, comparando la estimación de componentes principales utilizando Descomposición en Valores Singulares (SVD) y la implementación de PCA disponible en Scikit-Learn.
Se analizan representaciones del conjunto de datos utilizando una, dos y tres componentes principales, evaluando la varianza explicada por cada componente y generando visualizaciones que permitan interpretar la información conservada después de la reducción de dimensionalidad.


Objetivos
Objetivo General
Aplicar técnicas de reducción de dimensionalidad mediante PCA para analizar el comportamiento y la representación de los datos del conjunto Car Evaluation Data Set.
Objetivos Específicos

- Realizar el preprocesamiento del conjunto de datos.
- Implementar PCA utilizando Descomposición en Valores Singulares (SVD).
- Implementar PCA utilizando la librería Scikit-Learn.
- Reducir la dimensionalidad del conjunto de datos a: 
- 1 componente principal.
- 2 componentes principales.
- 3 componentes principales.
- Calcular la varianza explicada por cada componente principal.
- Comparar los resultados obtenidos mediante ambos enfoques.
- Generar visualizaciones que faciliten la interpretación de los datos reducidos.


Dataset Seleccionado
Para el desarrollo de este proyecto se seleccionó el conjunto de datos Car Evaluation Data Set, disponible en el repositorio UCI Machine Learning Repository.
Este dataset fue derivado de un modelo de decisión utilizado originalmente para evaluar la aceptabilidad de automóviles según diferentes características técnicas y económicas.
Variables del Dataset
Variables predictoras

- buying: precio de compra del vehículo.
- maint: costo de mantenimiento.
- doors: número de puertas.
- persons: capacidad de pasajeros.
- lug_boot: tamaño del maletero.
- safety: nivel de seguridad.
Variable objetivo

- class: evaluación final del automóvil.
Clases
Los vehículos son clasificados en:

- unacc: Unacceptable.
- acc: Acceptable.
- good: Good.
- vgood: Very Good.
Justificación de la Selección
El conjunto de datos Car Evaluation fue seleccionado porque presenta múltiples atributos categóricos que requieren transformación y preprocesamiento antes de aplicar técnicas de reducción de dimensionalidad. Además, permite analizar la capacidad de PCA para representar información relevante en un espacio de menor dimensión.
