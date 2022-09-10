Usuarios y grupos

Primero ingresamos como superusuario para crear los grupos con el comando 

su



Luego añadimos el grupo con los siguientes comandos

grupoadd casa



luego creamos 3 usuarios 

useradd jonathan 
useradd abril



luego añadimos los usuarios al grupo creado

adduser jonathan casa
adduser abril casa

luego cambiamos el nombre del grupo 

groupmod -n familia casa
