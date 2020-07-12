# Como programar 101

## Reglas generales

#### Semicolon
> El uso del semicolon **;** es muy importante en la mayoría de los lenguajes para delimitar/finalizar acciones.
```python
# | python |
x = y print('hola')
# ERROR Al intentar igualar X con Y el sistema entiende que X es igual a "y print('hola')"
x = y; print('hola');
# Al intentar igualar X con Y el sistema entiende que X es igual a Y, y aparte tiene que imprimir 'hola' en la consola
```

#### Imprimir en la consola
> Entre las funciones mas importantes para imprimir están 'print' y 'echo', los usos y variantes dependen del lenguaje.

```python
# | python |
print('hola')
```
```php
// | php |
echo 'hola';
```
```javascript
// | javascript |
console.log('hola');
```
```powershell
# | powershell |
Write-Host 'hola'
```

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
