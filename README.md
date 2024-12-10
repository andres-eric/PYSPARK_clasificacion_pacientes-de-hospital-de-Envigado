### **PYSPARK_clasificacion_pacientes-de-hospital-de-Envigado**

**Análisis de Pacientes Atendidos en un Hospital con KMeans**

Descripción del Proyecto
Este proyecto utiliza un conjunto de datos de pacientes atendidos en un hospital en Envigado para realizar un análisis de clustering utilizando el algoritmo KMeans implementado con PySpark. Además, se crea un modelo predictivo basado en PySpark para predecir el grupo al que pertenece cada paciente, utilizando como variable objetivo el clúster asignado.

Las clasificaciones se basan en la vulnerabilidad económica y social de los pacientes, tomando como variables de importancia la edad, el estado civil y el nivel de educación. A partir de estas características, se clasificó a los pacientes en dos grupos principales:

- Necesidad moderada de apoyo

- Alta necesidad de apoyo

**Fuente de Datos**

Los datos se obtuvieron de Datos Abiertos de Colombia.

Columnas del Conjunto de Datos **:**

- **SEXO** : Sexo del paciente.

- **ESTADO_CIVIL** : Estado civil del paciente.

- **ZONA_RES** : Zona de residencia.

- **MUN_RES** : Municipio de residencia.

- **PAIS_NCTO** : País de nacimiento.

- **EDAD** : Edad del paciente.

- **ESCOLARIDAD_PACIENTE** : Nivel de escolaridad del paciente.

### **METODOLOGIA**

**1. Preprocesamiento de Datos**

Conversión de variables categóricas a variables numéricas mediante transformaciones en PySpark.

Estandarización de la variable numérica EDAD utilizando StandardScaler de PySpark ML.

2. Clustering con KMeans

Se utiliza el algoritmo KMeans de PySpark ML para dividir a los pacientes en 5 clústeres.

3. Modelo Predictivo

Se entrena un modelo de clasificación basado en PySpark ML para predecir el clúster al que pertenece cada paciente.

Resultados

Clustering: Los pacientes fueron agrupados en 5 clústeres, cada uno representando un tipo específico de características.

Predicción: El modelo predictivo alcanza una alta precisión para predecir el clúster de cada paciente.
