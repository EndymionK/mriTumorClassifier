# Clasificación de Tumores Cerebrales en MRI usando CNN

Este proyecto utiliza redes neuronales convolucionales (CNN) para clasificar automáticamente imágenes de resonancia magnética (MRI) que presentan tumores cerebrales. Se enfoca en tres tipos comunes de tumores:

- **Glioma**
- **Meningioma**
- **Tumor genérico**

---

## 🧠 Contexto de Aplicación

La detección y clasificación de tumores cerebrales es un problema crítico en medicina. Este modelo tiene como objetivo apoyar a profesionales de la salud mediante un sistema automatizado que reduzca el tiempo de diagnóstico y mejore el acceso a servicios de calidad, especialmente en regiones con escasez de neurólogos.

---

## 🎯 Objetivo de Machine Learning

Entrenar un modelo capaz de predecir el subtipo de tumor cerebral presente en una imagen de MRI con evidencia de tumor:

- **Entrada**: Imagen MRI 224x224 px
- **Salida**: Clase predicha — Glioma, Meningioma o Tumor genérico

---

## 🗂️ Dataset

- **Nombre**: Brain Cancer - MRI Dataset  
- **Fuente principal**: [Kaggle](https://www.kaggle.com/datasets/orvile/brain-cancer-mri-dataset)  
- **Fuente original**: [Mendeley Data](https://data.mendeley.com/datasets/mk56jw9rns/1)  
- **Total de imágenes**: 6,056  
  - Brain_Glioma: 2,004 imágenes  
  - Brain_Menin (Meningioma): 2,004 imágenes  
  - Brain Tumor: 2,048 imágenes  
- **Resolución**: 224x224 px  
- **Tamaño estimado**: ~2.2 GB

---

## 📏 Métricas de Desempeño

### Métricas de Machine Learning:
- **Accuracy**: Precisión global del modelo.
- **Precision**: Qué tan precisas son las predicciones positivas.
- **Recall**: Capacidad del modelo para detectar todos los casos reales.
- **F1-score**: Equilibrio entre precisión y recall.
- **Matriz de confusión**: Visualización de errores entre clases.

### Métricas de Impacto:
- **Reducción del tiempo de diagnóstico.**
- **Soporte a decisiones clínicas.**
- **Facilita el acceso a diagnóstico en hospitales con menos recursos.**

---

## 🚀 Tecnologías

- Python
- TensorFlow / Keras o PyTorch
- Google Colab (con soporte de GPU)
- Matplotlib / Seaborn para visualización

---

## 📌 Video

📍 [https://www.youtube.com/watch?v=9XnxZyjYLic&ab_channel=ANDRESFELIPECALVOARIZA](https://www.youtube.com/watch?v=9XnxZyjYLic&ab_channel=ANDRESFELIPECALVOARIZA)

---

## 👤 Autores

**Andrés Arroyave Carmona**  
✉️ andres.arroyavec1@udea.edu.co  
🔗 [https://github.com/EndymionK](https://github.com/EndymionK)

**Andrés Felipe Calvo Ariza**  
✉️ andres.calvoa@udea.edu.co  
🔗 [https://github.com/andres-calvo](https://github.com/andres-calvo)

**Jair Santiago Leal Miranda**  
✉️ jair.leal@udea.edu.co  
🔗 [https://github.com/Jairleal14](https://github.com/Jairleal14)