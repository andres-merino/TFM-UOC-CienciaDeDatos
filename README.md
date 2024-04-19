<!-- PROJECT SHIELDS -->
[![Colaboradores][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Estrellas][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">TFM: Reconocimiento automático de imágenes para reconstrucción de redes planta-polinizador</h3>
  <p align="center">
    Trabajo de Fin de Master del Master Universitario en Ciencia de Datos de la UOC
  </p>
</div>

## Resumen TFM

El presente trabajo se centra en la construcción y entrenamiento de una red neuronal convolucional (CNN) con el objetivo principal de detectar polinizadores en imágenes de flores, lo que servirá como base para la reconstrucción de redes de interacción planta-polinizador. Los objetivos específicos incluyen la recopilación y etiquetado de alrededor de 5000 imágenes de polinizadores en dos hábitats de estudio en Cabrera, Islas Baleares; la evaluación de dos arquitecturas de redes neuronales convolucionales (YOLOv5 y EfficientNET) para la detección precisa de polinizadores (en grupos funcionales), el entrenamiento de la red seleccionada, la reconstrucción de una red de polinización a partir de las detecciones y la evaluación del desempeño utilizando métricas estándar sobre la red. Con los resultados de este trabajo, se busca poder automatizar la recolección y clasificación interacciones, entregando directamente la red de interacción planta-polinizador, que ofrezca información valiosa tanto para nuevas investigaciones como para la toma de decisiones en lo referente a agricultura y conservación.

### Construido con

![Jupyter Badge](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=fff&style=for-the-badge) ![Python Badge](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=for-the-badge) 

## Descripción

En este repositorio se puede encontrar los notebooks con el código necesario para replicar los resultados presentados en este proyecto. De manera específica, los notebooks que se pueden encontrar son los siguientes:
- [EfficientNET.ipynb](https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/blob/main/EfficientNet.ipynb): notebook con el código necesario para realizar el entrenamiento del modelo EfficientNet.
- [YOLOv5-entrenamiento.ipynb](https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/blob/main/YOLOv5-entrenamiento.ipynb): notebook con el código necesario para realizar el entrenamiento del modelo YOLOv5, este fue ejecutado en Google Colab.
- [YOLOv5-prediccion.ipynb](https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/blob/main/YOLOv5-prediccion.ipynb): notebook con el código necesario para realizar la predicción del modelo YOLOv5.
- [YOLOv5-prediccion-CrossVal.ipynb](https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/blob/main/YOLOv5-prediccion-CrossVal.ipynb): notebook con el código necesario para realizar la predicción del modelo YOLOv5 con validación cruzada.
- [EstimacionRedPolinizadores.ipynb](https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/blob/main/EstimacionRedPolinizadores.ipynb): notebook con el código necesario para realizar la estimación de la red de polinizadores.
- [RedPolinizadores.ipynb.ipynb](https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/blob/main/RedPolinizadores.ipynb): notebook con el código necesario para realizar el análisis de la red de polinizadores.

En el este [enlace](https://1drv.ms/f/s!AuK-ajP1UCYfoPF4K2pFOxNCGibnJg?e=RXUcK4), se puede acceder al repositorio particular de OneDrive del autor donde se puede encontrar los pesos de los modelos entrenados en este proyecto.
  
De manera específica, los pesos que se pueden encontrar son los siguientes:
- efficientnetb7_weights.h5: pesos del modelo EfficientNet.
- yolov5m_v01.pt: pesos del modelo YOLOv5, en su versión m.
- yolov5l_v01.pt: pesos del modelo YOLOv5 en su versión l.
- yolov5m_foldn.pt: pesos del modelo YOLOv5 en el fold n de la validación cruzada.

## Créditos

Andrés Merino\
[Proyecto Alephsub0](https://www.alephsub0.org/about/),\
Docente Investigador\
Pontificia Universidad Católica del Ecuador\
aemerinot@gmail.com\
[![LinkedIn][linkedin-shield]][linkedin-url-aemt]

## Licencia

Distribuido bajo la licencia MIT. 

[![MIT License][license-shield]][license-url]




<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/andres-merino/TFM-UOC-CienciaDeDatos.svg?style=for-the-badge
[contributors-url]: https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/andres-merino/TFM-UOC-CienciaDeDatos.svg?style=for-the-badge
[forks-url]: https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/forks
[stars-shield]: https://img.shields.io/github/stars/andres-merino/TFM-UOC-CienciaDeDatos?style=for-the-badge
[stars-url]: https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/stargazers
[issues-shield]: https://img.shields.io/github/issues/andres-merino/TFM-UOC-CienciaDeDatos.svg?style=for-the-badge
[issues-url]: https://github.com/andres-merino/TFM-UOC-CienciaDeDatos/issues
[license-shield]: https://img.shields.io/github/license/andres-merino/TFM-UOC-CienciaDeDatos.svg?style=for-the-badge
[license-url]: https://es.wikipedia.org/wiki/Licencia_MIT
[linkedin-shield]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url-aemt]: https://www.linkedin.com/in/andrés-merino-010a9b12b/

