# Tecnolochicas 

# Sesión 2 09/09/2023


https://esolangs.org/wiki/COW


**Compilación** Código escrito en un lenguaje que tiene que ser compilado (traducido) a lenguaje máquina, el lenguaje que los procesadores únicamente entienden el lenguaje máquina o lenguajes de bajo nivel. 
Se requiere de un alto rendimiento para que el proceso de ejecución y compilación sea rápido.


Ejemplo: Pascal, C, C++, Cobol, Fortran.



**Interpretados**: el código se ejecuta línea por línea, no necesita ser compilado. Ejemplo: Python, Ruby, JS


**Modelado o de estilado**: Son normas o instrucciones que nos dicen cómo se deben representar esquemas. Generan experiencias para el usuario. Ejemplo: CSS


**Algoritmos** serie de pasos lógicos, finitos para resolver una cuestión.


**Lenguaje Natural** descripción detallada paso por paso en lenguaje escrito de cada problema a resolver y cómo se espera resolverlo.

Ejemplo: 


Problema: lámpara no enciende


Solución: verificar que la lámpara esté conectada a la luz, si no está conectada, enchufarla; si sí está conectada, verificar que el foco no esté fundido, si está fundido comprar otro foco.


**Diagrama de flujo** representación visual del problema. Diagrama visualmente entendible de un flujo de datos en el cual se dibuja cada paso o proceso determinado dentro de un sistema, el cual resuelve un problema dado.


![DiagramaDeFlujo]()

**Pseudocódigo** Es una combinación del lenguaje natural con las convenciones y sintaxis de algún lenguaje de programación con el lenguaje natural, con el cual se describen estructuradamente los pasos a seguir para resolver algún problema determinado o se definen procesos dentro de un sistema
 Tim Berns del CERN

![PseudocodigoEj]()


![Ejercicios]()


1.-  Realizar un algoritmo que sume dos números


Inicio función Suma{
   
    #Quiero leer 2 números y guardarlos en variables
    Leer num1
    Leer num2
    
    #Quiero definir una variable llamada suma que tome num1 y num2 para sumarlos
    suma = num1 + num2

    #Retorna valor nuevo de suma
    return suma
}

### VSCode Extensions

* Live Server

* Material Icon Theme

JavaScript le da funcionalidad 
Front End 
Diseño web
Usabilidadn UX UI 

## Back End

Manejo de bases de datos
Python, Php, Ruby
MySQL

##HTML
HyperText Markup Language 

Versión más reciente html 5

Es un lenguaje de etiquetas, no da funcionalidad
1980 Berns del CERN

Da estructura

Elemento 
Componente báscico de un htmlSe utilizan elementos para definir la estructura

Etiqueta
Especifica el tipo de elemento que se va a crear 

charset indica el set de caracteres que se va a utilizar, para poder identificarlo


title aparece en la pestaña

viewport es la escala de la pantalla que depende del dispositivo en el que se ve 

<main></main> representa el contenido principal del documento o aplicación

<img src="" alt=""> en src va el link de la imagen

modelo responsivo --> debe funcionar en cualquier dispositivo

## Listas

ul --> unordered list

li --> item list, declara cada elemento de la lista, se pone uno por cada elemento
li*n donde n es el número de elementos que queremos poner

ol --> lista ordenada

div --> agrupar contenidos o crear secciones

a --> Ancla crea un enlace a otras páginas, archivos o dentro de la misma página (anchor), redirige 

href es como el src, indica a dónde va a redirigir

``` html 
<a href="#"></a> <!--el # indica el elemento dentro del documento a donde redirigirá-->
```
p  --> Párrafo

Para hacer referencia en h3 o en p se pone id="" y entre comillas se pone el nombre que tiene el #, si se pone en p, te lleva a donde comienza el párrafo

br --> break, para poner espacios

Metiendo una imagen en un ancla 

input --> permite que el usuario ingrese información
action (inside form) --> para mandar los datos a una BD

label --> Para una interfaz de usuario, dentro se pueden poner más elementos que tienen que ver con respuestas del formulario
input para ingresar información, si al type se le pone radio es para seleccionar una opción

FLEXBOX css froggy
flexboxfroggy.com

Leer instrucciones 
mdn web docs --> para tipo wiki de html


## CSS

Pasar de pixeles a porcentajes

section se utiliza de forma jerárquica antes de los divs, dentro de la sección se ponen divs

div es para dividir es lo mismo que section, una caja que ayuda a poner elementos en orden, en la práctica se usa de manera diferente

--> Tarea

