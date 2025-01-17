* Variables
  Las variables nos permiten guardar valores, como números o palabras, en nuestro código que queremos usar o cambiar en algún momento. Normalmente indicamos de que tipo de variable se trata, por ejemplo podemos indicar que una variable es del tipo "número", por lo tanto contendrá un número.
  En javascript, no es necesario indicar el tipo de variable. Simplemente basta con crear la variable y asignarle un valor que queramos:
  let variable = valor;


* Strings
  Un String es un tipo de dato que guarda palabras, o "conjunto de letras o caracteres". Si quisiera guardar un String en una variable, defino una variale con la palabra reservada "let" y luego guardo el valor, utilizando comillas (let str = "ejemplo"). No tiene porque ser solo una palabra, pueden ser también oraciones como "hola mundo!". 
  Es importante que, cuando se quiere guardar una palabra u oración como String, esta esté rodeado con comillas. 


* Funciones (argumentos, `return`)
  Las funciones nos sirven para escribir un conjunto de instrucciones de nuestro código que queremos realiar más de una vez. Esto simplifica nuestro código, ahorrándonos varias líneas que vemos que se repiten una y otra vez.
  
  Por ejemplo, si tengo que utilizar un conjunto de acciones cuyo objetivo es sumar dos números y luego mostrar un texto, y esto lo tengo que hacer varias veces, puedo encerrar todo eso en una sola función, llamada "SumaYMuestra()", y todo lo que tengo que hacer es llamar a esa función. 

  A veces las funciones pueden requerir que les pasemos ciertos datos para que trabajen con ellos, llamados "argumentos" o "parámetros". También las funciones, además de realizar acciones, pueden retornar un valor que podemos utilizar.


* Declaraciones `if`
  Las declaraciones "if" son un tipo de instrucción que se utilizan en los códigos para verificar que si una condición se cumple, el código haga cierto conjunto de acciones, y si no se cumple la condición que haga otro. 

  Por ejemplo, puedo comprobar si mi variable "numero" es mayor o no a 10, y que si llega a serlo, es decir se cumple la condición, el código muestre "hola mundo!":

  if(numero > 10)
    mostrar "hola mundo!;

  Si "numero" no llega a ser mayor a 10, el código seguirá su camino sin mostrar el texto.


* Valores booleanos (`true`, `false`)
  Al igual que el String, los booleanos son un tipo de dato que podemos utilizar, pero estos solo tienen dos valores específicos: True (verdadero) o False (falso). Aparecen cuando se habla de operaciones lógicas. Por ejemplo, si en mi código pregunto si "1 es mayor que 22" (1 > 22), este me devolvería false, ya que 1 no es mayor a 22.  