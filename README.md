# Guías de estilos en GBM

## Tabla de contenidos

1. [Otras guías de estilo](#otras-guías-de-estilo)
1. [Importancia de la etiqueta en código](#importancia-de-la-etiqueta-en-código)
1. [Utilizar lenguaje en modo imperativo](#utilizar-lenguaje-en-modo-imperativo)
1. [Agregar una tabla de contenidos](#agregar-una-tabla-de-contenidos)
1. [Estructura de apartados en guía de estilos](#estructura-de-apartados-en-guía-de-estilos)
1. [Agregar referencias que sirvan como inspiración](#agregar-referencias-que-sirvan-como-inspiración)

## Otras guías de estilo

 - [C# y Xamarin](c-sharp/)
 - [CSS, SASS y LESS](css/)
 - [CSHTML, HTML](cshtml/)
 - [Java](java/)
 - [JavaScript, AngularJS y ReactJS](js/)
 - [Markdown y Github Markdown](md/)
 - [Swift y Objective-C](swift/)

## Importancia de la etiqueta en código

Seguir un conjunto consistente de pautas en el desarrollo de software tiene las siguientes ventajas:
 
 - *Mejorar la comunicacipon entre desarrolladores*: El código debe estar hecho para ser leído por humanos.
 - *Hacer que los errores sean obvios*: Con las guías de estilos los desarrolladores se acostumbran a ciertos patrones y es más fácil identifica rpatrones extraños.
 - *Establecer pautas para establecer revisión automatizada de estilo en código*: Se pretende formalizar la guía de estilo para que todos los miembros del equipo de desarrollo trabajen de con mayor cohesión.

**[Regresar al inicio](#tabla-de-contenidos)**

 
## Utilizar lenguaje en modo imperativo.
 
 *¿Por qué?*: Ayuda a ser más asertivo al escribir.
 
 *¿Por qué?*: Se evita crear una guía de estilos basadas en opiniones personales y llevará aportes analizados por varios elementos del equipo de desarrollo..
 
### Mal
 > Para escribir una buena guía de estilos se recomienda tener una tabla de contenidos al inicio del documento. 
  
### Bien
 > Agregar una tabla de contenidos en sus primeros apartados de la guía de estilos. 

**[Regresar al inicio](#tabla-de-contenidos)**

## Agregar una tabla de contenidos
   
 *¿Por qué?*: Ayuda a identificar de un vistazo rápido los elementos cubiertos por al guía de estilos.
   
### Mal
 > __Otras guías de estilo__ 
 
 > A continuación un listado de guías de estilo [...]
 
 > __Importancia de la etiqueta en código__
 
 > Seguir un conjunto consistende de pautas en [...]
    
### Bien
 > 1. [Otras guías de estilo](#otras-guías-de-estilo)
 > 1. [Importancia de la etiqueta en código](#importancia-de-la-etiqueta-en-código)
 > 1. [Utilizar lenguaje en modo imperativo](#utilizar-lenguaje-en-modo-imperativo)
 > 1. [Agregar una tabla de contenidos](#agregar-una-tabla-de-contenidos)
 > [...]
 >
 > __Otras guías de estilo__
 
 **[Regresar al inicio](#tabla-de-contenidos)**
 
## Estructura de apartados en guía de estilos

- Iniciar el apartado con un título referenciado desde la tabla de contenidos.
- Si el título del apartado no es autoexplicativo, agregar una descripción más detallada inmediatamente después del título del apartado.
- Agregar de manera explícita la motivación de agregar el apartado.
- Incorporar al menos un ejemplo de lo que se busca evitar.
- Incorporar al menos un ejemplo de la solución propuesta en la guía de estilos.
- Al final del apartado agregar un vínculo que posicione el sitio en la tabla de contenidos.

 *¿Por qué?*: Al tener una estructura definida ayuda a los desarrolladores a identificar velozmente el contenido de cada regla.

### Mal
 > __Estructura de apartados en guía de estilos__
 > __Regresar al inicio__
 > Que tenga título, descripción y referencia
 
### Bien
 > __Referencias__
 > - ¿Por qué? Es indispensable reconocer a los miembros de la comunidad con sus aportes.
 > * [Guía de estilos de JavaScript](https://github.com/airbnb/javascript) de @airbnb.
 > * [Guía de estilos de AngularJS](https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md) de @johnpapa para AngularJS 1.
 >
 > __Regresar al inicio__
 
**[Regresar al inicio](#tabla-de-contenidos)**

## Agregar referencias que sirvan como inspiración

  *¿Por qué?*: Es indispensable reconocer a los miembros de la comunidad con sus aportes.
  
  *¿Por qué?*: Si es necesario implimentar una nueva regla se puede consultar en las que ya se han ocupado como referencia.
  
### Mal
> __Referencias__

 > Faltan agregar referencias

### Bien
> __Referencias__
> * [Guía de estilos de JavaScript](https://github.com/airbnb/javascript) de @airbnb.
> * [Guía de estilos de AngularJS](https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md) de @johnpapa para AngularJS 1.

**[Regresar al inicio](#tabla-de-contenidos)**