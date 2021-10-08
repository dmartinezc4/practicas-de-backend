Esta primera práctica no es necesaria entregarla a través de github (aunque quien quiera puede hacerlo). Solo es necesario enviar el archivo index.ts

Realizar una función toString que reciba cualquier tipo de dato y lo convierta en un string. La función debe recibir como parámetro una variable de tipo any y el resultado debe ser idéntico al resultado de llamar sobre dicha función JSON.stringify(variable).



Se debe incluir esta linea en el codigo:

if(toString(variable) == JSON.stringify(variable)) console.log("Ejercicio 1 funciona");

(probar con distintos tipos de variables, con al menos tres niveles de profundiad y que incluyan al menos un array de objetos y un array de números)
