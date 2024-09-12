TAREA 3. (11/0924):
##Formalismo
Al analizar el comportamiento de una función frente a distintos valores de un parámetro, como ϵ (donde ϵ > 0 es una entrada), es común estudiar cómo pequeños cambios en este parámetro afectan la gráfica de la función. Un enfoque típico utiliza nodos 
𝑛+1 para discretizar la función y estimar su derivada a través de métodos numéricos. Uno de los métodos más comunes es la diferencia finita, que calcula la derivada usando los valores de la función en nodos distribuidos en un intervalo.
Este método aproxima la pendiente de la función en cada nodo, proporcionando una derivada discreta. Aunque es eficiente y fácil de implementar, su precisión depende del número de nodos 
𝑛 y la distancia entre ellos. A mayor 
𝑛, la aproximación mejora debido a la reducción del error de truncamiento. El reto es determinar un valor óptimo de 
𝑛 para un valor dado de 
𝜖, de modo que aumentar más 
𝑛 no afecte significativamente la gráfica. Cuando el aumento de 
𝑛 ya no produce cambios importantes, se considera que la precisión es suficiente.
Este análisis es clave para funciones parametrizadas, permitiendo obtener una representación precisa sin gastar recursos computacionales innecesarios.

Algoritmos
Con lo anterior en mente, se estudiará una función para distintos valores de parámetros con 𝜖>0. Además, se analizará la derivada usando diferencias finitas y la integral de otra función mediante el método del trapecio y Gauss-Legendre, siguiendo el mismo procedimiento del ejercicio anterior.

Link: https://jupyter.org/try-jupyter/notebooks/index.html?path=Tarea+3+SSF.ipynb
