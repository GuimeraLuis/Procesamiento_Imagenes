Ejercicio Integrador con opencv, matplotlib, numpy
(Laboratorio hecho en Python para aplicar conocimientos adquiridos en materia Procesamiento Digital de Imagenes)

05 de mayo de 2025

por Luis Guimera

---------------------------------------
De que se trata?
Se trata de un script con extensión .ipynb donde se utilizan distintos métodos y funciones de algunas librerías de Python para trabajar con imagenes  
---------------------------------------
Que contiene?

Lab 05 - Ejercicio Integrador.ipynb: contiene una serie de métodos y funciones para:
- el análisis del espacio de color de una imagen
- aplicar el proceso de muestreo espacial de una imagen
- aplicar el proceso de cuantizacion de una imagen
- poder aplicar el proceso de segmentacion de una imagen por color

---------------------------------------
Como se usa?
1 - Se comienza cargando las librerías a utilizar
2 - Se carga una imagen a elección
3 - Se lleva a cabo la separación de canales y convertimos a escala de grises
4 - Se aplican distintos métodos y ciclos para la extracción de pixeles de la imagen seleccionada. 
5 - Se utilizan los pixeles extraidos para la creación de una nueva imagen
6 - Se visualizan las distintas imágenes creadas con distintos factores de muestreo para poder apreciar la técnica
7 - Se aplican distintos métodos para la disminución de niveles de profundidad. 
8 - Se utilizan los resultados para la creación de una nueva imagen
9 - Se visualizan las distintas imágenes creadas con distintos factores de cuantizacion para poder apreciar la técnica
10 - Se configuran y muestran los histogramas de la imagen original y de las imagenes donde se aplicó la cuantización.
11 - Se aplica peso promedio ponderado
12 - Se visualiza histograma de concentración de niveles
13 - Se aplica configuración de segmentación de umbrales por canal
14 - Se unifican canales
15 - Se eliminan pixeles aislados
16 - Se calculan las coordenadas de pixeles segmentados
17 - Con las coordenadas obtenidas se arman limites de rectángulo
18 - Se dibuja rectángulo con área especifica de la imagen, en nuestro caso con manzana roja