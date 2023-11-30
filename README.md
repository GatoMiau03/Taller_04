# Taller_04

Contexto del problema

Suponga que en el contexto de la Super Copa ¿A quién le han ganado? 2023, la FIFA le pide desarrollar un prototipo para la visualización y gestión básica de las selecciones y sus alineaciones.

La situación considera que:
- cada selección tiene un nombre (del país de origen), un ranking FIFA y además un ícono con la bandera de c/u.
- cada selección está compuesta por 23 jugadores (numerados de forma única del 1 al 23).
- cada jugador tiene un nombre, número y posee una posición en la juega (GK, DF, MF o FW). Cada selección debe tener 3 arqueros y no puede haber jugadores con el mismo número (1 a 23).

Datos del caso

Para esto cuenta con un set de datos previamente preparados en el archivo datos.zip, el cual contiene:

- las selecciones de la copa (id; nombre; ranking; ruta bandera .png) ----> teams.txt
- las alineaciones de c/u de las selecciones (nº, nombre jugador, posición (GK, DF, MF o FW) ) ----> *.txt
- ícono de las banderas de c/u de las selecciones ----> *.png

Prototipo de solución a entregar

- la aplicación consiste en un visor que muestre una lista con las selecciones presentes en el campeonato (para este prototipo consideraremos sólo las 4 del archivo)
- además de visualizar las selecciones, se debe visualizar el detalle de las formaciones de c/u de ellas
- finalmente, el visualizador de jugadores, debe permitir la edición de los datos de estos y guardar los cambios.

- La clase ventana principal es la ejecutora de todo el codigo, desplega el menu donde se puede elegir el equipo deseado para ver el archivo txt donde salen todos los jugadores y poder realizar cambios, ademas de poder guardarlos y salir de la ventana.
- Los commits realizados por la cuenta "Makx3" fueron culpa mia, ya que realizo los trabajos desde los computadores que entrega la universidad, y el computador tenia puesta la cuenta de mi compañero desde la terminal, luego lo cambie y realice los commits de buena manera. 
