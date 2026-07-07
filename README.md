# Introducción al Análisis de Datos — 2026, Segundo Semestre

Material de clases (notebooks de Jupyter) del curso **Introducción al Análisis de Datos**, orientado al análisis de datos en salud. Las clases están basadas en el libro *Python Essentials for Biomedical Data Analysis* (J. U. Kazi).

## Contenido

| Clase | Unidad | Tema |
|-------|--------|------|
| [Clase 2](Clase_2_Unidad_2.ipynb) | Unidad 2 | Fundamentos de Python |
| [Clase 3](Clase_3_Unidad_3.ipynb) | Unidad 3 | Trabajando con datos biomédicos: manejo básico de datos |
| [Clase 4](Clase_4_Unidad_4.ipynb) | Unidad 4 | Preprocesamiento de datos biomédicos |

## Cómo usar los notebooks

Cada notebook es autoejecutable: instala sus dependencias (con `%pip install ...`) y crea los datos de ejemplo que necesita. Se recomienda un entorno virtual:

```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS / Linux:
source .venv/bin/activate

pip install jupyter pandas numpy scikit-learn scipy matplotlib
jupyter notebook
```

## Notas

- Los notebooks de las Clases 3 y 4 usan datos sintéticos generados dentro de cada notebook, de modo que se pueden ejecutar de principio a fin sin archivos externos.
- Algunas secciones opcionales requieren librerías adicionales (`h5py`, `biopython`, `pydicom`, `anndata`, `pillow`); están protegidas para no interrumpir la ejecución si no están instaladas.
