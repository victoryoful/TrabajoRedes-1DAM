# TrabajoRedes-1DAM
Trabajo de Victor Rosa Arias


Ejercicio Redes 1º DAM IES FRANCISCO AYALA


1-Subredes.
Para esta parte he creado 3 switch uno para cada subred.
El primero tiene capacidad para 20 hosts. Con las siguientes ip:
serie 190.0.0.0
puerta 190.0.0.1
El segundo tiene capacidad para 100 hosts. Con las siguientes ip:
serie 192.168.4.0
puerta 192.168.4.1
El tercero tiene capacidad para 6 hosts. Con las siguientes ip:
serie 190.1.0.0
puerta 190.1.0.1

2-Los servidores DHCP estan creados con un server, un switch y los ordenadores indicados en cada caso conectados con cable eth.
En este caso asignamos una ip fija al servidor, y lo configuramos para que asigne una ip y puerta de enlace a cada uno de los ordenadores que se conecten, yo en mi caso he dejado solo capacidad para aquellos que estan ya conectados.
Cuando estan todos conectados, configuramos los pc para que se les asigne la ip mediante DHCP.
En el caso del punto de acceso con el servidor DHCP, configuramos el punto de acceso para crear una red y ponemos una contraseña. Vamos a los portatiles y apagandolos primero, ponemos la antena de red wifi para poder conectarlos.
Elegimos la red a la que deseamos conectarnos, ponemos la contraseña y ya estan conectados


3- Ordenadores con Ip fija
Asignamos las Ip a nuestros ordenadores y conectamos estos a un switch

4-Servidor DNS y servidores web
En este caso necesitamos 4 servidores (1 DNS 3 WEB) y un switch
Configuramos el DNS y les asignamos las direcciones IP de los dominios que necesitamos
Configuramos los servidores web con las ip de cada una de las paginas web que deseamos tener

5- Conexion 
Todos los switch estaran conectados mediante un cable eth a su router, que estaran configurados para tener puerto serial y asi tener todos conectados de manera Serial.
