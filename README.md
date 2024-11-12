# Prediccion-oleaje
Este repositorio corresponde a la entrega 6 de la asignatura Analisis de Datos de 4t curso de Matematicas en la UIB.
En este trabajo crearemos una base de datos aleatoria a partir de una matriz de covarianzas y un vector de medias. Además
hemos añadido algunas dependencias temporales para que la práctica sea más interesante.

Este trabajo es para practicar distintos comandos de R asi como conceptos básicos de análisis multivariante e inferencia 
estadística. Nuestra principal fuente de información han sido los apuntes de la asignatura que podemos encontrar en este 
[repositorio](https://github.com/AprendeR-UIB/AD.git) de la profesora [Irene]().

También hemos unido nuestros datos aleatorios con los datos de un proyecto ya realizado en Kaggle por [nom autor](), que
dejamos [aqui]()

## Resumen
En el proyecto analizamos varias variables que podriían influenciar en el oleaje. Nos centramos en las características que
podrían interesar al surfista como la altura, el periodo o la energia. 

Hemos supuesto que para nuestro análisis teniamos una boya para medir la altura de una ola y el periodo. Asi como un medidor 
del viento. Sin embargo el ayuntamiento de Bilbao no dispone de las herramientas para analizar la energía de las olas y ha 
alquilado a una empresa una boya capaz de medir la energía de las olas. Esta ha recojido un total de 200 datos en 100 días.
Se hacía una medición cada 12 horas, una por la mañana y otra por la tarde (con la marea alta y baja). Entonces el ayuntamiento
pretende poder preveer cual será la energía de las olas con su boya más austera. Además de aportar en que datos se debe centrar
el surfista para poder garantizarse un buen dia de surf.
