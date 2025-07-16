
# NLP & Deep Learning aplicado a Ciencia de Datos - Proyecto Final

Este proyecto forma parte del curso **DS3 - NLP & Deep Learning aplicado a Ciencia de Datos** de Coderhouse, etapa final de la carrera de Data Scientist.  
El objetivo principal fue aplicar técnicas modernas de procesamiento de lenguaje natural combinadas con redes neuronales profundas para **clasificar el sentimiento** en **tweets publicados por los partidos políticos más relevantes de España**.

---

## 📌 Descripción

Se recolectaron tweets de las cuentas oficiales de partidos como **PSOE, PP, Vox, Sumar y Podemos** durante el período de precampaña y campaña electoral.  
El propósito fue **predecir el sentimiento** (positivo, negativo o neutral) de cada tweet, comparando varios enfoques: desde vectorizaciones tradicionales (Bag‑of‑Words, TF‑IDF) hasta embeddings preentrenados y modelos basados en LSTM.

---

## 🧠 Herramientas y tecnologías utilizadas

- **Python** (Google Colab)
- **Librerías**: pandas, numpy, seaborn, matplotlib
- **Preprocesamiento de texto (español)**: NLTK, spaCy, regex
- **Vectorización**: CountVectorizer, TF‑IDF, Word2Vec
- **Modelado**: scikit‑learn, TensorFlow, Keras
- **Redes neuronales**: Dense, LSTM, Embedding
- **Evaluación de modelos**: accuracy, F1‑score, matriz de confusión, classification report

---

## 🧪 Etapas del proyecto

1. **Recolección y carga de datos desde la API de Twitter**  
2. **Análisis exploratorio (EDA) del corpus**  
3. **Limpieza y normalización de texto en español**  
4. **Tokenización y vectorización (TF‑IDF, Word2Vec)**  
5. **Entrenamiento de modelos clásicos (Logistic Regression, Random Forest)**  
6. **Entrenamiento de redes neuronales (DNN, LSTM)**  
7. **Evaluación comparativa y visualización de métricas**  
8. **Conclusiones y próximos pasos**

---

## 📈 Resultados destacados

- Los modelos clásicos alcanzaron una **precisión de hasta 83 %**.  
- El modelo **LSTM** mejoró el desempeño con una **accuracy del 86 %** y mejor F1‑score en la clase *neutral*.  
- Se observó que la rifea diversidad de vocabulario y la polaridad implícita en los tweets dificultan más la clasificación que en datasets de reseñas de productos, subrayando la importancia del preprocesamiento específico para español.

---

## 📎 Recursos del proyecto

- 📄 [Ver presentación del proyecto](./Informe%20Proyecto%20FinalDS3.pptx)
- 📊 [Ver código y dataset](./Proyecto%20Final%20DS3%20-%20Tweets)

---
