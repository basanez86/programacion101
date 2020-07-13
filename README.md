# Como programar 101

1. [Idea general](#Idea-general)
2. [Reglas básicas](#Reglas-básicas)
	- [Lineas de código](#Lineas-de-código)
	 - [Imprimir en la consola](#Imprimir-en-la-consola)
	 - [Anotaciones](#Anotaciones)

## Idea general
 Antes de aprender de la **a** a la **z** cualquier lenguaje de programación, es necesario poder entender la estructura lógica general de cada lenguaje.
 
Nuestro mayor propósito al escribir un código, al menos eso creo, es automatizar procesos. Desde crear un videojuego  hasta mandar un cohete al espacio, la programación es simplemente el manejo o manipulación de `información` a través de ciertos `procesos o reglas` en nuestro código para obtener un `resultado`.

> *Por ejemplo:* 
> - tengo esta `información` **1** y **2**
> - como `proceso` aplico una suma 1 **+** 2
> - mi `resultado` es **3**

Así de fácil es programar.

> *NOTA: Como referencia voy a estar usando ejemplos con **python**, **javascript**, **php** y **powershell***.
###### [Ir arriba](#Como-programar-101)

## Reglas básicas
### Lineas de código
Una linea de código es básicamente un proceso que le dice al programa que hacer escrito en una linea de nuestro documento. 

> *ejemplo en **python**:* 
> ```python
> print('hola')
> print('adios')
> ```
> *Estas lineas de código (2 lineas) le están diciendo al programa que primero imprima en la consola la palabra **hola** y después imprima la palabra **adios**.*
>
Como puedes ver en el ejemplo de arriba **python** y cualquier otro lenguaje lee las lineas de arriba hacia abajo, siempre en ese orden, y cada linea representa un proceso diferente. Pero que pasa si agrupamos 2 o mas procesos en una sola linea de código.
> *ejemplo de `error` en **python**:* 
> ```python
> print('hola') print('adios')
> ```
> *Esto nos generaría un `error` porque el programa no sabe donde empieza o termina nuestro proceso.*

En algunos lenguajes como **php** es muy necesario el uso de `delimitadores` como el `semicolon `**`;`** después de cada proceso. Este le permite saber al programa saber en donde empieza y termina la regla. En otros lenguajes no es necesario el uso del `semicolon` al final de cada linea de código. Solo se utilizan para delimitar procesos en la misma linea.
> *ejemplo en **python**:* 
> ```python
> print('hola'); print('adios')
> ```
> ```python
> print('hola')
> print('adios')
> ```
> *No es necesario terminar nuestras lineas de código con el `semicolon`, pero si es necesario delimitar nuestros procesos si están en la misma linea.*

> *ejemplo en **php**:* 
> ```php
> echo 'hola'; echo 'adios';
> ```
> ```php
> echo 'hola';
> echo 'adios';
> ```
> *Es necesario terminar nuestras lineas de código con el `semicolon`, al igual que delimitar nuestros procesos en la misma linea.*

> *NOTA: la única forma de saber si el uso del semicolon al final de cada linea de código es indispensable, es familiarizarse con el lenguaje.*
###### [Ir arriba](#Como-programar-101)
---
### Imprimir en la consola
Es muy importante saber lo que esta sucediendo en nuestro código y una herramienta fundamental es `imprimir en la consola`. Entre las funciones mas importantes para imprimir están `print` y `echo`, los usos y variantes dependen del lenguaje.

> ***python:***
> ```python
> print('hola')
> ```

> ***php:***
> ```php
> echo 'hola';
> ```

> ***javascript:***
> ```javascript
> console.log('hola');
> ```

> ***powershell:***
> ```powershell
> Write-Host 'hola'
> ```
###### [Ir arriba](#Como-programar-101)
---
### Anotaciones
Las Anotaciones o comentarios son parte fundamental a la hora de escribir un código, en especial si este tiene varias lineas escritas. Un comentario empieza con ciertos caracteres que les permiten ser ignorados al momento de ejecutar el código.
> ***python:***
> ```python
> # Este es un comentario
> ```

> ***php:***
> ```php
> // Este es un comentario
> ```

> ***javascript:***
> ```javascript
> // Este es un comentario
> /*
>     Este es un comentario
>     multilineal
> */
> ```

> ***powershell:***
> ```powershell
> # Este es un comentario
> <#
>     Este es un comentario
>     multilineal
> #>
> ```
