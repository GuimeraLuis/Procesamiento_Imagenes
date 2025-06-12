Ejercicio Reconocimiento Facial utilizando cv2, mediapipe y gradio
(Laboratorio hecho en Python para aplicar conocimientos adquiridos en materia Procesamiento Digital de Imagenes)

12 de junio de 2025

por Luis Guimera

---------------------------------------
De que se trata?
Se trata de un script con extensión .ipynb donde se utilizan distintos métodos y funciones de algunas librerías de Python para identificar landmarks faciales imágenes 
y mostrar los mismos a través de una interfaz grafica.
   
---------------------------------------
Que contiene?

Lab 08 - Reconocimiento Facial con MediaPipe y Gradio.ipynb: contiene una serie de métodos y funciones para:
- el reconocimiento de rostros en imagenes
- el reconocimiento de landmarks en rostros para el dibujo de mallas faciales
- interfaz grafica para la carga de la imagen a procesar y visualizacion del resultado en la imagen

---------------------------------------
Como se usa?
1 - Se comienza cargando las librerías a utilizar
2 - Se genera una función para el procesamiento de una imagen
2.a - Se carga un modelo facemesh
2.b - Se detectan los puntos faciales
2.c - Se dibuja malla facial a partir landmarks obtenidos
3 - Se carga una imagen a elección (a través de la interfaz de Gradio)
4 - Se muestra el resultado de la imagen procesada (a través de la interfaz de Gradio)
 
