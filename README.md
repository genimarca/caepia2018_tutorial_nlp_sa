# CAEPIA-Tutorial: Natural Language Processing and Sentiment Analysis

(Spanish version below)

## Abstract

> The communication protocol between humans is natural language. Humans communicate with each other and express their private states using language in the form of text or speech. Furthermore, language may be considered as the projection of human knowledge and intelligence. Hence, natural language is the right source of data to understand humans, to represent their intelligence and to communicate with them. However, natural language is unstructured data and it cannot be directly used by a computer system.
>
> In this tutorial, we will describe how to represent natural language in order to be processed by a computer, or in other words, how to build features that represent natural language. We will introduce Deep Learning methods for the extraction of rich linguistic features from written utterances, not limited to superficial views of the text as a bag or sequence of words, but including the syntactic (structural) analysis of the text. Moreover, we will show the usefulness of these linguistic features for the development of opinion classification systems, which is crucial for Sentiment Analysis tasks. Likewise, we will focus on the development of polarity classification methods grounded in **Deep Learning**.

## Contents

We release the contents of the tutorial with the aim of easing the approach of artificial intelligent practitioners to area of Natural Language Processing and in particular to the task of Sentiment Analysis.

The tutorial has three parts:

1. Natural Langauge Processing. It is focused on the language representation techniques and parsing.
  File: 2018_caepia_tutorial_nlp.pdf

2. Sentiment Analysis. It is focused on the definition of the task and the description of some works.
  File: 2018_caepia_tutorial_sentiment_analysis.pdf

3. Classification examples. It is a python notebook with some examples of polarity classification systems, specifically:
   1. Linear classifier: SVM  with unigrams imputs weighted by TF-IDF.
   2. Non-linear classifier: RNN LSTM with unigrams imputs weighted by TF-IDF.
   3. Non-linear classifier: RNN LSTM with random embeddings.
   4. Non-linear classifier: RNN LSTM with pre-train embeddings.

   The data used for the classification is the training set of the [General Corpus of TASS](http://www.sepln.org/workshops/tass/). The access to the data requires the signment of a license, more info at: [TASS webpage](http://www.sepln.org/workshops/tass/).
   The set of Spanish pre-train word embeddgins was built upon a set of tweets written in Spanish and with the method FastText. The set of embeddings are not available, but if you are interested on that set, please, write an email to of the authors of the tutorial.

## Authors

* [Carlos Gómez-Rodríguez](http://www.grupolys.org/~cgomezr/) - University of La Coruña (Spain).
* [Eugenio Martínez Cámara](http://decsai.ugr.es/index.php?p=miembros&id=19952) - University of Granada (Spain).

------


>This repository contains experimental software and is published for the sole purpose of providing practical examples to the theoretical part of the tutorial.


#### Spanish version
## CAEPIA-Tutorial: Procesamiento del Lengujae Natural y Análisis de opiniones


## Resumen

> El protocolo de comunicación entre humanos es el lenguaje natural. Los seres humanos se comunican entre sí y expresan sus estados personales o emocionales mediante lenguaje oral o escrito. Además, el lenguaje se puede considerar como la proyección y concreción del conocimiento e inteligencia humana. Por tanto, el lenguaje natural es la fuente apropiada de datos para entender a los seres humanos, representar su conocimiento y comunicarse con ellos. Sin embargo, el lenguaje natural es un dato no estructurado y no puede ser utilizado directamente por un sistema informático.
> 
> En este tutorial, describiremos como representar el lenguaje natural para ser procesado por una computadora, es decir, como construir características que representen el lenguaje natural. Se expondrán métodos basados en redes neuronales (Deep Learning) para la extracción de características lingüísticas de calidad de enunciados escritos, las cuales no estarán constreñidas por una interpretación superficial del texto como puede ser la representación basada en bolsa de oraciones o palabras, sino que incluirán la estructura sintáctica del texto. Así mismo, se mostrará la utilidad de dichas características lingüísticas para el desarrollo de un sistema de clasificación de opiniones, elemento esencial de la tarea de Análisis de Opiniones. Además, se mostrará como desarrollar un sistema de clasificación de opiniones basado en el uso de **redes neuronales**.


## Cotenidos

Se publica el material del tutorial con el fin de facilitar que los interesados en técnicas de inteligencia artificial se acerquen al área del Procesamiento del Lenguaje Natural y en particular a la tarea de Análisis de Opiniones.

El tutorial se divide en tres partes:

1. Procesamiento del Lenguaje Natural. Se centra en técnicas de representación del lenguaje y en métodos de análisis sintáctico.
Fichero: 2018_caepia_tutorial_nlp.pdf
2. Análisis de Opiniones. Se centra en la definición de la tarea y en la descripción de algunos trabajos.
Fichero: 2018_caepia_tutorial_sentiment_analysis.pdf
3. Ejemplos de sistemas de clasificación. Cuaderno de python con algunos ejemplos de sistemas de clasificación de opiniones, en concreto:
   1. Clasificador lineal: SVM cuyas entradas son unigramas ponderados por TF-IDF.
   2. Clasificador no lineal: RNN LSTM cuyas entradas son unigramas ponderados por TF-IDF.
   3. Clasificador no lineal: RNN LSTM con embeddings aleatorios.
   4. Clasificador no lineal: RNN LSTM con embeddings pre-entrenados.

   Los datos usados en los ejemplos provienen del conjunto de entrenamiento del corpus [General Corpus of TASS](http://www.sepln.org/workshops/tass/). El acceso a los datos requiere de la firma de una licencia de uso, más información en la [web de TASS](http://www.sepln.org/workshops/tass/).
   El conjunto de embeddings pre-entrenados en español fue generado sobre tuits en español y usando el método FastText. El conjunto de embeddings no está disponible, pero si está interesado puede escribirle un correo electrónico a alguno de los autores del tutorial.
   
## Autores

* [Carlos Gómez-Rodríguez](http://www.grupolys.org/~cgomezr/) - Universidad de La Coruña (España).
* [Eugenio Martínez Cámara](http://decsai.ugr.es/index.php?p=miembros&id=19952) - Universidad de Granada (España).

------


>Este repositorio contiene código experimental con el único propósito de proporcionar ejemplos prácticos a la parte teórical del tutorial.
