# Desarrollo de software orientado a objetos

### Que estudia este tema?

Se estudian los conceptos asociados a la *orientacion de objetos (OO)* y sus principios fundamentales: **abstraccion, jerarquia, clasificacion, encapsulamiento y polimorfismo**. Ademas de diferenciar entre el analisis oriantado a objetos (AOO) y el disenho orientado a objetos (DOO).

### Introduccion

El concepto de programacion orientada a objetos (OOP) aparecio en los lenguajes de programacion con *Smalltalk* cuando se consolido de manera definitiva. OOP se basa en la idea de un mundo lleno de objetos con *atributos* que los diferencias y las *operaciones* que pueden ser realizadas sobre ellos.

Estos atributos representan y almacenan datos, mientras las operaciones permiten manipular los atributos.

> Los programas orientados a objetos se contruyen mediante objetos que colaboran entre si mediante el intercambio de mensajes.

Asi mismo el OOP es un **metodo de implementacion** en el que os programas son colecciones de objetos que colaboran unos con otros y cada objeto representa una clase determinada, estas clases forman jerarquias que se pueden relacionar a travez de la **herencia**.

La gran diferencia entre OOP es su uso de objetos y no de los algoritmos para el desarrollo. Cada objeto debe venir definido por una **clase**.

*Los lenguajes orientados a objetos son: C++, Objective C, C#, Self, Eiffel y, mas conocido, Java*.

Para que un lenguaje sea considerado OOP se deben cumplir las siguientes condiciones:

1. Los objetos son maquetas o prototipos de como se organizan los datos y contienen las operaciones disponibles por cada objeto.
2. Los objetos tienen un tipo de dato asociado llamado **clase**
3. Las clases pueden heredar atributos de otra clase, a estas ultimas se les llama **superclases**

El disenho orientado a objetos fue utilizado por primera vez por Booch para posteriormente ser derivado en el desarrllo orientado a objetos.

Todos los objetos dependen de los problemas encontrados durante el analisis y son definidos en el disenho de la solucion, entonces es el *analisis orientado a objetos (OOA)* el que define los objetos a construir.

*El disenho orientado a objetos propone una solucion al problema mendiante crear y combinar objetos*

El OO parte de que el mundo real se puede representar por entidades conceptuales cuyas instancias colaboran entre si, sin embargo, si se es capaz de identificar los objetos pero no su colaboracion no tendria sentido este acercamiento.

Las ventajas de este enfoque son:

- **Analisis**. Se analizan los problemas a un nivel mayor de abstraccion
- **Comunicacion**.
- **Tolerancia**. Los objetos tienen mayor tolerancia a los cambios de enfoque
- **Reutilizacion**.
- **Verificacion**
- **Extensibilidad**

### Principios de la orientacion a objetos

#### Abstraccion

> La abstraccion son aquellas caracteristicas esenciales de un objeto que lo distingue de otros

Para un programador la abstraccion es una forma de simplificar la realidad.

- **Abstraccion de Entidad**. Representa un modelo util de una entidad
- **Abstraccion de Accion**. Proporcia un conjunto de operaciones con el mismo objetivo
- **Abstraccion de Maquina Virtual**. Agrupa operaciones que son usadas por otras en un conjunto de operaciones auxiliares
- **Abstraccion casual**. Operaciones que no tienen relacion entre si.

![Diferencia de visiones a la hora de abstraer](./images/ing_sof_lectura-3_1.png)

Dentr de la abstraccion se denomina *cliente* a cualquier objeto que use recursos de otro objeto (conocido como *servidor*) necesitando definir un protocolo. Este protocolo se define como *el conjunto de operaciones que hace un cliente para acceder a un servidor junto a sus restriccones* y estos requisitos delegados a un *objeto servidor* se denomina **responsabilidad**.

#### Clasificacion

Los objetos son clasificados entre la relacion entre las clases. La clasificacion permite asignar un tipo a los objetos y los objetos de diferente tipo no se pueden intercambiar, y en el caso de poderse intercambiar, lo haran de manera muy restrictiva.

![Principio d clasificacion](./images/ing_sof_lectura-3_2.png)

- **Fuerte vs debil**. Se considera fuerte cuando no se deja invocar la operacion de un objeto a menos que este definida en la clase o superclase de dicho objeto.

- **Estatica vs dinamica**. Se refiere a lo conocido como el *tipado* de variables y que sea estatico significa que se deben fijar en tiempo de compilacion mientras que una clasificacion dinamica permite que los tipos de las variables no se conozcan hasta el tiempo de ejecucion.

*Un lenguaje estatico fuertemente tipado seria Ada mientras que C++ y Java son fuertemente tipados pero dinamicos. En otro extremo se encuentra Smalltalk sin tipado y dinamico*

