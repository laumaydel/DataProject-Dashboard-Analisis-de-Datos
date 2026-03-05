# Riesgo Cardiovascular en España: Análisis Exploratorio de Factores de Salud y Estilo de Vida

## DESCRIPCIÓN
Las enfermedades cardiovasculares representan uno de los mayores desafíos para la salud pública en España. Aunque su aparición puede depender de múltiples factores, muchos de ellos están relacionados con características demográficas, hábitos de vida y condiciones clínicas que pueden ser analizadas mediante datos. 
En este proyecto se realiza un análisis exploratorio de un conjunto de datos obtenido de la web Kaggle, al que puede accedese en el siguiente enlace: https://www.kaggle.com/datasets/danicruzdevtech/datasets-sintticos-de-salud-diabetes-cardio/data . El objetivo es identificar patrones y relaciones entre distintas variables de salud y estilo de vida. 
Durante el análisis se examinan factores como la edad, actividad física, índice de masa corporal (IMC), niveles de colesterol, presión arterial, estrés, consumo de alcohol o ingresos, buscando entender cómo estos elementos pueden influir en los diferentes riesgos cardiovasculares.

## ESTRUCTURA DEL PROYECTO
Los documentos que pueden encontrarse en el repositorio son los siguiente: 
- db_cardio.csv  --> Dataset original descargado y sin modificar
- diario_diseno.pdf  --> Diario de diseño y decisiones tomadas durante el análisis  *
- dashboard_cardiovascular.xlsx  --> Dashboard interactivo en Excel
- README.md  --> Descripción del proyecto, objetivos y resultados principales

_*Importante:_ Dentro del "diario de diseño" están todos los pasos, indicaciones y consejos para poder replicar el estudios si se desea a partir de los datos *raw* que pueden encontrarse en esta mismo proyecto.

## VARIABLES 
A continuación se explican las más relevantes para el estudio, para poder ver todas leer el apartado análogo en el _diario de diseño_
1. Variable objetivo: Riesgo_Cardiovascular
Indica el nivel de riesgo cardiovascular estimado para cada individuo.
2. Variables demográficas: Edad, Sexo
  - Comunidad_Autonoma: Comunidad autónoma de residencia del individuo, utilizada para analizar posibles diferencias geográficas en el riesgo cardiovascular.

3. Variables de estilo de vida
- Actividad_Fisica: Nivel de actividad física habitual del individuo.
- Nivel_Estres: Nivel de estrés percibido por el individuo.
- Consumo_Alcohol: Frecuencia o nivel de consumo de alcohol.

4. Variables clínicas
- IMC (Índice de Masa Corporal): Indicador que relaciona peso y altura para estimar si el individuo se encuentra en un rango de peso saludable.
- Colesterol_Total: Nivel total de colesterol en sangre, asociado al riesgo de enfermedades cardiovasculares.
- PAS / PAD: Presión arterial sistólica (PAS) y diastólica (PAD), indicadores clave en la salud cardiovascular.

