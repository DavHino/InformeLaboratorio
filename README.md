# Informe N°1 LEYES DE KIRCHHOFF 

AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO
	 
## 1.PLANTEAMIENTO DE PROBLEMA

El problema que significa poder medir diferentes magnitudes en un circuito es esencial para elaborar un análisis correcto y así poder evitar cortocircuitos o fallas en el funcionamiento del circuito eléctrico, por ello es necesario saber cómo hacerlo tanto en la teoría como en la práctica, con la intención de comparar ambos datos, para ello se requiere conocer la función que cumple cada elemento en el circuito, las fórmulas a utilizar y los instrumentos que se usan para medir las diferentes magnitudes.

## 2.OBJETIVOS
-Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley 
de Kirchhoff de Corrientes.
-Medir y registrar las corrientes y voltajes de los elementos del circuito.
-Determinar el porcentaje de error de los datos medidos experimentalmente.

## 3.MARCO TEÓRICO
Ley de voltajes de Kirchhoff
La ley de voltajes de Kirchhoff nos dice que la sumatoria de voltajes en un camino cerrado es igual a cero, es decir, la suma de los aumentos y caídas de tensión es igual a cero.

![f1](https://user-images.githubusercontent.com/64505672/83993005-c43e9880-a917-11ea-859c-14703f357ff0.PNG)

Ley de corrientes de Kirchhoff
La ley de corrientes de Kirchhoff nos dice que la suma de las corrientes que ingresan a un nodo es igual a la suma de las corrientes que salen de él, por lo tanto:

![f2](https://user-images.githubusercontent.com/64505672/83993125-2a2b2000-a918-11ea-8b56-c83c35777fd6.PNG)
                                  
Ley de Ohm 
La ley de Ohm es ley fundamental para el análisis de circuitos electrónicos. Esta ley describe la relación entre el voltaje entre los terminales de un circuito, con la intensidad que cae en el  y la resistencia que presenta, por lo tanto:

![f3](https://user-images.githubusercontent.com/64505672/83993163-48911b80-a918-11ea-9ea6-7c244d53a649.PNG)
                         
Resistencias Equivalentes
Cuando un grupo de resistencias se puede simplificar en una sola, a esta resistencia se la llama resistencia equivalente y para obtenerla se considera si las resistencias están en serie o en paralelo de la siguiente manera:

En serie:     
                
![im1](https://user-images.githubusercontent.com/64505672/83993222-75453300-a918-11ea-9bfc-39c5c2f004b7.PNG)

Figura 1. Diagrama de circuito representando las resistencias en serie.


![f4](https://user-images.githubusercontent.com/64505672/83993256-8ee67a80-a918-11ea-8e98-cfff4dec8deb.PNG)



En Paralelo:                   

![im2](https://user-images.githubusercontent.com/64505672/83993290-9c036980-a918-11ea-9d69-fa4e07c058f2.PNG)
 
Figura 2. Diagrama de circuito representando las resistencias en paralelo


![f5](https://user-images.githubusercontent.com/64505672/83993339-bdfcec00-a918-11ea-8626-0b9c2708ac61.PNG)

## 4.DIAGRAMAS


![im3](https://user-images.githubusercontent.com/64505672/83993355-c9501780-a918-11ea-8ec3-14f0ddcba32f.PNG)

Figura 3. Dibujo del circuito resistivo mixto, detallando los nodos (azul) y corriente (morado) 		que pasa por cada una de las resistencias

Dentro de este circuito, se encuentran 5 resistencias y una fuente DC que otorga al circuito 10v. Se puede identificar que las resistencias R3 y R4 están en serie y la resistencia equivalente de estas (R), esta en paralelo con R2. Finalmente se puede obtener la resistencia equivalente del circuito sumando R1, R5 con el resultado de paralelo de R2 con R.


![im4](https://user-images.githubusercontent.com/64505672/83993373-d8cf6080-a918-11ea-8989-89a5e190844a.PNG)


Figura 4. Dibujo del circuito resistivo mixto, detallando la tensión (azul) que cae en cada una de las resistencias.

Dentro de la simulación digital, se utilizan dos multímetros para revisar la corriente y tensión de cada una de las resistencias y sus respectivos nodos. Se debe tener en cuenta el conectar en paralelo al multímetro cuando se requiera encontrar voltaje y en serie al estar buscando amperaje (corriente).

## 4.LISTA DE COMPONENTES

	A. Fuente de voltaje de C.D.
	
	B. Multímetros digitales.
	
	C. Resistor de 1 kΩ
	
	D. 2 Resistores de 2.2 kΩ
	
	E. Resistor de 1.8 kΩ
	
	F. Resistor de 3.9 kΩ
	
	G. Protoboard
	
	H. Cables conectores
	
	
## 7.CONCLUSIONES
A.Concluimos que el  porcentaje de error es muy pequeño en relación a las corrientes que se obtuvieron de forma  analítica con las       medidas, esto se  debe a que las resistencias poseen un porcentaje muy pequeño de error, especificado en la última banda de color de las resistencias, conocida como tolerancia.
 
B.Se puede concluir que se cumpe la Ley de Kirchhoff.  La corriente I1= 2.050mA medida , que entra en el segundo nodo  es experimentalmente igual a la sumatoria de las corrientes  I2=1,090 e I3=0.965 que sale por el mismo nodo con cierto grado de error, debido a la tolerancia. 

C.Se concluyó que se cumple la Ley de voltajes de Kirchhoff. Las sumatorias de voltajes en la malla uno es igual a 0, y además se comprobó que en el VR2=4.250 Y Veq= VR3+VR4=2.120+2.120=4.250 poseen el mismo voltaje , esto se debe a que se encuentran en paralelo.





