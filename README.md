# Jetson Nano DNN image
![output image]( https://qengineering.eu/images/SDcard32GBJetson.webp )<br/>
## A Jetson Nano image with OpenCV, TensorFlow and Pytorch
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/><br/>

------------

## Instalación

- Obtén una tarjeta SD de 128 GB (mínimo) que contendrá la imagen 

------------

## Tips.

* Si necesitas espacio adicional, puedes eliminar las carpetas opencv y opencv_contrib de la tarjeta SD. Ya no son necesarias ya que todas las bibliotecas se encuentran en el directorio /usr/ directory.
* Utiliza una herramienta como GParted sudo apt-get install gparted para expandir la imagen a tarjetas SD más grandes. Recomendamos un mínimo de 128 GB. El aprendizaje profundo simplemente requiere mucho espacio.<br/><br/>

------------

## OpenCV + TensorFlow.

Importar tanto TensorFlow como OpenCV en Python puede arrojar el error: no se puede asignar memoria en un bloque TLS estático.<br/>
Este comportamiento solo ocurre en un sistema aarch64 y es causado por los requisitos de memoria de OpenMP que no se cumplen<br/>

!


