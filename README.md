# 🛍️ Alura Store

## 📊 Descripción

Analizaremos datos para orientar al Sr. Juan a decidir qué tienda de su cadena "Alura Store" debe vender para iniciar un nuevo emprendimiento. Utilizaremos datos de ventas, rendimiento y reseñas de las 4 tiendas. El objetivo será identificar la menos eficiente y presentar una recomendación final basada en los datos.


## 🧰 Tecnologías utilizadas

- **Python** para codificar las métricas y **Jupyter Notebook (Google Colab)** para trabajar ahí.
- Datos **CSV** con la biblioteca **Pandas**.
- **NumPy** para análisis numérico.
- **Matplotlib** y **Seaborn** para crear gráficos estadísticos.
- **Contextily** para visualización geoespacial (requiere instalación adicional) y **GeoPandas** para trabajar los datos correspondientes

## 🗂️ Estructura del proyecto y organización de los archivos.
El proyecto está compuesto por 8 celdas de códigos de las cuales los archivos se organizan de la siguiente manera:

1. *Importación de datos*: Acá se extraen los archivos CSV con pandas para la correcta implementación de los datos en las siguientes celdas.
2. *Análisis de facturación*: En este primer análisis se calcula el ingreso total de cada tienda al sumando los valores de una columna llamada "Precio".
3. *Ventas por categoría*: Acá se calcula la cantidad de productos vendidos por categoría en cada tienda. La idea es agrupar los datos, contar el número de ventas y mostrar las categorías más populares.
4. *Calificación promedio de la tienda*: En este paso se calcula las calificaciones promedio de los clientes para cada tienda y conocer su satisfacción.
5. *Productos más y menos vendidos*: Aquí se identifican qué productos fueron los más vendidos y los menos vendidos en cada tienda.
6. *Envío promedio por tienda*: En esta sección se calcula el costo de envío promedio para cada tienda y se debe comprender cuánto se gasta en el envío.
7. *Análisis del desempeño geográfico*: En esta celda se explora las coordenadas geográficas de los datos de ventas y se identifican patrones relacionados con su ubicación. 
8. *Conclusión Final: Recomendación sobre la Tienda a Vender*: Por último, con base en los análisis y los gráficos, se redacta un informe final explicando los hallazgos obtenidos.

## 📈 Ejemplos de gráficos e insights obtenidos.

- 📊 Gráficos de columnas para los ingresos (celda 2)
- 🥧 Gráficos de torta para las categorías de productos vendidos (celda 3)
- 📉 Gráficos de barras horizontales para los productos más y menos vendidos (celda 5)
- 🗺️ Mapas geográficos con base de OpenStreetMap (celda 7)

## 🚀 Instrucciones para ejecutar el notebook.

1. Descarga el archivo `.ipynb` desde este repositorio.
2. Súbelo a tu [Google Drive](https://drive.google.com/) y ábrelo con [Google Colab](https://colab.research.google.com/).
3. Ejecuta las celdas en orden y comience por la importación de datos.

⚠️ Nota: Es necesario tener una cuenta en Google y GitHub. No olvides conectar el entorno de ejecución en Colab con Google Compute Engine y verificar que los archivos de datos estén correctamente cargados.
