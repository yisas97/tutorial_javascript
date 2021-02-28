# tutorial_javascript

## Clase 1:

### Variables:

Dentro de JavaScript tenemos tres formas de declarar una variable las cuales son: var, const y let.

1. Var: Era la forma en que se declaraban las variables hasta ECMAScript 5. Casi ya no se usa porque es de forma global y tiene las siguientes características:
```
- Se puede reinicializar: osea todas las variables se inicializan, por ejemplo:
    Var pokemonType = ‘electric’ entonces reinicializar es:
    Var pokemonType = ‘grass’ osea la misma variable con diferentes datos el último dato predomina.
- Se puede reasignar: osea la variable ya inicializada le reasignamos otro valor por ejemplo: inicializamos la variable: Var pokemonType = ‘electric’ ahora la       reasignamos pokemonType = ‘grass’ ya no va var
- Su alcance es función global: osea inicializamos la variable, pero la podemos llamar desde cualquier bloque (una llave abierta y una cerrada {}) pero hay que tener mucho cuidado con ello ya que puede haber peligro, no es recomendable usar VAR.

const y let es la forma en que se declaran las variables a partir de ECMAScript 6,
```
2. const: sirve para declarar variables que nunca van a ser modificadas:
```
- No se puede reinicilizar: es una const única no puede haber otra inicializada con el mismo nombre. const pokemonType = ‘electric’ no puede haber:
const pokemonType = ‘grass’
- No se pude re asignar: una vez que la hayamos inicializado no la podemos reasignar solo con su nombre: const pokemonType = ‘electric’ no puede ejecutarse:
pokemonType = ‘grass’
- No es inmutable: osea no puede cambiar con objetos:
```
3. Let: Son variables que pueden ser modificadas, se pueden cambiar:
```
- No se puede reinicilizar: es una const única no puede haber otra inicializada con el mismo nombre. let pokemonType = ‘electric’ no puede haber:
let pokemonType = ‘grass’
- Se puede reasignar: Osea la variable ya inicializada le reasignamos otro valor por ejemplo: inicializamos la variable: let pokemonType = ‘electric’ ahora la reasignamos pokemonType = ‘grass’
- Su contexto de es bloque: Solo funciona dentro de un bloque {}, fuera de ello no.
```


![Alt text](https://static.platzi.com/media/user_upload/JavaScript-4e0b4a50-c2ef-40af-b403-a1e4e7a64436.jpg "Title")


## Clase 2:

### Funciones:

Las funciones son las tareas que va a llevar a cabo el navegador. Existen 2 tipos de funciones

1) Declarativas
2) De expresión

```
Ambas pueden llevar parámetros, que son los datos que necesitan para ejecutarse.
Cada parámetro va separado por una coma.
Cada instrucción que tenga la función debe terminar con ; .
Si queremos que una función nos dé un numero o dato tenemos que usar la siguiente sintaxis:

return El dato que queremos que nos dé;
```

Las funciones declarativas tienen la siguiente sintaxis:
_function Nombre de la función (Parámetros de la función) {Instrucciones}_


Un ejemplo de una función puede ser una suma:

_function suma (a,b) {return a+b;}_

Las funciones de expresión son aquellas que guardamos en una variable, por lo tanto, no es necesario nombrarlas y tienen la siguiente sintaxis:

_var Nombre de la variable = function(Parametros){Instrucciones}._

Un ejemplo de una función de expresión sería:

_var suma = function(a,b){return a+b;}_

Para ejecutar las funciones debemos usar la siguiente sintaxis:

_Nombre de la funcion(Parametros función);_

Si la función no tiene ningún parámetro, únicamente se escribe:

_Nombre_de_la_función();_


