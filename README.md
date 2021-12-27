# TAREA 4
## 1.	OBJETIVOS

	1.1	GENERAL: 


	1.2	ESPECÍFICOS:

**a.**	
		
**b.**	

**c.**	

## 2.	MARCO TEÓRICO (RESUMEN)

### CAPÍTULO 7 :

	7–1 Identificación de relaciones en serie-paralelo
	
![1](https://user-images.githubusercontent.com/93396250/146879257-c8911531-5a32-490d-b85f-8ac747a42c2a.jpg)

	
	7–2 Análisis de circuitos resistivos en serie-paralelo 

![2](https://user-images.githubusercontent.com/93396250/146879273-8012cafd-0fe9-483e-9b61-0d7cb9f5723a.jpg)


	7–3 Divisores de voltaje con cargas resistivas 

![3](https://user-images.githubusercontent.com/93396250/146879290-417be375-6821-4dd1-9812-d628f99b6cab.jpg)


	7–4 Efecto de carga de un voltímetro 
	
Cuando la resistencia interna del voltímetro no es suficientemente más grande que la resistencia del circuito entre los extremos del cual está conectado, el efecto de carga hará que el voltaje medido sea menor que su valor real. Siempre se deberá estar consciente de este efecto

EJEMPLO: 

![image](https://user-images.githubusercontent.com/93396250/146879140-8bdca9d2-1f18-4d54-9c28-5d21c2efbb96.png)
![image](https://user-images.githubusercontent.com/93396250/146879160-9f2b67df-23ec-4af3-a26f-9edf47838615.png)

	7–5 Redes en escalera
	
![5](https://user-images.githubusercontent.com/93396250/146881363-e2b6ec5b-1eb6-4779-b9f4-eff5e1701246.jpg)

	
	7–6 El puente Wheatstone 
	
![6](https://user-images.githubusercontent.com/93396250/147421142-d19e4613-2997-4b2c-85a4-bde6984247df.jpg)

	
	7–7 Localización de fallas 

Algunas técnicas de localización de fallas y la aplicación de razonamiento lógico ya se analizaron en relación tanto con circuitos en serie como con circuitos en paralelo. Una premisa básica de la localización de fallas es que se debe saber qué buscar antes de poder localizar con éxito una falla en un circuito.

EJEMPLO: 

![image](https://user-images.githubusercontent.com/93396250/146879851-db98c897-01c0-4811-a9ab-71f2c6fd9eda.png)
![image](https://user-images.githubusercontent.com/93396250/146879868-2cf24a99-813e-4937-bb1a-0b70e424dccf.png)


### CAPÍTULO 8 : 
	
La fuente de voltaje de cd es uno de los principales tipos de fuente de energía la cual proporciona un voltaje constante a una carga, incluso cuando la resistencia de ésta varía. 
		
![8](https://user-images.githubusercontent.com/93834732/146826074-82017959-43f7-447f-90c8-fe11a6aafce2.PNG)

Ninguna fuente de voltaje es ideal; sin embargo, las fuentes de potencia regulada se aproximan a la situación ideal cuando funcionan dentro de la corriente de salida especificada.

Mientras más grande es RL, en comparación con RS, menos cambio ocurre en el voltaje de salida. El voltaje de salida disminuye significativamente conforme la resistencia de la carga se reduce en comparación con la resistencia interna de la fuente.

	8–2 La fuente de corriente
	

La fuente de corriente es otro tipo de fuente de energía que idealmente suministra una corriente constante a una carga, incluso cuando la resistencia de ésta varía. Aunque en la mayor parte del trabajo de análisis se puede utilizar la fuente de corriente ideal, ningún dispositivo real es ideal

![8 1](https://user-images.githubusercontent.com/93834732/146857573-ca2e865e-4284-4bb8-8a38-e17b759e719d.PNG)

Si la resistencia interna de la fuente, RS, es mucho más grande que un resistor de carga, la fuente práctica se aproxima a la fuente ideal.

	8–3 Conversiones de fuente

En ocasiones es útil convertir una fuente de voltaje en una fuente de corriente equivalente, o viceversa.

El voltaje de fuente, VS, dividido entre la resistencia interna de la fuente, RS, da el valor de la corriente de la fuente equivalente.

![8 3](https://user-images.githubusercontent.com/93834732/146857995-08a1c24f-f6d5-48df-800c-6387f69c5fa6.PNG)

La equivalencia terminal  significa que con cualquier resistencia de carga dada que se conecte a las dos fuentes, ambas fuentes producen el mismo voltaje de carga y la misma corriente de carga.

![8 4](https://user-images.githubusercontent.com/93834732/146863689-f7c5cf51-c403-4bf8-8726-db94d60fbb0f.PNG)


La corriente de la fuente, IS, multiplicada por la resistencia interna de la fuente, RS, da el valor del voltaje de la fuente equivalente.

![8 5](https://user-images.githubusercontent.com/93834732/146863781-771f488e-0aea-416c-997f-141e60c49034.PNG)


	8–4 El teorema de superposicion 
	
El método de superposición es una forma de determinar corrientes en un circuito con múltiples fuentes dejando una fuente a la vez y reemplazando las demás fuentes por sus resistencias

El método de superposición es una forma de determinar corrientes en un circuito con múltiples fuentes dejando una fuente a la vez y reemplazando las demás fuentes por sus resistencias internas. Es importante recalcar que una fuente de voltaje ideal tiene una resistencia interna de 0 y una fuente de corriente ideal tiene una resistencia interna infinita.
Los pasos para aplicar el método de superposición son los siguientes:

*Paso 1*

Dejar una fuente de voltaje (o de corriente) a la vez en el circuito y reemplazar cada una de las demás fuentes de voltaje (o de corriente) con su resistencia interna. Para fuentes ideales, un corto representa resistencia interna de cero y una abertura representa resistencia interna infinita. 

*Paso 2*

Determinar la corriente (o el voltaje) particular que se desea justo como si hubiera sólo una fuente en el circuito. 

*Paso 3*

Tomar la siguiente fuente que haya en el circuito y repetir los pasos 1 y 2. Hacer esto con cada una de las fuentes. 

*Paso 4* 

Sumar algebraicamente las corrientes producidas por cada fuente individual para encontrar la corriente real en una rama dada. (Si las corrientes están en la misma dirección, se suman. Si están en direcciones opuestas, se restan y la dirección de la corriente resultante será la misma que la presentada por la cantidad más grande de las
cantidades originales.) Una vez determinada la corriente, ya se puede calcular el voltaje mediante la ley de Ohm.

En el siguiente ejemplo se indica de manera grafica los pasos mencionados previamente.

![8 6](https://user-images.githubusercontent.com/93834732/146864478-6fe5f784-ab70-418a-affd-ecff4dae0c79.PNG)

	8–5 Teorema de Thevenin
	
Este se usa  para simplificar un circuito a una forma equivalente estándar. Se utiliza para hacer más sencillo el análisis de circuitos complejos.

La forma Thevenin equivalente de cualquier circuito resistivo de dos terminales consta de una fuente de voltaje equivalente (VTH) y una resistencia equivalente (RTH) como se indica en el siguiente grafico.

![8 7](https://user-images.githubusercontent.com/93834732/146865219-d78949c4-4665-4cb5-8bee-89fc0beb44b2.PNG)

*"En un circuito eléctrico, el voltaje equivalente de Thevenin (VTH) es el voltaje de circuito abierto (sin carga) presente entre dos terminales de salida."*

La resistencia equivalente de Thevenin (RTH) es la resistencia total que aparece entre dos terminales en un circuito dado que tiene todas las fuentes reemplazadas por sus resistencias internas. 

Para encontrar el equivalente de Thevenin de cualquier circuito, se determina el voltaje equivalente, VTH, y la resistencia equivalente, RTH, vistos desde las terminales de salida.

![8 8](https://user-images.githubusercontent.com/93834732/146865472-c84f5a47-6fef-4301-86ad-5241a28e4fff.PNG)

![8 9](https://user-images.githubusercontent.com/93834732/146865499-4f1a8aba-f31c-48d6-a71c-363d89d1a759.PNG)

El equivalente de Thevenin de cualquier circuito depende de la ubicación de las dos terminales de salida desde donde se “ve” dicho circuito.

En muchos casos, es de cierta ayuda thevenizar sólo una parte de un circuito como se muestra en el siguiente grafico.

![8 10](https://user-images.githubusercontent.com/93834732/146866141-ee1f739d-4157-48c9-9381-95983f8e0054.PNG)

Cabe mencionar que el teorema de Thevenin tambien puede ser usado para resolver circuitos puente como el del siguiente grafico.

![8 11](https://user-images.githubusercontent.com/93834732/146866265-813d0440-6234-42f8-bb44-10d05ec9ca83.PNG)

	8–6 Teorema de Norton
	
![Diagrama en blanco (4)](https://user-images.githubusercontent.com/93834732/146870496-7afaa955-64e4-4070-8863-975d9c4cecf8.png)

En  el siguiente grafico se muestra como aplicar estos pasos.

![8 12](https://user-images.githubusercontent.com/93834732/146870554-8a25ebcc-888e-4f96-b9ea-6f5f20bb4d13.PNG)


	8–7 Teorema de Trasnferencia de Potencia Maxima
	
Este teorema se usa cuando es importante cuando se tiene que conocer el valor de la carga con la cual la fuente suministra la máxima potencia.

Para una fuente de voltaje dada, la potencia máxima se transfiere desde una fuente hasta una carga cuando la resistencia de la carga es igual a la resistencia interna de la fuente.

![8 13](https://user-images.githubusercontent.com/93834732/146870787-71c78831-fc29-43d7-aaef-a5a65f338596.PNG)

Algunas aplicaciones prácticas del teorema de transferencia de potencia máxima incluyen sistemas de audio tales como aparatos estereofónicos, radios, y sistemas de alocución pública, etc. 

	8–8 Conversiones Delta a Y (V A Y) y Y a Delta (Y A V)
	
Las conversiones entre configuraciones de circuito tipo delta y tipo Y son útiles en ciertas aplicaciones especializadas de tres terminales.

![8 14](https://user-images.githubusercontent.com/93834732/146870983-131c3537-e19d-42f6-bed7-f3ca5e287419.PNG)

*Conversión V a Y*

Cada resistor localizado en la Y es igual al producto de los resistores incluidos en dos ramas delta adyacentes, dividido entre la suma de los tres resistores en delta.

![8 15](https://user-images.githubusercontent.com/93834732/146871053-a6277f57-704b-462a-9bbe-e0d6d78cdc6e.PNG)

![8 16](https://user-images.githubusercontent.com/93834732/146871078-0bf5e523-b076-4413-82ec-23d51eaec061.PNG)

![8 17](https://user-images.githubusercontent.com/93834732/146871121-dab0b593-c516-4184-8999-f42f3d655b48.PNG)

*Conversión Y a V*

Cada resistor incluido en la delta es igual a la suma de todos los posibles productos de resistores Y tomados dos a la vez, y divididos entre el resistor Y opuesto

![8 18](https://user-images.githubusercontent.com/93834732/146871279-5354d7a3-8d1d-4238-ad5f-d3b01324b0af.PNG)		

## 3.	EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

#### **CAPÍTULO 7 :**

	7-1 Identificación de relaciones en serie-paralelo
**1.  Visualice y trace las siguientes combinaciones en serie-paralelo:**
  (a) R1 en serie con la combinación en paralelo de R2 y R3
		
![Screenshot 2021-12-20 154406](https://user-images.githubusercontent.com/93826527/146830384-47201cee-f498-4b71-a460-cc283c11b37f.png)		
		
   (b) R1 en paralelo con la combinación en serie de R2 y R3
		   
![Screenshot 2021-12-20 160533](https://user-images.githubusercontent.com/93826527/146832703-3fc91a1e-7906-4894-b6a6-0e5c3823ad83.png)
		   
		   
   (c) R1 en paralelo con una rama que contiene R2 en serie con una combinación en paralelo de otros cuatro resistores
		   
![Screenshot 2021-12-20 160210](https://user-images.githubusercontent.com/93826527/146832327-d4189161-0912-4934-9775-a1989cd59b1c.png)		  















	7–2 Análisis de circuitos resistivos en serie-paralelo  

	7–3 Divisores de voltaje con cargas resistivas 

**25. Un divisor de voltaje está compuesto por dos resistores de 56 kΩ y una fuente de 15 V. Calcule el voltaje de salida sin carga ¿Cuál será el voltaje de salida si se conecta un resistor con carga de 1.0 MΩ a la salida?**

	Vsalida (sin carga) = (56/112)*15V ===> 7.5 V
	
	Vsalida (con resistor de 1.0 MΩ):
		Calculamos la resistencia en paralelo
		R2 || RL = (1/(1/56)+(1/1000)) = 53.03
		
	Vsalida (con carga) = (53.03/ 53.03 + 56) * 15V ===> 7.29 V
	
	
**27. Cuál de dos cargas, una de 10 kΩ y otra de 47 kΩ, provocará una disminución más pequeña en el voltaje de salida de un divisor de voltaje dado**

	Con la resistencia de 47kΩ
	Esto porque mientras más grande es RL en comparación con R2,
	menos se reduce el voltaje de salida con respecto a su valor sin carga.

**29. En la figura 7-74, determine el voltaje de salida con una carga de 33 kΩ conectada entre A y B**

![image](https://user-images.githubusercontent.com/93396250/147421770-b8eff7a4-16fb-4bd2-a1dd-02e793c30032.png)

	

**31. Determine los valores de resistencia para un divisor de voltaje que debe satisfacer las siguientes especificaciones: la corriente extraída de la fuente sin carga no debe exceder de 5 mA; el voltaje de fuente tiene que ser de 10 V, y las salidas requeridas deben ser de 5 y 2.5 V. Trace el circuito. Determine el efecto en los voltajes de salida si se conecta una carga de 1.0 kΩ a cada toma, una a la vez**

**33. La figura 7-76 muestra un circuito polarizador de cd para un amplificador de transistor de efecto de campo. La polarización es un método común empleado para establecer ciertos niveles de voltaje de cd para la operación apropiada de un amplificador. Aunque no se espera que usted conozca los amplificadores con transistores en este momento, los voltajes y las corrientes de cd presentes en el circuito pueden ser determinados con métodos ya conocidos**

   (a)  Encuentre VG y VS

   (b)  Determine I1, I2, ID, e IS

   (c)  Encuentre VDS y VDG
   
![image](https://user-images.githubusercontent.com/93396250/147421849-2bb05047-46af-4c0a-886d-0d9caa0cc53b.png)


**LOS TRANSISTORES DE EFECTO CAMPO NO SON TEMA DE ESTE PARCIAL POR LO QUE AUN NO SE VEN EN CLASE, POR ELLO EL EJERICIO NO SE REALIZARA**
	
	
	7–4 Efecto de carga de un voltímetro 
	
	7-5 Redes en escalera
	
	7–6 El puente Wheatstone
	
	7–7 Localización de fallas 



#### **CAPÍTULO 8 :**
	
	8–3 Conversiones de fuente 
	
**7. Con el método de superposición, encuentre la corriente a través de R5 en la figura 8-69.**

![image](https://user-images.githubusercontent.com/93396250/147422579-5b61b215-1874-4b0d-a742-39090c59e6ad.png)


**9. Con el teorema de superposición, determine la corriente a través de R3 en la figura 8-70.**

![image](https://user-images.githubusercontent.com/93396250/147422581-cf9d9228-4c99-46c2-84be-a70ed444b77e.png)


**11. En la figura 8-72 se muestra un circuito comparador. El voltaje de entrada, VENTRADA, se compara con el voltaje de referencia, VREFERENCIA, y se genera una salida negativa si VREFERENCIA > VENTRADA; de lo contrario es positiva. El comparador no carga a una u otra entrada. Si R2 es de 1.0 kÆ, ¿cuál es el intervalo del voltaje de referencia?**

![image](https://user-images.githubusercontent.com/93396250/147422591-3b66d26c-0e49-46a1-93cd-4cba9336cc89.png)

**13. Determine el voltaje del punto A al punto B en la figura 8-73**

**15. La figura 8-75 muestra dos redes en escalera. Determine la corriente producida por cada una de las baterías cuando se conectan las terminales A (A a A) y las terminales B (B a B).**





	8–4 El teorema de superposición 
	
**17. Con el teorema de Thevenin, determine la corriente a través de la carga RL en la figura 8-77.**

![image](https://user-images.githubusercontent.com/93396250/147422645-949c3d0c-b053-42a0-902d-522d23832393.png)

**19. Determine el equivalente de Thevenin para el circuito externo al amplificador de la figura 8-79.** 

![image](https://user-images.githubusercontent.com/93396250/147422659-edd0e11b-81c5-4ac0-8029-9de2523c5e17.png)

**21. Determine la corriente a través del resistor de carga en el circuito puente de la figura 8-81.**

![image](https://user-images.githubusercontent.com/93396250/147422667-53b2c2ce-a93c-4931-b8c6-4770993ba263.png)


	8–5 Teorema de Thevenin 
	
	
	8–6 Teorema de Norton 
	
	
	8–7 Teorema de transferencia de potencia máxima
	
	
	8–8 Conversiones delta a  Y (Δ a Y) y Y a delta (Y a Δ)


## 4. VIDEO
			
[![Presentación Tarea 1](https://img.youtube.com/vi/2iV6VzArCmY/0.jpg)](https://www.youtube.com/watch?v=2iV6VzArCmY)
	
## 5.	CONCLUSIONES
        

## 6.	BIBLIOGRAFÍA

Floyd, T. L. (2007). PRINCIPIOS DE CIRCUITOS ELÉCTRICOS - Octava edición. México: PEARSON EDUCACIÓN.

