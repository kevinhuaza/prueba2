# prueba2

la carpeta php contiene la creacion de la api y conecion a base de datos
la carpeta React contiene el front

 secuencias:
 Realizar una consulta que permita conocer cuál es el producto que más stock tiene
 .
SELECT nombre,MAX(stock) FROM `cafeteria` WHERE 1;
Realizar una consulta que permita conocer cuál es el producto más vendido.

SELECT nombre FROM venta WHERE cantidad = ( SELECT MAX( cantidad ) FROM venta);


Nombre de ka base de datos Konecta
