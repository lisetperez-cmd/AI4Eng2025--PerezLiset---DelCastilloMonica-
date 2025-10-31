# AI4Eng2025 - Perez Liset - Del Castillo Monica
# Competencia AI4Eng UdeA - Semestre 2025-2

## Integrantes
- Liset Pérez – Cédula: 1044509701 – Ingeniería Industrial  
- Mónica Del Castillo – Cédula: CC – Ingeniería Industrial

## Usuario de Kaggle
- Liset Pérez: lisetaperez 
- Mónica Del Castillo: 

## Entrega 2 - Preprocesamiento de Datos

### Notebook entregado
**`02 - preprocesado.ipynb`**

En este notebook se realiza la limpieza y transformación del dataset `train.csv`:
- Eliminación de duplicados y nulos  
- Conversión de la columna `timestamp` a formato de fecha  
- Creación de variables derivadas (`year`, `month`, `day`, `hour`)  
- Ajuste de valores atípicos en `meter_reading`  
- Exportación del dataset limpio como `train_clean.csv`  
- Visualización y análisis gráfico de resultados  

---

### Video explicativo (YouTube)  
**Enlace al video:** [https://youtu.be/tu_enlace_del_video]

El video incluye:
- Presentación de los integrantes (con cámara encendida)  
- Descripción breve del avance del proyecto  
- Explicación del notebook `02 - preprocesado.ipynb`  
- Dificultades encontradas y próximos pasos  

## Conclusiones del preprocesamiento

**Estructura del dataset:**  
Los datos fueron cargados correctamente (20.216.100 registros y 4 columnas).  

**Calidad de los datos:**  
No se encontraron valores nulos ni duplicados.  

**Preparación temporal:**  
Se generaron nuevas variables de tiempo (año, mes, día, hora).  

**Tratamiento de outliers:**  
Se ajustaron los valores extremos de `meter_reading` usando el rango intercuartílico.  

**Resultado final:**  
El dataset limpio se guardó como `train_clean.csv` y se verificó con gráficas descriptivas.
