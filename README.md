# Telecom X - Parte 2: Prediciendo la Evasión de Clientes (Churn) 📊

¡Misión cumplida! En esta segunda etapa del Challenge Telecom X, he asumido el rol de **Científico de Datos**. El objetivo principal fue construir, evaluar e interpretar modelos de Machine Learning para predecir qué clientes tienen mayor probabilidad de cancelar sus servicios.

## 🎯 Misión y Objetivos
La empresa Telecom X busca anticiparse al problema de la cancelación. Para ello, se desarrollaron las siguientes tareas:
* **Preprocesamiento:** Tratamiento de datos, codificación (Encoding) y normalización.
* **Análisis:** Identificación de correlaciones y variables críticas.
* **Modelado:** Entrenamiento de modelos de clasificación (Regresión Logística y Random Forest).
* **Estrategia:** Generación de insights para la retención de clientes.

## 🛠️ Herramientas Utilizadas
* **Python**
* **Pandas / Numpy**
* **Scikit-Learn**
* **Matplotlib / Seaborn**

## 📈 Resultados del Modelado

Tras evaluar los modelos, se obtuvieron las siguientes métricas:

| Métrica | Regresión Logística | Random Forest |
| :--- | :---: | :---: |
| **Exactitud (Accuracy)** | 79.79% | 78.51% |
| **Precisión** | 64.02% | 62.36% |
| **Recall (Sensibilidad)** | **54.55%** | 48.13% |
| **F1-Score** | 58.90% | 54.33% |

> **Nota técnica:** Se seleccionó la **Regresión Logística** como el modelo principal debido a su mejor desempeño en el **Recall**, permitiéndonos identificar a una mayor cantidad de clientes en riesgo de fuga.



## 💡 Hallazgos Críticos (Insights)
A través del análisis de importancia de variables, identificamos que:
1. **Tipo de Contrato:** Los contratos "Mes a Mes" son el factor de mayor riesgo.
2. **Cargos Mensuales:** Clientes con facturas elevadas tienden a cancelar con más frecuencia.
3. **Antigüedad (Tenure):** Los primeros meses de servicio son los más críticos para la retención.



## 🚀 Estrategias Sugeridas
* **Fidelización:** Incentivar el cambio de contratos mensuales a anuales con promociones exclusivas.
* **Soporte Preventivo:** Reforzar la atención técnica en clientes nuevos (baja antigüedad).
* **Gestión de Valor:** Ofrecer servicios adicionales (Online Security/Tech Support) a clientes con facturación alta para aumentar su lealtad.

---
**Proyecto desarrollado como parte del Desafío Telecom X - Challenge Data Science.**
