# Evaluación Unidad 1 - Ingeniería Civil en Obras Civiles

Repositorio reproducible para la evaluación de la unidad, correspondiente al análisis estructural de vigas, organizado bajo los principios de investigación reproducible (datos, análisis, figuras y reporte).

## Estructura del Repositorio

El proyecto se encuentra organizado de la siguiente manera para distinguir claramente entre entradas, procesamiento, resultados y documentación:

- `data/`: Contiene los archivos de datos iniciales y parámetros del modelo.
  - `datos_viga.csv`: Datos numéricos de entrada para el análisis de la viga.
  - `parametros_viga.xlsx`: Parámetros geométricos y mecánicos iniciales.
- `analysis/`: Scripts y hojas de cálculo con el desarrollo del análisis estructural.
- `figures/`: Gráficos y figuras generadas a partir del análisis (ej. curvas de carga-deflexión).
- `report/`: Documentación técnica final.
  - `main.tex`: Código fuente del reporte en LaTeX.
  - `referencias.bib`: Base de datos bibliográfica.
  - `nota_tecnica.pdf`: Documento PDF compilado con la nota técnica.
- `USO_IA.md`: Registro del uso de herramientas de inteligencia artificial durante el desarrollo de la evaluación.

## Requisitos y Reproducibilidad
Para reproducir los análisis y la compilación del reporte, asegúrese de contar con un entorno compatible con LaTeX para el documento principal y software de hoja de cálculo o Python para la lectura de los archivos en la carpeta `data`.
