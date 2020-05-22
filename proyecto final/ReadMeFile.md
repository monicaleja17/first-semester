# Análisis procesos de Contratación Estatal - Colombia - 2015 - 2020
---

*Presentado por: Mónica Robayo* 

## **Descripción y Motivación** 📋 🚀
---

<font size="3"> Analizar los datos de procesos de contratación estatal disponibles. El objetivo es procesarlos, analizarlos y realizar gráficas de comportamiento usando librerías de matplotlib y Pandas.  Así mismo realizar un análisis de redes de los procesos de contratación, con el fin de identificar la relación que existe entre las entidades estatales y los adjudicatarios principales.</font> 


<font size="3">Algunas preguntas y problemas que motivaron el proyecto:</font> 

+ <font size="3">¿Cuánto dinero se ha ejecutado por tipos de contratación?, las más comunes son mínima cuantía, selección abreviada, subasta inversa, licitación pública.</font> 


+ <font size="3">¿Cuáles modalidades de contratación se adjudican de forma más frecuente?</font> 


+ <font size="3">¿Cómo ha el comportamiento de la contratación a traves de estos últimos años?</font> 


+ <font size="3">¿Cuáles son aquellos posibles bienes y/o servicios que más se contratan, es posible saberlo por tipo de contratación?</font> 


+ <font size="3">¿Cuales son los Departamentos que más adjudican procesos?</font> 


+ <font size="3">¿ En el manejo de los recursos, como se ve plasmado por modalidades de Contratación? ¿Por cual Modalidad se ejecutan más recursos?</font> 


+ <font size="3">Teniendo en cuenta las entidades de orden Nacional y Territorial.¿ Es posible ver las adjudicaciones por modalidad de   contratación?</font> 


+ <font size="3">Analisis de redes de proveedores a nivel Nacional, Territorial y Ejercito Nacional. ¿Se presentaran nodos y aristas comunes?</font> 


+ <font size="3">Reflexionar sobre la importancia en términos de política pública sobre la pluralidad de oferentes, un principio fundamental en la contratación estatal, que sirve como instrumento de política pública, en terminos de optimizar los recursos y velar por el bienestar de la sociedad.</font> 

## **Métodos Usados** 🔧⚙️
---

<font size="3">**1.Libreria Pandas:**

 - La utilice para realizar Dataframe de la información.
 
 - Me ayudó a organizar y a leer el contenido de la información.
 
 - Uso de Group by y agg(count y sum), con el fin de contabilizar y sumar las variables de estudio.
 
 - Multiple Group by, para agrupar diferentes variables y analizar la información.
 
 - Series de Tiempo dt.day y definición de funciones con formato fecha.
 
 - Con las series de tiempo, utilice timestamp y unstack 
 
 - Utilice sort_values para organizar la información de manera ascendente 
    
 - Indexación [ ] y eliminación (drop) de variables que no son tenidas en cuenta, sea el caso. 
 
<font size="3">**2.Matplotlib:**

 - Realice gráficas de torta
 
 - Utilicé Gráficas de Barra de manera horizontal 
 
 - Para realizar las gráficas utilice algunas opciones como explode, startangle, pctdistance, bbox_to_anchor, loc y autopct
 
 - Utilice la Paleta de Colores cmap='Paired'
 
 
<font size="3">**3.Networkx**
 
 - Lo utilicé para realizar el análisis de redes.
 
 - Utilice la invocación de un G de la siguiente manera: nx.read_adjlist(G) , ya que la información esta de manera matricial.
 
 - Para realizar la red, hice uso de Matplotlip con las siguientes opciones relacionadas a la red: spring_layout(G), node_colorlinewidths, style ,font_size, font_family, node_size)
 

## Hallazgos Encontrados 📄 📌

La modalidad de Contratación que más se adjudica es la Contratación Directa, seguida de Régimen Especial y Mínima Cuantía.

Los contratos que con más frecuencia son adjudicados: Servicios de aprovisionamiento, Suministros y Compraventas. 
    
Los Departamentos que más adjudican procesos son: Bogotá, Antioquía y Valle del Cauca. Entre los más rezagados se encuentran Guaviere, Guanía y Vaupés.

De acuerdo a la Serie de Tiempo, se ha venido avanzando en el número de procesos adjudicados por día desde 2018 hasta la fecha. La modalidad que mayoritariamente ha estado en cabeza es la Contratación Directa. 

Otras modalidades importantes que se han adjudicado con más frecuencia desde el años 2017, son: Mínima Cuantía, Selección abreviada de menor cuantía, Selección abreviada subasta inversa, Licitación pública. Siendo más Mínimas que Licitaciones.

Se contrata por Madalidad de Contratación a nivel Nacional por: Minima Cuantía, Contratacion directa, Licitacion, Subasta y seleccion abrevidad. A nivel territorial por la modalidad de Regimen especial.

Las Modalidades que tienen mayores apropiaciones y por tanto se gastan más recursos son: Contratación régimen especial, Contratación Directa y Licitación Pública. 

Se evidencia nodos...



![Modalidades.jpg](attachment:Modalidades.jpg)


![TipoContrato.jpg](attachment:TipoContrato.jpg)

![Departamento.jpg](attachment:Departamento.jpg)

![Contratosporaño.jpg](attachment:Contratosporaño.jpg)

![otrasporaño.jpg](attachment:otrasporaño.jpg)

![minima_orden.jpg](attachment:minima_orden.jpg)

![directa_orden.jpg](attachment:directa_orden.jpg)

![licitacion_orden.jpg](attachment:licitacion_orden.jpg)

![subasta_orden.jpg](attachment:subasta_orden.jpg)

![abreviada_orden.jpg](attachment:abreviada_orden.jpg)

![especial_orden.jpg](attachment:especial_orden.jpg)

![monto_modalidad.jpg](attachment:monto_modalidad.jpg)

![rednacional.jpg.jpg](attachment:rednacional.jpg.jpg)

![redterritorial.jpg](attachment:redterritorial.jpg)

![redejercito.jpg](attachment:redejercito.jpg)
