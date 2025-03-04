# **Predicción y seguridad de datos en seguros**  

## **Situación**  
La compañía de seguros **Sure Tomorrow** quiere mejorar su capacidad de análisis de clientes y protección de datos mediante Machine Learning. Para ello, plantea cuatro retos:  
1. **Identificación de clientes similares** para mejorar estrategias de marketing.  
2. **Predicción de la probabilidad de recibir una prestación de seguro** mediante modelos supervisados.  
3. **Estimación del número de prestaciones** que un nuevo cliente podría recibir utilizando **regresión lineal**.  
4. **Protección de datos personales** sin afectar la precisión de los modelos de Machine Learning.  

## **Tarea**  
Desarrollar y evaluar modelos de Machine Learning que permitan abordar cada una de las tareas planteadas, asegurando que la última (ofuscación de datos) no degrade la calidad de los modelos predictivos.  

## **Acción**  
1. **Análisis de datos y preprocesamiento:**  
   - Se limpiaron y transformaron los datos para asegurar consistencia.  
   - Se estandarizaron características para mejorar el desempeño de los modelos.  

2. **Implementación de soluciones para cada tarea:**  
   - **Tarea 1 (Clientes similares):** Se utilizó **K-Nearest Neighbors (KNN)** para encontrar clientes con características similares a un cliente objetivo, optimizando la métrica de distancia.  
   - **Tarea 2 (Probabilidad de recibir una prestación):** Se entrenó un modelo de **clasificación** y se comparó contra un modelo **dummy** para evaluar si la predicción era superior a un enfoque aleatorio.  
   - **Tarea 3 (Número de prestaciones esperadas):** Se implementó una **regresión lineal basada en álgebra de matrices**, evaluando su precisión con métricas de error.  
   - **Tarea 4 (Ofuscación de datos):**  
     - Se desarrolló un algoritmo de transformación de datos que impidió la recuperación de información personal sin afectar la precisión del modelo.  
     - Se probó que, después de la transformación, el modelo de regresión mantenía un desempeño similar al modelo original.  

## **Resultado**  
- **KNN permitió encontrar clientes similares**, facilitando estrategias personalizadas de marketing.  
- **El modelo de clasificación superó al modelo dummy**, demostrando que Machine Learning aporta valor en la predicción de prestaciones de seguro.  
- **La regresión lineal basada en matrices logró predicciones precisas del número de prestaciones esperadas.**  
- **La ofuscación de datos protegió la información sin afectar la calidad del modelo**, asegurando un equilibrio entre privacidad y rendimiento.  
- **Conclusión:** La compañía **Sure Tomorrow** ahora cuenta con herramientas avanzadas para mejorar su análisis de clientes y resguardar la privacidad de los datos sin perder precisión en sus modelos.  

