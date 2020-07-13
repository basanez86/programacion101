# Como programar 101

## Idea general
 Antes de aprender de la **a** a la **z** cualquier lenguaje de programación, es necesario poder entender la estructura lógica general de cada lenguaje.
 
Nuestro mayor propósito al escribir un código, al menos eso creo, es automatizar procesos. Desde crear un videojuego  hasta mandar un cohete al espacio, la programación es simplemente el manejo o manipulación de `información` a través de ciertos `procesos o reglas` en nuestro código para obtener un `resultado`.

> *Por ejemplo:* 
> - tengo esta `información` **1** y **2**
> - como `proceso` aplico una suma 1 **+** 2
> - mi `resultado` es **3**

Así de fácil es programar.

> *NOTA: Como referencia voy a estar usando ejemplos con **python**, **javascript**, **php** y **powershell***.


## Reglas básicas
**Lineas de código**
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

---
**Imprimir en la consola**
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

#### Anotaciones
> Los comentarios son parte fundamental a la hora de escribir un código, en especial si este tiene varias lineas escritas. Un comentario empieza con ciertos caracteres que les permiten ser ignorados al momento de ejecutar el código.
```python
# | python |
# Este es un comentario
print('hola')
```
```php
// | php |
// Este es un comentario
echo 'hola';
```
```javascript
// | javascript |
// Este es un comentario
/*
Este es un comentario multilineal
*/
console.log('hola');
```
```powershell
# | powershell |
# Este es un comentario
<#
Este es un comentario multilineal
#>
Write-Host 'hola'
```

## Variables
> Dependiendo del lenguaje las variables pueden o no empezar con el símbolo **$**
```python
# | python |
miVariable = <valorAsigando>
miVariable = 'abc'
```
```php
// | php |
$miVariable = <valorAsigando>
$miVariable = 'abc';
```
```javascript
// | javascript |
var miVariable = <valorAsigando>;
var miVariable = 'abc';
```
```powershell
# | powershell |
$miVariable = <valorAsigando>
$miVariable = 'abc'
```

#### Tipos de variable
 - Integer (Números enteros)
```python
# | python |
miVariable = 1
miVariable = 158
miVariable = abc # [ERROR] Una letra no puede ser un numero  
```
 - String (Cadenas de texto)
```python
# | python |
# Cualquier caracter dentro de comillas
miVariable = 'abc'
miVariable = 'Cualquier valor, 123456'
miVariable = '123456' # Un numero puede ser una letra
miVariable_2 = miVariable # Traduccion: miVariable_2 = '123456'
```
 - List o Array 
>Cualquier conjunto de letras y o numeros como 'Values' asignados a un 'Key', separados generalmente por una coma.
> array = [ key1:valor1, key2:valor2, key3:valor3, key4:valor4 ]

*Ejemplo con valores NO asignados*
```python
# | python |
miVariable = [ 'valor1', 'valor2', 'valor3', 'valor4' ]
```
```php
# | php |
$miVariable = array('valor1', 'valor2', 'valor3', 'valor4');
```
```javascript
// | javascript |
var miVariable = [ 'valor1', 'valor2', 'valor3', 'valor4' ];
```
```powershell
# | powershell |
$miVariable = @('valor1', 'valor2', 'valor3', 'valor4')
```
> Traduccion: [ 0:'valor1', 1:'valor2', 2:'valor3'... ]
`;`

*Ejemplo con valores asignados*
```python
# | python |
miVariable = [ 'valor1', 'valor2', 'valor3', 'valor4' ]
```
```php
# | php |
$miVariable = array('valor1', 'valor2', 'valor3', 'valor4');
```
```javascript
// | javascript |
var miVariable = [ 'valor1', 'valor2', 'valor3', 'valor4' ];
```
```powershell
# | powershell |
$miVariable = @('valor1', 'valor2', 'valor3', 'valor4')
```
> Traduccion: [ 0:'valor1', 1:'valor2', 2:'valor3'... ]
