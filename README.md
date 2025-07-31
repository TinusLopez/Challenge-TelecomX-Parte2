
# 📊 Telecom X – Parte 2: Predicción de Cancelación de Clientes (Churn)

Este proyecto forma parte de una especialización en Ciencia de Datos y tiene como objetivo principal construir un pipeline de Machine Learning para predecir la cancelación de clientes de una empresa de telecomunicaciones. Se aplican modelos supervisados para analizar los factores que influyen en la pérdida de clientes y se proponen estrategias de retención basadas en los hallazgos.

---

## 🎯 Objetivo

El propósito central del proyecto es desarrollar modelos predictivos que identifiquen a los clientes con mayor probabilidad de cancelar su servicio. Al entender los factores asociados al churn, se busca proporcionar recomendaciones que mejoren la fidelización.

---

## 🧰 Tecnologías y Herramientas

- **Lenguaje:** Python 3.11+
- **Análisis de Datos:** pandas, numpy
- **Visualización:** matplotlib, seaborn
- **Modelado:** scikit-learn, XGBoost
- **Entorno:** Jupyter Notebook

---

## 📁 Estructura del Proyecto

El proyecto está contenido en el archivo `telecomx_parte2.ipynb`, el cual se organiza en las siguientes secciones:

1. **Carga y exploración inicial de los datos**
2. **Limpieza y transformación del dataset**
3. **Análisis exploratorio (EDA)**
4. **Preprocesamiento para modelos de ML**
5. **Entrenamiento de modelos supervisados:**
   - Regresión Logística
   - K-Nearest Neighbors (KNN)
   - Random Forest
   - Support Vector Machine (SVM)
   - (Opcional) XGBoost
6. **Evaluación y comparación de modelos**
7. **Análisis de importancia de variables**
8. **Conclusiones y recomendaciones de negocio**

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/TinusLopez/Challenge-TelecomX-Parte2.git
   cd Challenge-TelecomX-Parte2
   ```

2. Crear un entorno virtual e instalar dependencias:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows usar venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Ejecutar el notebook:
   ```bash
   jupyter notebook telecomx_parte2.ipynb
   ```

---

## 📈 Principales Resultados

- **Factores que contribuyen al churn:** monto mensual elevado, poca antigüedad en el servicio, contratos cortos y ausencia de servicios de valor agregado como soporte técnico o respaldo en línea.
- **Modelos más efectivos:** Random Forest y SVM ofrecieron buen desempeño predictivo y claridad en la interpretación de resultados.
- **Recomendaciones:** campañas de retención segmentadas, impulso a contratos de mayor duración y promoción de servicios adicionales.

---

## 👤 Autor

Proyecto desarrollado por **Florentino López** como parte de la Especialización en Ciencia de Datos.

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más información.
