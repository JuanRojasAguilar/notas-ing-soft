# Desarrollo de software basado en modelos

### Que estudia este tema?

Se estudiaran los conceptos basicos sobre **modelado** de software OO. Se revisara el lenguade unificado de modelado (UML) y el papel de las herramientas CASE en el proceso del desarrollo.

### La necesidad de modelar

En los anhos 60 la industria tuvo que enfrentarse a la *complejidad inherente* del software, en esta epoca se formulan los conceptos basicos para la programacion y sistemas operativos. Fortran presento el concepto de *abstraccion*, Algol60 presento el concepto de *tipos de datos, recursividad, etc*.

Simula67, que tambien aparecio en esta epoca, fue el primer lenguaje en usar el concepto OO a traves de clases y subclases. Algol68 y Pascal trajeron los tipo de datos definidos por el usuario, variables por referencia y estructura de tipos disjuntos. Esta fue la epoca de la optimisacion (parsing) y del uso eficiente del hardware.

En los anhos 70 se presentaron grandes proyectos dificiles de controlar por un unico software. Esto impulso el uso de la modularidad y programacion Estructurada. Ademas, en este perioso aparecio el principio de encapsulamiento junto a los mecanismo de control de versiones.

En los anhos 80 la industria se enfrento a la variabilidad de requisitos, este problema fue gestionado por el paradigma OO y el modelado. En este tiempo todo era un objeto y el UML era la pieza clave para la transicion de POO a una ingenieria de software basada en modelos. *Se lanzo al publico "Smalltalk" el segundo lenguaje OO inspirado en Simula*

En los anhos 90 la industria se enfrenta a sistemas de despliegue y distribucion masiva y tuvo que valerse de lineas de produccion. Por otro lado la *ingenieria de software basada en componentes (CBSE)* surgio como una tecnica basa en la reutilizacion que ayudaba el desarrollo debido a que los componentes son mas abastractos que los objetos y puden ser mas reutilizables.

#### Lenguajes Formales

La teoria de los lenguajes formales considera a los lenguajes como cadenas de caracteres basados en alfabetos con conjuntos infinitos de reglas llamadas "gramaticas". Un alfabeto es un conjunto finito no vacio y los elementos de el se llaman letras, una palabra es una cadena finita formada por cero o mas letras, una palabra vacia se denota como &#955;

- Una gramatica es un *cuadruplo ordenado* G = (V<sub>N</sub>V<sub>T</sub>X~0~,F)
- V<sub>N</sub> y V<sub>T</sub> son alfabetos disjuntos. Siendo V~N~ elementos **no-terminales** y V~T~ son **terminales**.
- X~0~ &#8714; V~N~ se conoce como **letra inicial**
- F es un conjunto finito d pares ordenados (P, Q) donde Q es una palabra del alfabeto V = V~N~ &#8746; V~T~. P es una palabra de V que contiene al menos una letra de V~N~.
- Los elementos (P, Q) de F s denominan **reglas de escritura** y se escribe P -> Q.

En general las gramaticas se pueden considerar *descripciones estructurales* de los sistemas y por lo tanto incluyen:
- **Gramaticas de contexto libre**. Permiten la definicion de la sintaxis concreta de los lenguajes de programacion.
- **Diccionarios de clases**.
- **XML Schemas** Permiten la definicion de formatos para el intercambio en aplicaciones, asi cmo otras formas de gramaticas para grafos y arboles (estructuras de grafos).

Los antiguos lenguajes de programacion aparecieron para areas especificas, COBOL para procesos de negocio, FORTRAN para calculo numero y Lisp para procesamiento de simbolos sin embargo han ido evolucionando hasta lenguajes de proposito general (GPL) y esto ha generado la necesidad de un soporte dado por lenguajes especializados para resolver problemas en dominios concetros y son conocidos por ser lenguajes de dominio especifico (DSL).

