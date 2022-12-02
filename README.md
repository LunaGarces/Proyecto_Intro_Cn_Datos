# Violencia intrafamiliar Femenina

### Integrantes:

|Nombre     |  Correo UC   | 
|---------|-----------------|
|Luna Garcés| luna.garcs@uc.cl        |
|Maria Jose Ortega |     mariajoseortega@uc.cl    |
|Richard Aguilera | ri.aguilera@uc.cl        |
|Sebastian Assereto |     sebastian.assereto@uc.cl    |

## Objetivo del proyecto

El principal objetivo que busca el proyecto, es dar a cuenta la violencia que puede llegar a sufrir una mujer dentro de su familia,y cuales pueden ser las causales que producen este problema.

### Metodos utilizados:
* Machine learning 
* Clustering 
* Arboles de decision 
* Analisis graficos

### Tecnologias:

* Python
* Jupyter Notebook
* Pandas, matbplotlib, seaborn
* Requiere tener descompresor de archivos .rar

## Descripcion del proyecto

Esta investigacion, busca a partir de una recopilacion de resultados de encuestas realizadas a mujeres que residen en Chile, encontrar los patrones que se pueden reconocer entre los diferentes casos de violencia intrafamiliar y ver como estos se relacionan, ya sea el tipo de relacion que se lleva a cabo, como son las decisiones al interior de la relacion. Además se identifica en que sectores economicos es más comun este tipo de problematicas y en que sectores de Chile es más frecuente 

## Motivacion de este proyecto 

* Visualizar los diferentes factores que pueden producir este tipo de agresiones y ver si hay caracteristicas comunes entre los diferentes casos

* Localizar las zonas donde es más frecuente este tipo de actos 


## Para empezar a correr el codigo 

El usuario puede decidir si correr directamente el producto final (2da Etapa) o ejecutar el codigo desde el principio (1ra Etapa), esta primera etapa en forma resumida, consta en ejecutar los dataset tal como los extrajimos de internet, para en el interior del archivo jupyter hacer el filtrado y limpieza de datos necesario para poder ejecutar la Segunda Etapa del codigo que posee los resultados finales de nuestra investigacion.
### Pasos para realizar la 1ra Etapa:

1.- Abra la carpeta "Datasets" en su interior encontrara 4 carpetas (E.laboral, femicidios-info(extra), ingresos, principal-encuestas). Ingresaremos a cada una de estas carpetas, menos a la de "femicidios-info(extra).

2.- En la carpeta E.laboral descomprimiremos "E.laboral_formato_sav.rar" ; En ingresos, descomprimiremos "ingresos-personas.rar" ; por ultimo en la carpeta principal-encuestas descomprimiremos el archivo "principal-encuestas.rar"

3.-A continuacion volveremos a la carpeta en la cual clonamos el repositorio y abriremos el archivo "proyecto.ipynb". En el interior de este archivo y si vamos leyendo las lineas, veremos todo el proceso que realizamos para poder filtrar, reordenar y limpiar los datos que utilizariamos en la siguiente etapa del codigo.

4.- Si ejecuta cada linea del codigo, se crearan nuevos archivos de datos en las carpetas "E.laboral", "ingresos" y "pricipal-encuestas" los cuales en su nombre tendran la terminacion **"__final"**. Estos archivos generados seran el producto de la limpieza realizada en el actual archivo y que posteriormente utilizaremos en la siguiente etapa del trabajo

### Pasos para realizar la 2da Etapa:
***Importante***:
Si no realizo la ejecucion de los pasos de la primera etapa es necesario que realice los siguientes pasos para la correcta ejecucion del codigo
1.- Ingrese a la carpeta "Datasets", en la carpeta "E.laboral" descomprima el archivo "Laboral_Final.rar", en la carpeta "ingresos" descomprima el archivo "Ingresos_Final.rar" y por ultimo en la carpeta "principal-encuestas" descomprima el archivo "VIF_Final.rar"

2.- A continuacion regresamos a la carpeta que clonada a partir del repositorio y abriremos el documento "Analisis y Construcción.ipynb"

**Cualquier duda respecto a temas de variables y que significan sus opciones, la informacion se encuentra dentro del archivo "descripcion_variables.xlsx"**

1.- Una vez ya con los archivos necesarios, ya sea porque completo los 2 pasos anteriores o porque realizo la primera etapa, ya puede ejecutar el archivo "Analisis y Construcción.ipynb"
2.- En el interior de este archivo encontrara todo el desarrollo e informacion respecto al proyecto 

### Fuentes de recoleccion de los datos

* Estado laboral:https://www.ine.gob.cl/estadisticas/sociales/ingresos-y-gastos/encuesta-de-presupuestos-familiares

* Ingresos: https://www.ine.gob.cl/estadisticas/sociales/ingresos-y-gastos/encuesta-suplementaria-de-ingresos

* Encuestas: http://cead.spd.gov.cl/estudios-y-encuestas/