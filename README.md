# AlixPartners Data Analytics & BI Challenge - Caso de Estudio 2025

## 📌 1. Propósito del Repositorio
Este espacio contiene la preparación técnica, la simulación de arquitectura relacional y el pipeline de procesamiento de datos desarrollado como entrenamiento para la Competencia de Datos de AlixPartners. Se toma como base el caso histórico **"La Casa de Asterión (2025)"** para validar la manipulación de Big Data, la generación de estructuras dinámicas y la analítica orientada al negocio.

---

## 🛠️ 2. Fases de Ingeniería de Datos Implementadas
El desarrollo técnico fue estructurado en un cuaderno predictivo interactivo (`.ipynb`) bajo metodologías de alto rendimiento:

1.  **Optimización de Memoria (Big Data Wrangling):** Definición explícita de tipos de datos lógicos (`dtypes` eficientes como `int16` y `float32`) para mitigar el consumo de memoria RAM en el procesamiento de archivos transaccionales masivos (1.6 GB).
2.  **Cruce de Tablas Relacionales:** Consolidación de hechos y dimensiones mediante la unificación indexada (`pd.merge`) de tablas operativas con el maestro de productos a través de la clave común `sku_id`.
3.  **Pipeline de Sumisión R2:** Agrupación y formateo automatizado de registros mediante la concatenación técnica del ID compuesto exigido por el jurado evaluador para la plataforma Kaggle (`STORE_SUBGROUP_DATE_ID`).
4.  **Visualización Exploratoria Avanzada (EDA):** Renderizado de gráficos estáticos con Seaborn y Matplotlib para el análisis de distribución de demanda por subgrupos de negocio.

---

## 🎯 3. Resultados Visuales y Archivos de Salida
*   **Dataset Generado:** `submission_casa_asterion_2025.csv` (Validado con la estructura regulatoria del certamen).
*   **Análisis Gráfico:** El reporte incluye la distribución del volumen acumulado, identificando los activos críticos de rotación y facilitando la toma de decisiones para estrategias de pricing y márgenes de utilidad.

---

## 🚀 4. Tecnologías Utilizadas
*   **Lenguaje:** Python 3.x
*   **Librerías Críticas:** Pandas, NumPy, Matplotlib, Seaborn.
*   **Entorno:** Google Colab Cloud Infrastructure conectado de forma nativa.

*   ![Análisis Operativo](grafico_ventas_asterion.png)
