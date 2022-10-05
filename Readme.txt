
Descripción de las bases de datos:

Pima: 
Este conjunto de datos procede del Instituto Nacional de Diabetes y Enfermedades Digestivas y Renales. El objetivo del conjunto de datos es predecir de forma diagnóstica si un paciente tiene o no diabetes, basándose en determinadas mediciones diagnósticas incluidas en el conjunto de datos. La selección de estas instancias de una base de datos más amplia está sujeta a varias restricciones. En particular, todos los pacientes aquí son mujeres de al menos 21 años de edad de origen indio Pima. Los conjuntos de datos constan de varias variables médicas predictoras y una variable objetivo, el resultado. Las variables predictoras incluyen el número de embarazos que ha tenido la paciente, su IMC, su nivel de insulina, su edad, etc.

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

Wine:

Para cargar este conjunto de datos: 
from sklearn import datasets
wine = datasets.load_wine()
La descripción puede obtenerse aquí:
print(wine.DESCR)

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

