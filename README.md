# Buscando_Alquiler_CienciaDeDatos
Análisis de Datos de Viviendas
 Este repositorio contiene código en Python para analizar datos de viviendas de diversas fuentes,
 incluyendo Housing Anywhere, Uniplaces y Spotahome. El código realiza tareas de limpieza,
 fusión y análisis de datos para responder preguntas específicas relacionadas con precios de
 viviendas, tamaños de habitaciones y preferencias de ubicación.
 Requisitos
 Python (3.x.x)
 Pandas (2.1.2)
 Numpy (1.26.1)
 Matplotlib (3.8.2)
 Seaborn (0.13.0)
 Fuentes de Datos
 rooms_data_housing.csv: Datos de viviendas de Housing Anywhere.
 rooms_data.csv: Datos de viviendas de Uniplaces.
 datosCasasPorColonia.xlsx: Datos de viviendas de Spotahome.
 Cómo ejecutar el código
 Mueva los datos de los 3 sitios web a la misma carpeta que el script python y ejecútelo.
 Resumen del Código
 1. Limpieza y Preparación de Datos
 Cargar y explorar el estado inicial de los data frames.
 Renombrar columnas para mayor claridad.
 2. Fusión de Data Frames con la Tabla Principal
 Realizar uniones izquierdas para fusionar cada data frame con la tabla principal
 utilizando la clave "IDENTIFICADOR".
 3. Análisis y Visualización de Datos
 Analizar y visualizar diversos aspectos de los datos, como:
 Comparación de precios promedio entre diferentes sitios web.
 Precios promedio según el número de habitaciones y baños.
 Relación entre el tamaño de la habitación y los precios.
 4. Análisis por Barrio
 Analizar datos de viviendas por barrios utilizando información de diferentes fuentes.
 Comparar precios promedio y cantidades de propiedades en diferentes barrios.
 5. Categorización y Visualización de Precios
Categorizar precios en intervalos y analizar la distribución de opciones de vivienda
 en cada categoría.
 Visualizar precios promedio según la cantidad de habitaciones y combinaciones de
 habitaciones/baños.
 Explorar la distribución de opciones de vivienda por categoría de precios.
 Integrantes
 Denisse Dominguez Bolaños
 
Daniel Rettberg Soler
 
Iris Sutizal Pablo
