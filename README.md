# Python para Data Science

Este repositorio hace parte de los cursos de Python para Data Science publicado en la plataforma de Alura Latam. Introduce los conceptos básicos de Python para ciencia de datos.

## Contenido

Se cubre los siguientes temas:

- Introducción a Python y Google Colaboratory
- Manipulación de datos
  - Variables
  - Tipos de variables
  - Variables numéricas
  - Strings
  - Captura de datos
- Estructuras condicionales
  - if
  - els
  - elif
  - Operadores lógicos
- Estructuras de repetición
  - While
  - For
- Estructuras de datos
  - Listas
  - Tuplas
  - Diccionarios
  - Conjuntos
- Bibliotecas:
    - Instalación e importación de bibliotecas
    - Utilizando módulos/bibliotecas
- Funciones:
    - Built-in function (Función Incorporada)
    - Creando funciones
        - Funciones sin parámetros
        - Funciones con parámetros
    - Funciones que retornan valores
    - Funciones lambda
        - Mapeando valores
- Estructuras de Datos Compuestas
    - Estructuras anidadas
        - Lista de listas
        - Lista de tuplas
    - List comprehension
    - Dict comprehension
- Challenge

## ¿Cómo usar?

1. Abre el notebook en Google Colab.
2. Ejecuta cada celda del notebook en orden.
3. Experimenta con el código y modifica los ejemplos para profundizar tu comprensión.

## Requisitos previos

* Una cuenta de Google
* Google Colab
* Curso [Python para Data Science: Primeros Pasos](https://app.aluracursos.com/course/python-data-science-primeros-pasos)
* Curso [Python para Data Science: trabajar con funciones, estructuras de datos y excepciones](https://app.aluracursos.com/course/python-data-science-trabajar-funciones-estructuras-datos-excepciones).

## Recursos adicionales

* [Documentación de Python](https://docs.python.org/es/3/)
* [Matplotlib](https://matplotlib.org/stable/tutorials/introductory/pyplot.html)
* [Random](https://docs.python.org/es/3/library/random.html)
* [Help](https://docs.python.org/es/3/library/functions.html?#help)
* [Built-in Functions](https://docs.python.org/es/3/library/functions.html)
* [Round](https://docs.python.org/es/3/library/functions.html#round)
* [Lambda](https://docs.python.org/es/3/reference/expressions.html?#lambda)
* [List Comprehensions](https://docs.python.org/es/3/tutorial/datastructures.html?#list-comprehensions)
* [Zip](https://docs.python.org/3/library/functions.html#zip)
* [Dict Comprehensions](https://peps.python.org/pep-0274/)

## Challenge

Este challenge tiene como objetivo analizar la rentabilidad de cuatro tiendas minoristas utilizando datos de ventas. El análisis se centra en identificar la tienda con menor rentabilidad para recomendar su venta posterior. Se consideran diversos factores como ingresos, ventas por categoría, calificaciones de clientes, productos más vendidos y costos de envío.

### Estructura

El proyecto se compone de un único archivo Jupyter Notebook:

* `Análisis_de_Rentabilidad_de_Tiendas.ipynb`: Contiene el código completo para el análisis, incluyendo la carga de datos, limpieza, análisis exploratorio, visualización y conclusiones.

### Ejemplos de Gráficos e Insights

**Gráfico de Ingresos por Tienda:**

![Gráfico de Ingresos por Tienda](https://github.com/J-R1v3r/python-data-science/blob/main/assets/Ingresos%20por%20Tienda.png?raw=true)

Este gráfico muestra que la Tienda 1 tiene los ingresos más altos, mientras que la Tienda 4 tiene los ingresos más bajos.

**Gráfico de Comparativa de Productos Vendidos por Categoría entre Tiendas:**

![Gráfico de Comparativa de Productos Vendidos por Categoría entre Tiendas](https://github.com/J-R1v3r/python-data-science/blob/main/assets/Comparativa%20Productos%20Vendidos%20por%20Categor%C3%ADa.png?raw=true)

Este gráfico muestra la cantidad de productos vendidos por categoría en cada tienda, identificando las categorías más populares.

**Gráfico de Comparativa de Precio Promedio por Categoría entre Tiendas:**

![Gráfico de Comparativa de Precio Promedio por Categoría entre Tiendas](https://github.com/J-R1v3r/python-data-science/blob/main/assets/Comparativa%20Precio%20Promedio%20por%20Categor%C3%ADa.png?raw=true)

**Correlación entre Precio y Costo de Envío por Tienda:** 

![Correlación entre Precio y Costo de Envío por Tienda](https://github.com/J-R1v3r/python-data-science/blob/main/assets/Correlacion%20Precio%20Costo%20de%20Env%C3%ADo.png?raw=true)

Este gráfico muestra la correlación que hay entre el precio total y el costo de envío total para cada tienda.

### Instrucciones para Ejecutar el Notebook

1. **Abrir en Google Colab:** Puedes abrir este notebook directamente en Google Colab haciendo clic en el botón "Abrir en Colab" en la parte superior del archivo.
2. **Instalar librerías:** El notebook requiere la instalación de la librería `folium` para la visualización de mapas. Se debe ejecutar la siguiente celda para instalarla: `python !pip install folium==0.14.0`.
3. **Ejecutar las celdas:** Se puede ejecutar el notebook paso a paso o ejecutar todas las celdas a la vez. Los gráficos y resultados se generarán en línea dentro del notebook.
4. **Análisis de resultados:** Observar los gráficos, tablas y resultados generados para obtener insights sobre la rentabilidad de las tiendas y determinar cuál tiene menor rentabilidad.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún error o tienes alguna sugerencia, por favor abre un issue o envía un pull request.
