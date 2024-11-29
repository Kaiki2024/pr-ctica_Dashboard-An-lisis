El archivo utilizado es el siguiente: [Adidas US Sales Datasets.xlsx](https://github.com/user-attachments/files/17872842/Adidas.US.Sales.Datasets.xlsx)

El análisis se ha hecho con GoogleSheets: https://docs.google.com/spreadsheets/d/1MLguqi2DyTALhf9cErmfXi0QfOCFrDH0jcjH9ZsNAOc/edit?gid=2094923310#gid=2094923310

OBJETIVO:

Queremos saber si los hábitos de consumo de los productos Adidas en EEUU son estables o varían. Para ello contamos con los datos de venta de 2020 y 2021. Tengamos en cuenta que en 2020 se produjo una pandemia mundial que provocó cambios en los hábito de consumo. Queremos comprobar si dicha afirmación se cumple en este caso, así como conocer los principales mercados de Adidas dentro de los Estados Unidos.

![image](https://github.com/user-attachments/assets/04469289-9904-4faa-9e31-9c37d5e492b7)


PASOS SEGUIDOS:

1- Desunimos la columna de "Product" mediante la herramienta de "Datos" y "Dividir el texto en columnas"

2- Al hacerlo nos queda un espacio en blanco en la columna "J"

3- Eliminamos los espacios en blanco mediante la siguiente fórmula: =ARRAYFORMULA(IF(I2:I <> "Apparel", I2:I, "Dress") & " " & IF(J2:J <> "", J2:J, "Apparel"))

4- De nuevo utilizamos la herramienta de "Datos" y "Dividir el texto en columnas"

5- Ocultamos las columnas I y J

6- Renombramos las columnas en "Estilo" y "Producto"

7- Renombramos el resto de columnas

8- Nos detecta correctamente los datos de fechas, porcentajes, números y moneda

9- Cambiamos los datos de las columnas "Ventas totales" y "Beneficios" mediante "Formato" y "Formato de número personalizado" para que los datos numéricos no sean tan extensos

10- Cambiamos los datos de las columnas "Facturación", dejando solo mes y año

11- Nos sigue teniendo en cuenta el día del mes en los datos por lo que creamos una nueva columna y empleamos la fórmula =TEXT( D2; "YYYY/MM") para agrupar la información por mes para el análisis. Creamos la columna "Mes Facturación". Ocultamos la columna D

12- Generamos una nueva columna de "Año Facturación"

13- Convertimos en tabla mediante "Formato" y "Convierte en tabla"

INFORME:

1- Ventas totales 2478861, de las cuales 2016512 son en 2021 (el 81.3% del total de las ventas, un +436.1% respecto a 2020).

2- Local con más ventas West Gear (con el 25% del total de las ventas) y la principal fuente de ventas es Online (37.9%) seguido de cerca de los Outlets (34.3%).

3- La tendencia en la compra varía de un año a otro. En 2020, la mayoría de las ventas vienen por los Outlets (47.3%) siendo la venta Online la que trae menos ventas (18.8%). Sin embargo, en 2021, la venta viene mayoritariamente de la venta Online (con un 42.3% del total)

4- El 53.9% de los productos vendidos son para hombres. Tendencia que se mantiene tanto en 2020 (52.4%) como en 2021 (54.2%).

5- Producto más vendido: Footwear (70.1% del total). En 2020 supone un 69.4% del total de las ventas, en 2021 un 70.3%.

6- El mes con más ventas es el mes de agosto. En 2020, 53.2% de las ventas son en Outlet y Footwear el producto más vendido. En 2021, el producto más vendido es el mismo (Footwear) pero la mayoría de ventas son Online (42.7%). En ambos casos, el lugar con más ventas en agosto es Wallmart y la ciudad Dallas.

7- Lugar con más ventas totales es Nueva York con 111954 unidades (todo vendido solo en 2020). 76.5% de las ventas son en Outlet, Footwear lo más vendido (75464 unidades) y en su mayoría en tiendas Foot Locker (72196 unidades, 64.5% del total de las ventas realizadas en la ciudad).

8- En 2021, el lugar con más ventas es Charleston con 102483 productos vendidos. El 77.1% de las ventas son Online, Footwear lo más vendido (69880 unidades) y su mayoría en las tiendas Foot Locker (68381 unidades, 66.7% del total de las ventas realizadas en la ciudad).

9- Respecto a los beneficios reportados, Sports Direct es el vendedor que más margen de beneficio arroja por sus ventas (44%, un 2% más que la mayoría de los vendedores). En cuanto a los productos vendidos, el beneficio es muy similar (43% Apparel y 42% Footwear). Por contra, la venta Online se impone frente al resto de puntos de venta con un 46% de beneficio (+7% con respecto al siguiente que más beneficio arroja que es la venta Outlet).

CONCLUSIONES:

1- La venta Online gana terreno frente al resto de puntos de venta. Cambio claro de tendencia en los hábitos del consumidor a partir de 2021. Las ventas por Sports Direct suponen un mayor margen de beneficio y es la segunda fuente de ventas. Interesante convertirla en la primera fuente de la venta.

2020

![image](https://github.com/user-attachments/assets/15a6da2e-10ce-47b6-b8af-65d42fd7662e)


2021 

![image](https://github.com/user-attachments/assets/aade36c3-a743-4486-a9c7-0686ec401109)

2- Los productos más consumidos de la marca son las zapatillas (Footwear), algo que se mantiene año a año.

2020

![image](https://github.com/user-attachments/assets/f75c1d64-fd9e-42d7-8101-3f40cb82aac4)

2021

![image](https://github.com/user-attachments/assets/d353aa84-bcf9-4bdb-8d22-ef0d3a9ef810)

3- Respecto a la venta en tienda. Wallmart es el que menos clientes trae y el menos margen de beneficio tiene. Valorar si tiene interés seguir teniendo los productos disponibles en ese vendedor. 

![image](https://github.com/user-attachments/assets/954782d2-b553-46cd-bcbe-107b389cb98b)

4- En cuanto a la venta en Outlet, de nuevo Sports Direct es el vendedor que aporta un mayor margen de beneficio y, además, el principal vendedor por esta vía.

![image](https://github.com/user-attachments/assets/a40ddd8b-ebce-4cca-814e-efdf31c995cd)
![image](https://github.com/user-attachments/assets/010d9083-e07e-414c-8343-352d21965334)



