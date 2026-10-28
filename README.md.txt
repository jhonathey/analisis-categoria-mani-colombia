CRECIMIENTO COMERCIAL CATEGORIA DE MANI EN EL TERRITORIO COLOMBIANO


1.	DESCRIPCION DEL PROYECTO
Analizar el comportamiento de una categoría acorde a los objetivos establecidos por la compañía, estos objetivos son considerados ambiciosos y realistas y están asignado en crecimiento en venta (valor) de un 8%, se utiliza una base de datos histórica para el análisis del año 2025y se genera un dashboard orientado al análisis y toma de decisiones con el fin de identificar tendencias de ventas oportunidades territoriales y palanca comerciales que permitan acelerar el crecimiento y ampliar la cobertura de nuestros productos.
El dashboard permite analizar el desempeño por periodo de tiempo, territorio, segmentos, negocios, y detectar aquellos comportamientos que ameritan un análisis más detallado, los resultados de estos análisis deben tomarse como soporte para un plan de acción y toma de decisiones.


2.	PREPARACION Y LIMPIEZA DE DATOS
La información se cargo desde un archivo csv (adjunto), se realizo una revisión de la calidad del dato antes de utilizar la data para el análisis:
•	Revisión e identificación de variables relevantes para el análisis
•	Consistencia en el dato de los campos relevantes
•	Evaluación de datos faltantes, se conservaron campos vacíos no esenciales para el análisis como por ejemplo en la columna proveedor
•	Identificación y eliminación de registros duplicados
•	Revisión de outliers en este caso la información es real útil y relevante ya que los outliers muestran un mal desempeño de negocios que no cumplen con cabalidad la estrategia comercial por ejemplo negocios con ventas muy reducidas que se alejan de la media que corresponde a una realidad y no a un error del dato y que es relevante mantener para el análisis y toma de decisiones en el plan de acción.
•	Creación de variables categóricas y derivadas para enriquecer la lectura comercial.
•	Exploración de patrones y tendencias de ventas
•	Clusterizacion de los territorios para entender zonas e identificar oportunidades.




3.	ESTRUCTURA DEL PROYECTO
├── C:\the power\EDA\ORIGEN.csv          # Datos crudos y procesados 
├── C:\the power\EDA\POS 201512 MANI Y NUECES.XLS    # Gráficos y archivos de resultados 
├── C:\the power\EDA\README      # Descripción del proyecto




4.	HERRAMIENTAS Y REQUISITOS
El origen de dato es un archivo csv y el entregable analítico es un dashboard, la herramienta de visualización es Microsoft Excel, no se indican comando de instalación para herramientas de visualización adicionales debido a que no son necesarios en este caso.
•	Herramienta de análisis y visualización para construir el dashboard Microsoft Excel 2016
•	Herramienta de preparación del dato Microsoft Excel 2016
•	Origen del dato Archivo csv suministrado por un excompañero de trabajo (Adjunto)
•	Pasos para actualizar el dato: importar achivo csv actualizado con la misma estructura y actualizar 1 tabla dinámica (cualquiera)
•	En el archivo están definidos los KPIs de manera clara visible e interactiva, entre ellos ventas totales, negocios, y productos (SKU).
•	Filtros interactivos para facilitar el manejo de la herramienta de visualización como lo son segmentos, meses, negocios nuevos o antiguos, distrito.








5.	RESULTADOS PRELIMINARES
Según el análisis comercial la empresa cuenta con una tendencia general de crecimiento promedio anual superior al 4% en ventas, se identifican 2 meses con variación negativa Abril y noviembre, y un mes (junio) sin crecimiento, también vemos un comportamiento estacionario en Diciembre que dispara las ventas en un 26% que corresponde a las festividades del mes y a la cultura culinaria de postres y tortas con maní y nueces que representa esta temporada, lo cual asumimos como un comportamiento circunstancial que ocurre cada año y se mueve entre estos dígitos mencionados.










En el distrito de Medellín se reporta la apertura de 6 nuevos negocios durante el año, pasando 11 a 17 punto de ventas esto es un incremento del 54% en cobertura en este distrito logrando así romper la barrera de los 20 millones mensuales en este distrito, a continuación, veremos una gráfica con el crecimiento por distrito el cual muestra la mayor fluctuación en Medellín debido a las nuevas aperturas y fiestas gastronómicas celebradas en el mes de septiembre.
 
Y asi se refleja el comportamiento de ventas del distrito de medellin durante el año 2025.
 

La lectura conjunta de ventas y cobertura permite orientar las decisiones hacia territorios con potencial, detectar meses de bajo desempeño y evaluar si nuestra expansión de puntos de ventas se traduce en ventas.





6.	OBJETIVO COMERCIAL Y PROXIMOS PASOS
Objetivo propuesto: lograr un crecimiento del 10% en la categoría de mani y nueces durante el año 2025 acompañado de una expansión rentable de cobertura.
•	Definir los argumentos de crecimiento para considerar un 10% de meta y definir la meta para próximo año.
•	Cuantificar la brecha entre el crecimiento actual de 4%y el objetivo del 10%, identificar planes de acción y estrategias comerciales para alcanzar la meta.
•	Analizar abril, junio y noviembre por ventas, distribución, precio, promociones, inventario y comportamiento territorial.
•	Medir la productividad de las nuevas aperturas (Medellín y demás): ventas por punto, evolución mensual, disponibilidad y tiempo desde apertura
•	Priorizar territorios mediante potencial de mercado, cobertura actual, ventas por negocio y viabilidad de distribución.
•	Construir un plan de acción con palancas medibles: distribución numérica, surtido, disponibilidad, ejecución comercial, precio y promoción, según los datos disponibles.
•	Incorporar seguimiento de KPIs generados en el dasboard: ventas en valor y volumen, crecimiento interanual, distribución/cobertura, ventas por punto, precio promedio y contribución de las iniciativas.
•	Validar los resultados con periodos comparables (años anteriores) y documentar supuestos, limitaciones y cambios de metodología


7.	CONTRIBUCIONES Y USO DEL PROYECTO
Las mejoras al análisis pueden incluir la validación de indicadores, el enriquecimiento de variables, la revisión de agrupaciones territoriales y la incorporación de nuevas fuentes. Toda modificación debería documentar qué cambió, por qué se cambió y cómo afecta la comparabilidad de los resultados.


8.	AUTORIA Y AGRADECIMIENTO.
Análisis y dashboard: elaborado por el estudiante de master en data analitics en The Power Jonathan Ignacio Martínez Quintero del proyecto, con enfoque de Category Management y análisis comercial.
Fuente de datos: archivo facilitado por Cristian Mulford, excompañero de trabajo en Supertiendas y Droguerías Olímpica, quien desempeñaba también funciones de Category Manager.
Agradecimiento a Cristian Mulford por compartir el archivo de origen que sirvió como punto de partida para el análisis. La atribución de la fuente no implica necesariamente la titularidad de los datos ni autorización para su difusión pública.
https://www.linkedin.com/in/christian-d-mulford-m-b3207660/


