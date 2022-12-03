# Act1-Operaciones-basicas-y-metodos-de-JavaScript

<<<<<<< HEAD
## Explicacion de Lineas De Codigo

### Clase1.js

  Se definen 2 variables de tipo string, llamadas nombre y apellido, cuyos valores son "Zaid" y "Mahatma"
```javascript
  var nombre = 'Mahatma', apellido = 'Barcenas';
  ```
  Se define una variable de tipo de int, llamada edad con un valor equivalente a 17
```javascript
  var edad = 17;
  ```
  Se escribe console.log para escribir un mensaje el cual dira "Hola Mahatma Barcenas"
```javascript
  console.log("Hola" + " " + nombre + " " + apellido);
  ```
  Se escribe console.log para escribir un mensaje el cual dira "Se que tienes 17 años"
   ```javascript
  console.log("Se que tienes " + edad + " años");
  ```
### Clase2.js
 Se definen 2 variables de tipo string, llamadas nombre y apellido, cuyos valores son "Dayana" y "Perez"
```javascript
  var nombre = "Dayana", apellido = "Perez";
  ```
Se modifica la variable mombre, haciendo que se escriba todo en mayusculas, viendose asi "DAYANA"
  ```javascript
  var NombreEnMayusculas = nombre.toUpperCase();
  ```
Se modifica la variable apellido, haciendo que se escriba todo en minusculas, viendose asi "perez"
  ```javascript
  var apellidoEnMinusculas = apellido.toLowerCase();
  ```
Se modifica la variable mombre, haciendo que se solo se escriba la primera letra, viendose asi "D"
  ```javascript
  var primeraletradelnombre = nombre.charAt(0);
  ```
Se modifica la variable mombre, haciendo que se cuenten el numero de caracteres, mostrando 6 como resultado
  ```javascript
  var cantidaddeletrasdelnombre = nombre.length;
  ```
Se usan las variables mombre y apellido, haciendo que solamente la variable apellido se modifica y se escriba en mayusculas, viendose asi "Dayana PEREZ"
  ```javascript
  var nombrecompleto = `${nombre} ${apellido.toUpperCase()}`;
  ```
### Clase3.js
Se define una variable de tipo int llamada a, con un valor equivalenta 5
```javascript
  var a = 5;
  ```
Se define una variable de tipo int llamada b, con un valor equivalenta 10
  ```javascript
  var b = 10;
  ```
Se define una variable la cual suma la varible a mas la variable b, dando como resultado 15
  ```javascript
  var c = a + b;
  ```
Se define una variable la cual suma la varible a menos la variable b, dando como resultado -5
  ```javascript
  var d = a - b;
  ```
Se define una variable la cual suma la varible a por la variable b, dando como resultado 50
  ```javascript
  var d = a * b;
  ```
Se define una variable la cual suma la varible a entre la variable b, dando como resultado 0.5
  ```javascript
  var d = a / b;
  ```
Esto es un comentario
  ```javascript
 //Esto es un comentario
  ```
Se define una variable de tipo int llamada precio, con un valor equivalenta 200.3
  ```javascript
  var precio = 200.3;
  ```
Se define una variable de tipo int llamada total, la cual multiplica la variable precio por 100, lo vuelve a multplicar por 3 y al final lo divide entre 100,la razon por la que se multplica por 100 y despues se devide entre 100 es para borrar los decimales innecesarios
  ```javascript
  var total = precio * 100 * 3 / 100;
  ```
Se define una varible de tipo int llamada totalStr, la cual hace que la variable total muestre 2 decimales pero la convierte en una variable de tipo string
  ```javascript
  var totalStr = total.toFixed(2);
  ```
Se define una varible de tipo int llamada total2; la cual hace que la variable totalStr vuelva ser una variable de tipo int
  ```javascript
  var total2 = parseFloat(totalStr);
  ```
Esto es un comentario
  ```javascript
  //Mostrar con 2 decimales con variable numerica
  ```
Aqui se mostrara un mensaje en la consola el cual dira "Resultado"
  ```javascript
  console.log("Resultado")
  ```
Aqui se mostrara un mensaje con la varible totalStr con sus 2 decimales pero sin cambiarla de tipo int
  ```javascript
  console.log(total.toFixed(2));
  ```