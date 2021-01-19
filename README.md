# TEOREMA DE SUPERPOSICIÓN

1. OBJETIVOS

Generales

* Analizar el circuito  y justificar el uso de la teoría del teorema de superposición para los diferentes cálculos. 

Especificos

* Demostrar la funcionalidad del teorema de superposición y revisar los valores medidos con los valores teóricos mediante el uso de simuladores. 
* Explicar los datos obtenidos en las tablas, mediante las formulas establecidas.
* Practicar la resolucion de ejercicios usando el teorema de superposición.

2. MARCO TEÓRICO 

El análisis de mallas es un método bien organizado para resolver circuitos. Al igual que en cualquier análisis de circuito, tenemos que resolver un sistema de ecuaciones depediendo de las mallas que tengamos propiamente en el circuito. El método de la corriente de malla facilita el análisis, y produce un número relativamente pequeño de ecuaciones a resolver. 

El método de la corriente de malla se basa en la ley de voltaje de Kirchhoff visto anteriormente. 

El método de la corriente de malla utiliza dos términos especiales: lazo y malla. Un lazo es cualquier trayectoria cerrada alrededor de un circuito mientras que una malla es una clase restringida de lazo; una malla es un lazo que no contiene otros lazos. En el método de la corriente de malla, usamos las mallas de un circuito para generar las ecuaciones LVK.

3. DIAGRAMAS

<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Circuito%20para%20comprobar%20el%20Teorema%20de%20Superposici%C3%B3n.png">
</p>
<p align="center">
  Diagrama 3.1: Circuito para comprobar el Teorema de Superposición.
</p>

4. LISTA DE COMPONENTES

* 2 Fuente de Voltaje de C.D.
* 2 Multimetros Digitales.
* 1 Resistor de 1kΩ
* 1 Resistor de 2.2kΩ
* 1 Resistor de 820Ω
* 1 Resistor de 470Ω
* 1 Protoboard

5. PROCEDIMIENTO

5.1 Arme el circuito que se muestra en el diagrama 3.1.

5.2 Con las dos fuentes conectadas, mida el voltaje V_A y la corriente I_x, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 5.1 y 5.2 respectivamente.

5.3 Haga "cero" la fuente de voltaje de 12 V (V_2) y mida el voltaje V_A y la corriente I_x, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 5.1 y 5.2 respectivamente.

5.4 Haga "cero" la fuente de voltaje de 20 V (V_1) y mida el voltaje V_A y la corriente I_x, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 5.1 y 5.2 respectivamente.

<p align="center">
  Tabla 5.1: Medición de voltaje aplicando superposición.
</p>
<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Medici%C3%B3n%20de%20voltaje%20aplicando%20superposici%C3%B3n.png">
</p>

<p align="center">
  Tabla 5.2: Medición de corriente aplicando superposición.
</p>
<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Medici%C3%B3n%20de%20corriente%20aplicando%20superposici%C3%B3n.png">
</p>

5.5 Verifique el cumplimiento del Teorema de Superposición y compare los resultados obtrenidos prácticamente con los obtenidos analíticamente. Realice sus conclusiones.

El procedimiento lo puede observar entrando al siguiente enlace:

<p><a href="https://github.com/Dillanj2/Informe2/blob/main/C%C3%B3digo%20Fuente/Procedimiento_de_Laboratorio_2.pdf">Procedimiento</a>

6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

* Tinkercad: Es una herramienta online de Autodesk, que permite la simulacion de circuitos, al igual que permite dibujar esquemas circuitales de forma sencilla.
* LTspice: Es un simulador de alto rendimiento en el que pueden armarse diagramas esquemáticos de reguladores de alimentación conmutados o Convertidores DC-DC. Permite la simulacion de circuitos.

7. CONCLUSIONES

* El análisis de mallas nos permite, como cualquier análisis, hacer la resolución mas fácil al momento de trabajar con circuitos con numerosas mallas.
* Para emplear este análisis debemos conocer la ley de voltaje de Kirchhoff, ya que esta se basa en aquella ley. 

8. BIBLIOGRAFÍA

McAllister, W. (S/F). El método de la corriente de malla. Khan Academy. Obtenido de: https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method

9. ANEXOS

<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Circuito%20en%20LTspice.jpeg">
</p>
<p align="center">
  Figura 9.1: Circuito en LTspice.
</p

<p align="center">
  <img src="https://github.com/Dillanj2/Informe2/blob/main/Im%C3%A1genes/Corriente%202.jpeg">
</p>
<p align="center">
  Figura 9.2: Medición de la corriente 2 en LTspice.
</p

<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Circuito%20con%20V_1%20cero.jpeg">
</p>
<p align="center">
  Figura 9.3: Circuito con V_12 cero.
</p
  
<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Circuito%20con%20V_2%20cero.jpeg">
</p>
<p align="center">
  Figura 9.4: Circuito con V_20 cero.
</p


