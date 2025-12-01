# Proyecto Propaganda Digital y Elecciones: _Caso de Estudio de Gasto Digital por Partido y Resultados Electorales en Chile_

# Parte I

## Tema del Proyecto
**Relación entre el gasto monetario en publicidad digital por parte de partidos políticos y resultados electorales.**
<br>
<br>

## Diagnóstico del Problema 
 A día de hoy, la creciente importancia del espacio digital en las dinámicas políticas está muy reconocida por todos los agentes políticos del sistema nacional e internacional, desde los partidos políticos, los académicos, las ONGs, y los individuos que participan del sistema.
 
 Sin embargo, las formas particulares en las que se da esa relación no están del todo claras. Fallas en los mecanismos de reporte e intercambio de información, problemas metodológicos e intereses políticos, entre otros, impiden el desarrollo de un estudio más completo sobre cómo, exactamente, el espacio digital influye en la participación política, en las elecciones, y en el funcionamiento de los partídos políticos en el país.
 
Por tanto, es necesario gatillar un proceso de investigación más amplio, a través de un análisis descriptivo inicial de la información disponible, para identificar dinámicas tentativas y espacios futuros de investigación.
<br>
<br>

## Marco Teórico

Con lo anterior en mente, se utilizaron principalmente 3 papers de investigación relevantes: 

1. Derechos Digitales. (2021). Publicidad Electoral en Redes Sociales.

2. Jaraquemada, M. (2023). Political Finance in the Digital Age in Chile. IDEA.

3. Tapia, M. (2021). Análisis de la conducta electoral de los votantes: ¿Cómo influyen las redes sociales en las campañas políticas?. Universidad de Chile. 2021.
<br>


## Estudio de Derechos Digitales y ADS (2021)
**Plebiscito Constitucional 2020 (Posts Electorales en RRSS):**
- RRSS principalmente para fines electorales.

**Elecciones Presidenciales 2021 (Posts Electorales en RRSS):**
- **Primera Vuelta: 62% No-Electorales; 36% Electorales**
  - El porcentaje de posts electorales era inversamente proporcional al tamaño del partido.
- **Segunda Vuelta: 59% Electorales ; 37% No-Electorales**

<br>

**Ha aumentado la importancia de las RRSS para los candidatos en sus campañas electorales.**
<br>
<br>

## Campaña digital y Elecciones en Chile: Desafíos
**Ambiguedad sobre qué es una campaña digital (Jaraquemada, 2023)**
- Campaña vs Libertad de Expresión
  - Ej: Parisi con su canal de YouTube (Tapia, 2021)
  - Ej: Influencers
- Métodos de Campaña
  - Ej: Bots

**Falta de transparencia en los datos (Jaraquemada, 2023)**
- No se tienen detalles concretos (categorías vagas), hay falta de información y lagunas entre los datos dados por los candidatos y otras bases de datos.
- Ej: Los datos entregados por los candidatos no coinciden con los datos entregados por Meta (Derechos Digitales, 2021).

**Falta de concordancia en los datos (Jaraquemada, 2023)**
- Distintos parámetros entre empresas sobre qué es una propaganda política.
  - Genera omisiones y subdeclaraciones de gastos
<br>


## Pregunta de Investigación
**¿Cómo afecta la actividad partidaria en el espacio digital en su rendimiento electoral?**
<br>
<br>

## Hipótesis
**"Un mayor gasto en campañas digitales por parte de los partidos políticos deviene en un mejor rendimiento electoral”**
<br>
<br>


## Objetivos
### Objetivo General:
Evaluar, de manera tentativa, la realidad chilena con respecto a una posible correlación entre el espacio digital y los resultados electorales.

### Objetivo Específico 1:
Evaluar la “rentabilidad” del gasto en propaganda digital para los partidos políticos. Si es que un mayor gasto se traduce en mejor rendimiento electoral.

### Objetivo Específico 2:
Evaluar los espacios de mejora con respecto a la información disponible y posibles futuros espacios de investigación académica.
<br>
<br>


## Metodología: 
El presente trabajo consiste en un análisis exploratorio cualitativo y cuantitativo, enfocado en identificar posibles dinámicas y patrones preliminares relevantes, a través del estudio de bases de datos sobre gasto en campañas electorales y los resultados de dichas campañas. 

