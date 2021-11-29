# **Visualización AD3 proyecto Tresca**

Los datos son sacados del  [Proyecto TRESCA](https://github.com/flowsta/nebrija-2021/blob/main/data/tendencias-millonarias-nebrija.csv) sobre los tuits que se producieron durante las elecciones de **Estados Unidos** entre **2020** y **2021** cuando **Joe Biden**, **Kamala Harris**, **Donald Trump** y **Mike Pence** se disputaban la presidencia. 

### Limpieza de datos en Open Refine

El primer paso es cambiar en “Character encoding” a un UTF-8 que es la codificación universal. La configuración predeterminada no lo he cambiado.
![1](https://user-images.githubusercontent.com/94476300/143947105-e594df35-8818-4fa4-8f28-e14b193f21f3.png)

Lo siguiente que hice fue cambiar el nombre al archivo a: ad3-tresca-republicanos-vs democratas puse dos etiquetas: tresca y Nebrija y pulsé en “crear proyecto”
![2   detrás de  crear proyecto](https://user-images.githubusercontent.com/94476300/143947265-060727b4-93d5-4859-b7e0-519af53b29ef.png)

Después renombré las columnas para facilitar su comprensión en:
As_of – edit column – rename this column y lo mismo en las otras dos para que quede de esta manera:
![3 transformar](https://user-images.githubusercontent.com/94476300/143947313-31642dac-7462-4a60-9d89-23b8146a8a02.png)

Y tras convertir al tipo de dato que corresponde:
El primero: As_of – edit cells – common transforms – to date (faceta temportal):
![4](https://user-images.githubusercontent.com/94476300/143947417-6d810a04-abd8-42d7-b2c3-199d341c0f14.png)

El segundo paso sería para convertirlos en números (faceta numérica):
![5](https://user-images.githubusercontent.com/94476300/143947452-7674cf18-dc9c-4edc-83b8-e66e97c8603e.png)

Quedaría hacer la faceta de línea temporal:
![6](https://user-images.githubusercontent.com/94476300/143947468-e5879780-8708-4503-be83-2514d87c8ccc.png)
Es lógico ver que durante la etapa de las elecciones se dieron la mayoría de los tuits.

### Para la visualización en Datawrapper

Yo he elegido un gráfico de líneas.

Hay que convertirlo en columnas y poner los valores dondecorresponda en **Open Refine**.
![7](https://user-images.githubusercontent.com/94476300/143947501-48206f50-9001-45d0-8cc5-7049b5c28598.png)
![8](https://user-images.githubusercontent.com/94476300/143947535-f2d38674-8145-4368-afea-bb9e14329611.png)

Y ordenar desde tuits los textos de** Donald Trump** juntos y después**Joe Biden**.
![9](https://user-images.githubusercontent.com/94476300/143947563-29f9e2d7-52b9-4027-8c7e-49568243c263.png)

Después lo exporté a un archivo separado por comas.
Y para la fecha la transformé para que en Datawrapper se pudiera leer.
![10](https://user-images.githubusercontent.com/94476300/143947603-cd837e26-b08e-4953-a36b-6c5884ed59fd.png)

Y desde Datawrapper, en subir archivos, subir Excel subí el documento.

Lo cambié por “Text”-
![12](https://user-images.githubusercontent.com/94476300/143947670-81ed73a5-2767-469a-80c6-fd0b5f2c45ec.png)

Y por último en visualización lo he cambiado a mi gusto en colores yformas.
![13](https://user-images.githubusercontent.com/94476300/143947704-1ff0851c-afdf-4164-a592-153eb7b3fea4.png)
