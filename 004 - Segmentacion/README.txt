Segmentación con opencv, matplotlib, numpy
(Laboratorio hecho en Python para aplicar conocimientos adquiridos en materia Procesamiento Digital de Imagenes)

19 de abril de 2025

por Luis Guimera

---------------------------------------
De que se trata?
Se trata de un script con extensión .ipynb donde se utilizan distintos métodos y funciones de algunas librerías de Python para trabajar con imagenes  
---------------------------------------
Que contiene?

Lab 04 - Segmentacion.ipynb: contiene una serie de métodos y funciones para poder aplicar el proceso de segmentacion de una imagen por color, que consiste en localizar un área especifica de la imagen.
---------------------------------------
Como se usa?
1 - Se comienza cargando las librerías a utilizar
2 - Se carga una imagen a elección
3 - Se lleva a cabo la separación de canales y convertimos a escala de grises
4 - Se aplica peso promedio ponderado
5 - Se visualiza histograma de concentración de niveles
6 - Se aplica configuración de segmentación de umbrales por canal
7 - Se unifican canales
8 - Se eliminan pixeles aislados
9 - Se calculan las coordenadas de pixeles segmentados
10 - Con las coordenadas obtenidas se arman limites de rectángulo
11 - Se dibuja rectángulo con área especifica de la imagen, en nuestro caso con manzana roja