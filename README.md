1. Descripción del proyecto (Customer Churn Prediction)

Este proyecto desarrolla un modelo de Machine Learning supervisado para predecir la fuga de clientes (Customer Churn), es decir, identificar qué clientes tienen alta probabilidad de cancelar un servicio, dejar de comprar o abandonar la relación comercial con una empresa.

El objetivo principal es anticipar el abandono para apoyar estrategias de retención, fidelización y toma de decisiones basadas en datos.

2. Objetivo de negocio

La fuga de clientes representa una de las principales amenazas para la sostenibilidad comercial de muchas organizaciones. Retener un cliente suele ser más rentable que adquirir uno nuevo.

Este modelo busca:

Detectar clientes con riesgo de fuga.
Priorizar campañas de retención.
Optimizar recursos comerciales y de atención.
Generar valor a partir del análisis predictivo.

3. Objetivo analítico

Construir, entrenar y evaluar un modelo predictivo capaz de clasificar clientes en dos categorías:

0 = Cliente permanece
1 = Cliente se fuga

El enfoque incluye:

Limpieza y preparación de datos.
Análisis exploratorio.
Ingeniería de características.
Entrenamiento de modelos.
Evaluación de desempeño.
Interpretación de resultados.

4. Dataset

El conjunto de datos contiene información histórica de clientes y su comportamiento, incluyendo variables como:

Información demográfica.
Tiempo de permanencia.
Tipo de contrato.
Consumo o uso del servicio.
Facturación.
Método de pago.
Soporte o interacción con la empresa.
Estado final del cliente (fuga / no fuga).
Variable objetivo
Churn: indica si el cliente abandonó el servicio.
variables predictoras del dataset:

PORC_CUOTAS_PAGADAS     0.769378
SALDO_CAPITAL           0.180433
MORA                    0.023501
TASA                    0.015737

5. Flujo metodológico

El proyecto sigue una estructura analítica típica en problemas de clasificación supervisada:

5.1. Entendimiento del problema

Definición del objetivo de negocio.
Comprensión del fenómeno de fuga.
Identificación de variables relevantes.

5.2. Preparación de datos

Revisión de calidad de datos.
Tratamiento de valores nulos.
Eliminación de inconsistencias.
Transformación de variables categóricas.
Escalamiento de variables numéricas (si aplica).

5.3. Análisis exploratorio (EDA)

Distribución de la variable objetivo.
Correlaciones.
Variables con mayor relación con la fuga.
Detección de patrones y segmentos de riesgo.

5.4. Ingeniería de características

Codificación de variables categóricas.
Creación o transformación de atributos.
Selección de variables relevantes.

5.5. Modelado

Se pueden evaluar varios algoritmos, por ejemplo:

DecisionTreeClassifier
Random Forest
XGBoost / Gradient Boosting
Support Vector Machine (SVM)

5.6. Evaluación

Los modelos se comparan usando métricas de clasificación como:

Accuracy
Precision
Recall
F1-Score
ROC-AUC
Matriz de confusión

5.7. Interpretación
Importancia de variables.
Explicación del comportamiento del modelo.
Identificación de factores asociados a la fuga.
