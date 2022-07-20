* Arrays
  Un array, tambien llamado "Arreglo", es un tipo de dato el cual guarda una lista de datos, como pueden ser numeros, palabras, booleanos, funciones, otros arrays, etc. Cada elemento del array tiene su posición, que empieza desde el 0, y el valor. Se define un arreglo con sus elementos, o vacío, encerrándolos en corchetes, y los elementos separados por comas.
  let varArray = []
  let varArray2 = [1, 2]

  Si mostramos uno por consola, mostraría algo como lo siguiente:
  [1, 2, 'tres", null, [5, 6], 'otro elemento']

  Para poder acceder a un valor del array, debemos poner el número de la posición deseada entre corchetes, de esta forma:
  varArray[0] -> así accedemos al primer elemento de varArray.

  Con varArray.length obtenemos el largo del array, es decir la cantidad de elementos que posee. Hay que recordar que, si bien .length devuelve el largo de la lista, por ejemplo 7, las posiciones de los elementos empieza desde el 0, es decir dicho array de ejemplo tendría los elementos del 0..6, haciendo 7 elementos (me refiero a las posiciones, no los valores).
  