👥 Autores
Marideli Yabur Pérez – Universidad de Ciencias Informáticas, Cuba
Alayn Lado Chaviano – Universidad de Ciencias Informáticas, Cuba
Manuel Villanueva Betancourt – Universidad de Ciencias Médicas de La Habana, Cuba

Este repositorio contiene el código fuente, los datos y la documentación asociada al artículo científico presentado a la Convención UCIENCIA 2025, titulado: 
"Método de Detección de Anomalías para Identificación de Malware en el Motor Antivirus de Segurmática". 
El objetivo del proyecto es desarrollar e implementar un modelo de aprendizaje automático basado en LightGBM para mejorar la detección de malware en archivos Portable Executable (PE), 
reduciendo los falsos positivos generados por sistemas antivirus tradicionales como Segurmática .

🔍 El proyecto se enfoca en:

Preprocesamiento y limpieza de datos de archivos PE.
Selección de características relevantes mediante técnicas como RFE y análisis de correlación.
Entrenamiento y optimización de modelos de aprendizaje automático, principalmente LightGBM, usando GridSearchCV.
Comparación con otros modelos como Random Forest, Decision Tree y Gradient Boosting.
Validación empírica del modelo en entorno simulado usando una interfaz Flask conectada a Google Colab.

El conjunto de datos proporcionado por Segurmática, compuesto por archivos PE etiquetados como maliciosos y benignos con el cual se entrenó y validó la solución, 
está disponible públicamente en: https://zenodo.org/records/15700501.
