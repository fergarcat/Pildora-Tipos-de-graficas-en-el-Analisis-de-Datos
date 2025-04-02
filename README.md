# Pildora-Tipos-de-graficas-en-el-Analisis-de-Datos

El mundo esta lleno de datos, sin embargo es todo un arte interpretarlos y representarlos, este es el propósito de este repositorio darte unas pinceladas para que saques el artista que hay en ti.


## Recursos útiles

* Tipos de gráficos de datos y cómo crearlos en Python [crear gráficas en python](https://www.datacamp.com/es/tutorial/types-of-data-plots-and-how-to-create-them-in-python)
* Ejemplos de uso de gráficos [tipo graficas](https://uni.edu.gt/noticias/tipos-de-graficas/)
* Guía práctica para machine learning [gráficos data science](https://iddigitalschool.com/bootcamps/tipos-de-graficos-para-data-science-y-data-analytics-guia-practica/)
* el arte de mostrar información:[Edward Tufte](https://www.linkedin.com/pulse/edward-tufte-el-arte-de-mostrar-informaci%C3%B3n-rafael-l%C3%B3pez-callej%C3%B3n/)
*  Gráficar con barras divergentes en python: [graficar con barras python](https://r-charts.com/es/parte-todo/grafico-barras-divergentes-ggplot2/)
*  Cómo elegir el gráfico correcto para visualizar datos abiertos: [guía para visualizar datos](https://datos.gob.es/es/blog/como-elegir-el-grafico-correcto-para-visualizar-datos-abiertos)
* El arte y la ciencia de visualizar datos: [el arte de los datos](https://egobiernoytp.tec.mx/es/blog/el-arte-y-la-ciencia-de-visualizar-datos)
*  [Errores en la visualizacion datos](https://tcagency.es/errores-de-visualizacion-de-datos/)



## ¿Por qué visualizar los datos?
Su objetivo es ayudar a nuestra comprensión de los datos aprovechando el sistema visual humano altamente sintonizado para ver patrones, detectar tendencias e identificar valores atípicos.

Antes de continuar me gustaría presentarte a un personaje clave:
> En 1975, [Edward Tufte](https://es.wikipedia.org/wiki/Edward_Tufte), un joven profesor en Princeton, sentó las bases del visual analytics. Hoy es profesor emérito en Yale y es reconocido como una figura clave en la visualización de datos, siendo considerado el “Leonardo da Vinci de los datos”. Entre 2001 y 2006 escribió cuatro libros fundamentales sobre el tema. Sus ideas destacan la importancia de eliminar elementos decorativos e innecesarios en los gráficos, enfocándose en mostrar solo la información relevante y explicativa.


## Tipos de gráficas y cuando usarlas
Ahora si vamos con el plato fuerte de esta píldora:

### Desviación:
Sirve para subrayar las variaciones numéricas desde un punto de referencia fijo. Habitualmente, el punto de referencia es cero, pero también puede ser un objetivo o un promedio a largo plazo. Además, este tipo de gráficos resultan útiles para mostrar sentimientos (positivo, neutral o negativo).  comparar resultados vs. objetivos. Por ejemplo, ingresos esperados vs. reales, o encuestas con opiniones positivas/negativasLos gráficos más frecuentes son:

#### Barra Divergente
Un gráfico de barras estándar simple que permite manejar valores de magnitud tanto negativos como positivos.

 Usos: Muy útil para comparar resultados vs. objetivos. Por ejemplo, ingresos esperados vs. reales, o encuestas con opiniones positivas/negativas

![]()

#### Tabla de columna
Divide un valor único en 2 componentes contrastables.

Usos: Útil para comparar proporciones binarias, como sexo o elecciones (masculino/femenino).

![]()

### Correlación
Útil para mostrar la relación entre dos o más variables. Conviene tener en cuenta que, a menos que les diga lo contrario, muchos lectores asumirán que las relaciones que les muestra son causales. Estos son algunos de los gráficos.

#### Gráfico de dispersión
La forma estándar de mostrar la relación entre dos variables continuas, cada una de las cuales tiene su propio eje.

Usos: Para estudiar cómo se relacionan dos variables, como ingresos vs. gasto, o edad vs. rendimiento.

![]()

#### Línea del tiempo
Una buena manera de mostrar la relación entre una cantidad (columnas) y un ratio (línea).

Usos: Muestra simultáneamente una cantidad absoluta (barras/línea) y un ratio (línea secundaria). Ideal para comparar métricas como ventas absolutas vs. porcentaje de crecimiento.


![]()

### Clasificación
Es necesario clasificar variables numéricas cuando la posición de un elemento en una lista ordenada es más importante que su valor absoluto o relativo. A través de los gráficos dispuestos a continuación es posible resaltar los puntos de interés.

#### Gráfico de barras
Este tipo de visualizaciones permiten mostar los rangos de valores de forma sencilla cuando se ordenan.

Usos: Ideal para rankings, como ventas por producto o rendimiento por empleado.

![]()

#### Diagrama tira de puntos
Los puntos están ordenados en una tira. Esta distribución ahorra espacio para diseñar rangos en múltiples categorías.

Usos:  Alternativa más limpia y compacta a las barras, especialmente útil cuando hay muchas categorías.

![]()

### Distribución
Este tipo de gráficos buscan resaltar una serie de valores dentro de un conjunto de datos y representar con qué frecuencia ocurren. Es decir, se utilizan para mostrar cómo se distribuyen las variables a lo largo del tiempo, lo que ayuda a identificar valores atípicos y tendencias.

La forma en sí misma de una distribución puede ser una forma interesante de resaltar la falta de uniformidad o igualdad en los datos. Las visualizaciones más recomendadas para representar, por ejemplo, una distribución por edad o sexo son las siguientes:

##### Histograma
Es la forma más habitual de mostrar una distribución estadística. Para desarrollarlo se recomienda mantener un pequeño espacio entre las columnas para, así, resaltar la "forma" de los datos.

Usos: Se usa para analizar la frecuencia, como distribución de edades, tiempos de respuesta o precios. 

![]()

#### Gráfico de cajas
Eficaz para visualizar distribuciones múltiples mostrando la mediana (centro) y el rango de los datos.

Usos: Resume la mediana, cuartiles y posibles valores atípicos. Muy útil en análisis estadístico.

![]()

#### Pirámide poblacional
Conocido por mostrar la distribución de la población por sexo. De hecho, se trata de una combinación de dos gráficos de barras horizontales compartiendo el eje vertical.

Usos: Muestra la distribución de población por grupos de edad y sexo.

![]()

### Cambios en el tiempo
A través de esta combinación de variables numéricas es posible dar énfasis a tendencias cambiantes. Estos pueden ser movimientos cortos o series extendidas que atraviesan décadas o siglos. Elegir el período de tiempo correcto a representar es clave para ofrecer un contexto al lector.

#### Línea
Es la forma estándar para mostrar una serie temporal cambiante. Si los datos son muy irregulares puede ser útil emplear marcadores que ayuden a representar puntos de datos.

Usos: Seguimiento de KPIs, como tráfico web por mes o crecimiento de usuarios

![]()

#### Mapa de calor calendario
Sirve para mostrar patrones temporales (diario, semanal, mensual). Es necesario ser muy precisos con la cantidad de datos.

Usos: Ideal para visualizar patrones temporales como actividad diaria, asistencia, o ventas a lo largo del año.

![]()

### Magnitud
Útil para visibilizar comparaciones de tamaño. Estas pueden ser relativas (simplemente pudiendo ver más grande/mayor) o absolutas (requiere ver diferencias más específicas). Por lo general, muestran variables que pueden ser contadas (por ejemplo, barriles, dólares o personas), en lugar de una tasa calculada o un porcentaje.

#### Columnas
Una de las maneras más comunes de comparar el tamaño de las cosas. El eje siempre debe comenzar en 0.

Usos: Comparar cantidades totales, como presupuesto por departamento o población por ciudad.

![]()

#### Gráfico de Marimekko
deal para mostrar el tamaño y la proporción de los datos al mismo tiempo, y siempre y cuando, los datos no sean muy complejos.

Usos: Excelente para visualizar composición de mercados.

![]()

### Parte de un todo
Este tipo de combinaciones numéricas son útiles para mostrar cómo una entidad en sí misma puede dividirse en los elementos que lo conforman. Por ejemplo, es común utilizar la parte de un todo para representar la asignación de unos presupuestos o resultados electorales.

Usos: Representa conjuntos y sus intersecciones. Por ejemplo: usuarios que usan App A, App B, o ambas.

#### Gráfico de tarta
Uno de los gráficos más comunes para mostrar datos parciales o completos. Conviene tener presente que no es fácil comparar de forma precisa el tamaño de los distintos segmentos.

Usos: Muy usado en reportes para mostrar distribución de presupuestos, participación de mercado

![]()

#### Diagrama de Venn
Limitado a representaciones esquemáticas que permiten mostrar interrelaciones o coincidencias.

![]()

### Espacial
Se recurre a este tipo de gráficos cuando las ubicaciones precisas o los patrones geográficos en los datos son más importantes para el lector que cualquier otra cosa. Algunos de los más utilizados son:

#### Mapa coroplético
Se trata del enfoque estándar para colocar datos en un mapa.

Usos: Normalmente se aplica sobre un mapa real para mostrar intensidad por región (como casos por estado, ingresos por país).

![]()

#### Mapa de flujo
Es utilizado para mostrar un movimiento de cualquier tipo dentro de un mismo mapa. Por ejemplo, puede emplearse para representar movimientos migratorios.

Usos: Muestra movimiento o migración de un lugar a otro, muy útil en logística o migraciones humanas.

![]()

