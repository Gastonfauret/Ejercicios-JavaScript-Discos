# Ejercicios-JavaScript-Discos

- Ejercicios JavaScript.

- Coleccion de Discos.

Tenemos un objeto que representa parte de una coleccion
de albumes musicales.
Cada album tiene un numero de identificacion unico (id)
asociado a otras propiedades

Define una funcion actualizarDiscos que tome los siguientes parametros:
- Disco (El Objeto que representa la coleccion de discos).
- id.
- Propiedad ("artista" o "canciones").
- valor.
Tu meta es completar la funcion implementando las siguientes reglas
para modificar el objeto pasado a la funcion:
- si "valor* es una cadena vacia, eliminar la propiedad 
del album correspondiente.
- Si "propiedad" es igual a la cadena de caracteres "canciones" pero
el album no tiene una propiedad llamada "canciones", crea un arreglo
vacio y agrega "valor" a ese arreglo.
- Si "propiedad" es igual a la cadena de caracteres de "canciones" y
"valor" no es una cadena vacia, agrega "valor" al final del arreglo
de canciones del album correspondiente.
- Si "valor" no es una cadena vacia y "propiedad" no es igual a
"canciones", asigna el valor del parametro "valor" a la propiedad.
Si la propiedad no existe, debes crearla y asignar este valor.
