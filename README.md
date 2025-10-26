# Challenge-Alura-Store

## 🎯 Propósito del Proyecto

Este análisis de datos tiene como objetivo identificar la **tienda menos eficiente** de la cadena Alura Store. El resultado es una recomendación estratégica para el Sr. Juan sobre qué tienda vender para **liberar capital** para un nuevo emprendimiento, manteniendo la estabilidad financiera del negocio principal.

## 💡 Conclusión Principal

La recomendación es vender la **Tienda 4**.

| Métrica | Tienda 1 (Máx Ingresos) | **Tienda 4 (Mínimo Financiero)** |
| :---: | :---: | :---: |
| **Ingresos Totales** | \$1.150 Millones | **\$1.038 Millones** |
| **Contribución (%)** | 26.1% | **23.6%** |

* **Justificación:** La Tienda 4 registra el **menor ingreso total** y la **menor contribución porcentual** a la facturación. Vender la unidad menos rentable minimiza el impacto en el flujo de caja, a pesar de que tiene el costo de envío más bajo de la cadena.

## 📊 Estructura y Análisis Clave

El proyecto se desarrolla en un cuaderno de Jupyter/Colab (Archivo `.ipynb`) utilizando **Pandas** y **Matplotlib**.

| Sección | Métrica Clave | Insight Relevante |
| :---: | :---: | :---: |
| **Facturación** | Ingresos Totales | La Tienda 4 es consistentemente la más baja en ingresos. |
| **Calidad y Costos** | Reseñas y Costo de Envío | La Tienda 1 es la más problemática: **peor reseña** (3.977) y **costo de envío más alto** (\$26,018.69). |
| **Visualización** | Gráficos Combinados | Los gráficos Circular y de Barras demuestran visualmente la baja contribución de la Tienda 4. |

## ⚙️ Ejecución del Notebook

El proyecto requiere **Python 3** con las librerías **Pandas** y **Matplotlib**.

1.  Abre el archivo `.ipynb` en **Google Colab**.
2.  Ejecuta la primera celda para **cargar los datos** desde GitHub.
3.  Ejecuta las celdas de análisis (Secciones 1 a 5) y la última celda para generar las **visualizaciones** que respaldan la recomendación.
