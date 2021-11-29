# **Visualización AD3 proyecto Tresca**

Los datos son sacados del  [Proyecto TRESCA](https://github.com/flowsta/nebrija-2021/blob/main/data/tendencias-millonarias-nebrija.csv) sobre los tuits que se producieron durante las elecciones de **Estados Unidos** entre **2020** y **2021** cuando **Joe Biden**, **Kamala Harris**, **Donald Trump** y **Mike Pence** se disputaban la presidencia. 

### Limpieza de datos en Open Refine

El primer paso es cambiar en “Character encoding” a un UTF-8 que es la codificación universal. La configuración predeterminada no lo he cambiado.
![1](https://user-images.githubusercontent.com/94476300/143947914-9230833a-b51c-4dea-93f8-0fc9af23433b.png)

Lo siguiente que hice fue cambiar el nombre al archivo a: ad3-tresca-republicanos-vs democratas puse dos etiquetas: tresca y Nebrija y pulsé en “crear proyecto”
![2   detrás de  crear proyecto](https://user-images.githubusercontent.com/94476300/143947964-4b146220-14dd-4120-b062-785d51a0fbe8.png)

Después renombré las columnas para facilitar su comprensión en:
As_of – edit column – rename this column y lo mismo en las otras dos para que quede de esta manera:
![5](https://user-images.githubusercontent.com/94476300/143948455-1e42754b-b066-4b4e-a998-8d151980ff1a.png)

Y tras convertir al tipo de dato que corresponde:
El primero: As_of – edit cells – common transforms – to date (faceta temportal):
![3 transformar](https://user-images.githubusercontent.com/94476300/143948493-9c5d26e1-c848-4eea-95cf-6f8bf0b5053d.png)

El segundo paso sería para convertirlos en números (faceta numérica):
![4](https://user-images.githubusercontent.com/94476300/143948507-4683eab8-13b7-4e4a-8d56-d177673b882f.png)

Quedaría hacer la faceta de línea temporal:
![6](https://user-images.githubusercontent.com/94476300/143948569-b0604459-2578-48f8-bd78-0007a75ed23c.png)

Es lógico ver que durante la etapa de las elecciones se dieron la mayoría de los tuits.
![7](https://user-images.githubusercontent.com/94476300/143948585-5ff8d9f8-52eb-4e5a-bd87-460ce592c070.png)

### Para la visualización en Datawrapper

Yo he elegido un gráfico de líneas.

Hay que convertirlo en columnas y poner los valores dondecorresponda en **Open Refine**.
![8](https://user-images.githubusercontent.com/94476300/143948611-f81adc0a-7b52-481e-af0a-4d7e00064760.png)
![9](https://user-images.githubusercontent.com/94476300/143948635-6d7ceeff-5b2e-47ae-a9c3-3da72ad684e8.png)

Y ordenar desde tuits los textos de** Donald Trump** juntos y después**Joe Biden**.
![10](https://user-images.githubusercontent.com/94476300/143948656-9f01d638-98fd-475c-a1a7-0fb300bc0ee9.png)

Después lo exporté a un archivo separado por comas.
Y para la fecha la transformé para que en Datawrapper se pudiera leer.
![11](https://user-images.githubusercontent.com/94476300/143948680-78718d94-e5c4-4870-ad54-9021da820d4b.png)

Y desde Datawrapper, en subir archivos, subir Excel subí el documento.

Lo cambié por “Text”-
![12](https://user-images.githubusercontent.com/94476300/143948710-d62b4b5f-d2a6-4bb1-8f10-b6a6d08c6c79.png)

Y por último en visualización lo he cambiado a mi gusto en colores yformas.
![13](https://user-images.githubusercontent.com/94476300/143947704-1ff0851c-afdf-4164-a592-153eb7b3fea4.png)
