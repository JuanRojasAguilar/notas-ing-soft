# Introduccion a la ingenieria de **software**
### Por que estudiar esto?

Se exploraran los conceptos de software y el porque se entienden como una disciplina que formaliza el dominio y desarrollo de **software** con el objetivo de implementar aplicaciones de calidad.

### Introduccion
> La **ingenieria** es la **profesion** en la que el **conocimiento** de las ciencias y matematicas es **aplicado**

Por otro lado, el **software** es un producto disenhado para un usuaro y engloba todo lo que pertenece al sistema de computo.
Podemos asi pensar en la **ingenieria de software** como una disciplina que comprende los aspectos de la **produccion de software** (abarca desde su concepcion hasta su ditribucion y mantenimiento).

Otra manera de verlo es como el `estudio de metodos y herramientas` usadas para producir el software.

Aunque este clasificada y tratada como una ingenieria tiene *caracteristicas peculiares* que le hacen distinguirse de las otras:

- El producto es intangible, siendo su desarrollo diferente a las pautas ingenieriles.
- Los requisitos y enfoques cambian con cada proyecto y en el desarrollo del mismo.
- Su documentacion queda a criterio del proyecto y necesidades.

Clasicamente las ingenierias esperan a tener un disenho completo antes de llevar a cabo el desarrollo y esta implicacion no-fisica del software hace que inevitablemente el disenho y desarrollo se solapen.
Otra diferencia fundamental es en los cambios al producto, en una ingenieria clasica los pequenhos cambios al producto hacen pequenhos cambios al comportamiento mientras los *productos de software* son de caracter **discreto** los cuales pueden desencadenar una cantidad mayor en el comportamientos de las que hubo en el codigo.
Ademas las ingenierias se pueden verificar de manera matematica mientras el software es impredecible, por ejemplo:

|Ingenieria|Producto|Teoria|Propiedades|
|----------|--------|------|-----------|
|Aeronautica|Avion|Dinamica de fluidos|Relacion de planeo, turbulencias|
|Civil|Puente|Mecanica clasica|Carga maxima, resistencia lateral, etc...|
|**Software**|*Software*|??|??|

### La crisis del software

En estos ultimos anhos la ingenieria del *software* se ha enfrentado a diferentes problemas que conocemos como **la crisis del software**:

- Planificaciones imprecisas dificiles de cumplir con costes y tiempos irreales
- Baja productividad
- Clientes insatisfechos por programas que no satisfacen sus necesidades
- Software de mala calidad, dificil de mantener y mal integrado a las companhias
- Mantener un departamento de tecnologia se ha visto como una carga

Y fue debido a estos errores que se acunho la ingenieria de software como concepto para intentar responder el porque de estas situaciones. En ese tiempo (1968) el software era visto como un anhadido que era realizado de manera artesanal donde no habia ningun tipo de metodologia ni se realizaba una planeacion.

La conclusion a la que habia llegado la OTAN fue que `el software como producto tecnologico debia ser tratado como una ingenieria mas que aplicara sus principios y los modificara segun su necesidad` para asi crear metodos mas *cuantitativos, sistematicos y menos artesanales*. Con tal se puede decir que la ingenieria de software es una disciplina joven siendo diferente a la ingenieria de **sistemas** que se enfoca en la evolucion de sistemas complejos y no solo del software.

Con el tiempo se han visto mas softwares en los sistemas (llegando casi al 90%) y sus tecnicas se han ido refinando para sus necesidades particulares y se han ido aplicando en la ingenieria de sistemas. La evolucion del hardware y la caida de sus precios ha sido la razon por la cual los softwares se han ido complicando mas haciendo mas lejano el dia en el que se acabe la *crisis del software*.

Desarrollar software puede *parecer* dificil y es debido que son muy pocos los productos que han sido realmente terminados a tiempo, dentro del presupuesto y cumpliendo los requisitos. Aqui una tabla de errores cometidos por software.

|Anho|Entidad|Descripcion|Impacto|
|----|-------|-----------|-------|
|2015|Avion A400M|El sotware del motor hizo que el avion se estrelle en sevilla, cuatro tripulantes muertos y dos heridos.|Alto|
|2013|Juzgado de Madrid|Un fallo informatico colapsa 46 juzgados durante 12 dias|Media|
|2012|Gobierno de Canarias|Se pierden los datos fundamentales acerca de la erupcion volcanida de 'El hierro'|Media|
|2012|Gobierno de Navarra|Se interrumpen los servicios de Salud, Hacienda y Desarrollo Rural|Medio|
|2012|Aeropuerto de Malaga|Un fallo deja a oscuras la torre de control|Alto|
|2011|Periodico 'El Pais'|Casi se cancela la impresion de su edicion dominical por un fallo y la falta de tecnicos|Medio|
|2003|Vodafone Espanha|La red telefonica cayo dejando sin servicio a mas de 8 millones de usuarios|Alto|

Es un proceso arduo y costoso debido a su complejidad, cambio constante y la necesidad de satisfacer a un cliente. Y fue en estos esfuerzos donde se intento usar las practicas clasicas ingenieriles al software sin mucho exito.

Ince (1993) afirma que los cambios y la velocidad experimentada en el software es una representacion 1 a 1 de la velocidad en como se dan los cambios en el mundo actual y para poder adaptarse a estos cambios sociales se enumeran tres requisitos que deben ser satisfechos en el desarrollo de estos productos.

