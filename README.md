# 📊 TelecomX - Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en la **cancelación de clientes (Churn)** en una empresa de telecomunicaciones y desarrollar modelos de **Machine Learning** capaces de predecir qué clientes tienen mayor probabilidad de abandonar el servicio.

A través de técnicas de **análisis exploratorio de datos**, **procesamiento de datos** y **modelado predictivo**, se busca identificar patrones en el comportamiento de los clientes y generar información útil para apoyar estrategias de **retención de clientes**.

---

## 📂 Estructura del Proyecto

El proyecto incluye las siguientes etapas:

1. **Limpieza y preparación de datos**
   - Tratamiento de valores faltantes
   - Conversión de variables
   - Codificación de variables categóricas

2. **Análisis exploratorio de datos**
   - Distribución de la variable Churn
   - Análisis de correlación
   - Visualización de variables relevantes

3. **Análisis dirigido**
   - Tiempo de permanencia vs cancelación
   - Gastos de clientes vs cancelación

4. **Modelado predictivo**
   - Regresión Logística (con normalización)
   - Random Forest (sin normalización)

5. **Evaluación de modelos**
   - Accuracy
   - Matriz de confusión
   - Comparación de modelos

6. **Análisis de importancia de variables**
   - Coeficientes en Regresión Logística
   - Importancia de variables en Random Forest

---

## 🤖 Modelos Utilizados

### Regresión Logística
Este modelo requiere normalización de los datos debido a su sensibilidad a la escala de las variables.

**Accuracy obtenido:**  
≈ **0.74**

---

### Random Forest
Modelo basado en árboles de decisión que no requiere normalización de las variables.

**Accuracy obtenido:**  
≈ **0.73**

---

## 📊 Principales Factores que Influyen en el Churn

El análisis de los modelos permitió identificar variables relevantes para la predicción de cancelación, entre ellas:

- **Cuentas_Diarias**
- **Charges.Monthly**
- **Charges.Total**
- **tenure (tiempo de permanencia)**
- **Método de pago**
- **Servicios contratados**

Estas variables están relacionadas con el **uso del servicio, el costo para el cliente y el tiempo de relación con la empresa**.

---

## 💡 Estrategias de Retención Propuestas

A partir de los resultados obtenidos se sugieren algunas estrategias para reducir la cancelación de clientes:

- Implementar **programas de fidelización para clientes nuevos**
- Ofrecer **descuentos o beneficios a clientes con altos cargos mensuales**
- Mejorar la **experiencia del cliente en servicios más utilizados**
- Identificar clientes con alto riesgo de churn mediante modelos predictivos

---

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## 📈 Conclusión

El uso de técnicas de **ciencia de datos y machine learning** permitió identificar patrones en el comportamiento de los clientes y desarrollar modelos capaces de predecir la cancelación con una precisión superior al **70%**.

Este tipo de análisis puede ayudar a las empresas a **anticipar la pérdida de clientes** y diseñar estrategias de retención más efectivas.

---

## 👨‍💻 Autor
Yeicob David Rodriguez Rinaldy
Proyecto desarrollado como parte de un ejercicio de **análisis de datos y machine learning de ALURA LATAM**
