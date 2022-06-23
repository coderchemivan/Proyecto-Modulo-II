README. PROYECTO ANÁLISIS DE DATOS: DEPORTISTAS MEJOR PAGADOS 

INTRODUCCIÓN 
En este proyecto se analizó el CSV sobre los atletas mejor pagados en 2020. El cual contiene los nombres de los atletas, el país al que pertenecen, sus ganancias, así como los rankings obtenidos por año.

TIDY DATA
Como primer paso se consideraron las buenas prácticas de data. Se rellenaron los espacios vacíos de la columna ‘Previus Year’ con un N/A (No Aplica), ya que en algunos casos los deportistas no tuvieron un antecedente de ranking en el año previo. Se homogenizaron los datos de la columna deportes, colocando una mayúscula a la primera letra de cada deporte en la columna. 


SOLUCIÓN DE PREGUNTAS
Con la Información dada, se resolvieron las siguientes preguntas: 
•	Deportistas cuyo ranking ha subido al menos dos lugares entre 2010 y 2020.
Para esto se realizó una tabla nueva en la cual se visualizó de mejor forma el ranking que obtuvo cada deportista por año. Con la cual se concluyó que si hubo una gran cantidad de deportistas que ascendieron con el tiempo y otros que no tuvieron oportunidad de volver a obtener un lugar en el ranking. 
•	Atleta con el menor número de apariciones y mayores ganancias.
Para hacerlo se realizó una tabla con filtrado de los deportistas que solo aparecen una vez, a lo largo de los años. Se signaron sus ganancias y por último se ordenaron de forma descendente, para visualizar quienes tuvieron las mayores ganancias.
•	Deporte y país con mayor número de atletas no rankeados que entraron en la lista de atletas mejor pagados.
En este caso se consideró como los No rankeados, los que solo tuvieron una aparición, tomando en cuenta la información de la pregunta anterior, se agregaron las columnas de país y deporte, con respecto a ello se asignaron sus ganancias para ordenar la cantidad de atletas. 
•	País con mayor número de deportes con atletas en el dataset
•	¿Cuántos atletas por deporte tiene cada país?
•	Ganancia mínima y máxima (dentro del dataset) por deporte y por país.
Para estas tres preguntas se elaboró una tabla que indicara los países con sus respectivos deportes la cantidad de deportistas por deporte en una columna que los contaba, así como el año al que correspondía cada uno con la ganancia. De ello se pudo jalar el páis con mayor número de deportes con atletas y cuántos atletas había por deporte, además de que ordenado se sacó el mínimo y máximo de ganancia. 
•	Atleta con mayores ganancias por deporte por década
En esta pregunta se hizo una tabla con columnas de los atletas y las tres décadas contenidas en el dataset en las cuales se colocó el valor de mayor ganancia por atleta.
•	Ganancia total por cada deporte por cada año.
En esta última se consideró una tabla con la columna de deportes, años y ganancias, estas últimas sumadas de acuerdo a los valores de los deportes por año. 


ANÁLISIS EN POWER BI
Por último, se hizo un análisis en general en Power BI, en el que se hicieron las siguientes gráficas: 






