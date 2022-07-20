* Objetos
  Un objeto es una colección de características o atributos, llamados "propiedades", que "describen" al objeto, y un conjunto de funciones llamados "métodos", que son los comportamientos que tiene ese objeto.

  Por ejemplo, puedo tener un objeto llamado perro, que tenga una propiedad llamada "nombre" y un método "ladrar"
  let perro = {
    nombre: 'Tony',

    ladrar: function() {
      console.log('woof')
    }
  }
  Así definimos un objeto perro. Tiene una propiedad y un método. A diferencia de los arrays, se puede llamar a sus atributos con el nombre de la variable, un punto y el nombre:
  perro.nombre -> 'Tony'
  perro.ladrar() -> 'woof' en consola
  (aunque también pueden llamarse con los corchetes: perro['nombre'])
  Es importante notar que los métodos son funciones, por lo que hay que llamarlos con los paréntesis al lado.

* Propiedades
  Las propiedades son un conjunto de claves y valores, donde las claves son el nombre de la propiedad y se utilizan para obtener el valor de la misma. 
  En el caso anterior, una propiedad de "perro" es:
  clave: nombre
  valor: 'Tony'

* Métodos
  Los métodos son el "comportamiento" del objeto. Son funciones que se definen dentro de este. Estas funciones solo pueden llamarse al nombrar al objeto al que definen:
  perro.ladrar();

* Bucle `for…in`
  

* Notación de puntos vs notación de corchetes
  Son dos formas distintas de llamar a las propiedades o funciones de un objeto.

  Tomemos por ejemplo el siguiente objeto:
  let perro = {
    nombre = 'Tony',

    ladrar: function() {
      console.log('woof')
    }
  }

  En la notación de corchetes, se utiliza el nombre de la propiedad como si fuera un string dentro de los corchetes:
  perro['nombre'] -> 'Tony'
  perro['ladrar']()

  En la notación de puntos, solo basta con utilizar un punto luego de la variable:
  perro.nombre -> 'Tony'
  perro.ladrar() 