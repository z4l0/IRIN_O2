# IRIN_O2
## Repositorio utilizado en el trabajo obligatorio 2 de Introducción a la Robótica Inteligente: Robótica Evolutiva, realizado por Gonzalo Jaraba y Lucía Cepedano.

**Experimento 1**: fitness realizada a partir de la media aritmética de los valores de las baterías, generación de 5000. Se obseva que el robot realiza triángulos para pasar por las 3 luces. 

**Experimento 1.2**: misma fitness que el exp1, se añade aleatorización en la posición inicial (3 evaluaciones por cromosoma y 1500 generaciones). El robot sigue haciendo un triángulo, pero esta vez es uno que siempre pasa por debajo de la luz azul.

**Experimento 2**: fitness realizada a partir de la multiplicación de los 3 valores de las baterías, sin media, generación de 5000. El resultado en cuanto a fitness es peor (~0.45), pero el comportamiento es más natural, realizando movimientos curvos para mantenerse cerca de las 3 luces.

**Experimento 3**: fitness realizada a partir de la media geométrica: https://es.wikipedia.org/wiki/Media_geom%C3%A9trica. Generación de 5000. El resultado en cuanto a fitness es mejor que el caso anterior (~0.68). El robot realiza un recorrido similar al experimento 1 (en triángulo), pero de manera progresiva va curvando su recorrido al trazar las aristas de este mismo.

**Experimento 3.2**: misma función fitness que el anterior experimento, hemos ajustado los rangos de batería para que el robot haga menos recorrido por la periferia.

**Futuros Experimentos**:
**Experimento 4**: Hemos metidos luces en la fitness --> Cambiar params 
**Experimento 5**: CTRNN --> Cambiar todo
**Experimento 6**: CTRNN por partes
**Experimento 7**: CTRNN con varias muestras por cromosoma y entorno aleatorio
