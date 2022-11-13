# PROG03.1_Ejer03
Queremos desarrollar una aplicación que nos ayude a gestionar las notas de los alumnos de
un centro educativo. Cada alumno tiene diversas notas por cada uno de los módulos, siendo
el profesor de cada módulo el encargado de introducir, borrar y modificar las notas del
módulo de cada alumno. Se necesita crear una aplicación en la que cada profesor pueda
gestionar sus notas por cada alumno. Para simplificar la aplicación, ésta (la aplicación), sólo
va a poder gestionar las notas de un alumno en un sólo módulo, pero se tiene un problema,
el número de notas de los alumnos por módulo se desconoce.
Se pide realizar una aplicación que muestre un menú semejante al de la siguiente imagen,
que permita ‘Añadir nota’, ‘Borrar nota’, ‘Borrar posición’, ‘Ordenar notas’, ‘Mostrar
notas’, ‘Calcular la Media’, ‘Obtener Nota Máxima’ y ‘Obtener Nota Mínima’ de un alumno
en un determinado módulo.
Para cada una de las funciones, se tiene que tener en cuanta los siguientes aspectos:
a) Añadir nota : El sistema solicitará una nota que será validad entre 0 y 10, y se añadirá
una nota al final de todas las notas. Si la nota no es correcta, el sistema volverá a
solicitar la nota hasta que la nota introducida sea correcta.
b) Borrar nota: la aplicación solicitará que se introduzca el valor de una nota y se
eliminará todas las notas que coincidan con el valor introducido. Después de borrar
las notas, la aplicación indicará cuantas notas se han borrado, pudiendo no borrar
ninguna nota porque la nota a borrar no exista.
c) Borrar posición: la aplicación solicitará la posición de la nota que se quiere borrar. La
aplicación indicará si el borrado tuvo éxito (la posición existe y se ha borrado), o por
el contrario, si la posición no existe, la aplicación indicará que ‘no se ha podido borrar
ninguna nota’.
d) Ordenar notas: las notas se ordenarán de forma ascendente.
e) Mostrar notas: las notas se mostrarán de la más reciente a la más antigua.
f) Calcular Media: se mostrará la media de todas las notas existentes.
g) Obtener Nota Máxima: se obtendrá la nota máxima de entre todas las notas.
h) Obtener Nota Mínima: se obtendrá la nota mínima de entre todas las notas.
IMPORTANTE: cada que se añada o borren notas, el tamaño del array deberá ser
recalculado al nuevo número de notas.
NOTA: emplea los métodos de la clase Arrays que creas oportunos para el desarrollo
de la actividad.
