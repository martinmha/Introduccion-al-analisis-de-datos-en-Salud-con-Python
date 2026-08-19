# 🩺 Base de datos NHANES 2017–2018 (consolidada)

![NHANES](https://img.shields.io/badge/NHANES-2017--2018-2ea44f)
![Formato](https://img.shields.io/badge/Formato-CSV%20%2B%20XLSX-150458)
![Uso](https://img.shields.io/badge/Uso-educativo-blue)

Base de datos utilizada en el curso **ENO4135 — Introducción al Análisis de Datos en Salud**
(Pontificia Universidad Católica de Chile · Escuela de Enfermería) para el desarrollo del **trabajo final**.

Los datos provienen de la **National Health and Nutrition Examination Survey (NHANES)**, ciclo **2017–2018**,
una encuesta del CDC (EE. UU.) que combina entrevistas, exámenes físicos y análisis de laboratorio para
evaluar el estado de salud y nutrición de la población.

---

## 📦 Contenido

| Archivo | Descripción |
|---|---|
| [`Bases de datos/NHANES_2017_2018_dataset.csv`](Bases%20de%20datos/NHANES_2017_2018_dataset.csv) | Dataset consolidado: **9.254 participantes × 1.173 variables**. |
| [`Bases de datos/diccionario_NHANES_2017_2018_por_bloque.xlsx`](Bases%20de%20datos/diccionario_NHANES_2017_2018_por_bloque.xlsx) | Diccionario de variables organizado por **bloque** (una hoja por bloque + hoja resumen). |

---

## 🧬 Estructura de las variables

- **`SEQN`** — identificador único de cada participante (permite unir bloques).
- El resto de las columnas sigue el formato **`BLOQUE_J__VARIABLE`**. Por ejemplo:
  - `DEMO_J__RIDAGEYR` → edad en años
  - `DEMO_J__RIAGENDR` → sexo
  - `BMX_J__…` → medidas corporales (IMC, peso, talla…)
  - `BPX_J__…` → presión arterial
- Los **bloques** corresponden a los módulos de NHANES: demografía (**DEMO**), examen físico (**BMX**, **BPX**),
  laboratorio (**CBC**, **BIOPRO**), y cuestionarios (**DIQ** diabetes, **BPQ** presión, **ALQ** alcohol), entre otros.
  El detalle de cada variable está en el **diccionario** (`.xlsx`).

---

## 🐍 Cómo cargarla en Python

```python
import pandas as pd

df = pd.read_csv("Bases de datos/NHANES_2017_2018_dataset.csv")
print(df.shape)   # (9254, 1173)

# Ejemplo: edad y sexo de los primeros participantes
df[["SEQN", "DEMO_J__RIDAGEYR", "DEMO_J__RIAGENDR"]].head()
```

> 💡 El dataset tiene muchas columnas. Para el trabajo final se recomienda **seleccionar los bloques y variables**
> relevantes a tu pregunta de investigación (usando el diccionario) antes de analizar.

---

## 🔗 Fuente

- **NHANES 2017–2018** — CDC / National Center for Health Statistics (NCHS):
  https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?BeginYear=2017
- Datos de **dominio público**.

---

<sub>Uso educativo — curso ENO4135, Pontificia Universidad Católica de Chile.</sub>
