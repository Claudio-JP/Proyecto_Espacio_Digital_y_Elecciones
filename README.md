## Proyecto Espacio Digital y Elecciones

### Parte I

#### Tema del Proyecto: Relación entre el gasto monetario en publicidad digital por parte de partidos políticos y resultados electorales

#### Diagnóstico del Problema: 
 A día de hoy, la creciente importancia del espacio digital en las dinámicas políticas está muy reconocida por todos los agentes políticos del sistema nacional e internacional, desde los partidos políticos, los académicos, las ONGs, y los individuos que participan del sistema. Sin embargo, las formas particulares en las que se da esa relación no están del todo claras. Fallas en los mecanismos de reporte e itnercambio de información, problemas metodológicos e intereses políticos, entre otros, impiden el desarrollo de un estudio más completo sobre cómo, exactamente, el espacio digital influye en la participación política, en las elecciones, y en el funcionamiento de los partídos políticos en el país. Por tanto, es necesario gatillar un proceso de investigación más amplio, a través de un análisis descriptivo inicial de la información disponible, para identificar dinámicas tentativas y espacios futuros de investigación

#### Marco Teórico: Con lo anterior en mente, se utilizarán 4 papers de investigación relevantes: 
1.- Derechos Digitales. (2021). Publicidad Electoral en Redes Sociales.

2.- Jaraquemada, M. (2023). Political Finance in the Digital Age in Chile. IDEA.

3.- Tapia, M. (2021). Análisis de la conducta electoral de los votantes: ¿Cómo influyen las redes sociales en las campañas políticas?. Universidad de Chile. 2021.

#### Metodología: 
El presente trabajo consistirá en un análisis exploratorio cualitativo y cuantitativo, enfocado en identificar posibles dinámicas y patrones preliminares relevantes, a través del estudio de bases de datos sobre gasto en campañas electorales y los resultados de dichas campañas. 

Para esto, se definen las siguientes variables ->

- Variable Independiente: gasto partidario en campañas de publicidad digital
- Variable Dependiente: resultados electorales
- Variables Intervinientes: orientación política del partido; tamaño del partido por militancia; antigüedad del partido

A su vez, se definen 2 principales ejes de análisis -> Análisis cuantitativo de estadísticos primarios (correlación y regresión lineal); Análisis cualitativo de interpretación desde el análisis cuantitativo y a partir de las teorías y conceptos del marco teórico

Por unidad principal de análisis se tendrán a 10 partidos políticos transversales a las 4 bases de datos seleccionadas

#### Bases a Utilizar:
 Servicio Electoral. (2021). Gastos Elecciones Municipales, Convencionales Constituyentes y Gobernador Regional 2021. [Data set]. 

 Servicio Electoral. (2021). Elección Convencionales Constituyentes 2021. [Data set].
 
 Servicio Electoral. (2021). Gastos Elecciones Presidencial, Parlamentarias y de Consejeros Regionales 2021. [Data set]. 
 
 Servicio Electoral. (2021). Elección de Senadores 2021. [Data set].
 
 Servicio Electoral. (2021). Elección de Diputados 2021. [Data set].
 
 Servicio Electoral. (2017). Gastos, Partido político, Presidenciales primera elección 2017. [Data set].
 
 Servicio Electoral. (2018). Gastos Presidencial y Parlamentarias 2017. [Data set].
 
 Servicio Electoral. (2017). Elección de Senadores 2017. [Data set].
 
 Servicio Electoral. (2017). Elección de Diputados 2017. [Data set].

---O---

### Parte II

#### Plan de Análisis: 
Con los outputs iniciales de Gastos y Resultados electorales, el objetivo ahora es comenzar con la identificación inicial de las relaciones entre las variables dependiente e independiente. Esto, mediante la aplicación de herramientas estadísticas varias como el cálculo de correlación, regresiones logística multinomial, regresión lineal múltiple, análisis de efectos marginales, entre otras consideraciones según el avance de los estudios. Además, se controlará por concepto de variable interviniente a: Región, Tipo de Elección, Evolución Temporal. Según el avance del análisis, se podrán considerar otras variables intervinientes.

#### Outputs iniciales: 

<img width="875" height="540" alt="image" src="https://github.com/user-attachments/assets/ba43508c-f8b2-471c-839c-7348f24dfeef" />
##### Gasto en espacio digital por partido elecciones parlamentarias 2021

<img width="1371" height="418" alt="image" src="https://github.com/user-attachments/assets/5350f828-27e6-4401-9fe5-8658c93135e6" />
Resultado electoral por partido elecciones parlamentarias 2021


---O---

