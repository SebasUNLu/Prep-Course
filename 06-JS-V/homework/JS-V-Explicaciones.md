* `prototype`
  Todos los objetos tienen acceso a una referencia hacia el objeto "padre" del mismo, llamado "prototype". Este objeto padre fue el que se utilizó como plantilla para crear otros objetos que también haran uso de sus propiedades y métodos.

  Por ejemplo, un array es un objeto que posee métodos como .push, .pop, pero estas no las definimos nosotros cuand creamos un array. Estas funciones vienen de la clase padre "Array", que contiene todas las propiedades y funciones necesarias que hacen que un array sea un array.

  let arr = [1, 2]
  arr.push(3)

  Esta es la forma en que definimos un array. Solamente definimos los elementos que contiene, y también podemos utilizar .push, pero nunca lo definimos nosotros. Cuando llamamos una propiedad de un objeto que normlamente nosotros no definimos, lo que se hace es que se busca esa propiedad en el prototipo del objeto, en este caso Array, que tiene el método .push.

  Para acceder al prototipo, se hace uso de obj.__proto__; 

  Esta utilización de clases padres y la capacidad de utilizar sus propiedades se llama "herencia".

* _Constructors_ (de Clases)
  Son funciones cuya finalidad es la de crear un objeto, con las propiedades y funciones definidas en la clase, para poder usarlo finalmente como una variable. Estas funciones pueden recibir y utilizar parámetros. 

  Ejemplo:
  function Persona(nombre, edad){
    this.nombre = nombre;
    this.edad = edad;
  }

  Esta es una función contructora de la clase Persona, usada para crear objetos. Para poder crear objetos de esta clase, se debe llamar esta función constructora junto a la palabra "new":
  let obj = new Persona('seba', 23);