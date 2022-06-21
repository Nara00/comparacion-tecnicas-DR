# Comparación de Técnicas de Reducción de Dimensionalidad

## Introducción
Curse of Dimentionality refiere a los problemas que conlleva trabajar con datos en múltiples dimensiones. Los algoritmos de reducción de dimensionalidad (DR) mapean el conjunto de los datos a subespacios derivados del espacio original, de menor dimensión, que permiten hacer una descripción de los datos a un menor costo. Los métodos de DR pueden enfocarse en conservar las distancias entre los puntos de datos dentro de los clústeres (estructura local) o entre los clústeres (estructura global).

El clustering consiste en separar un conjunto de datos en grupos que emergen naturalmente. De esta manera el algoritmo encuentra patrones y los datos caen naturalmente en ciertos grupos. Las técnicas de clustering aplicadas en el presente trabajo son HDBSCAN y k-means y las medidas externas para evaluar la agrupación rand score (medida de similitud entre dos agrupaciones de datos) y  adjusted mutual information score (medida de la dependencia mutua entre las dos variables).

## Objetivo
Evaluar y caracterizar las ventajas y desventajas de NeuralMap, UMAP y tSNE sobre bases de datos conocidas.

## Guía
La base de datos sobre la que se realizó el presente trabajo es MNIST, primero se realizó un sampleo aleatorio manteniendo la distribución de las clases que se encuentra en el archivo _sample-mist-DF_.

El archivo principal del trabajo es _MNIST_ donde se comparan los diferentes métodos, esta comparación se aplica sobre la base de datos Iris en el archivo _Iris_.

Los resultados del análisis se encuentran reflejados en el poster del archivo _Resultados.pdf_.

Por último cabe aclarar que los path de carga y guardado de archivos deben ser sustituidos por los pertinentes en su file system. Todos estos archivos pueden ser generados desde el código provisto, sin embargo se adjuntan ejemplos de ellos en la carpeta comprimida _MNIST-results_



## Autores

* [Ticiana Cobresi Serrevalle](https://github.com/Ticicobresiserr) - Facultad de Ingeneiría, Universidad Católica de Córdoba (UCC)
* [Nara Abril Nanfara](https://github.com/Nara00) - Facultad de Ingeneiría, Universidad Católica de Córdoba (UCC)
* Ing. Pablo Pastore - DeepVisionAi, inc.
* [Bioing. PhD Elmer Fernández](https://github.com/elmerfer) - CIDIE-CONICET-UCC
