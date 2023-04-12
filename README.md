# TDD (202304-w2ExTDD)

Crea y testea usando TDD una funcion que se llame `calculateSumOfValues` que reciba un string de numeros separados con comas y devuelve la suma de los numeros como string.

e.g `"3,12,14.3,-12"` devuelve `"17.3"`

Si no recibe ninguna cadena, la funcion debe lanzar un error con el siguiente mensaje: "No numbers provided"

Si algun valor no es numero, la funcion debe lanzar un error con el siguiente mensaje: "Please provide numbers separated by commas"

Debemos llegar a la implementacion mediante **fake-it** y **triangulation**.

Haced los tres ciclos de **RED, GREEN, REFACTOR** para cada responsibilidad de la funcion.

Bola extra implementar mas corner-cases
