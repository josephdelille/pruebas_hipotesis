# 🧪 Pruebas Estadísticas y Pruebas A/B

Este proyecto pone en práctica conceptos de **hipótesis estadísticas** y **pruebas A/B**, aplicando además técnicas de **priorización de hipótesis** mediante los frameworks **ICE** y **RICE**.

## 📂 Estructura del proyecto

- **Importación y limpieza de datos**
  - Carga de datasets: `hypotheses_us-1.csv`, `orders_us-1.csv`, `visits_us-1.csv`
  - Conversión de columnas de fechas
- **Priorización de hipótesis**
  - Cálculo de métricas ICE y RICE
  - Ordenamiento de hipótesis según prioridad
- **Análisis de pruebas A/B**
  - Comparación de métricas entre grupos
  - Aplicación de pruebas estadísticas:
    - `ttest_ind` (prueba t de Student)
    - `proportions_ztest` (prueba de proporciones)
- **Conclusiones y recomendaciones**

## 🛠️ Requisitos

El proyecto está desarrollado en **Python 3.x** y utiliza las siguientes librerías:

```bash
numpy
pandas
matplotlib
scipy
statsmodels
```

Puedes instalarlas con:
```bash
pip install numpy pandas matplotlib scipy statsmodels
```

## 🚀 Uso
- Clona este repositorio o descarga el notebook.

- Asegúrate de tener los datasets en la carpeta de trabajo:

  - hypotheses_us-1.csv
  
  - orders_us-1.csv
  
  - visits_us-1.csv

- Ejecuta el notebook Pruebas_estadisticas.ipynb en Jupyter Notebook o JupyterLab.

Ejemplo para iniciar:
```bash
jupyter notebook Pruebas_estadisticas.ipynb
```

## 📈 Resultados esperados
- Lista priorizada de hipótesis según ICE y RICE.

- Comparación estadística entre grupos de pruebas A/B.

- Evaluación de la significancia estadística de las diferencias observadas.

- Recomendaciones basadas en los resultados.

## 📜 Licencia
Este proyecto se distribuye bajo la licencia MIT. Puedes usarlo, modificarlo y compartirlo libremente.
