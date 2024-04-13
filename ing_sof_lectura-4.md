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

- Una gramatica es un *cuadruplo ordenado* G = (V<sub>N</sub>V<sub>T</sub>X<sub>O</sub>,F)
- V<sub>N</sub> y V<sub>T</sub> son alfabetos disjuntos. Siendo V<sub>N</sub> elementos **no-terminales** y V<sub>T</sub> son **terminales**.
- X<sub>O</sub> &#8714; V<sub>N</sub> se conoce como **letra inicial**
- F es un conjunto finito d pares ordenados (P, Q) donde Q es una palabra del alfabeto V = V<sub>N</sub> &#8746; V<sub>T</sub>. P es una palabra de V que contiene al menos una letra de V<sub>N</sub>.
- Los elementos (P, Q) de F s denominan **reglas de escritura** y se escribe P &#10132; Q.

En general las gramaticas se pueden considerar *descripciones estructurales* de los sistemas y por lo tanto incluyen:
- **Gramaticas de contexto libre**. Permiten la definicion de la sintaxis concreta de los lenguajes de programacion.
- **Diccionarios de clases**.
- **XML Schemas** Permiten la definicion de formatos para el intercambio en aplicaciones, asi cmo otras formas de gramaticas para grafos y arboles (estructuras de grafos).

Los antiguos lenguajes de programacion aparecieron para areas especificas, COBOL para procesos de negocio, FORTRAN para calculo numero y Lisp para procesamiento de simbolos sin embargo han ido evolucionando hasta lenguajes de proposito general (GPL) y esto ha generado la necesidad de un soporte dado por lenguajes especializados para resolver problemas en dominios concetros y son conocidos por ser lenguajes de dominio especifico (DSL).

> DSL es definido como un lenguaje que proporciona, mediante notaciones y abstracciones, un alto poder expresivo en un dominio. Otros autores dstacan que en vez de atacar un problema tecnologico particular, estan disenhados para representar de manera mas directa el dominio en el que se emplean

#### Lenguaje Visual

> Un lenguaje es visual si permite una representacion multi-dimensional de los elementos del lenguaje.

Los lenguajes visuales pueden usarse con varios propositos y por tanto ha sido necesario clasificarlos.

- **Para procesamiento de informacion**.
- **Para la interaccion**.
- **Para la programacion**.

#### Gramaticas de grafos

Un grafo es un par G=(K,R) donde K es un conjunto finito de *nodos* y R&#8712;KxK un conjunto de arcos. El grafo sera **dirigido** si R esta ordenado y **no dirigido** en caso contrario. Un *grafo etiquetado* es un cuadrupo MG=(K,R,k,r).

(Seria bueno que miraran esta pag, es la 7 del archivo, para ver una explicacion mas amplia del tema).

Las gramaticas de grafos son usadas para la generacion de grafos y son usadas en aplicaciones como bases de datos, reconocimiento de patrones, etc. Esta gramatica es parecida a la de caracteres que consiste en un conjunto de etiquetas de nodos, un conjunto de etiquetas de arcos, un axioma y un conjunto finito de producciones.

Los *editores dirigidos por sintaxis* consituyen un ejemplo de la aplicacion de las gramaticas de grafos y son estos losque facilita la construccion de programas, brindando una plantilla que describen estructuras de la construcciones de los programas. De esta manera se generan programas sintacticamente correctos reduciendo los errores de introduccion del codigo.

### Modelado de sistemas software

- **Esquema ad hoc**. Segun esta tecnica los modelos son construidos en el instante, se basa en codificar sin apenas planificar ni estructurar.
- **Modelos diagramaticos estandares**. Debido a la aceptacion de UML que muestran de forma grafica un grupo de elementos que pertenecen a un modelo. Algunos autores los consideran informales pero su gran ventaja es que pueden reutilizar su trabajo tambien en modelos formales.
- **Especificaciones formales**. Corresponde a la aplicacion de tecnicas matematicas que permiten el disenho e implementacion del hardware y de sistemas de software. El lenguaje de especificacion se define matematicamente y es esto lo que los hace mas dificiles de tratar y la multitud de metodos viene con su propia notacion y tecnica de desarrollo generando problemas de compatibilidad en la comunicacion.

Al analizar las tecnicas se ve que la formalidad es una caracteristica a tener en cuenta y esta formalidad sera medida en funcion a su semantica.

### Modelado de objetos

Ya que se ha dejado en claro que construir software basado en un unico modelo es inviable y que es la creacion de varios objetos interconectados los que construyen un sistema se puede decir que los objetos permiten simplificar los procesos de construccion de modelos. El modelado de ojetos es una forma de representar conocimiento donde el dominio como su solucion se representa con objetos que interactuan entre si.

> Aunque el mundo real se pueda representar como si estuviera compuesto por objetos no significa que este creado por ellos puesto que NO se comunican entre si aunque nosotros, por conveniencia, tratamos como si asi fuese

- **Modelos de dominio**. Objetos de la vida real.
- **Modelos de especificacion**. Objetos de software.

De este modo en el mundo real se usan dos conceptos: **objetos (clases)** y **eventos** que representan cosas y hechos.
En el codigo se usan otros dos conceptos: **objetos (clases)** y **mensajes** que hacen referencia a el encapsulamiento de datos y a las operaciones asociadas donde los *mensajes* hacen referencia a las invocaciones de esas operaciones.

En definitiva, un modelo de objetos es un conjunto de **clases** y **asociaciones** entre objetos. Por tanto, la OO es interesante cuando los objetos y, especialmente, las colaboraciones entre ellos tengan mas importancia que los algoritmos y las funciones, `la OO solamente tiene sentido cuando hay colaboracion entre diferentes objetos`.

### UML

> Unified Modeling Language, Lenguage unificado de modelado

Es un lenguaje visual de proposito general para el modelado de sistemas, que gracias a sus mecanismos de extensibilidad puede ser aplicado en varios campos. Fue disenhado para incorporar las mejores practicas en el modelado de ingenieria de software. Es importante no confundirlo con **metodologias** de modelado (como UP) de las que tambien se sirve UML para la notacion. UML se puede utilizar con todas las metodologias porque lo que hace es proporcionar una sintaxis visual.

UML nace de los esfuerzos de Booch, Rumbaugh y Jacobson que unieron sus tecnicas OOD, OMT y OOSE para crear un estandar y darle consistencia al medio.

1. Cada metodo iba evolucionando hacia los otros dos lo que hacia que tuviese sentido unirlos en un unico metodo.
2. Si se alcanzaba la unificacion en cuanto semantica y notacion se alcanzaria cierta estabilidad en el mundo de OO.
3. Los tres autores (conocidos como los tres amigos) esperaba que la colaboracion diera pie a abarcar problemas que ninguno haya podido abarcar correctamente.
*El primer trabajo dio como fruto las versiones UML 0.9 y 0.91*



