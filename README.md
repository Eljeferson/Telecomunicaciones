<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Telecomunicaciones ENACOM`**</h1>

¡Bienvenidos al análisis exploratorio de los datos del Enacom durante los años 2014-2022, desarrollado por ***Jeferson A. Peña***.
<p align='center'>
<img src="https://www.enacom.gob.ar/public/enacom/tecnopolis2021/img/tecnopolis890.png"  height=300>
<p>

## **DESCRIPCIÓN DEL PROYECTO **

### **Contexto**

Las telecomunicaciones se refieren a la transmisión de información a través de medios electrónicos, como la telefonía, la televisión, la radio y más recientemente, el internet. Estos medios de comunicación permiten la transmisión de información entre personas, organizaciones y dispositivos a largas distancias.

El internet, por su parte, es una red global de computadoras interconectadas que permite el intercambio de información en tiempo real. Desde su creación, ha tenido un impacto significativo en la vida de las personas, transformando la manera en que nos comunicamos, trabajamos, aprendemos y nos entretenemos.

La industria de las telecomunicaciones ha jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua incluso en medio de una pandemia mundial. La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, y en casi cualquier lugar del mundo. 

En comparación con la media mundial, Argentina está a la vanguardia en el desarrollo de las telecomunicaciones, teniendo para el 2020 un total de [62,12 millones de conexiones](https://www.datosmundial.com/america/argentina/telecomunicacion.php). 


### **Rol a desarrollar**

`EDA` (Exploratory Data Analysis)

Se realizó una exploración de los **Datasets** para poder entender de manera clara y concisa el comportamiento de los datos a través de los años; por un lado, se logró concluir con respecto a los **tipos de conexiones** tienen cierto crecimiento a través de los años como por ejemplo: Banda ancha fija, pero también hay declives como en Dial UP.

Por otro lado, se exploró la **Media de Bajada** el cual tiene una tendencia positiva desde su inicio del 2014 y de tal manera llegando al pico en 2022.

Finalmente, también se exploro los **ingresos** que se recibieron por año, en el cual se concluye que dichos ingresos fueron incrementando, debido a que las coberturas se fueron ampliando en las distintas provincias.

`KPIs`

### _**Primer KPI**_
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



### _**Segundo KPI**_
- *El KPI "Tasa de Crecimiento en Fibra Óptica por Trimestre" mide la variación porcentual en el acceso a Internet a través de la tecnología de fibra óptica entre dos trimestres consecutivos*.
La fórmula es la siguiente:

 $`Tasa de Crecimiento Fibra Óptica = ((Nuevo Acceso Fibra Óptica - Acceso Actual Fibra Óptica) / Acceso Actual Fibra Óptica) * 100`$
 
Donde:

- "Acceso Actual Fibra Óptica" se refiere a la cantidad de hogares con acceso a Internet a través de fibra óptica en el trimestre actual.
- "Nuevo Acceso Fibra Óptica" se refiere a la cantidad de hogares con acceso a Internet a través de fibra óptica en el próximo trimestre.

Esta fórmula te ayudará a calcular el KPI para medir la Tasa de Crecimiento en Fibra Óptica por Trimestre.

**Ejemplo de uso:**

Tasa de Crecimiento Fibra Óptica= ((170 - 150) / 150) * 100 = 13.33%

Esto indicaría un aumento del 13.33% en fibra óptica para el próximo trimestre.

`Dashboard`

### _**Acceso a hogares**_
<div align="center">
    <img src="assets\SumaAcc100.png" alt="Acceso a hogares" width="50%">
</div>
<br>

Este gráfico nos presenta la suma por cada provincia del acceso a internet, en el cual se observa que Capital Federal es el que tiene más acceso a internet.

<div align="center">
    <img src="assets\SumAcc100Hab.png" alt="Acceso a hogares 100 habitantes" width="50%">
</div>
<br>

El gráfico nos presenta la suma por cada periodo del acceso a internet, en el cual se observa que en el periodo octubre-diciembre 2022 tiene una ligera diferencia con los demás periodos, por lo cual se podría concluir que en ese periodo esta el mayor acceso.

### _**TIPO DE CONEXIÓN**_
<div align="center">
    <img src="assets\SumBA_DU.png" alt="Tipo de conexión" width="50%">
</div>
<br>

Este gráfico de líneas nos presenta la suma de la Banda Ancha fija y Dial Up a traves de los años y cuál ha sido su comportamiento. Además, se denota una clara tendencia creciente a lo que respecta a la Banda Ancha fija.

<div align="center">
    <img src="assets\SumaTipConex.png" alt="Conexiones" width="50%">
</div>
<br>

Este gráfico de columnas agrupadas detalla comó fue el comportamiento de las distintas tipos de conexiones al pasar de años, en ella se ve que cifra óptica tiene un crecimiento exponencial entre el año 2019-2022 .

### _**HISTÓRICO DE VELOCIDAD**_
<div align="center">
    <img src="assets\MediaBajada.png" alt="Media de bajada" width="50%">
</div>
<br>

La media de bajada a traves de los años está teniendo una mejora progresiva, este gráfico muestra el comportamiento creciente de la media de bajada desde el 2014 hasta el 2022 . 

<div align="center">
    <img src="assets\VelBajadaProv.png" alt="Velocidad de Bajada en 4 provincias importantes" width="50%">
</div>
<br>

La referencia tomada fue en 4 provincias las cuales fueron Buenos Aires, Capital Federal, Córdoba, Santa Fe ; con el fin de poder visualizar como va la velocidad de bajada, cuanta de diferencia hay entre ella y de ellas hacia las demás provincias.

### _**INGRESOS**_
<div align="center">
    <img src="assets\SumaIngresos.png" alt="Media de bajada" width="50%">
</div>
<br>

En el presente gráfico se muestra cuánto fue el ingreso en el transcurso de los años 2014-2022, con un ingreso exponencial en el año 2022.

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