### Parte III

#### Transformación de Datos y Fase Descriptiva

Primeramente, se realizó una estandarización de la información contenida en las bastes de datos sobre gasto digital, homogeneizando los nombres de los partidos, y unificando los nombres y el orden de las columnas relevantes, para posteriormente poder realizar una base unificada.

<img width="846" height="781" alt="image" src="https://github.com/user-attachments/assets/0e712a23-5202-4df5-86cd-baf56323c3f5" />

##### Observaciones brutas sobre gasto digital

A partir del gráfico anterior, se seleccionan solo aquellos partidos que contienen información del gasto para los 4 períodos eleccionarios, y se obtiene una serie de gráficos que permiten visualizar la evolución temporal de los registros de gasto electoral.

<img width="875" height="540" alt="image" src="https://github.com/user-attachments/assets/1c3c45f9-5913-48c0-ad3e-2756e6175acd" />

##### Evolución del gasto digital registrado en los períodos eleccionarios seleccionados

Posteriormente, se realizó la unificación de la base de gastos digitales con los datos disponibles de las votaciones en los períodos eleccionarios relevantes. Se destaca que la base de datos para los resultados de las elecciones de la primera vuelta presidencial del 2017  no pudo ser utilizada, debido a que el registro de resultados electorales de esa elección fueron agrupadas bajo listas en vez de partidos. Así, la base de datos final con la que se realiza el análisis cualitativo y cuantitativo es la siguiente.

<img width="1682" height="372" alt="image" src="https://github.com/user-attachments/assets/805d905b-067b-4bc2-bab9-5747c4d089bc" />

#### Resultados preliminares

A partir de este tibble, se calculan una serie de estadísticos con tal de realizar un análisis cuantitativo tentativo. Principalmente, cálculos de correlación y regresión lineal.

Para cada proceso eleccionario, se realizó un cálculo de correlación y un modelo de regresión lineal. Los 3 modelos indicaron una relación positiva y estadísticamente significativa entre el gasto electoral y los resultados electorales para los partidos políticos seleccionados. Esto demostraría que sí existe una influencia del gasto en publicidad digital y los resultados electorales de los partidos. Debido a que los 3 modelos ilustran la misma dinámica, se muestra acá solo uno de los modelamientos.

<img width="703" height="75" alt="image" src="https://github.com/user-attachments/assets/6d9b94f2-bfbd-4021-ad36-390689c40f85" />

##### Correlación gasto digital - resultado electoral elecciones parlamentarias 2017

<img width="412" height="314" alt="image" src="https://github.com/user-attachments/assets/bdd06f96-65f8-41c0-b113-f05b900ecf80" />

##### Regresión lineal gasto digital - resultado electoral elecciones parlamentarias 2017


Posteriormente, se realiza un cálculo de correlación y de regresión lineal utilizando el promedio del gasto digital por partido y el promedio de los resultados electorales, con tal de observar de mejor manera las posibles dinámicas generales en los procesos analizados.

<img width="988" height="85" alt="image" src="https://github.com/user-attachments/assets/3544a3e1-a7e1-4e31-b1bc-c701915c8ad9" />

##### Correlación promedio gasto digital - promedio resultado electoral

<img width="383" height="288" alt="image" src="https://github.com/user-attachments/assets/7c3401b3-c725-4297-bf46-d1c83069380f" />

##### Regresión lineal promedio gasto digital - promedio resultado electoral 


Teniendo ya la relación general entre gasto y en espacio digital y resultados electorales, se procede a modelar la relación, pero controlando por las variables intervinientes definidas

<img width="501" height="538" alt="image" src="https://github.com/user-attachments/assets/8b624041-70b9-432b-bb78-9ffcfc4de79a" />

##### Regresión lineal controlada por las variables antigüedad (partido_nuevo, con 0 indicando partido fundado antes del 2000, y 1 fundado posterior al 2000), tamaño del partido por militancia y orientación ideológica del partido.


Debido a que ideología pareciera no tener influencia en el modelo, se continúa con la realización de varios modelos y relaciones entre variables, identificando finalmente una relación entre ideología y gasto electoral

<img width="495" height="392" alt="Captura de pantalla (249)" src="https://github.com/user-attachments/assets/4e606716-52e9-4d20-9d30-afe095816193" />

##### regresión lineal ideología - gasto digital por partido


A partir de todo lo visto anteriormente, es posible estipular la conformación de una estructura causal que adopta la siguiente forma:

#### Ideología de partido → Gasto Digital por partido --- Tamaño del partido por militantes // Antigüedad del partido--> Resultados electorales

### Conclusiones
