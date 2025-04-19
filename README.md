# 📊 Datasets Públicos - Ramón Enríquez

Este repositorio contiene datasets utilizados en los proyectos de mi portafolio de ciencia de datos. Su objetivo es permitir la carga directa desde notebooks y scripts, sin necesidad de almacenar archivos pesados en el repositorio principal.

---

## 🗂️ Estructura

Los archivos están organizados de forma simple y accesible para ser consumidos desde otros repositorios o notebooks con `pandas.read_csv()`.

---

## 🔗 Cómo usar los datasets en tus notebooks

Puedes cargar un dataset directamente usando su enlace `raw`, por ejemplo:

```python
import pandas as pd

url = "https://github.com/Ramon-Bravo/datasets_publicos/raw/main/car_data.csv.gz"
df = pd.read_csv(url, compression='gzip')


Archivo | Descripción
games.csv | Dataset de videojuegos: nombres, años, plataformas y ventas globales
car_data.csv.gz | Dataset comprimido de autos usados para modelo de predicción de precios
megaline_calls.csv | Registros de llamadas de clientes de compañía de telefonía móvil
megaline_internet.csv | Consumo de internet por usuario en MB
megaline_messages.csv | Número de mensajes enviados por usuario
megaline_plans.csv | Detalles del plan contratado por cada usuario
megaline_users.csv | Información general de usuarios (ID, ciudad, plan, etc.)

CONTACTO

[LinkedIn](https://www.linkedin.com/in/ramon-wh-bravo-19a352290/)
- ✉️ [e.bravo.hp@outlook.com](mailto\:e.bravo.hp@outlook.com)
