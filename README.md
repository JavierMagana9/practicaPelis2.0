# practicaPelis2.0

# PracticaDomYEventos2.0

Lo primero que he tenido en cuenta es que elementos del documento HTML iban a ser estaticos y cuales dinamicos. En este caso el HTML se me vino dado.


Una vez deidido, elegí que elementos del DOM tenía que capturar para usar posteriormente:

```js
const formulario = document.querySelector('#formulario');
const genero = document.querySelector('#genero');
const filtrar = document.querySelector('#filtrar');
const cajaPelis = document.querySelector('#cajaPelis');
const listaErrores = document.querySelector('#listaErrores');
const mensajeTabla = document.querySelector('#mensajeTabla');

```

Despues decidi que habia que crear para posteriormente pintar, en este caso un array con los generos que saldrian del

```js
let arrayPelis = [];
let arrayGeneros=['Terror','Comedia','Acción', 'Romántica']

```
### Funciones

una vez decidido esto, pense que acciones necesitaba:

