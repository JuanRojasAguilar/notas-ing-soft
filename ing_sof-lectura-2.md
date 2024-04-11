# El proceso de desarrollo de **software**

### Que estudia este tema?

Se estudiara el proceso de desarrollo y los modelos mas comunes a la hora de implementar una aplicacion. Las caracteristicas propias del proyecto haran que este tenga que ir cambiando su modelo para dar solucion a los problemas que surgen.

### Definicion

> Un proceso define: Quien esta haciendo `que, cuando y como` para alcanzar un objetivo

*Este objetivo puede ser desarrollar, modificar o expandir un software ya existente*

Este proceso de desarrollo de software se ha definido de diferentes maneras
- *El conjunto de actividades necesarias para transformar los requisitos en un sistema. Jacobson, Booch y Raumbaugh.*
- *El conjunto de actividades para la creacion de un software. Sommerville.*
- *El conjunto de herramientas, metodos y practicas que utilizamos para crear un software. Humphrey.*

Sin importar la definicion son los ingenieros de software los que llevan a cabo este conjunto de actividades y seleccion de herramientas para la realizacion del desarrollo.

Toda actividad de desarrollo de software va a generar dos tipos de artefactos:
- Artefacto interno del proceso de desarrollo
- Artefacto entregable al cliente
*Un artefacto se puede definir como una pieza de informacion que se produce en un proceso de desarrollo de software*

Todo proceso de desarrollo de software debe definir el problema solucionado para favorecer la comprencion del codigo y el diseño de la solucion asi anticipando de manera ordenada los problemas para poder elaborar las formas de prevenir y resolver riesgos potenciales. Humphfrey (1990) destaca que el mayor interes del software debe ser la **calidad**.

`Requisitos de usuario -> Proceso de desarrollo de software -> Producto software`

Sommerville (2005) destaca cuatro actividades fundamentales comunes en los procesos de desarrollo:

- **Especificacion**. Clientes e ingenieros definen que van a construir y las restricciones que tendra.
- **Desarrollo**. Se diseña e implementa a la vez que se verifica su calidad.
- **Validacion**. Se valida que sea valioso para los clientes teniendo en cuenta los requisitos
- **Evolicion**. El software cambia para adaptarse a los cambios del cliente y/o mercado.

### Modelo de proceso software

Un **modelo de proceso** de desarrollo es una **descripcion simplificada** de un proceso de desarrollo real. Aun tratandose de una *simplificacion* del proceso es esto su principal ventaja: un modelo de proceso software deberia ser **facil de entender** por sus desarrolladores.

Cada desarrollo va a adoptar un modelo que mejor se le adapte dependiendo de su **complejidad** y sus **caracteristicas** del sistema. La eleccion inadecuada del modelo de proceso va a tener un gran impacto en la calidad del software.

#### Modelo en cascada

El *modelo en cascada (waterfall model)* fue el **primer paradigma** de proceso de desarrollo de software y se deriva de los procesos usados en las otras ingenierias de productos fisicos. Toma las *cuatro actividades comunes (especificacion, desarrollo, validacion y evolucion),* y presenta cada una como un momento distinto.

1. Especificacion de requisitos.
2. Diseño del software.
3. Implementacion
4. Pruebas
*Cada fase debe ser aprobada para poder continuar a la siguiente*

Desgraciadamente, este modelo es poco realista debido a que el modelo es poco flexible y es muy improbable encontrar software que se beneficie de esto.

![Imagen del modelo cascada](./images/ing_sof_lectura-2_1.png)

#### Modelo en espiral

Desarrollada por Boehm (1988) y representa el proceso como una espiral que `comprende tanto el modelo **iterativo** y el modelo **incremental**` debido a su diseño **exclusivo** para soportar iteraciones que añaden funcionalidades al sistema hasta llegar a tener un sistema completo.

Cada bucle puede significar una fase del proceso

1. Viabilidad del sistema
2. Definicion de requistos
3. Diseño del sistema
4. etc...

Y asi mismo este bucle se divide en cuatro:

1. Establecimiento de objetivos
2. Evaluacion y reduccion de riesgos
3. Desarrollo y validacion
4. Planificacion

![Imagen del modelo espiral](./images/ing_sof_lectura-2_2.png)

![Imagen del modelo espiral](./images/ing_sof_lectura-2_3.png)

