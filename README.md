# ANÁLISIS DE MALLAS

1. OBJETIVOS

Generales

* Analizar el circuito  y justificar el uso de la teoría del análisis de mallas para los diferentes cálculos. 

Especificos

* Demostrar la funcionalidad del análisis de mallas y revisar los valores medidos con los valores teóricos mediante el uso de simuladores. 
* Explicar los datos obtenidos en las tablas, mediante las formulas establecidas.
* Practicar la resolucion de ejercicios usando el análisis de mallas.

2. MARCO TEÓRICO 

El análisis de mallas es un método bien organizado para resolver circuitos. Al igual que en cualquier análisis de circuito, tenemos que resolver un sistema de ecuaciones depediendo de las mallas que tengamos propiamente en el circuito. El método de la corriente de malla facilita el análisis, y produce un número relativamente pequeño de ecuaciones a resolver. 

El método de la corriente de malla se basa en la ley de voltaje de Kirchhoff visto anteriormente. 

El método de la corriente de malla utiliza dos términos especiales: lazo y malla. Un lazo es cualquier trayectoria cerrada alrededor de un circuito mientras que una malla es una clase restringida de lazo; una malla es un lazo que no contiene otros lazos. En el método de la corriente de malla, usamos las mallas de un circuito para generar las ecuaciones LVK.

3. DIAGRAMAS

<p align="center">
  <img src="https://github.com/Dillanj2/Informe2/blob/main/Im%C3%A1genes/Circuito%20para%20el%20an%C3%A1lisis%20de%20mallas.png">
</p>
<p align="center">
  Diagrama 3.1: Circuito para el análisis de mallas
</p>

4. LISTA DE COMPONENTES

* 1 Fuente de Voltaje de C.D.
* 1 Multimetros Digitales.
* 1 Resistor de 820Ω
* 1 Resistor de 390Ω
* 1 Resistor de 1kΩ
* 1 Resistor de 1.2kΩ
* 1 Resistor de 2.2kΩ
* 1 Protoboard

5. PROCEDIMIENTO

5.1 Implemente el circuito que se representa en el diagrama 3.1.

5.2 Mida cada una de las corrientes de malla y anote los resultados en la tabla 5.1.

5.3 Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito del diagram 3.1, obteniendo los valores de las corrientes de malla. Anote los resultados en la tabla 5.1.

Usamos el software LTspice para la simulacion del circuito.

El instalador se puede obtener en el siguiente enlace:

<p><a href="https://github.com/Dillanj2/Informe2/blob/main/Instaladores/LTspice">Instalador LTspice</a>

5.4 Compare los valores del diagrama 3.1 y realice sus conclusiones.

<p align="center">
  Tabla 5.1: Resultados obtenidos para el circuito del diagrama 3.1.
</p>
<p align="center">
  <img src="https://github.com/Dillanj2/Informe2/blob/main/Im%C3%A1genes/Resultados%20obtenidos%20para%20el%20circuito%20del%20diagrama%203.1.png">
</p>

<p align="center">
  Tabla 5.2: Tabla de errores.
</p>
<p align="center">
  <img src="https://github.com/Dillanj2/Informe2/blob/main/Im%C3%A1genes/Tabla%20de%20errores.png">
</p>

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
  <img src="https://github.com/Dillanj2/Informe2/blob/main/Im%C3%A1genes/Corriente%201.jpeg">
</p>
<p align="center">
  Figura 9.1: Medición de la corriente 1 en LTspice.
</p

<p align="center">
  <img src="https://github.com/Dillanj2/Informe2/blob/main/Im%C3%A1genes/Corriente%202.jpeg">
</p>
<p align="center">
  Figura 9.2: Medición de la corriente 2 en LTspice.
</p

<p align="center">
  <img src="https://github.com/Dillanj2/Informe2/blob/main/Im%C3%A1genes/Corriente%203.jpeg">
</p>
<p align="center">
  Figura 9.3: Medición de la corriente 3 en LTspice.
</p
  
<p align="center">
  <img src="https://github.com/Dillanj2/Informe2/blob/main/Im%C3%A1genes/Circuito%20para%20el%20an%C3%A1lisis%20de%20mallas%20Tinkercad.png">
</p>
<p align="center">
  Figura 9.4: Circuito para el análisis de mallas en Tinkercad
</p

<p align="center">
  <img src="https://github.com/Dillanj2/Informe2/blob/main/Im%C3%A1genes/Circuito%20para%20el%20an%C3%A1lisis%20de%20mallas%20medici%C3%B3n.png">
</p>
<p align="center">
  Figura 9.5: Medición de corrientes en Tinkercad.
</p

