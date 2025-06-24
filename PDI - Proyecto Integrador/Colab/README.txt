Proyecto Integrador Reconocimiento Facial utilizando cv2 y mediapipe para la detección de somnolencia
(Script hecho en Python donde se aplican conocimientos adquiridos en materia Procesamiento Digital de Imágenes)

24 de junio de 2025

por Luis Guimera

---------------------------------------
De que se trata?
Se trata de un script con extensión .ipynb donde se utilizan distintos métodos y funciones de algunas librerías de Python para detectar somnolencia gracias al calculo del promedio de ear de los ojos detectados en videos, ya grabados o desde la cámara y a través de una interfaz gráfica creada por Gradio   
---------------------------------------
Que contiene?

PDI_Proyecto Integrador - Detección_de Somnolencia.ipynb: contiene una serie de métodos y funciones para:
- reconocer landmarks faciales
- obtener los puntos faciales correspondientes a los ojos del rostro detectado
- determinar la apertura de ojos, a trevés del calculo de ear de cada ojo
- lanzar alarma si el promedio de ear es menor a umbral determinado (lo que supone estado de somnolencia) 

---------------------------------------
Como se usa?
1 - Se comienza cargando las librerías a utilizar
2 - Se carga un modelo facemesh
3 - Se crea interfaz grafica con Gradio para carga de video a analizar
4 - Se detectan los puntos faciales y se guardan los correspondientes a los ojos
5 - Se calculan la apertura de los ojos a partir del promedio de ear de ojos 
5 - Muestra resultado calculado en interfaz grafica y alerta en caso de no superar el umbral determinado.

----------------------------------------
Anexos
Se fue trabajando de manera gradual en distintos archivos .ipynb con procesos incrementales para llegar a la detección de ear menor a un umbral
- PDI_PI_A - Landmarks_Faciales_con_Mediapipe.ipynb
- PDI_PI_B - Calculo_EAR_con_Mediapipe_y_Gradio.ipynb