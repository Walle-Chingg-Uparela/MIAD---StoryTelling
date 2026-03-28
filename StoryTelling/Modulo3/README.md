# Analisis Encuesta de salarios

## Contexto

Para esta actividad se desarrolló un dashboard en Power BI orientado al análisis de salarios de profesionales, considerando variables clave como la industria, la profesión y la ubicación geográfica.

La base de datos utilizada proviene de una encuesta realizada en el año 2021 a un grupo de profesionales de diferentes sectores, lo que permite explorar tendencias salariales desde una perspectiva global y con ella se buscaba responder a las siguientes preguntas.

## Preguntas de análisis

¿ cómo se distribuyen geograficamente los encuestados?
¿ Qué industrias concentran la mayor cantidad de profesionales dentro de la muestra?
¿ Qué industria presenta el mayor salario promedio anual ?
¿ Existe relación entre la cantidad de encuestados por industria y el nivel salarial promedio?

El dashboard construido permite:

- Visualizar la distribución de los encuestados por ubicación geográfica.
- Analizar el salario anual promedio por industria.
- Identificar la participación de cada industria en la muestra de datos.

Este enfoque facilita la comprensión de cómo varían los salarios según el sector y la localización, proporcionando una visión clara y estructurada de la información.

# Metodologia

## 1. Limpieza y preparación de datos 
- Depuración de registros incompletos o inconsistentes.
- Estandarización de variables clave como industria, país y ciudad.
- Homogenización de nombre para evitar duplicidades en el analisis.
  
## 2. Transformación de variables
- Conversión de salarios y compensaciones a una moneda común (para esta actividad se utiliza COP) utilizando tasas de cambio.
- Creación de variables como "Salario anual en COP" y "Compensación total".
- Simplificación de nombres de variables para facilitar su manipulación.

## 3. Modelado de datos 
- Estructuración de un modelo de datos limpoio y consistente.
- Preparación de la información para su visualización en Power BI.

## 4. Visualización
Se desarrollo un dashboar interactivo en power BI  compuesto por:
- indicador KPI: para el total de registros válidos en la base de datos.
- Mapa geograafico: distribución de encuestados por país.
- Grafico de barras: mostrando el promedio de salario anual por industria.
- Treemap: para la distribución de encuestados por industria en la cual se encuentran.

## DashBoard

![Dashboard2](Dashboard_2.jpg)

## Conclusiones

- Existe una alta concentración entre algunos paises , destacando Estados Unidos
- La industria de la tecnología presenta un mayor nivel de participación por parte de los encuestados
- La industria que cuenta con un mayor salario promedio anual es la de finanzas  y contabilidad
- Luego entonces con los 2 indices anteriores se puede decir que no existe una relación entre la canitdad de encuestados por industrias y el nivel salarial ya que industrias con menos encuestados poseen un salario más grande)




