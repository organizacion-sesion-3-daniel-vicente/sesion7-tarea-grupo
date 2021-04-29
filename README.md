# Crea el modelo E/R para una empresa de alquiler de vehículos.
Se desea diseñar una base de datos sobre la información de las reservas de una empresa dedicada al alquiler de automóviles teniendo en cuanta que:
* Un determinado cliente puede tener en un momento dado hechas varias reservas.
* De cada cliente se desea almacenar su DNI, nombre, dirección y teléfono. Además dos clientes se diferencian por un código único.
* Cada cliente puede ser avalado por otro cliente de la empresa.
* Una reserva la realiza un único cliente pero puede involucrar a varios coches.
* Es importante registrar la fecha de inicio y final de la reserva, el precio del alquiler de cada uno de los coches, los litros de gasolina en el depósito en el momento de realizar la reserva, el precio total de la reserva y un indicador de si el coche o los coches han sido entregados.
* No se mantienen los datos de reservas anteriores.
* Todo coche tiene siempre asignado un determinado garaje que no puede cambiar. De cada coche se requiere la matricula, el modelo, el color y la marca.
* Cada reserva se realizara en una determinada agencia.
