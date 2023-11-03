# Projects_JavaScript

## Tabla de Contenido

* [P01-Sistema de Ventas](#sistemaventas)
* [P02-Mundo PC](#mundoPC)
* [P03-Aplicación Calculadora](#appCalculadora)
* [P04-Aplicación Listado de Personas](#appPersonas)
* [P05-Aplicación Reloj Digital](#appReloj)
* [P06-Aplicación Presupuesto](#appPresupuesto)

## P01-Sistema de Ventas

Simula un ticket de venta que incluye el nro de orden, el total y especifica los productos con sus detalles previamente cargados.

Aplicación que simula sistema de ventas:
* Clase _Producto_: que almacena los productos que tiene el sistema. Incluye constructor, getters y setters.
* Clase _Orden_: toma los productos como arreglo y cuenta cuantas ordenes se han creado.
* Luego se ponen a prueba y se crean varios productos para crear una orden.

## P02-Mundo PC

Aplicación que permite practicar la herencia y simula una computadora con sus partes:
* Clase _DispositivoEntrada_: clase padre que tiene dos clases hijas: Raton y Teclado. Tiene constructor, getter y setter.
* Clase _Raton_: Clase hija de DispositivoEntrada, crea objetos del tipo Raton.
* Clase _Teclado_: similar a Raton, pero crea objetos del tipo Teclado.
* Clase _Monitor_: No tiene clase padre, es independiente. Incluye el constructor, getter y setter.

Finalmente se procede a crear el objeto _Computadora_ que recibe atributos de las clases Monitor, Teclado, Raton, además de sus atributos propios. Incluye getter y setter.

Por último se crea una orden para agregar varias computadoras y así almacenar varias computadoras en una orden.

## P03-Aplicación Calculadora

Aplicación que permite desarrollar una calculadora que sólo sume dos operandos.

En este caso se utiliza HTML, Bootstrap y JS, respectivamente.

Si se dejan números vacíos muestra un mensaje _La operación no incluye números_.

En JS se desarrolla únicamente la función sumar, que luego es llamada dentro del html con onClick.

## P04-Aplicación Listado de Personas

Aplicación que permite mostrar el Nombre y Apellido de un listado de personas.

Es una aplicación que lista dos elementos previamente cargados, pero además permite añadir nuevas personas a la lista.

Para ello se crean lo siguiente:
* funcion mostrarPersonas: que permite cargar la lista de personas.
* funcion agregarPersona: que al hacer click funciona para cargar la persona a la lista.
* clase Persona: que almacena el constructor, getter y setters.

## P05-Aplicación Reloj Digital

En este proyecto, realizaremos un reloj digital con HTML, CSS y JavaScript, en donde se incluira la hora minutos y segundos y también la fecha. 

El elemento de CSS, tendrá un efecto de animación al momento de mostrar la hora.

## P06-Aplicación Presupuesto]

En este proyecto se maneja el concepto de presupuesto. Se genera el presupuesto total, además de todos los ingresos y egresos.

Se agrega un formulario que permite añadir un egreso o egreso.

Y se listan en la parte inferior de la App los ingresos y egresos respectivos.
