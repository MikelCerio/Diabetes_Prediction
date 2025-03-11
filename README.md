# 🔬 Predicción de Diabetes con Machine Learning

Este proyecto utiliza **Machine Learning (Support Vector Machine - SVM)** para predecir si un paciente tiene diabetes basado en ciertas métricas de salud. Se trabajó con el conjunto de datos de **Diabetes del Pima Indians Dataset**, y se aplicaron técnicas de **limpieza, estandarización, modelado y optimización de hiperparámetros** para mejorar la precisión del modelo.

---

## 🚀 **Objetivo del Proyecto**
El objetivo principal de este proyecto es construir un modelo predictivo que pueda:
✅ **Identificar pacientes con alto riesgo de diabetes.**  
✅ **Ayudar a la toma de decisiones en la prevención de la enfermedad.**  
✅ **Optimizar la precisión del modelo mediante ajuste de hiperparámetros.**

---

## 📂 **Estructura del Proyecto**


---

## 📊 **Dataset Utilizado**
El dataset proviene de [Kaggle - Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

🔹 **Variables Principales del Dataset:**
- `Pregnancies`: Número de embarazos.
- `Glucose`: Nivel de glucosa en sangre.
- `BloodPressure`: Presión arterial (mm Hg).
- `SkinThickness`: Espesor del pliegue cutáneo (mm).
- `Insulin`: Nivel de insulina en sangre.
- `BMI`: Índice de masa corporal.
- `DiabetesPedigreeFunction`: Probabilidad de diabetes según historial familiar.
- `Age`: Edad del paciente.
- `Outcome`: **0 = No diabético, 1 = Diabético**.

---

## 🛠 **Técnicas Utilizadas**
🔹 **Exploración de Datos (EDA)**  
- Análisis estadístico de los datos.  
- Visualización de correlaciones mediante `seaborn`.  
- Identificación y tratamiento de valores atípicos.  

🔹 **Preprocesamiento de Datos**  
- Escalado de datos con `StandardScaler`.  
- División en conjunto de entrenamiento y prueba (`train_test_split`).  

🔹 **Entrenamiento de Modelos**  
- Se probó con **Support Vector Machine (SVM)**.  
- Optimización de hiperparámetros con `GridSearchCV`.  
- Comparación con **Random Forest y Regresión Logística**.  

🔹 **Evaluación del Modelo**  
- **Precisión en entrenamiento:** XX%  
- **Precisión en prueba:** XX%  
- **Matriz de confusión y clasificación** con `accuracy_score`.  

---

## 🤖 **Cómo Usar Este Proyecto**
### **1️⃣ Instalación de Dependencias**
Clona este repositorio en tu máquina y luego instala los paquetes necesarios:

```bash
git clone https://github.com/MikelCerio/Diabetes-Prediction.git
cd Diabetes-Prediction
pip install -r requirements.txt


---

## **🔥 ¿Por qué este README es profesional?**
✅ **Explica el propósito del proyecto** y por qué es relevante.  
✅ **Muestra el dataset y variables** utilizadas en el análisis.  
✅ **Detalla las técnicas de Machine Learning** y visualizaciones aplicadas.  
✅ **Incluye pasos para instalación y uso del código**.  
✅ **Presenta conclusiones claras y accionables**.  
✅ **Enlaza el perfil de LinkedIn y GitHub** para networking.  

---

Con este README, cualquier persona que visite tu repositorio **entenderá el proyecto de inmediato y verá tu capacidad como Data Analyst**. 🚀💡

### **💡 ¿Listo para subirlo a GitHub? ¡Hazlo y compártelo en LinkedIn!** 📢
