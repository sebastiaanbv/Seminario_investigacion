# 📊 Predicción de Riesgo de Mora en Créditos - Confirmeza S.A.S.

Este proyecto tiene como propósito predecir el riesgo de mora de los clientes de **Confirmeza S.A.S.**, utilizando técnicas de análisis exploratorio de datos (EDA), reducción de dimensiones y algoritmos de machine learning.

---

## 🎯 Objetivos

1. **Explorar y segmentar** la cartera de clientes.
2. **Determinar las variables más relevantes** en la entrada en mora usando PCA.
3. **Desarrollar modelos predictivos** (Regresión Logística, Random Forest, XGBoost).
4. **Evaluar el desempeño** con métricas como precisión, recall y curva AUC-ROC.
5. **Proponer estrategias** para la prevención y recuperación de cartera.

---

## 📁 Estructura del Proyecto

modulo_2/
│
├── data/
│   ├── raw/               # Datos originales (no se suben a GitHub)
│   └── processed/         # Datos limpios/listos para análisis
│
├── notebooks/
│   ├── EDA.ipynb          # Exploración y visualización
│   └── Modeling.ipynb     # Pruebas y evaluación de modelos
│
├── src/
│   └── preprocessing.py   # Funciones reutilizables (cargar, limpiar, transformar)
│
├── main.py                # Para ejecutar todo junto (opcional, estilo producción)
├── README.md
├── .gitignore
├── pyproject.toml
└── poetry.lock



## 🧪 Tecnologías y librerías utilizadas

- `pandas`, `numpy` → manipulación de datos
- `scikit-learn` → modelos y métricas
- `xgboost` → modelo de boosting
- `matplotlib`, `seaborn` → visualización
- `openpyxl` → lectura de archivos Excel
- `jupyter`, `ipykernel` → notebooks interactivos

---

## 📂 Datos

📌 Los archivos de datos se encuentran en la carpeta `data/raw/`  
❌ **No se incluyen en GitHub** por su tamaño.  
📥 Puedes acceder a ellos a través de **OneDrive** o enlaces compartidos de forma privada.

---

## ⚙️ Instrucciones de instalación

1. Instala [Poetry](https://python-poetry.org/docs/#installation).
2. Clona este repositorio.
3. Instala las dependencias y activa el entorno:

```bash
poetry install
poetry shell
jupyter notebook