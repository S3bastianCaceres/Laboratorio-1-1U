# Laboratorio-1-1U
 Laboratorio 

**1 OBJETIVOS**

- **Objetivo General**

Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de Kirchhoff de Corrientes mediante su representación con un circuito mixto en el simulador Tinkercad, lo cual ayudara al estudio de circuitos resistivos con fuentes de diferencia de potencial continuo.

- **Objetivos Específicos**

- Verificar mediante la simulación las leyes de la conservación de energía electrica y la conservación de carga.

- Interpretar de manera correcta el diagrama del circuito para poder reproducirlo en el simulador y asi obtener las mediciones correctas.

- Aplicar conocimientos teoricos como formulas y conceptos clave que ayuden a resolver de forma adecuada las ejercicios planteados.




























**2.MARCO TEÓRICO**

**Ley de las corrientes de Kirchhoff**

![Marco Teorico](https://user-images.githubusercontent.com/93739242/141380900-caacbabf-1214-4cd2-b78c-a052c58683ff.jpeg)

**Ley de los voltajes de Kirchhoff**

[![Voltaje-de-Kirchhoff.png](https://i.postimg.cc/5yXTHNmN/Voltaje-de-Kirchhoff.png)](https://postimg.cc/jnrZmT9G)

















































**3.EXPLICACIÓN DEL PROCEDIMIENTO**

**Materiales y equipo requerido**

|**Cantidad**|**Material o equipo**|
|----|----|
|1|Fuente de Voltaje de C.D.|
|2|Multímetros Digitales|
|1|Resistor de 1kΩ|
|2|Resistores de 2.2 kΩ|
|1|Resistores de 1.8 kΩ|
|1|Resistores de 3.9 kΩ|
|1|Protoboard|

Arme el circuito que se muestra en la figura 1.1.

![image](https://user-images.githubusercontent.com/93739242/141354630-7fb2ebbe-ca95-4d70-aece-c4ec74589ae0.png)

Mida el voltaje y corriente en cada uno de los elementos del circuito. Anote los
resultados de las mediciones en la **tabla 1.1**.

Datos teóricos

[![Datos-tabla-1.png](https://i.postimg.cc/tTtwWxhk/Datos-tabla-1.png)](https://postimg.cc/Kkj0y4p3)

[![Datos-tabla-1-1.png](https://i.postimg.cc/FzHWSnFF/Datos-tabla-1-1.png)](https://postimg.cc/mzKyfjFK)











































**4.RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**

Tabla 1.1. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

| **VARIABLE** | **VALOR CALCULADO** | **VALOR MEDIDO** |**%ERROR**
| ------------- | ------------- | ------------- | ------------- |
| VR1 (V)  |        2.05          |      2.05 V           |0%|
| IR1 (mA)  |       2.05       |     2.05 mA            |0%|
| VR2 (V)  |        4.26  |      4.25 V             |0.23%|
| IR2 (mA)  |       1.09          |     1.09 mA           |0%|
| VR3 (V)  |        2.13     |     2.12 V            |0.46%|
| IR3 (mA)  |       0.9681  |    0.965 mA           |0.32%|
| VR4 (V)  |        2.13       |      2.12 V           |0.46%|
| IR4 (mA)  |       0.9681        |    0.965 mA           |0.32%|
| VR5 (V)  |        3.69       |       3.70 V          |0.27%|
| IR5 (mA)  |       2.05        |     2.05 mA            |0%|

Tabla 1.2. Verificación de la LVK.
|  | **Trayectoria 1**     | | **Trayectoria 2** | | **Trayectoria 3** | |
| ------------- | ------------- |----------| ------------- |------------- |----------| ------------- |
| **VOLTAJE**  |**Calculado**|**Medido**|**Calculado**|**Medido**|**Calculado**|**Medido**|
| VT (V)  |      |    |    |     |      |      |
| VR1 (V) | 2.05| 2.05|    |     | 2.05   |2.05      |
| VR2 (V) | 4.26| 4.25| 4.26|4.25|      |      |
| VR3 (V) |   |       | 2.13|2.12| 2.13 |  2.12    |
| VR4 (V) |   |       | 2.13|2.12| 2.13 |  2.12   |
| VR5 (V) |3.69| 3.70|     |     |  3.69| 3.70
|  ΣV (V) | 10  |10      |8.52  |8.49 |10      |9.99      |

Tabla 1.3. Verificación de la LCK.

|  | **Nodo 1** | | **Nodo 2** | | **Nodo 3** | | **Nodo 4** | | **Nodo 5** | |
| ------------- | ------------- |----------| ------------- |------------- |----------| ------------- | ------------- |------------- |----------| ------------- |
|**CORRIENTE**|**Calculado**|**Medido**|**Calculado**|**Medido**|**Calculado**|**Medido**|**Calculado**|**Medido**|**Calculado**|**Medido**|
| IT (A)  |2.05 mA|2.05 mA|2.05 mA|2.05 mA|0.9681 mA|0.965mA|0.9681 mA|0.965mA|0.9681 mA|0.965mA|
| IR1 (A) |2.05 mA|2.05mA|2.05 mA|2.05mA|2.05 mA|2.05mA|2.05 mA|2.05mA|2.05 mA|2.05mA|
| IR2 (A) |1.09 mA|1.09 mA|1.09 mA|1.09 mA|1.09 mA|1.09 mA|1.09 mA|1.09 mA|1.09 mA|1.09 mA|
| IR3 (A) |0.9681 mA|0.965mA|0.9681 mA|0.965mA|0.9681 mA|0.965mA|0.9681 mA|0.965mA|0.9681 mA|0.965mA|
| IR4 (A) |0.9681 mA|0.965mA|0.9681 mA|0.965mA|0.9681 mA|0.965mA| 0.9681 mA|0.965mA|0.9681 mA|0.965mA|
| IR5 (A) |2.05 mA  |2.05 mA|2.05 mA|2.05 mA|2.05 mA|2.05 mA|2.05 mA|2.05 mA|2.05 mA|2.05 mA|
|  ΣI (A) |9.1762mA|9.17mA|9.1762mA|9.17mA|8.0943mA|8.085mA|8.0943mA|8.085mA|8.0943mA|8.085mA|

















































**5.VIDEO**



https://www.youtube.com/watch?v=Hll4t0dDCxo






































**6.CONCLUSIONES**

- Gracias a la simulación que realizamos en Tinkercad se pudo comprobar el como las leyes de conservación de energia y conservación de carga se cumplen y demuestran que la energia no se crea ni se destruye solo se transforma.
- Luego de analizar y utilizar los componentes dentro del simulador se pudo realizar la interpretacion del diagrama del circuito de manera adecuada obteniendo valores que cumplen con el tema del laboratorio.
- Al revisar y analizar la teoria propuesta sobre varios temas que fueron utiles para la comprención de los ejercicios fue mas sencillo realizarlos

























**7.BIBLIOGRAFÍA**


Latam, M. (2020, 6 julio). Leyes de Kirchhoff. Mecatrónica LATAM. Recuperado 11 de noviembre de 2021, de https://www.mecatronicalatam.com/es/tutoriales/teoria/leyes-de-kirchhoff/

Las leyes de Kirchhoff (artículo). (s. f.). Khan Academy. https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws






































