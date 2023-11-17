<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Telecomunicaciones ENACOM`**</h1>

¡Bienvenidos al analisis exploratorio de los datos del Enacom durante los años 2014-2022, desarrollado por ***Jeferson A. Peña***.
<p align='center'>
<img src="https://www.enacom.gob.ar/public/enacom/tecnopolis2021/img/tecnopolis890.png"  height=300>
<p>

## **Descripción del problema **

### **Contexto**

Las telecomunicaciones se refieren a la transmisión de información a través de medios electrónicos, como la telefonía, la televisión, la radio y, más recientemente, el internet. Estos medios de comunicación permiten la transmisión de información entre personas, organizaciones y dispositivos a largas distancias.

El internet, por su parte, es una red global de computadoras interconectadas que permite el intercambio de información en tiempo real. Desde su creación, ha tenido un impacto significativo en la vida de las personas, transformando la manera en que nos comunicamos, trabajamos, aprendemos y nos entretenemos.

La industria de las telecomunicaciones ha jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua incluso en medio de una pandemia mundial. La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, y en casi cualquier lugar del mundo. 

En comparación con la media mundial, Argentina está a la vanguardia en el desarrollo de las telecomunicaciones, teniendo para el 2020 un total de [62,12 millones de conexiones](https://www.datosmundial.com/america/argentina/telecomunicacion.php). 


### **Rol a desarrollar**

`EDA` (Exploratory Data Analysis)

Se realizo una exploraciono de los **Datasets** para poder endender de manera clara y concisa el comportamiento de los datos atravez de los años; por un lado, se logro concluir con respecto a los **tipos de conexiones** tienen cierto crecimiento atravez de los años como por ejemplo: Banda ancha fija, pero tambien hay declives como en Dial UP.

Por otro lado, se exploro la **Media de Bajada** el cual tiene una tendencia positiva desde su inicio del 2014 y de tal manera llegando al pico en 2022.

Finalmente, tambien se exploro los **ingresos** que se recibienron por año, en el cual se concluye que dichos ingresos fueron incrementando, debido a que las coverturas se fueron ampliando en las distintas provincias.

`KPIs`

El primer KPI es:
- *Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia*.
La fórmula es la siguiente:

 $`KPI = ((Nuevo acceso - Acceso actual) / Acceso actual) * 100`$
 
Donde:

- "Nuevo acceso" se refiere al número de hogares con acceso a Internet después del próximo trimestre.
- "Acceso actual" se refiere al número de hogares con acceso a Internet en el trimestre actual.

Esta fórmula te ayudará a calcular el KPI para medir el aumento en el acceso a Internet por cada 100 hogares en cada provincia.

**Ejemplo de uso:**

KPI = ((510 - 500) / 500) * 100 = 2%

Esto indicaría un aumento del 2% en el acceso a Internet en esa provincia para el próximo trimestre.


El segundo KPI es:
- *El KPI "Tasa de Crecimiento en Fibra Óptica por Trimestre" mide la variación porcentual en el acceso a Internet a través de la tecnología de fibra óptica entre dos trimestres consecutivos*.
La fórmula es la siguiente:

 $`Tasa de Crecimiento Fibra Optica = ((Nuevo Acceso Fibra Optica - Acceso Actual Fibra Optica) / Acceso Actual Fibra Optica) * 100`$
 
Donde:

- "Acceso Actual Fibra Optica" se refiere a la cantidad de hogares con acceso a Internet a través de fibra óptica en el trimestre actual.
- "Nuevo Acceso Fibra Optica" se refiere a la cantidad de hogares con acceso a Internet a través de fibra óptica en el próximo trimestre.

Esta fórmula te ayudará a calcular el KPI para medir Tasa de Crecimiento en Fibra Óptica por Trimestre.

**Ejemplo de uso:**

Tasa de Crecimiento Fibra Optica= ((170 - 150) / 150) * 100 = 13.33%

Esto indicaría un aumento del 13.33% en fibra óptica para el próximo trimestre.

`Dashboard`

-### _**Acceso a hogares**_
<div align="center">
    <img src="assets\SumaAcc100.png" alt="Acceso a hogares" width="50%">
</div>
<br>

Este gráfico nos presenta la suma por cada provincia del acceso a internet, en el cual se observa que Capital Federal es el que tiene mas acceso a interenet.

<div align="center">
    <img src="assets\SumAcc100Hab.png" alt="Acceso a hogares 100 habitantes" width="50%">
</div>
<br>

El gráfico nos presenta la suma por cada periodo del acceso a internet, en el cual se observa que en el periodo octubre-diciembre 2022 tiene una ligera diferencia con los demas periodos, por lo cual se podria concluir que en ese periodo esta el mayor acceso.

### _**TIPO DE CONEXION**_
<div align="center">
    <img src="assets\SumBA_DU.png" alt="Tipo de conexion" width="50%">
</div>
<br>

Este gráfico de lineas nos presenta la suma de la Banda Ancha fija y Dial Up atravez de los años y cual ha sido su comportamiento. Ademas, se denota una clara tendencia creciente a lo que respeta Banda Ancha fija.

<div align="center">
    <img src="assets\SumaTipConex.png" alt="Conexiones" width="50%">
</div>
<br>

Este gráfico de columnas agrupadas detalla como fue el comportamiento de las distintas tipos de conexiones al pasar de años, en ella se ve que sifra optica tiene un crecimiento exponencial entre el año 2019-2022 .

### _**HISTORICO DE VELOCIDAD**_
<div align="center">
    <img src="assets\MediaBajada.png" alt="Media de bajada" width="50%">
</div>
<br>

La media de bajada atravez de los años esta teniendo una mejora progresiva, este grafico muestra el comportamiento creciente de la media de bajada desde el 2014 hasta el 2022 . 

<div align="center">
    <img src="assets\VelBajadaProv.png" alt="Velocidad de Bajada en 4 provincias importantes" width="50%">
</div>
<br>

La referencia tomada fue en 4 procincias las cuales fueron Buenos Aires, Capital Federal, Córdoba, Santa Fe ; con el fin de poder visualizar como va la velocidad de bajada, cuanta de diferencia hay entre ella y de ellas hacia las demas provincias.

### _**INGRESOS**_
<div align="center">
    <img src="assets\SumaIngresos.png" alt="Media de bajada" width="50%">
</div>
<br>

En el presente grafico se muestra cuanto fue el ingreso en el transcurso de los años 2014-2022, con un ingreso exponecial en el año 2022.

<div align="center">
    <img src="assets\SumaTipConex.png" alt="Velocidad de Bajada en 4 provincias importantes" width="50%">
</div>
<br>

El grafico representa la suma de conexiones ADLS, Dial Up, Cabledemon y Telefonia Fija. Entre las conexiones se visualiza que hay una mayor conexion con lo que respecta Telefonia Fija.


## Herramientas utilizadas
- Python, Power BI, Git

## Fuente de datos
- [Datasets principales](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/)

## Contacto
- Mail : micuentajeferson@gmail.com