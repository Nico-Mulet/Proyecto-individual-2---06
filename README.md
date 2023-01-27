# Proyecto-individual-2---06

El proyecto propuesto fue:<br>
​Usted ha sido contactado para el área de Machine Learning de una importante empresa inversora dentro del rubro de la inmobiliaria en Estados Unidos.​El Team Lider le propone dos predicciones posibles, de las cuales puede elegir cuál realizar (o ambas si así lo quiere):​

1) Implementar un modelo de clasificación con aprendizaje supervisado que permita clasificar el precio de las propiedades en venta, utilizando los datos que se han puesto a su disposición.​Para esto debe crear la columna category_price, en la cual se consideran las categorías <br>
'low': Para precios entre 0 y 999 dólares (debe tomar valor 1 en el archivo con las predicciones).<br>
'medium': Para precios entre 1000 y 1999 dólares (debe tomar valor 0 en el archivo con las predicciones).<br>
'high': Para precios desde 2000 dólares en adelante (debe tomar valor 0 en el archivo con las predicciones).<br>
​Considerando esta categorización, el objetivo es predecir si una propiedad pertenece a la categoría de precios bajos (low).​<br>
2) Implementar un modelo de clasificación con aprendizaje no supervisado, utilizando clustering que agrupe las propiedades por segun las 3 categorias a las que pueden pertenecer. Para ello, solo usaran el dataset de test provisto, eliminando previamente las caracteristicas que presenten nulos.​<br>

De lo cual yo elegi para realizar estre proyecto fue la opcion uno.<br>

Para empezar debiamos realizar un analisis de los DataFrame brindados de los cuales lo podemos encontrar aqui https://drive.google.com/drive/folders/1nJ9ZMj6E6zh6McC9NwCA6KopfUIOG_1O que cuenta con:<br>
1_'train.parquet': Contiene 346479 registros y 22 dimensiones, el cual incluye la información numérica del precio en la columna price.<br>
2_'test.csv': Contiene 38498 registros y 21 dimensiones, el cual no incluye la información del precio.<br>
Despues fue realizar un modelo de Machine Learning para predecir <br>
