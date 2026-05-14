# 🎵 ADNE: Music Analysis con Deep Learning

> **Asignatura:** Aprendizaje Profundo en Redes Neuronales (ADNE)  
> **Curso:** 2025–2026  
> **Entrega:** Proyecto Final de Grupo  
> **Repositorio:** [MrFat1/ADNE-Music-Analysis](https://github.com/MrFat1/ADNE-Music-Analysis)

---

## 📋 Descripción del proyecto

Este proyecto forma parte de la entrega final de la asignatura **ADNE** y tiene como objetivo explorar el uso de técnicas de **Deep Learning** para la comprensión musical automática. El trabajo aborda tres grandes bloques:

1. **Análisis del espectro de audio** — Representación y procesado de señales de audio mediante espectrogramas y técnicas de transformada de Fourier. Foco en analisis de los espectros de los instrumentos y diferencias entre el mismo instrumento producido acústicamente, eléctricamente o sintéticamente.
2. **Clasificación de instrumentos** — Entrenamiento de redes neuronales para identificar instrumentos musicales a partir de fragmentos de audio.
3. **Generación musical** — Exploración de modelos generativos capaces de crear secuencias musicales coherentes.

---

## 🗂️ Estructura del repositorio

```
ADNE-Music-Analysis/
│
├── Notebooks               # Jupyter Notebooks del proyecto
└── README.md
```

---

## 🧠 Metodología

### 1. Análisis del espectro de audio
Se procesan las señales de audio transformándolas en representaciones visuales como **espectrogramas de Mel** y **MFCCs** (Mel-Frequency Cepstral Coefficients), que capturan las características perceptivas del sonido de forma compacta y adecuada para alimentar modelos de Deep Learning. Foco en analisis de los espectros de los instrumentos y diferencias entre el mismo instrumento producido acústicamente, eléctricamente o sintéticamente.

### 2. Clasificación de instrumentos
Se entrena una red neuronal convolucional (CNN) sobre los espectrogramas extraídos para distinguir entre distintos instrumentos musicales. Se evalúa el rendimiento del modelo con métricas estándar (accuracy, F1-score, matriz de confusión).

### 3. Generación musical
Se exploran arquitecturas generativas (RNN/LSTM o similares) para aprender patrones musicales a partir de secuencias y generar nuevas melodías de forma automática.

---

## 🛠️ Tecnologías utilizadas

- **Python 3.12**
- **Jupyter Notebook**
- **TensorFlow / Keras** o **PyTorch**
- **Librosa** — procesado y análisis de audio
- **NumPy / Pandas** — manipulación de datos
- **Matplotlib / Seaborn** — visualización
- **Scikit-learn** — métricas y utilidades de ML


---

## ▶️ Cómo ejecutar el proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/MrFat1/ADNE-Music-Analysis.git
   cd ADNE-Music-Analysis
   ```

2. Instala las dependencias necesarias:
   ```bash
   pip install librosa tensorflow numpy pandas matplotlib scikit-learn jupyter
   ```

3. Abre los notebooks en orden:
   ```bash
   jupyter notebook
   ```
   Ejecuta los notebooks dentro de la carpeta `Notebooks/`


---

**📝 Notas de la entrega**: Todos los notebooks están documentados con explicaciones de cada paso.

---

*Proyecto desarrollado con fines académicos · ADNE 2025–2026*
