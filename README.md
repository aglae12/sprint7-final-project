# Análisis de Datos - ConnectaTel

## Objetivo del Proyecto
Analizar el comportamiento de uso de los clientes de ConnectaTel mediante técnicas de limpieza de datos, análisis exploratorio y segmentación para identificar patrones de consumo y oportunidades de negocio.

## Datasets Utilizados
- `users`: Información demográfica y planes de los clientes.
- `usage`: Registro histórico del tipo de uso (llamadas y mensajes), fechas y duraciones.

## Etapas del Análisis
1. **Inspección inicial y limpieza de datos:** Tratamiento de sentinels (`-999`, `?`), manejo de nulos estructurales (MAR) y corrección de fechas fuera de rango.
2. **Resumen estadístico:** Agregación de uso por usuario y análisis de distribución por tipo de plan.
3. **Visualización y Outliers:** Histogramas de consumo y detección de valores atípicos mediante el método IQR.
4. **Segmentación de clientes:** Clasificación según nivel de uso (Bajo, Medio, Alto) y grupos de edad.
5. **Insights ejecutivos:** Conclusiones estratégicas y recomendaciones comerciales.

## Instrucciones para Ejecutar
1. Abrir el archivo `.ipynb` directamente desde este repositorio.
2. Hacer clic en el botón **Open in Colab** o descargar el notebook y ejecutarlo localmente en Jupyter Notebook.
3. Asegurarse de tener instaladas las librerías: `pandas`, `seaborn`, `matplotlib` y `numpy`.
