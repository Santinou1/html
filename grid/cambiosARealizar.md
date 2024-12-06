Ejercicios para Practicar

TRABAJAR EN EL ARCHIVO "gridEjemplo.css"

1- Cambiar el numero de columnas

Cambia :  grid-template-columns: repeat(3,1fr) ;

            A

          grid-template-columns: repeat(4,1fr) ;  

Observa como se distribuyen ahora 4 columnas en lugar de 3.

2- Definir tamaños especificos

Cambia las columnas por tamaños especificos:

Cambia : grid-template-columns: repeat(3,1fr) ;

                    A

        grid-template-columns: 100px 200px 1fr;

Observa como la primera columna tiene 100px, la segunda 200px, y la terca ocupa el espacio restante.

3- Ajutar las filas.

usa grid-template-rows para ajustar la altura de las filas:

Agrega: grid-template-rows: 100px auto;

Observa como la primera fila tiene un tamaño fijo y la segunda se ajusta automaticamente.


