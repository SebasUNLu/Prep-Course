* Funciones Callback
  En javascript pueden pasarse funciones como parámetros de otras funciones. 
   
  Ejemplo: function func1(arg, cb) {
    return cb(arg)
  }
  En este ejemplo, la función func1 recibe un parámetro que dentro se trata como si fuera una llamada a una función (por conveniencia, se le suele llamar "cb"). Esta funcion cb a su vez recibe como parámetro arg.

  Estas funciones que se pasan pueden estar:

  - Ya definidas: 
    function mostrar(arg) {
      console.log(arg)
    }

    func1('hola', mostrar) --> muestra 'hola' por consola
  
  - Definidas donde se ponen los argumentos: 
    func1('Adios', function mostrar(argumento){
      console.log(argumento);
    }) --> imprime 'Adios' en consola

  - Incluso pasarlas sin nombre: 
    func1('Adios', function (argumento){
      console.log(argumento);
    }) --> imprime 'Adios' en consola
  
  Estas funciones que se pasan como parámetros son las funciones "callback".