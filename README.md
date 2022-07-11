# Modelo de recomendación de profesionales médicos para una mejor experiencia de usuarios - Mentoria_DiploDatos2021
El proyecto tiene como objetivo resolver una problemática común en el mundo de la salud: la concentración de la demanda en unos pocos centros médicos. Esta disparidad entre la oferta y la demanda genera experiencias negativas en los usuarios del sistema (principalmente, una escasa disponibilidad de turnos).

Un modelo de recomendación que considere las características del paciente y su nivel de satisfacción podría lograr la descompresión de la demanda y mejorar la experiencia de los usuarios.


## Los datos
Si querés inspeccionar el conjunto de datos, lo encontrarás en https://github.com/CSilvi/Mentoria_DiploDatos2021/tree/main/Data

El dataset consistirá en tres tablas:

- Tabla consumos: consultas médicas, con id del centro médico y del paciente asociados.

- Tabla centros médicos: características de los centros médicos.

- Tabla pacientes: características de los pacientes.


## Contenidos

1. **Análisis y Visualización de Datos**

En esta etapa se consistirá en entender el problema de concentración de la demanda en unos pocos oferentes y
encontrar patrones de consumo que permitan generar propuestas para lograr una descompresión de la demanda
       
       - Notebook JupiteLab: https://github.com/CSilvi/Mentoria_DiploDatos2021/blob/main/Notebooks/An%C3%A1lisis_oferta_demanda.ipynb
       - Informe_1: https://github.com/CSilvi/Mentoria_DiploDatos2021/blob/main/Notebooks/Practico_1.ipynb
       
       
2. **Análisis Exploratorio y Curación de Datos**

En esta etapa de análisis exploratorio y curación de datos, se enfocará en feature engineering

       - Notebook JupiteLab: https://github.com/CSilvi/Mentoria_DiploDatos2021/blob/main/Notebooks/Pr%C3%A1ctico_2.ipynb
     

3. **Modelos Aprendizaje Automático**

En esta etapa e consistirá en aplicar algoritmos básicos para entender 
las características asociadas a los distintos segmentos de pacientes y centros médicos. Métricas y validación de resultados

       - Notebook JupiteLab: https://github.com/CSilvi/Mentoria_DiploDatos2021/blob/main/Notebooks/Pr%C3%A1ctico%203.ipynb
       - Informe_2: https://github.com/CSilvi/Mentoria_DiploDatos2021/blob/main/Informes/Informe_2_Exploracion_modelos_ML.docx

Se aplicaron dos modelos de clasificacion decision tree, logistic regression que tengan como target feature categoria_socio.
Para la construcción de los modelos: se dividir los datos en conjunto de entrenamiento y validación, cross-validation, grid-search.

4. **Modelos de Aprendizaje Supervisado**

En esta etapa consistirá en desarrollar algoritmos de recomendación

       - Notebook JupiteLab: https://github.com/CSilvi/Mentoria_DiploDatos2021/blob/main/Notebooks/Practico_4.ipynb
       - Informe_3: https://github.com/CSilvi/Mentoria_DiploDatos2021/blob/main/Informes/Informe_3_Modelo_de_Recomendacion.docx

5. **Modelos Aprendizaje No Supervisado**

En esta etapa que consistirá en explorar reglas de asociación.

       - Notebook JupiteLab: https://github.com/CSilvi/Mentoria_DiploDatos2021/blob/main/Notebooks/Practico_5.ipynb
       










