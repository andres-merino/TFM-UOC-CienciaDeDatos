# TFM-UOC-CienciaDeDatos
Código utilizado en el desarrollo de TFM «Reconocimiento automático de imágenes para reconstrucción de redes planta-polinizador», para la obtención del título de Master en Ciencia de Datos de la UOC

En este repositorio se puede encontrar los notebooks con el código necesario para replicar los resultados presentados en este proyecto. De manera específica, los notebooks que se pueden encontrar son los siguientes:
- [EfficientNET.ipynb](https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/blob/main/EfficientNet.ipynb): notebook con el código necesario para realizar el entrenamiento del modelo EfficientNet.
- YOLOv5-entrenamiento.ipynb: notebook con el código necesario para realizar el entrenamiento del modelo YOLOv5, este fue ejecutado en Google Colab.
- YOLOv5-prediccion.ipynb: notebook con el código necesario para realizar la predicción del modelo YOLOv5.
- YOLOv5-prediccion-CrossVal.ipynb: notebook con el código necesario para realizar la predicción del modelo YOLOv5 con validación cruzada.
- EstimacionRedPolinizadores.ipynb: notebook con el código necesario para realizar la estimación de la red de polinizadores.
- RedPolinizadores.ipynb.ipynb: notebook con el código necesario para realizar el análisis de la red de polinizadores.

En el siguiente enlace, se puede acceder al repositorio particular de OneDrive del autor donde se puede encontrar los pesos de los modelos entrenados en este proyecto.
  https://1drv.ms/f/s!AuK-ajP1UCYfoPF4K2pFOxNCGibnJg?e=RXUcK4

De manera específica, los pesos que se pueden encontrar son los siguientes:
- efficientnetb7_weights.h5: pesos del modelo EfficientNet.
- yolov5m_v01.pt: pesos del modelo YOLOv5, en su versión m.
- yolov5l_v01.pt: pesos del modelo YOLOv5 en su versión l.
- yolov5m_foldn.pt: pesos del modelo YOLOv5 en el fold n de la validación cruzada.
