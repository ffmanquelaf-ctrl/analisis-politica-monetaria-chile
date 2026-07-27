# Análisis de la Política Monetaria e Inflación en Chile (2018-2026)

## Resumen del Proyecto
Este proyecto analiza la relación entre la **Tasa de Política Monetaria (TPM)** y la **Variación Mensual del IPC** utilizando datos oficiales extraídos de la Base de Datos Estadísticos del Banco Central de Chile. 

El objetivo es evaluar el comportamiento del ciclo contractivo de la política monetaria implementado para contener las presiones inflacionarias post-pandemia y su posterior fase de normalización.

---

## Hallazgos
* **Pico Inflacionario:** En marzo de 2022, la variación mensual del IPC alcanzó su máximo de **1.9%**.
* **Respuesta Monetaria:** En respuesta, el Banco Central elevó la TPM desde un piso de **0.5%** hasta un techo de **11.25%** (noviembre de 2022).
* **Estabilización:** El enfriamiento de la demanda logró contener el IPC, permitiendo un ciclo de recortes progresivos hacia un nivel cercano al **4.5%**.

---

## Herramientas y Librerías Utilizadas
* **Lenguaje:** Python 3.x
* **Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Lectura de Fuentes:** OpenPyXL (Archivos Excel del BCCh)

---

## Estructura del Repositorio
* `analisis_tpm_ipc.ipynb`: Cuaderno de Jupyter con el flujo completo de limpieza, agrupación mensual, gráfico de doble eje y métricas.
* `datos_banco_central_TPM.xlsx`: Serie histórica diaria de la TPM (BCCh).
* `datos_banco_central_IPC.xlsx`: Serie histórica mensual del IPC (BCCh).
