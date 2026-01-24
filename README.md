Análisis de Fidelización y Actividad de Vuelos 

Evaluación Módulo 3

Este proyecto forma parte de la Evaluación del Módulo 3 del Bootcamp de Analisis de Datos de Adalab (Promo 59). El objetivo es realizar una exploración, limpieza y análisis estadístico de datos relacionados con la actividad de vuelos y el historial de lealtad de una base de clientes en Canadá.

Autora: María del Rocío Sánchez Gálvez

📋 Estructura del Proyecto
El análisis se divide en cuatro fases principales:

Fase 1: Exploración y Limpieza: Identificación de valores nulos, duplicados y corrección de tipos de datos.

Fase 2: Análisis Estadístico de variables numéricas y categóricas.

Fase 3: Visualización: Análisis gráfico de la relación entre variables (educación, salario, estado civil, etc.) y la reserva de vuelos.

Fase 4: Evaluación Estadística: Pruebas de hipótesis para determinar si existen diferencias significativas en la actividad de reserva de vuelos según el nivel educativo.

🛠️ Tecnologías y Librerías Utilizadas
Para el desarrollo de este proyecto se han utilizado las siguientes herramientas de Python:

Pandas & Numpy: Tratamiento y manipulación de estructuras de datos.

Seaborn & Matplotlib: Visualización de datos y generación de gráficos estadísticos.



📊 Datos Utilizados
Se han procesado dos conjuntos de datos principales:

Customer_Flight_Activity.csv: Contiene registros de vuelos reservados, distancia recorrida y puntos acumulados/canjeados.

Customer_Loyalty_History.csv: Contiene información demográfica de los clientes como ubicación, educación, salario y estado civil.

🔍 Hallazgos Principales
Limpieza de Datos: Se unificó el renombre de las columnas de forma coherente, se eliminó una columna que no se iba a utilizar y se cambiaron algutos datos a un tipo más adecuado.

Pruebas de Hipótesis: Aquí se llegaron a diversas conclusiones como, por ejemplo, que los meses donde más se reservaban vuelos eran los de verano, concretamente julio y el mes que menos reservas había era enero. 
Asímismo, se evidenció una fuerte relación entre la distancia de los vuelos y el número de puntos acumulados por los clientes. 
En cuanto a la ubicación de los clientes, se vio una notable diferencia entre las distintas provincias, siendo en sólo tres de ellas donde residía la mayor parte de los clientes.
Por otra parte, se acreditó que hay otros factores que hacen que los clientes vuelen más, como son el estado civil y el género, teniendo un salario mayor los que más nivel educativo tienen.
Por último, tamién se observó que la tarjeta que tiene casi la mitad de los clientes es la 'Star' 

Relación Educación-Vuelos: Mediante el análisis descriptivo, se observó que los promedios de vuelos reservados se mantienen estables entre los diferentes niveles educativos, sugiriendo una falta de correlación directa.

🚀 Cómo usar este repositorio
Se han de tener instaladas las librerías mencionadas en la sección de tecnologías.

Los archivos .csv se han de guardar dentro de una carpeta llamada files/.

Debe ejecutarse el archivo Rocio_Sanchez_EvaluacionModulo3.ipynb en caso de que se quiera realizar el análisis.