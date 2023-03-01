# **Estudio de atención en salud**

## Introducción

Este proyecto consta de tres fases:

#### `1. Análisis exploratorio de datos`
#### `2. Transformar y preparar los datos adecuadamente`
#### `3. Modelamiento y evaluación`

## Todo
- [ ] Entender la problemática y comprender los datos.
- [ ] Realizar el análisis exploratorio de los datos y prepararlos para el siguiente TO-DO.
- [ ] Experimentar con los modelos de machine learning en un contexto real.
- [ ] Usar las métricas correspondientes para medir el performance de los modelos.
- [ ] Seleccionar el mejor modelo.



### 1. Análisis exploratorio de los datos

Conseguiremos informacion a partir de los datos, por ejemplo, de historias clínicas o registros de prestadores de servicios de salud. De esta manera, se pueden emitir diagnósticos predictivos, evaluar la efectividad de estrategias de intervención y anticipar comportamientos en escenarios relacionados con la atención.

## Planteamiento de la problematica.
  **Nuestro cliente desea saber las características más importantes que tienen los pacientes de cierto tipo de enfermedad que terminan en hospitalización.** Fue definido como caso aquel paciente que fue sometido a biopsia prostática y que en un periodo máximo de 30 días posteriores al procedimiento presentó fiebre, infección urinaria o sepsis; requiriendo manejo médico ambulatorio u hospitalizado para la resolución de la complicación y como control al paciente que fue sometido a biopsia prostática y que no presentó complicaciones infecciosas en el período de 30 días posteriores al procedimiento.
  
  Dado que tienen en su base de datos algunos datos referentes a los pacientes y resultados de exámenes diagnósticos, de pacientes hospitalizados y no hospitalizados, nos han entregado esta información.  

Para ello, nuestro departamento de datos ha recopilado:
- `Antecedentes del paciente`
- `Morbilidad asociada al paciente`
- `Antecedentes relacionados con la toma de la biopsia`
- `Complicaciones infecciosas`

En la siguiente tabla, se encuentra un diccionario de datos asociado:

![image](https://user-images.githubusercontent.com/118769777/220240501-8c21461d-2de5-495b-954e-10fb9bf38014.png)


## Consideraciones

- Mantener todo ordenado.
- Formato py o ipynb.
- Explicar claramente cada paso realizado mediante comentarios o markdown.
- Cualquier persona debe entender de la mejor manera posible cada razonamiento y pasos aplicados.
- README acorde que sirva de introducción.

## El cliente desea saber:

+ **Las características más importantes que tienen los pacientes de cierto tipo de enfermedad que terminan hospitalizados.**

+ **Crear un modelo predictivo de clasificación para la variable objetivo:** `Hospitalización`.