Para esto, se definen las siguientes variables:
-	__Variable Independiente__: Gasto partidario en campañas de publicidad digital.
-	__Variable Dependiente__: Resultados electorales.
-	__Variables Intervinientes__: Orientación política, tamaño del partido (militancia) y antigüedad del partido.

A su vez, se definen 2 principales ejes de análisis:
- __Análisis cuantitativo__ de estadísticos primarios.
- __Análisis cualitativo__ de teoría y supuestos basados en la interpretación del análisis cuantitativo y conceptos del marco teórico.

Por unidad principal de análisis se tendrán a 10 partidos políticos transversales a las 4 bases de datos seleccionadas.
<br>
<br>


## Bases de Datos a Utilizar:
- Servicio Electoral. (2021). Gastos Elecciones Municipales, Convencionales Constituyentes y Gobernador Regional 2021. [Data set]. 

- Servicio Electoral. (2021). Elección Convencionales Constituyentes 2021. [Data set].
 
- Servicio Electoral. (2021). Gastos Elecciones Presidencial, Parlamentarias y de Consejeros Regionales 2021. [Data set]. 
 
- Servicio Electoral. (2021). Elección de Senadores 2021. [Data set].
 
- Servicio Electoral. (2021). Elección de Diputados 2021. [Data set].
 
- Servicio Electoral. (2017). Gastos, Partido político, Presidenciales primera elección 2017. [Data set].
 
- Servicio Electoral. (2018). Gastos Presidencial y Parlamentarias 2017. [Data set].
 
- Servicio Electoral. (2017). Elección de Senadores 2017. [Data set].
 
- Servicio Electoral. (2017). Elección de Diputados 2017. [Data set].
<br>


## Limitantes en las Bases de Datos Presidenciales

**Presidenciales 2017:**
- Las coaliciones de partidos por un candidato dificulta la estimación del gasto.

**Presidenciales 2021:**
- La glosa de gasto digital se encuentra incompleta por parte de la mayoría de los candidatos.
<br>

---

<br>


# Parte II

## Plan de Análisis
Con los outputs iniciales de Gastos y Resultados electorales, el objetivo ahora es comenzar con la identificación inicial de las relaciones entre las variables dependiente e independiente.

Esto, mediante la aplicación de herramientas estadísticas varias como el cálculo estadísticos como la correlación, regresiones logística simple y múltiple.

Además, se controlará por concepto de variable interviniente a:antigüedad del partido, tamaño según militancia, y orientación ideológica del partido.
<br>
<br>


## Outputs iniciales

**Gasto en Espacio Digital por Partido - Elecciones Parlamentarias 2021:**

<img width="875" height="540" alt="image" src="https://github.com/user-attachments/assets/ba43508c-f8b2-471c-839c-7348f24dfeef" />

**Resultado Electoral por Partido - Elecciones Parlamentarias 2021:**
<img width="1371" height="418" alt="image" src="https://github.com/user-attachments/assets/5350f828-27e6-4401-9fe5-8658c93135e6" />
<br>
<br>

---

<br>

# Parte III

## Transformación de Datos y Fase Descriptiva

Primeramente, se realizó una estandarización de la información contenida en las bastes de datos sobre gasto digital, homogeneizando los nombres de los partidos, y unificando los nombres y el orden de las columnas relevantes, para posteriormente poder realizar una base unificada.

<img width="846" height="781" alt="image" src="https://github.com/user-attachments/assets/0e712a23-5202-4df5-86cd-baf56323c3f5" />
<br>
<br>

## Observaciones brutas sobre gasto digital

A partir del gráfico anterior, se seleccionan solo aquellos partidos que contienen información del gasto para los 4 períodos eleccionarios, y se obtiene una serie de gráficos que permiten visualizar la evolución temporal de los registros de gasto electoral.

<img width="875" height="540" alt="image" src="https://github.com/user-attachments/assets/1c3c45f9-5913-48c0-ad3e-2756e6175acd" />
<br>
<br>

## Evolución del gasto digital registrado en los períodos eleccionarios seleccionados

Posteriormente, se realizó la unificación de la base de gastos digitales con los datos disponibles de las votaciones en los períodos eleccionarios relevantes.