- Minimizar la complejidad de un sistema.
- Crear diferentes maneras de validar la validez de las soluciones presentadas en el software.
- Mantener tecnicas de desarrollo que minimicen los efectos que dan las modificaciones y evolucion del software

Ince defiende el enfoque ingenieril del software mediante `el uso de herramientas y metodologias` sin dejar de tener en cuenta las caracteristicas inherentes a el mismo que `permite gestionar los cambios y evolucion del software a lo largo del tiempo`

### Ingenieria de software vs ciencias de la computacion

Hay que aclarar que un ingeniero trata de darle una **aplicacion** a las cosas **descubiertas** por los **cientificos** para un desarrollo social. `Todo ingeniero debe asegurar su funcionalidad, eficacia y eficiencia.`

> Los ingenieros de software son los profesionales que aplican los conocimientos en pos de construir productos de software y sus restricciones son de presupuesto, duracion, tiempo de respuesta del sistema y tamanho de la aplicacion

> El cientifico de computacion busca nuevos conocimientos para que los ingenieros puedad tener nuevas maneras de resolver problemas

*Un ingeniero de software es un programador pero un programador no es un ingeniero de software pues el acto de escribir el codigo es uno entre tantos que competen a la ingenieria de software*

Parnas (1999) resume las *responsabilidades* de un ingeniero de software:

- Conocer el entorno para el que se desarrolla para poder documentar los requisitos a tener en cuenta de manera precisa y organizada para poder ser cosunlata de manera rapida
- Participa en el diseño de los sistemas para determinar que **hardware** va a realizar que operacion del **software** para asegurar consistencia, disponibilidad, compatibilidad y rendimiento.
- Diseña la estructura del **software** la divide en modulos ademas de documentar las desiciones de su diseño 
- De ser necesario, integra aplicaciones ya existentes o comerciales.
- Revisa y mejora los sistemas mediante pruebas para mantener la integridad del proyecto y la documentacion actualizada.

### Etica y responsabilidad profesional en la ingenieria del software

> Trata a los demas como te gustaria que te trataran a ti 

Al igual que una ingenieria clasica, la ingenieria de software ha de estar dentro de un marco legal y social que debe limitar la libertad de los ingenieros de software

> Sin una solida educacion etica especifica de su profesion, el ingeniero se convierte en un instrumento en las manos de otros

En `El codigo de etica y practica profesional de ingenieria de software de la ACM / IEEE computer society` se encuentran los 8 principios basicos que se deben seguir a la hora de desarrollar software:

1. **Publico**. Los ingenieros de software deben actuar de manera consciente en bien del interes general.
2. **Cliente y contratista**. Los ingenieros ademas deben actuar de manera concorde con los intereses del cliente y contratista.
3. **Producto**. Se deben asegurar que su producto cumple con los mayores estandares profesionales.
4. **Juicio**. Deben mantener la integridad y honestidad en sus valoraciones profesionales.
5. **Gestion**. Los gestores y lideres en el campo promoveran un enfoque etico en el desarrollo y mantenimiento de software.
6. **Profesion**. Los ingenieros realizan avances en coherencia e integridad del interes general.
7. **Compañeros**. Seran justos y apoyaran a sus compañeros de profesion.
8. **Persona**. Participaran en el aprendizaje continuo de la practica de su profesion y en la promocion del comportamiento etico de la misma.

### Fabricas de software

Desde el comienzo de la crisis en España en el año 2008, bastantes sectiores se vieron afectados, sin embargo, el negocio de las llamadas *fabricas de software* no se vio afectado debido a que sale mas barato hacer el outsorcing del desarrollo y mantenimiento a estas *fabricas de software*.

El termino de fabrica de software se acuña en el año 1968 por la **International Federation for Information Processing (IFIP)** y cambio el entorno laboral porque se estandarizaron los procesos implicados en su desarrollo y esto hizo que el software pasara de ser un servicio desestructurado a un servicio con un nivel de calidad optimo.

En esta epoca las empresas de software se empezaron a ver los siguientes retos:
- Adopcion de estandares para el desarrollo de software
- Supervisar de manera efectiva el proceso de produccion
- Estandarizar la fase de diseño de software
- Reutilizar modulos de software ya desarrollados

Asi mismo se vieron diferentes tipos de fabricas de software especializadas en diseños y desarrollos:

(FS = Fabrica de software)
- FS basada en la madurez de procesos
- FS basada en la experiencia para el desarrollo de modulos
- FS basada en la reutilizacion
- FS basada en la renovacion de software
- FS basada en tecnicas para la gestion de calidad

Pero todas conllevan tres necesidades principales:

1. **Mano de obra cualificada**: dificil de conseguir por la velocidad en la que se mueve la industria que muchas veces se mueve por modas
2. **Mejor gestion de los proyectos de software**: Debido a la gran cantidad de fracasos en este campo, muchas veces dados por la falta de madurez de la propia industria y la creciente complejidad implicada en los sistemas a desarrollar
3. **Adaptacion a las nuevas tecnologias**: Debido a la rapida evolucion de las tecnologias las empresas son impulsadas a innovar para seguir siendo competitivas

# DESARROLLEN LOS EJERCICIOS AL FINAL DEL PDF QUE EL PROFE SUBIO AL GOOGLE CLASSROOM PAGINA 22

