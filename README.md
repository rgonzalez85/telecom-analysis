# telecom-analysis
Análisis de comportamiento de clientes para el año 2024en la empresa ConnectaTel
## Objetivo General:
* Traducir datos de uso y perfiles de usuario en conclusiones accionables para los stakeholders. El análisis se enfoca en: 
* Identificar y corregir inconsistencias en la calidad de los datos.
* Segmentar a los usuarios por edad, nivel de uso y rentabilidad.
* Detectar comportamientos atípicos (outliers) que impactan la operación.
* Proponer recomendaciones estratégicas para mejorar la oferta comercial.
## Datasets Utilizados
* plans.csv: Detalles de los planes (Básico y Premium), precios, minutos/GB incluidos y costos por excedentes.
* users.csv: Información demográfica de los clientes (edad, ciudad, fecha de registro y plan actual).
* usage.csv: Registro detallado de la actividad real de servicios (duración de llamadas y cantidad de mensajes).
## Etapas del Análisis
* Exploración Inicial: Identificación de la estructura y tipos de datos.
* Limpieza y Preprocesamiento: Tratamiento de valores nulos (especialmente en la columna de ciudades), corrección de valores "Sentinels" en edades (-999) y manejo de tipos de datos.
* Análisis Estadístico: Cálculo de medidas de tendencia central y dispersión para entender el comportamiento promedio vs. extremos.
* Segmentación: Agrupación de usuarios según su plan y patrones de consumo.
* Generación de Insights: Traducción de hallazgos técnicos a recomendaciones de negocio.
## Como ejecutar el Notebook
1. Puedes dar click directamente en el archivo adjunto para visualizarlo sin realizar modificaciones
2. Abrir un nuevo notebook en Colab, seleccionar la opcion GitHub y seguir los pasos".
  2.1 Sube los archivos .csv a la sesión de Colab cuando el código lo solicite.
  2.2 Ejecuta las celdas en orden (Runtime > Run all).
## Guia de Reproduccion
* Para obtener los mismos resultados presentados en el análisis se debe:
* 1.	Utiliza los datasets originales proporcionados en la carpeta /data (o la raíz).
  2.	Sigue el orden secuencial de las celdas, ya que la fase de limpieza es necesaria para que las visualizaciones se generen correctamente.
  3.	Si utilizas un entorno virtual, se recomienda Python 3.8 o superior.
