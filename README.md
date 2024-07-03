# quiz-prework-ts-node

Preguntas Abiertas (10)

    JavaScript Básico:
        Describe qué es una función en JavaScript y cómo se declara.
        R// una función en JavaScript se puede declarar de muchas maneras sin embargo las mas comunes son ()=>{} la arrow function y  function hola(){}

    Manipulación del DOM:
        Explica cómo seleccionar un elemento del DOM y cambiar su contenido.
        R// un elemento del DOM se puede seleccionar de muchas maneras, por la clase, el id o la misma etiqueta 
          document.getElementById("hola").
            document.querySelector("")
            document.getElementsByClassName("")
            document.getElementsByTagName("")


    Programación Orientada a Objetos (OOP):
        ¿Qué es una clase en JavaScript y cómo se define una?
        R// una clase en javascript se define como class name {...}

    Eventos en JavaScript:
        ¿Cómo se agrega un evento de clic a un botón en JavaScript?
        R// con el DOM agarramos el elemento button del html y lo declaramos como una variable y luego a la variable se le agrega un addEventListener("click" () =>{})
            
    Variables y Tipos de Datos:
        Explica las diferencias entre var, let, y const en JavaScript.
        R//let es una variable que se puede cambiar a lo largo del codigo, const es una variable unica e irrepetible osea constante y var es una manera de nombrar una variable para luego agregarle algo osea un var puede estar vacio y solo tener declarada el nombre para en cualquier momento ser usada

    Control de Flujo:
        ¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?
        R//las estructuras de control de flujo son las que nos permiten controlar el algoritmos como ciclos y concicionales los cuales se pueden declarar como, switch, if, while, do while o for

    Funciones de Flecha:
        Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
        R// una función de flecha es una función que se declara con los parametros y luego la flecha que representa la funcion por ejemplo ()=>{}

        const x = 5;
        const y = 10;

        const ejSuma = (a,b)=>{
            return a+b;
        }

        cconsole.log(`el resultado es: ${ejSuma(x,y)}`)


    JSON:
        ¿Qué es JSON y cómo se utiliza en JavaScript?
        R// JSON es un formato de datos que se utiliza para intercambiar datos entre la maquina o el lenguaje de javaScript y los  navegadores

    Promesas:
        Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.
        R// una promesa es una función que se declara con un then y un catch para pasar datos en javaScript

    Depuración:
        ¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?
        R//Error lens, hacer console.logs y breakpoints en el navegador

Preguntas de Selección Múltiple (20)

    ¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?

    (A) var myVariable; CORRECTA
    B) variable myVariable;
    C) let myVariable;
    D) A y C son correctas.

    ¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?

    (A) push() CORRECTA
    B) pop()
    C) shift()
    D) unshift()

    ¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?

    A) == 
    (B) === CORRECTA
    C) !=
    D) !==

    ¿Cuál es la salida del siguiente código?

    console.log(typeof null);

    (A) null CORRECTA
    B) undefined
    C) object
    D) number

    ¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?

    A) forEach()
    B) map()
    C) filter()
    (D) Todas las anteriores 

    ¿Qué se entiende por “hoisting” en JavaScript?

    A) Declaraciones de variables y funciones se mueven al principio de su ámbito.
    B) Es un término para describir la eliminación de variables.
    C) Es un método para agrupar varias funciones.
    (D) Ninguna de las anteriores. 

    ¿Cuál es la diferencia entre null y undefined en JavaScript?

    A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
    B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.
    (C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor. CORRECTA
    D) No hay diferencia.

    ¿Cuál es el propósito del método Array.prototype.map()?

    A) Modificar el array original.
    (B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original. CORRECTA
    C) Filtrar los elementos de un array.
    D) Encontrar un elemento en un array.

    ¿Qué es el Event Loop en JavaScript?

    A) Un ciclo que controla las llamadas recursivas. 
    B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
    (C) Un método para iterar sobre arrays.
    D) Ninguna de las anteriores.

    ¿Cuál es la salida del siguiente código?

    console.log(0.1 + 0.2 === 0.3);

    A) true 
    (B) false CORRECTA
    C) undefined
    D) NaN

¿Qué se entiende por strict mode en JavaScript?

    A) Un modo que permite utilizar características experimentales.
    B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
    (C) Un método para validar datos. 
    D) Ninguna de las anteriores.

¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

    A) let obj = {};
    B) let obj = Object.create();
    C) let obj = new Object();
    (D) A y C son correctas. 

¿Qué es un callback en JavaScript?

    (A) Una función que se pasa como argumento a otra función. 
    B) Un tipo de variable especial.
    C) Un método para declarar funciones.
    D) Ninguna de las anteriores.

¿Cuál es el propósito de async y await en JavaScript?

    (A) Ejecutar funciones síncronas. 
    B) Manejar operaciones asincrónicas de manera más simple y legible.
    C) Declarar variables globales.
    D) Ninguna de las anteriores.

¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

    A) Arrays
    B) Strings
    (C) Objetos 
    D) Ninguna de las anteriores.

¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

    A) JSON.parse()
    (B) JSON.stringify()
    C) toString()
    D) parseInt()

¿Qué es un Promise en JavaScript?

    A) Una función que se ejecuta inmediatamente.
    (B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
    C) Un método para declarar variables.
    D) Ninguna de las anteriores.

¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

    A) push()
    B) pop()
    C) shift()
    (D) unshift()

¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

    A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
    (B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente.
    C) No hay diferencia entre ellos.
    D) Ambos almacenan datos solo durante la sesión del navegador.

¿Qué método se utiliza para detener la propagación de un evento en el DOM?

    A) event.stopPropagation()
    (B) event.preventDefault()
    C) event.stop()
    D) event.cancel()

