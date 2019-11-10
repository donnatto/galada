---
layout: post
title:  ¿En qué consiste la computación cuántica? ¿Es realmente importante?
date:   2019-11-09
image:  post-03.jpg
img-author: jonassvidras
tags:   [Tecnología, Computación cuántica]
---
Hace unos días fuimos testigos de cómo [Google anunciaba haber alcanzado la supremacía cuántica](https://www.nature.com/articles/s41586-019-1666-5) a través de una máquina que solo necesita 200 segundos para resolver un problema que hasta una supercomputadora tardaría 10 000 años en cumplir.

Pero, **¿qué es la computación cuántica?**, **¿cuáles son sus bases?**, y **¿porque este suceso marca un antes y un después en el mundo digital?** Veremos de una forma fácil de comprender, las implicancias que esta tiene en la actualidad.

## Fundamentos de la Computación Clásica

<figure>
  <img src="{{site.baseurl}}/img/ibmq.webp" alt="IBM Quantum Computer">
  <figcaption class="image-caption">IBM Q</figcaption>
</figure>

El mundo digital está regido por ceros y unos, en donde **1** representa el paso de electricidad a través de un circuito, y el **0** la ausencia de esta. Cada representación de estos ceros o unos se conoce como un bit.

Este sistema es la base de todas las abstracciones que surgen a partir de esta, como por ejemplo la letra A que simplemente es una representación del número 65 (1000001 en sistema binario) en un contexto textual. Es por esto, y por una mayor eficiencia, que los bits son agrupados en bytes (8 bits), permitiendo una mayor abstracción.

Ahora pasemos a un contexto más visual. Para representar el color de cada pixel de la pantalla desde donde te encuentras leyendo esto, se utilizan 3 bytes, uno para la cantidad de **rojo**, otro para el **verde** y otro para el **azul**, dando lugar al conocido sistema **RGB** en donde se combinan estos para dar lugar al color que se desea obtener.

Así es como, si nos pondríamos a contar la cantidad de pixeles que tiene una imagen y la multiplicamos por 3 (una por cada byte), encontramos su tamaño en **bytes**, **kilobytes** (1024 bytes) o **megabytes** (1024 kilobytes).

## Computación cuántica vs clásica

<figure>
  <img src="{{site.baseurl}}/img/sycamore.jpg" alt="Procesador Sycamore">
  <figcaption class="image-caption">Procesador Sycamore de Google</figcaption>
</figure>

Ahora que tenemos un poco más de conocimiento acerca de Ciencias de la computación, sabemos que las computadoras normales realizan millones de procesos basados en ceros o unos. Pero imagina que en vez de tener un bit que represente un cero o uno, tengamos una unidad de medida que **sea un cero y uno simultáneamente**, algo así como el [gato de Schrödinger](https://www.youtube.com/watch?v=WMnjRIx3_XE)  que se encuentra vivo y muerto al mismo tiempo.

Esta es la unidad mínima de la información cuántica, llamado **quantum bit** o **qubit**, el cual utiliza un fenómeno cuántico conocido como entrelazamiento, permitiendo un mucho mayor nivel de procesamiento.

Veámoslo de la siguiente manera. Si tengo 1 bit y 1 qubit, con un bit se puede obtener 1 valor (cero o uno) mientras que con el qubit 2 (cero y uno). Con 2 bits puedo tener 2 valores, mientras que con el qubit tengo 4. La relación es **lineal** en el caso de los bits (n), mientras que, en el caso de los qubits, es **exponencial** (2<sup>n</sup>).

Es por esto que Google, habiendo desarrollado un procesador con 54 qubits (una capacidad de procesamiento de **2<sup>54</sup>** resultados), declaro haber alcanzado la supremacía cuántica. IBM, para sorpresa de algunos, se pronunció al respecto en [este artículo.](https://www.ibm.com/blogs/research/2019/10/on-quantum-supremacy/)

## ¿Hacia donde se dirige la computación cuántica?

Existen muchos mitos en cuanto a lo que una computadora cuántica puede o es capaz de hacer. Muchas personas creen que las computadoras cuánticas servirán para realizar las mismas tareas que hoy en día son llevadas a cabo por una computadora normal, pero de una manera mucho más rápida.

Sin embargo, los algoritmos cuánticos servirán para resolver problemas **de una forma distinta**, los cuales serían realizados mucho más eficientemente.

Tomemos como ejemplo la física cuántica. En el estudio de las leyes de la naturaleza **a escala atómica o de partículas**, la computación clásica se ha encontrado con un problema. Al intentar simular las mecánicas cuánticas, ésta tiene tantas variables que le es imposible a una computadora normal mantener el seguimiento de todas ellas. Es en este contexto que la computación cuántica entra a escena, teniendo la capacidad suficiente para el procesamiento de todas estas variables.

<figure>
  <img src="{{site.baseurl}}/img/security.jpg" alt="Seguridad">
  <figcaption class="image-caption">Imagen de <a href="https://unsplash.com/@theframedbear">@theframedbear</a></figcaption>
</figure>

Otra de las cuestiones que supone el surgimiento de la computación cuántica, es el **peligro que corre la criptografía en el mundo entero.**

Nuestro sistema criptográfico actual protege nuestros datos utilizando algoritmos de encriptación que reemplaza nuestra información por una serie de valores de tal complejidad que a una computadora normal le tomaría **miles de años** encontrarla a través de un ataque de fuerza bruta (probando miles de combinaciones hasta que eventualmente una sea la correcta).

Mientras tanto, una computadora cuántica sería capaz de encontrarla en **cuestión de segundos.**
Es por esto que actualmente se encuentra en desarrollo un [nuevo sistema de encriptación](https://www.scientificamerican.com/article/new-encryption-system-protects-data-from-quantum-computers/) que permita proteger nuestra información de las computadoras cuánticas.

Además, países como China y Estados Unidos consideran a la computación cuántica como prioridad nacional invirtiendo millones de dólares en la actualidad.

¿Qué crees que podamos esperar a futuro con el uso de estas nuevas tecnologías? ¿Qué otros usos piensas que se le pueda dar, que no sean capaces de realizarse en la actualidad?

Comparte el artículo si es que te interesó, y deja tu respuesta en la sección de comentarios.
