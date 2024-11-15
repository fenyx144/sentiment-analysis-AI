# 🚨 Detector de Sentimiento en Tweets - AI

## 📝 Descripción
Este proyecto utiliza técnicas de procesamiento de lenguaje natural (NLP) y clasificación de texto para detectar el sentimiento de los tweets, clasificándolos como **positivos** o **negativos**. El modelo fue entrenado usando un dataset de tweets etiquetados y se implementó un clasificador con un umbral ajustable para mejorar la precisión y el recall.

## 📊 Resultados
- **Precisión inicial (Accuracy):** 95.8%
- **Precisión ajustada (con umbral de 0.4):** 94.3%
  
### Reporte de clasificación (con umbral ajustado):

| Clase      | Precisión | Recall | F1-Score |
|------------|-----------|--------|----------|
| Negativo   | 0.99      | 0.90   | 0.94     |
| Positivo   | 0.91      | 0.99   | 0.95     |
| **Total**  | 0.96      | 0.94   | 0.94     |

## 🛠️ Tecnologías utilizadas
- **Python**: Lenguaje principal para la implementación.
- **scikit-learn**: Biblioteca de machine learning para el modelo de clasificación.
- **Pandas**: Para la manipulación y análisis de datos.
- **Numpy**: Para el procesamiento numérico.
- **TfidfVectorizer**: Para convertir los tweets en vectores numéricos.

## 💻 ¿Cómo usarlo?
1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu-usuario/detector-sentimiento-tweets.git
    cd detector-sentimiento-tweets
    ```

2. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

3. Ejecuta el script principal:
    ```bash
    python detector_sentimiento.py
    ```

4. Ingresa un tweet para predecir su sentimiento:
    ```bash
    "El producto fue increíble y funcionó perfectamente!"
    ```

5. El modelo clasificará el tweet como **positivo** o **negativo**.

## 📈 Cómo mejorar el modelo
- **Ajustar el umbral**: Puedes cambiar el umbral de decisión para mejorar la precisión o el recall, dependiendo de tus necesidades.
- **Probar otros modelos**: Puedes experimentar con modelos como **Random Forests**, **XGBoost** o redes neuronales más complejas.
- **Ajuste de hiperparámetros**: Realiza una búsqueda de hiperparámetros usando **GridSearchCV** para optimizar el modelo.

## 📜 Contribuciones
Si deseas contribuir a este proyecto, siéntete libre de realizar un **fork** del repositorio y hacer tus propios cambios. ¡Las contribuciones son bienvenidas!

## 📬 Contacto
Para preguntas o sugerencias, por favor contacta a [tu-correo@ejemplo.com](mailto:tu-correo@ejemplo.com).

