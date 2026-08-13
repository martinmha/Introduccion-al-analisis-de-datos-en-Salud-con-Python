# 🩺 Introducción al Análisis de Datos en Salud con Python

![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-data-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![Clases](https://img.shields.io/badge/Clases-2--9-2ea44f)
![Uso](https://img.shields.io/badge/Uso-educativo-blue)

> **ENO4135 — Introducción al Análisis de Datos en Salud**
> Postgrado · 10 créditos · Optativo de Profundización · 2026, Segundo Semestre
> Palabras clave: *ciencia de datos · Python · análisis de datos en salud*

Repositorio con el **material de clases** (notebooks de Jupyter) del curso. Cada unidad combina una breve explicación con **código ejecutable** y **datos biomédicos simulados**, de modo que todos los notebooks se pueden correr de principio a fin sin archivos externos.

---

## 📖 Descripción del curso

Curso de posgrado que ofrece una **introducción aplicada al análisis de datos en ciencias de la salud utilizando Python**. Está diseñado para estudiantes que buscan adquirir competencias en programación, estadística computacional y visualización de datos orientadas a la investigación biomédica.

A lo largo del curso, los estudiantes se familiarizan con el ecosistema de Python y sus principales librerías, aprenden a **importar, limpiar y estructurar** bases de datos biomédicas, y aplican técnicas de **bioestadística, machine learning y visualización** para interpretar resultados de manera crítica. La propuesta combina fundamentos teóricos con un enfoque práctico, promoviendo la **reproducibilidad** y la comunicación clara de hallazgos en contextos clínicos.

Al finalizar, los estudiantes estarán en condiciones de **diseñar y ejecutar flujos básicos de análisis de datos biomédicos en Python**, comprendiendo tanto los aspectos técnicos como las implicancias científicas y éticas de su uso.

---

## 📚 Contenido de las clases

| Clase | Unidad | Tema |
|-------|--------|------|
| [Clase 2](Clase_2_Unidad_2.ipynb) | Unidad 2 | Fundamentos de Python |
| [Clase 3](Clase_3_Unidad_3.ipynb) | Unidad 3 | Trabajando con datos biomédicos: manejo básico de datos |
| [Clase 4](Clase_4_Unidad_4.ipynb) | Unidad 4 | Preprocesamiento de datos biomédicos |
| [Clase 5](Clase_5_Unidad_5.ipynb) | Unidad 5 | Técnicas básicas de exploración de datos (EDA) |
| [Clase 6](Clase_6_Unidad_6.ipynb) | Unidad 6 | Visualización de datos en biomedicina |
| [Clase 7](Clase_7_Unidad_7.ipynb) | Unidad 7 | Análisis estadístico en biomedicina |
| [Clase 8](Clase_8_Unidad_8.ipynb) | Unidad 8 | Machine Learning en biomedicina |
| [Clase 9](Clase_9_Unidad_9.ipynb) | Unidad 9 | Procesamiento de imágenes en investigación biomédica |

> 📓 Las clases están basadas en el libro *Python Essentials for Biomedical Data Analysis* (J. U. Kazi).

---

## 🎯 Resultados de aprendizaje

1. **Comprender** los fundamentos del análisis de datos aplicados a las ciencias de la salud y el rol de Python en la investigación biomédica.
2. **Implementar** flujos básicos de programación en Python para importar, limpiar, organizar y transformar datos biomédicos.
3. **Aplicar** técnicas de bioestadística descriptiva e inferencial y algoritmos básicos de machine learning, interpretando resultados en contextos clínicos.
4. **Generar** visualizaciones claras y efectivas para comunicar hallazgos de manera comprensible.
5. **Integrar** buenas prácticas de reproducibilidad científica: control de versiones, documentación y organización de proyectos.
6. **Analizar críticamente** bases de datos biomédicas, identificando limitaciones, sesgos y consideraciones éticas.

---

## ⚙️ Cómo usar los notebooks

Cada notebook es **autoejecutable**: instala sus dependencias (con `%pip install ...`) y genera los datos de ejemplo que necesita. Se recomienda trabajar en un entorno virtual:

```bash
# Crear y activar un entorno virtual
python -m venv .venv

# Windows:
.venv\Scripts\activate
# macOS / Linux:
source .venv/bin/activate

# Instalar dependencias principales
pip install jupyter numpy pandas scipy scikit-learn scikit-image matplotlib seaborn

# Abrir Jupyter
jupyter notebook
```

Luego abre cualquier `Clase_X_Unidad_X.ipynb` y ejecuta las celdas de arriba hacia abajo
(**Kernel → Restart & Run All**).

---

## 🧰 Tecnologías

`Python` · `Jupyter` · `NumPy` · `Pandas` · `Matplotlib` · `Seaborn` · `SciPy` · `scikit-learn` · `scikit-image`

---

## 🗂️ Estructura del repositorio

```
.
├── Clase_2_Unidad_2.ipynb   →  Fundamentos de Python
├── Clase_3_Unidad_3.ipynb   →  Manejo básico de datos
├── Clase_4_Unidad_4.ipynb   →  Preprocesamiento
├── Clase_5_Unidad_5.ipynb   →  Exploración de datos (EDA)
├── Clase_6_Unidad_6.ipynb   →  Visualización
├── Clase_7_Unidad_7.ipynb   →  Análisis estadístico
├── Clase_8_Unidad_8.ipynb   →  Machine Learning
├── Clase_9_Unidad_9.ipynb   →  Procesamiento de imágenes
└── README.md
```

---

## 📕 Bibliografía

**Mínima**
- Haslwanter, T. (2022). *An Introduction to Statistics with Python: With Applications in the Life Sciences* (2.ª ed.). Springer. https://doi.org/10.1007/978-3-030-97371-1
- Downey, A. (2015). *Think Python: How to Think Like a Computer Scientist* (2.ª ed.). Green Tea Press.
- Rule, A., et al. (2019). *Ten simple rules for writing and sharing computational analyses in Jupyter Notebooks*. PLoS Comput Biol, 15(7), e1007007. https://doi.org/10.1371/journal.pcbi.1007007

**Complementaria**
- Deprez, M., & Robinson, E. C. (2024). *Machine Learning for Biomedical Applications: With Scikit-learn and PyTorch*. Academic Press / Elsevier.
- James, G., et al. (2023). *An Introduction to Statistical Learning: with Applications in Python*. Springer. https://doi.org/10.1007/978-3-031-38747-0

---

<sub>Material educativo del curso ENO4135. Adscrito al Código de Honor UC. Los notebooks usan datos biomédicos **simulados** con fines didácticos.</sub>