Se destaca que la base de datos para los resultados de las elecciones de la primera vuelta presidencial del 2017 no pudo ser utilizada, debido a que el registro de resultados electorales de esa elección fueron agrupadas bajo listas en vez de partidos. Así, la base de datos final con la que se realiza el análisis cualitativo y cuantitativo es la siguiente.

<img width="1682" height="372" alt="image" src="https://github.com/user-attachments/assets/805d905b-067b-4bc2-bab9-5747c4d089bc" />
<br>
<br>

## Resultados preliminares

A partir de este tibble, se calculan una serie de estadísticos con tal de realizar un análisis cuantitativo tentativo; principalmente, cálculos de correlación y regresión lineal. Para cada proceso eleccionario, se realizó un cálculo de correlación y un modelo de regresión lineal.

Los 3 modelos indicaron una relación positiva y estadísticamente significativa entre el gasto electoral y los resultados electorales para los partidos políticos seleccionados. Esto demostraría que sí existe una influencia del gasto en publicidad digital y los resultados electorales de los partidos. Debido a que los 3 modelos ilustran la misma dinámica, se muestra acá solo uno de los modelamientos.

<img width="703" height="75" alt="image" src="https://github.com/user-attachments/assets/6d9b94f2-bfbd-4021-ad36-390689c40f85" />
<br>
<br>

## Correlación Gasto Digital - Resultado Electoral Elecciones Parlamentarias 2017

<img width="412" height="314" alt="image" src="https://github.com/user-attachments/assets/bdd06f96-65f8-41c0-b113-f05b900ecf80" />
<br>
<br>

## Regresión Lineal Gasto Digital - Resultado Electoral Elecciones Parlamentarias 2017


Posteriormente, se realiza un cálculo de correlación y de regresión lineal utilizando el promedio del gasto digital por partido y el promedio de los resultados electorales, con tal de observar de mejor manera las posibles dinámicas generales en los procesos analizados.

<img width="988" height="85" alt="image" src="https://github.com/user-attachments/assets/3544a3e1-a7e1-4e31-b1bc-c701915c8ad9" />
<br>
<br>

## Correlación Promedio Gasto Digital - Promedio Resultado Electoral

<img width="383" height="288" alt="image" src="https://github.com/user-attachments/assets/7c3401b3-c725-4297-bf46-d1c83069380f" />
<br>
<br>

## Regresión Lineal Promedio Gasto Digital - Promedio Resultado Electoral 


Teniendo ya la relación general entre gasto y en espacio digital y resultados electorales, se procede a modelar la relación, pero controlando por las variables intervinientes definidas.

<img width="501" height="538" alt="image" src="https://github.com/user-attachments/assets/8b624041-70b9-432b-bb78-9ffcfc4de79a" />
<br>
<br>

## Regresión lineal controlada por las variables intervinientes

Siendo las variables intervinientes:
- Antigüedad (partido_nuevo, con 0 indicando partido fundado antes del 2000, y 1 fundado posterior al 2000)
- Tamaño del partido por militancia
- Orientación ideológica del partido


Debido a que ideología pareciera no tener influencia en el modelo, se continúa con la realización de varios modelos y relaciones entre variables, identificando finalmente una relación entre ideología y gasto electoral.

<img width="495" height="392" alt="Captura de pantalla (249)" src="https://github.com/user-attachments/assets/4e606716-52e9-4d20-9d30-afe095816193" />
<br>
<br>

## Regresión Lineal Ideología - Gasto Digital por Partido


A partir de todo lo visto anteriormente, es posible estipular la conformación de una estructura causal que adopta la siguiente forma:

```
Ideología de Partido --> Gasto Digital --> Resultados Electorales
                                        ^
                                        |
                       Tamaño del partido por militantes
                            Antigüedad del partido
```
<br>
<br>

# Conclusiones

- Pareciera que una __mayor inversión en espacio digital afecta directamente al rendimiento electoral__ de los partidos, aún controlando por militancia, antigüedad y orientación política.
- De las variables de control, __militancia y antigüedad__ parecieran ser elementos relevantes para estudios posteriores.
  - __Ideología afectaría indirectamente__, pero igualmente requiere de una profundización posterior.
- El espacio digital es un factor influyente en procesos democráticos, por lo que es primordial promover la __estandarización, regulación y transparencia del registro y medición__ en la glosa de gastos.
