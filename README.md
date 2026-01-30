#  Análisis de Ventas – Alura Store LATAM

##  Descripción del Proyecto

Este proyecto consiste en un **análisis exploratorio de datos** de las ventas de **el Sr Juan**, utilizando información de **cuatro tiendas diferentes**. El análisis se desarrolló en Python con el objetivo de obtener identioficar la tienda menos eficiente y apoyar la **toma de decisiones para vender esta**.



---

##  Propósito del Análisis

El objetivo principal del proyecto es:

* Calcular la **facturación total por tienda**, incluyendo el costo de envío.
* Analizar la **calificación promedio** de cada tienda.
* Identificar el **costo de envío promedio** por tienda.
* Determinar las **categorías de productos más populares** en cada tienda.
* Identificar los **productos más y menos vendidos** por tienda.
* Visualizar los resultados mediante **gráficos claros y comparativos**.

Este análisis permite comparar el rendimiento de cada tienda y detectar oportunidades de mejora.

---

##  Estructura del Proyecto

```

├── challenge1.ipynb   # Notebook principal con todo el análisis
├── README.md              # Documentación del proyecto
```

Los datos se cargan directamente desde URLs públicas proporcionadas por Alura, por lo que no es necesario descargar archivos CSV localmente.

---

##  Análisis y Gráficos Realizados

Durante el desarrollo del notebook se obtuvieron los siguientes análisis:

###  Facturación por Tienda

* Se calculó sumando el **Precio del producto + Costo de envío**.
* Se comparó la facturación total de las cuatro tiendas.
* Se visualizó mediante **gráficos de barras** usando Matplotlib.

###  Calificación Promedio por Tienda

* Se calculó el promedio de la columna **Calificación**.
* Se representó mediante gráficos para facilitar la comparación entre tiendas.

###  Costo de Envío Promedio

* Se calculó el costo de envío promedio por tienda.
* Se visualizó utilizando un **gráfico de torta (pie chart)**.

###  Categorías Más Populares

* Se identificaron las categorías con mayor número de ventas por tienda usando `value_counts()`.
* Los resultados se presentaron en **tablas organizadas** para facilitar la lectura.

### Productos Más y Menos Vendidos

* Se identificaron los productos con mayor y menor cantidad de ventas por tienda.
* Se utilizó ordenamiento de frecuencias para obtener los rankings.

---

##  Insights Obtenidos

Algunos hallazgos importantes del análisis:

* Existen **diferencias claras en la facturación** entre las tiendas.
* Las **categorías más populares** no son iguales en todas las tiendas.
* El **costo de envío promedio** impacta de forma distinta en cada tienda.
* Las tiendas con **mejor calificación promedio** no siempre son las de mayor facturación.

Estos insights pueden ser utilizados para mejorar estrategias comerciales, logísticas y de atención al cliente.

---

##  Instrucciones para Ejecutar el Proyecto

1. Clona este repositorio:

   ```bash
   git clone https://github.com/ElJorsh/CHALLENGE_1.git
   ```

2. Abre el proyecto en Jupyter Notebook o Google Colab.

3. Asegúrate de tener instaladas las siguientes librerías:

 
   pip install pandas matplotlib
  







##  Tecnologías Utilizadas

* Python 🐍
* Pandas
* Matplotlib
* Colab

---

## 📬 Autor

Jorge Andres Rodriguez Romero  Desafío Alura LATAM – Data Analysis

 Ideal para portafolio de análisis de datos y práctica de fundamentos de Python para Data Science.

