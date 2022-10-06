
Descripción de las bases de datos:

-------------------------------------------------------------------------------------------------------------------------------------------------------
Pima: 
Este conjunto de datos procede del Instituto Nacional de Diabetes y Enfermedades Digestivas y Renales. El objetivo del conjunto de datos es predecir de forma diagnóstica si un paciente tiene o no diabetes, basándose en determinadas mediciones diagnósticas incluidas en el conjunto de datos. La selección de estas instancias de una base de datos más amplia está sujeta a varias restricciones. En particular, todos los pacientes aquí son mujeres de al menos 21 años de edad de origen indio Pima. Los conjuntos de datos constan de varias variables médicas predictoras y una variable objetivo, el resultado. Las variables predictoras incluyen el número de embarazos que ha tenido la paciente, su IMC, su nivel de insulina, su edad, etc.

-------------------------------------------------------------------------------------------------------------------------------------------------------
Housing: 
Cada registro de la base de datos describe un suburbio o ciudad de Boston. Los datos se extrajeron del área estadística metropolitana estándar de Boston (SMSA) en 1970. Los atributos se deﬁnen de la siguiente manera (tomados del Repositorio de Aprendizaje Automático de la UCI):

CRIM: tasa de criminalidad per cápita por ciudad
ZN: proporción de terrenos residenciales con una superficie superior a 25.000 pies cuadrados.
INDUS: proporción de acres comerciales no minoristas por ciudad
CHAS: variable ficticia del río Charles (= 1 si la zona linda con el río; 0 en caso contrario)
NOX: concentración de óxidos nítricos (partes por 10 millones)
RM: número medio de habitaciones por vivienda
EDAD: proporción de unidades ocupadas por sus propietarios construidas antes de 1940
DIS: distancias ponderadas a cinco centros de trabajo de Boston
RAD: índice de accesibilidad a las autopistas radiales
TAX: tasa del impuesto sobre la propiedad por cada 10.000 dólares
PTRATIO: ratio alumno-profesor por zona de la ciudad 
MEDV: Valor medio de las viviendas ocupadas por sus propietarios en miles de dólares
Podemos ver que los atributos de entrada tienen una mezcla de unidades.

-------------------------------------------------------------------------------------------------------------------------------------------------------
Wine:

Para cargar este conjunto de datos: 
from sklearn import datasets
wine = datasets.load_wine()
La descripción puede obtenerse aquí:
print(wine.DESCR)



-------------------------------------------------------------------------------------------------------------------------------------------------------
Adult:

La extracción fue realizada por Barry Becker a partir de la base de datos del censo de 1994. Se extrajo un conjunto de registros razonablemente limpios utilizando las siguientes condiciones: ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0)). La tarea de predicción consiste en determinar si una persona gana más de 50.000 dólares al año.

Información de las variables 
Listado de atributos:

>50K, <=50K.

edad: continua.
clase de trabajo: Privado, Autónomo-no-inc, Autónomo-inc, Federal-gov, Local-gov, Estatal-gov, Sin-pago, Nunca-trabajó.
fnlwgt: continuo.
educación: Bachillerato, Algún tipo de universidad, 11º, Grado de secundaria, Escuela profesional, Asistente de dirección, Asistente de dirección, 9º, 7º-8º, 12º, Máster, 1º-4º, 10º, Doctorado, 5º-6º, Preescolar.
education-num: continuous.
estado civil: Casado-cónyuge, Divorciado, No casado, Separado, Viudo, Casado-cónyuge-ausente, Casado-cónyuge.
Ocupación: Apoyo técnico, Reparación artesanal, Otros servicios, Ventas, Directivo, Especialidad profesional, Manipulador-limpiador, Operador de maquinaria, Administrativo-empleado, Agricultura-pesca, Transporte-movimiento, Servicio doméstico privado, Servicio de protección, Fuerzas armadas.
Relación: Esposa, Hijo propio, Esposo, No familiar, Otro pariente, Soltero.
Raza: Blanco, Asiático-Pacífico-Islandés, Amerindio-Esquimal, Otro, Negro.
Sexo: Mujer, Hombre.
plusvalía: continua.
pérdida de capital: continua.
horas-semana: continuo.
país de origen: Estados Unidos, Camboya, Inglaterra, Puerto Rico, Canadá, Alemania, EE.UU. periférico (Guam-USVI-etc), India, Japón, Grecia, Sur, China, Cuba, Irán, Honduras, Filipinas, Italia, Polonia, Jamaica, Vietnam, México, Portugal, Irlanda, Francia, República Dominicana, Laos, Ecuador, Taiwán, Haití, Colombia, Hungría, Guatemala, Nicaragua, Escocia, Tailandia, Yugoslavia, El Salvador, Trinad&Tobago, Perú, Hong, Holanda.

