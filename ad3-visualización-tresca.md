# **Visualización AD3 proyecto Tresca**

Los datos son sacados del  [Proyecto TRESCA](https://github.com/flowsta/nebrija-2021/blob/main/data/tendencias-millonarias-nebrija.csv) sobre los tuits que se producieron durante las elecciones de **Estados Unidos** entre **2020** y **2021** cuando **Joe Biden**, **Kamala Harris**, **Donald Trump** y **Mike Pence** se disputaban la presidencia. 

### Limpieza de datos en Open Refine

El primer paso es cambiar en “Character encoding” a un UTF-8 que es la codificación universal. La configuración predeterminada no lo he cambiado.

Lo siguiente que hice fue cambiar el nombre al archivo a: ad3-tresca-republicanos-vs democratas puse dos etiquetas: tresca y Nebrija y pulsé en “crear proyecto”

Después renombré las columnas para facilitar su comprensión en:

As_of – edit column – rename this column y lo mismo en las otras dos para que quede de esta manera:

Y tras convertir al tipo de dato que corresponde:

El primero: As_of – edit cells – common transforms – to date (faceta temportal):

El segundo paso sería para convertirlos en números (faceta numérica):

Quedaría hacer la faceta de línea temporal:

Es lógico ver que durante la etapa de las elecciones se dieron la mayoría de los tuits.

### Para la visualización en Datawrapper

Yo he elegido un gráfico de líneas.

Hay que convertirlo en columnas y poner los valores dondecorresponda en **Open Refine**.

Y ordenar desde tuits los textos de** Donald Trump** juntos y después**Joe Biden**.

Después lo exporté a un archivo separado por comas.

Y para la fecha la transformé para que en Datawrapper se pudiera leer.

Y desde Datawrapper, en subir archivos, subir Excel subí el documento.

Lo cambié por “Text”-

Y por último en visualización lo he cambiado a mi gusto en colores yformas.
