# Informe N°1 LEYES DE KIRCHHOFF 

AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO
	 
## PLANTEAMIENTO DE PROBLEMA

El problema que significa poder medir diferentes magnitudes en un circuito es esencial para elaborar un análisis correcto y así poder evitar cortocircuitos o fallas en el funcionamiento del circuito eléctrico, por ello es necesario saber cómo hacerlo tanto en la teoría como en la práctica, con la intención de comparar ambos datos, para ello se requiere conocer la función que cumple cada elemento en el circuito, las fórmulas a utilizar y los instrumentos que se usan para medir las diferentes magnitudes.

## OBJETIVOS
-Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley 
de Kirchhoff de Corrientes.
-Medir y registrar las corrientes y voltajes de los elementos del circuito.
-Determinar el porcentaje de error de los datos medidos experimentalmente.

## MARCO TEÓRICO
Ley de voltajes de Kirchhoff
La ley de voltajes de Kirchhoff nos dice que la sumatoria de voltajes en un camino cerrado es igual a cero, es decir, la suma de los aumentos y caídas de tensión es igual a cero.

![f1](https://user-images.githubusercontent.com/64505672/83993005-c43e9880-a917-11ea-859c-14703f357ff0.PNG)

InformeLaboratorio/img/f1.PNG

Ley de corrientes de Kirchhoff
La ley de corrientes de Kirchhoff nos dice que la suma de las corrientes que ingresan a un nodo es igual a la suma de las corrientes que salen de él, por lo tanto:

                                    




Ley de Ohm 
La ley de Ohm es ley fundamental para el análisis de circuitos electrónicos. Esta ley describe la relación entre el voltaje entre los terminales de un circuito, con la intensidad que cae en el  y la resistencia que presenta, por lo tanto:

(3)                              




Resistencias Equivalentes
Cuando un grupo de resistencias se puede simplificar en una sola, a esta resistencia se la llama resistencia equivalente y para obtenerla se considera si las resistencias están en serie o en paralelo de la siguiente manera:

En serie:     
                





Figura 1. Diagrama de circuito representando las resistencias en serie.

(4)                           


En Paralelo:                   



 



Figura 2. Diagrama de circuito representando las resistencias en paralelo
(5)                  









DIAGRAMAS

	Figura 3. Dibujo del circuito resistivo mixto, detallando los nodos (azul) y corriente (morado) 		que pasa por cada una de las resistencias

Dentro de este circuito, se encuentran 5 resistencias y una fuente DC que otorga al circuito 10v. Se puede identificar que las resistencias R3 y R4 están en serie y la resistencia equivalente de estas (R), esta en paralelo con R2. Finalmente se puede obtener la resistencia equivalente del circuito sumando R1, R5 con el resultado de paralelo de R2 con R.

Figura 4. Dibujo del circuito resistivo mixto, detallando la tensión (azul) que cae en cada una de las resistencias.

Dentro de la simulación digital, se utilizan dos multímetros para revisar la corriente y tensión de cada una de las resistencias y sus respectivos nodos. Se debe tener en cuenta el conectar en paralelo al multímetro cuando se requiera encontrar voltaje y en serie al estar buscando amperaje (corriente).







