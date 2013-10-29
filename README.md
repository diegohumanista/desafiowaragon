desafio Waragon
===============

Repositorio para participar del desafío Waragon

Tuve que hacerlo en javascript porque no tenía ningún lenguaje de programación instalado en la máquina (ahora hago mas tareas de análisis funcional que de programación)
Con respecto al problema en sí, primero que nada decidí representar las tortas en strings de 9 caracteres, porque me iba a permitir trabajarlo mejor en javascript. Tal vez en otro lenguaje hubiera usado una matriz de 3x3.
Luego, la parte que parecía facil (chequear si una torta es "rica") se volvió medio complicada al considerar el comodín (la masita). Así que si se estaba chequeando verticalmente era distinto que horizontalmente.
Por último, el problema de generar todas las tortas, que al principio parecía un caso de "fuerza bruta" luego resultó ser un poco mas complicado, porque los ingredientes repetidos eran idénticos entre sí y tenían una numeralidad acotada.
Ese último problema (el de la generación de las posibilidades) me tuvo pensando un rato mas, pero al final utilicé una solución como la que se utilizaría al recorrer un grafo, utilizando "dispensadores" de ingredientes (eso lo permite visualizar mejor)
