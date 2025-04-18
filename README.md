# 📊 Datasets Públicos - Ramón Enríquez

Este repositorio contiene datasets utilizados en los proyectos de mi portafolio de ciencia de datos. Su objetivo es permitir la carga directa desde notebooks y scripts sin necesidad de almacenar archivos pesados en el repositorio principal.

---

## 🗂️ Estructura

Los archivos están organizados de forma simple y accesible para enlazarlos desde los notebooks. Aquí se alojarán archivos como `.csv`, `.xlsx`, `.json`, etc.

---

## 🔗 Cómo usar los datasets en tus notebooks

Puedes cargar directamente un archivo usando su enlace `raw`, por ejemplo:

```python
import pandas as pd

url = "https://raw.githubusercontent.com/Ramon-Bravo/datasets_publicos/main/games.csv"
df = pd.read_csv(url)