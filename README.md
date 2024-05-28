# PROYECTO PARA INGENIERIA DE SOFTWARE
 
###  Descripción:
Aplicación software que permita a sus usuarios capturar los datos requeridos para loguearser a una plataforma, la cual les muestra un dashboard presentando la proporcion de tipos primarios de todos los pokemon existentes hasta la actualidad.
 
### Objetivo general:
Desarrollar un software que haga uso de bases de datos para almacenar informacion de registro de usuario, asi como extraer informacion de las mismas y presentarla en un dashboard.

###  Integrantes

 - [Fausto Medina](https://github.com/Harico04)
 - [Joaquin Sotelo](https://github.com/JoaquinSotel0) 
 - [Manuel Gortarez](https://github.com/Mgb64) 
 - [Alan Torres](https://github.com/TumbadoBoy0604) 
 - [Rogelio Peralta](https://github.com/rgperalta04) 
 - [Ernesto Carrasco](https://github.com/jesuscarra) 
 - [Ricardo Peña](https://github.com/RemilZarza)
 - [Ian Zepeda](https://github.com/I4NzG)

#Como utilizar el programa

###Clonar el repositorio
Primero se debe clonar el repositorio a la carpeta de su preferencia.

###Configurar servidor de Node.js
Se debe iniciar en la carpeta a la que se clono un servidor Node.js, y se deben descargar todas las dependencias (express, mySQL, passport, etc.).

###Tener capacidad de crear e importar bases de datos en mySQL
Se debe tener a la vez software necesario para tener bases de datos de mySQL, ya se el mismo mySQL o uno como XAMPP. Se debe crear una base de datos llamada nodejs-users, que tenga un tabla llamada users. La tabal debe tener 4 columnas llamadas id(INT 11), name(VARCHAR 100), email(VARCHAR 100) y password(VARCHAR 255). id debe tener autoincremento.
Tambien se debe importar la base de datos pokemon_data, la cual se puede encontrar en Kaggle.

###Iniciar el proyecto

Con todo listo se debe iniciar la base de datos en la que se tienen guardadas tanto nodejs-users como pokemon_data. Se inicia el servidor con el comando "npm run devStart", y en el navegador se abre el link localhost:300. Una vez todo esto este listo de debera ver la pagina.
