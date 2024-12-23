# Monitoreo Predictivo de Pozos con Hydrogdatos

Este repositorio contiene el desarrollo de un proceso ETL basado en datos del sistema único, utilizado para el monitoreo y análisis de pozos.

En la reunión sobre el monitoreo de pozos con Hydrogdatos, se destacó la importancia de que un ingeniero de pozo pueda interpretar variables clave para ajustar el funcionamiento del equipo y tomar decisiones cruciales, como modificar la velocidad de la máquina o detectar la presencia de gas o arena.

El proceso ETL desarrollado extrae, transforma y carga datos en tiempo real, permitiendo prever problemas potenciales como el arenamiento de pozos, lo que facilita la toma de decisiones informadas para optimizar las operaciones y minimizar riesgos.

Este proyecto tiene como objetivo mejorar la eficiencia y seguridad en la operación de pozos, aplicando técnicas de procesamiento de datos a través de un flujo ETL para el monitoreo efectivo.

![](images/apache-spark-python-pyspark.jpg)

## Contenido
- [Requisitos](#requisitos)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instrucciones de Ejecución](#instrucciones-de-ejecución)

---

## Requisitos

Para ejecutar este proyecto, necesitas:

- **Google Colab**: Para ejecutar el código del proyecto en un entorno basado en la nube.
- **Python 3.x**: Para trabajar con PySpark y las bibliotecas requeridas.

Instala las dependencias necesarias dentro del notebook ejecutando:

```python
!pip install pyspark
```

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- **images/**
  Contiene imágenes relacionadas con el proyecto:
  - `apache-spark-python-pyspark.jpg` - Estructura de trabajo representada en Jupyter.

- **scripts/**
  Contiene los notebooks del proyecto:
  - `HydrogFinal.ipynb` - Desarrollo completo del modelo predictivo para monitoreo de pozos.

- **.gitignore**
  Archivo para excluir archivos innecesarios del control de versiones.

## Instrucciones de Ejecución

### Ejecución en Google Colab

1. Abre el archivo `HydrogFinal.ipynb` en Google Colab.
2. Asegúrate de que PySpark esté instalado ejecutando el siguiente comando en la primera celda:
   ```python
   !pip install pyspark
   ```
3. Ejecuta las celdas en orden para:
   - Procesar datos en tiempo real utilizando PySpark.
   - Construir y evaluar el modelo predictivo.
   - Generar visualizaciones de los resultados y conclusiones.

---
