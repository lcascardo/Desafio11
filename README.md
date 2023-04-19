# Desafio 11

1- Descargar librerias con comando: npm i <br>
2- Correr servidor con comando: nodemon src/app.js <br>

DESAFIO: <br>
- Primero, definir un sistema de niveles que tenga la siguiente prioridad (de menor a mayor): debug, http, info, warning, error, fatal. <br>
- Después implementar un logger para desarrollo y un logger para producción, el logger de desarrollo deberá loggear a partir del nivel debug, sólo en consola. <br>
- Sin embargo, el logger del entorno productivo debería loggear sólo a partir de nivel info. <br>
- Además, el logger deberá enviar en un transporte de archivos a partir del nivel de error en un nombre “errors.log”. <br>
- Agregar logs de valor alto en los puntos importantes de tu servidor (errores, advertencias, etc) y modificar los console.log() habituales que tenemos para que muestren todo a partir de winston. <br>
- Crear un endpoint /loggerTest que permita probar todos los logs. <br>

INSTRUCCIONES PARA REVISAR LO HECHO EN EL DESAFIO: <br>
1-Correr servicios (explicado en instrucciones para correr servicios) <br>
2-Colocar en el navegador el endpoint http://localhost:8080/loggerTest <br>
3- Deberia mostrar un success en el navegador y en la terminal del VSC deberia mostrar todos los logs 