-------------------------------------------------------------------------------------------------------------------------------------------------------

CMC:
Este conjunto de datos es un subconjunto de la Encuesta Nacional de Prevalencia de Anticonceptivos de Indonesia de 1987. Las muestras son mujeres casadas que no estaban embarazadas o no saben si lo estaban en el momento de la entrevista. El problema es predecir la elección del método anticonceptivo actual (no uso, métodos de larga duración o métodos de corta duración) de una mujer en función de sus características demográficas y socioeconómicas.


Información de atributos:

1. Edad de la mujer (numérica)
2. Educación de la esposa (categórica) 1=baja, 2, 3, 4=alta
3. Educación del marido (categórica) 1=baja, 2, 3, 4=alta
4. Número de hijos nacidos (numérico)
5. Religión de la esposa (binario) 0=no islámico, 1=islámico
6. ¿La esposa trabaja ahora? (binario) 0=Sí, 1=No
7. Ocupación del marido (categórica) 1, 2, 3, 4
8. Índice de nivel de vida (categórico) 1=bajo, 2, 3, 4=alto
9. Exposición a los medios de comunicación (binario) 0=buena, 1=no buena
10.Método anticonceptivo utilizado (atributo de clase) 1=No uso, 2=Largo plazo, 3=Corto plazo

-------------------------------------------------------------------------------------------------------------------------------------------------------
mtcars:

Los datos fueron extraídos de la revista Motor Trend US de 1974, y comprenden el consumo de combustible y 10 aspectos del diseño y rendimiento de los automóviles para 32 automóviles (modelos de 1973-74). 32 observaciones sobre 11 variables.

mpg: Millas/(US) galón
cyl: Número de cilindros
disp: Cilindrada (cu.in.)
CV: Potencia bruta
drat: Relación del eje trasero
wt: Peso (1000 lbs)
qsec: Tiempo de 1/4 de milla
vs: V/S
am: Transmisión (0 = automática, 1 = manual)
marcha: Número de marchas
carburador: Número de carburadores

-------------------------------------------------------------------------------------------------------------------------------------------------------
Life Expectancy:
Se han realizado muchos estudios en el pasado sobre los factores que afectan a la esperanza de vida teniendo en cuenta las variables demográficas, la composición de los ingresos y las tasas de mortalidad. Se descubrió que en el pasado no se tuvo en cuenta el efecto de la inmunización y el índice de desarrollo humano. Además, algunas de las investigaciones anteriores se realizaron teniendo en cuenta la regresión lineal múltiple basada en un conjunto de datos de un año para todos los países. Por lo tanto, esto nos motiva a resolver los dos factores mencionados anteriormente formulando un modelo de regresión basado en un modelo de efectos mixtos y una regresión lineal múltiple, considerando los datos de un período de 2000 a 2015 para todos los países. También se tendrá en cuenta la inmunización importante, como la hepatitis B, la poliomielitis y la difteria. En resumen, este estudio se centrará en los factores de inmunización, los factores de mortalidad, los factores económicos, los factores sociales y otros factores relacionados con la salud. Dado que las observaciones de este conjunto de datos se basan en diferentes países, será más fácil para un país determinar el factor de predicción que está contribuyendo a un menor valor de la esperanza de vida. Esto ayudará a sugerir a un país a qué área se debe dar importancia para mejorar eficazmente la esperanza de vida de su población.

