# Modelado de aplicaciones con UML

### Que estudia este tema?

Se trabajaran los conceptos de modelado con UML y se analizara con detalle ciertos elementos de la ingenieria de requisitos.

### Modelo avanzado de requisitos

La extraccion de requisitos puede que sea la mas critica de las tareas a realizar en proyectos.

![Problemas en los requisitos](./images/ing_sof_lectura-5_1.png)

Los modelos deben ser una herramienta para la comunicacion entre los clientes y contratistas de manera que el contratista pueda especificar los requisitos y que estos sean entendibles sin ambiguedades ni contradicciones, o darse cuenta de ellas en fases mas tempranas del proyecto.

> La gestion de requisitos es el enfoque sistematico para la documentacion de los requisitos del sistema, y el proceso que establece los acuerdos entre el cliente y el equipo.

Dentro de la fase de **elicitacion de requisitos** el cliente y el contratista analizan los problemas del dominio y las necesidades que tiene, aqui se definen los requisitos de software que son las responsabilidades que tendra el software

**Requisito de software falso**. Es aquel que aun sin ser implementado la aplicacion sigue cumpliendo sus objetivos.

- **Requisito falso de tipo tecnologico**.
- **Requisito falso de tipo arbitrario**. Se introducen al especificar mas funcionalidades de las necesarias al sistema.

Estos requisitos son un gran problema pues puede derivar en especificaciones incorrectas, por lo tanto hay que ser conscientes de la ambiguedad presente en UML. Esta ambiguedad solo es posible solventarla con mas informacion adicional usando diagramas de interaccion, diagramas de actividad y diagramas de estados.

![Diagrama de ejemplo](./images/ing_sof_lectura-5_2.png)

Por otro lado es mejor eliminar las relaciones <<include>> y <<extend>> porque suele dar caso a ambiguedades por su diferencia (reutilizacion vs insercion) que pueden dar caso a malos entendidos.

![Include Extend](./images/ing_sof_lectura-5_3.png)



