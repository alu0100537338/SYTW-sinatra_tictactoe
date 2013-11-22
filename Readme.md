Practica 7 - TicTacToe 
======================

Enunciado
---------

TicTacToe usando DataMapper y SASS y desplegar en Heroku.


Resolucion
----------

A traves del fichero usuarios.rb hemos creado el modelo de la Base de Datos, 
creandola a traves del fichero app.rb, quien la guardara en development.db.

Por ultimo se ha cambiado la apariencia del programa a traves de modificaciones
en los ficheros ya dados, y la creacion de views/usuarios.haml, quien se encarga
de mostrar un historial de los jugadores que han usado la aplicacion y sus resultados.


Warning
-------

Es posible que sean necesarias librerias complementarias para el correcto funcionamiento:

    sudo apt-get install libecpg-dev
    sudo apt-get install postgresql-client
    sudo apt-get install postgresql
    

Ejecucion
---------

Para ejecutar la aplicacion desde una consola:

    1.rake
    2.localhost:4567
    
Para acceder directamente:

    http://boiling-refuge-5409.herokuapp.com/
    
-----------------------------------------------------------------------------------------------------------------
Jessica A. Ramos Villarreal - ETSII-ULL