El proyecto se basa en la precisión de los datos. El repositorio de datos del Observatorio Global de la Salud (GHO), dependiente de la Organización Mundial de la Salud (OMS), realiza un seguimiento del estado de salud y de muchos otros factores relacionados con todos los países. El conjunto de datos relacionados con la esperanza de vida y los factores de salud de 193 países se ha recogido del mismo sitio web del repositorio de datos de la OMS y los datos económicos correspondientes se han recogido del sitio web de las Naciones Unidas. Entre todas las categorías de factores relacionados con la salud, sólo se eligieron los factores críticos que son más representativos. Se ha observado que en los últimos 15 años se ha producido un enorme desarrollo en el sector sanitario que ha dado lugar a una mejora de las tasas de mortalidad humana, especialmente en los países en desarrollo, en comparación con los últimos 30 años. Por lo tanto, en este proyecto hemos considerado los datos del año 2000-2015 de 193 países para su posterior análisis. Los archivos de datos individuales se han fusionado en un único conjunto de datos. En la inspección visual inicial de los datos se observaron algunos valores que faltaban. Como los conjuntos de datos eran de la OMS, no encontramos errores evidentes. Los datos que faltaban se trataron en el software R utilizando el comando Missmap. El resultado indicó que la mayoría de los datos que faltaban correspondían a la población, la hepatitis B y el PIB. Los datos que faltaban eran de países menos conocidos como Vanuatu, Tonga, Togo, Cabo Verde, etc. Fue difícil encontrar todos los datos de estos países, por lo que se decidió excluirlos del conjunto de datos del modelo final. El archivo final fusionado (conjunto de datos final) consta de 22 columnas y 2.938 filas, lo que supone 20 variables de predicción. Todas las variables de predicción se dividieron en varias categorías generales: factores relacionados con la inmunización, factores de mortalidad, factores económicos y factores sociales.


-------------------------------------------------------------------------------------------------------------------------------------------------------
CALIFORNIA:

import sklearn.datasets

data = sklearn.datasets.fetch_california_housing(return_X_y=False, as_frame=True)
data = data["frame"]
print(data)

Este es el conjunto de datos utilizado en el segundo capítulo del reciente libro de Aurélien Géron 'Hands-On Machine learning with Scikit-Learn and TensorFlow'. Sirve como una excelente introducción a la implementación de algoritmos de aprendizaje automático porque requiere una limpieza de datos rudimentaria, tiene una lista de variables fácilmente comprensible y se sitúa en un tamaño óptimo entre ser demasiado juguetón y demasiado engorroso.

Los datos contienen información del censo de California de 1990. Por lo tanto, aunque no pueda ayudar a predecir los precios actuales de la vivienda como el conjunto de datos Zillow Zestimate, proporciona un conjunto de datos introductorio accesible para enseñar a la gente los fundamentos del aprendizaje automático. Los datos se refieren a las casas que se encuentran en un determinado distrito de California y algunas estadísticas resumidas sobre ellas basadas en los datos del censo de 1990. Hay que tener en cuenta que los datos no están depurados, por lo que se requieren algunos pasos de preprocesamiento. Las columnas son las siguientes, sus nombres son bastante autoexplicativos:

longitud
latitud
housingmedianage
total_habitaciones
total_habitaciones
población
hogares
ingresos_medios
valor medio de la vivienda
proximidad al mar

-------------------------------------------------------------------------------------------------------------------------------------------------------
OpenML

Datos comunicados a la policía sobre las circunstancias de los accidentes de tráfico con lesiones personales en Gran Bretaña desde 1979, así como la información sobre el fabricante y el modelo de los vehículos implicados en el respectivo accidente.

Esta versión incluye datos hasta 2015.

from sklearn.datasets import fetch_openml
dataset = fetch_openml(data_id=42803, as_frame=True)
df_X = dataset["frame"]
