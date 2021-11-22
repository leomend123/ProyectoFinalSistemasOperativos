# ProyectoFinalSistemasOperativos
Los algoritmos son evaluados con cadenas de referencias, que son cadenas de números que indican las páginas que son referenciadas. La idea es simular cómo actúan los distintos algoritmos para estas cadenas, de forma tal de conocer su eficiencia.
En este proyecto los algoritmos que se van a codificar son: FIFO (First in First out) y LRU (Least recently used).

FIFO:
En el algoritmo FIFO, el sistema operativo lleva la cuenta de todas las páginas de la memoria en una cola, la página más antigua está al frente de la cola. Cuando hay que reemplazar una página, se selecciona la que está al frente de la cola para eliminarla.
El código genera automaticamente la secuencia de 30 procesos de 10 caracteres diferentes para lograr el funcionamiento correcto del algoritmo a través del programa.

LRU
En este algoritmo, el sistema operativo lleva la cuenta de todas las páginas de la memoria en una cola, la página más antigua está al frente de la cola. Cuando hay que reemplazar una página, la página que se ha utilizado menos recientemente se sustituye por la página entrante.
