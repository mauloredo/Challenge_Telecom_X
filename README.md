# Challenge Telecom X: Análisis y Modelado del Churn

## Descripción
Este proyecto explora el comportamiento de abandono (churn) de clientes en Telecom X. A través de técnicas de análisis exploratorio, visualizaciones y pruebas estadísticas, buscamos identificar variables que influyen en el churn para proponer estrategias de retención.

## Objetivos
- Analizar patrones de comportamiento relacionados con el churn.
- Identificar variables significativas (por ejemplo, tipo de contrato, cargos mensuales, antigüedad).
- Generar insights que permitan proponer recomendaciones para mejorar la retención de clientes.

## Estructura del Proyecto
- **Data:** Conjunto de datos provenientes de Telecom X en formato CSV.
- **ETL:** Procesos de extracción, limpieza y transformación de los datos.
- **Análisis Exploratorio:** Incluye tabulaciones cruzadas, pruebas de Chi-cuadrada y diagramas de dispersión.
- **Notebook Principal:** `Challenge_Telecom_X.ipynb` que contiene el flujo completo del análisis.
- **Visualizaciones:** Gráficos y diagramas generados para evidenciar patrones de churn.

## Tecnologías Utilizadas
- **Python** y sus librerías: pandas, NumPy, matplotlib, seaborn, etc.
- **Jupyter Notebook:** Para el desarrollo interactivo del análisis.
- **GitHub:** Para el control de versiones y la colaboración.

## Cómo Ejecutar el Proyecto
1. **Clona el repositorio:**
    ```bash
    git clone https://github.com/mauloredo/Challenge_Telecom_X.git
    ```
2. **Accede al directorio del proyecto:**
    ```bash
    cd Challenge_Telecom_X
    ```
3. **Abre el Notebook principal:**
    ```bash
    jupyter notebook Challenge_Telecom_X.ipynb
    ```

## Resultados y Conclusiones
El análisis reveló que la **antigüedad** de los clientes es un factor determinante en el churn, junto con el nivel de *Monthly Charges*. Los clientes con contratos mes a mes tienen mayor propensión al churn, especialmente cuando se combinan con altos cargos mensuales, lo que brinda insights valiosos para la retención.

## Contribución
¡Tu colaboración es bienvenida! Si deseas aportar ideas, mejoras o solucionar algún issue, realiza un fork del repositorio y envía un pull request con tus cambios.

## Licencia
Este proyecto está bajo la [Licencia MIT](LICENSE).

## Contacto
Para dudas, sugerencias o colaboraciones, puedes contactarme a través de [maurilorepina@gmail.com] o visitar mi [mauloredo](https://github.com/mauloredo).
