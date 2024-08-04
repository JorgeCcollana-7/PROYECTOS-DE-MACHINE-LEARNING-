# Detección de Covid-19 mediante RANDOM FOREST VS REGRESION LOGISTICA
El avance tecnológico ha tenido un impacto profundo en todos los aspectos de la vida, incluyendo el ámbito médico. La inteligencia artificial, en particular, ha demostrado ser prometedora en la atención médica mediante el análisis y procesamiento de datos para la toma de decisiones. La detección temprana de enfermedades potencialmente mortales es crucial para prevenir su propagación y desarrollo. COVID-19, una enfermedad extremadamente contagiosa, ha causado una pandemia global que requiere una intervención rápida. La necesidad de un sistema eficaz para detectar el virus es evidente dada su rápida propagación. Con el aumento del uso de la tecnología, ahora tenemos acceso a una gran cantidad de datos sobre COVID-19 que pueden proporcionar información valiosa sobre el virus. En este proyecto, comparamos la precisión de varios algoritmos de aprendizaje automático para la predicción de COVID-19, y seleccionamos el algoritmo más preciso para el modelo final de prueba.
## Diccionario de Datos

### Breathing Problem

Descripción: Indica si el individuo tiene problemas respiratorios.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 3620
No: 1814

### Fever

Descripción: Indica si el individuo tiene fiebre.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 4273
No: 1161

### Dry Cough

Descripción: Indica si el individuo tiene tos seca.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 4307
No: 1127

### Sore throat

Descripción: Indica si el individuo tiene dolor de garganta.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 3953
No: 1481

### Running Nose

Descripción: Indica si el individuo tiene secreción nasal.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2952
No: 2482

### Asthma

Descripción: Indica si el individuo tiene asma.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2514
No: 2920

### Chronic Lung Disease

Descripción: Indica si el individuo tiene una enfermedad pulmonar crónica.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2565
No: 2869

### Headache

Descripción: Indica si el individuo tiene dolor de cabeza.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2736
No: 2698

### Heart Disease

Descripción: Indica si el individuo tiene una enfermedad cardíaca.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2523
No: 2911

### Diabetes

Descripción: Indica si el individuo tiene diabetes.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2588
No: 2846

### Hyper Tension

Descripción: Indica si el individuo tiene hipertensión.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2663
No: 2771

### Fatigue

Descripción: Indica si el individuo tiene fatiga.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2821
No: 2613

### Gastrointestinal

Descripción: Indica si el individuo tiene síntomas gastrointestinales.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2551
No: 2883

### Abroad travel

Descripción: Indica si el individuo ha viajado al extranjero.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2451
No: 2983

### Contact with COVID Patient

Descripción: Indica si el individuo ha estado en contacto con un paciente con COVID-19.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2726
No: 2708

### Attended Large Gathering

Descripción: Indica si el individuo ha asistido a una gran reunión.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2510
No: 2924

### Visited Public Exposed Places

Descripción: Indica si el individuo ha visitado lugares públicos expuestos.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2820
No: 2614

### Family working in Public Exposed Places

Descripción: Indica si algún miembro de la familia del individuo trabaja en lugares públicos expuestos.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 2262
No: 3172

### Wearing Masks

Descripción: Indica si el individuo usa mascarillas.
Tipo: Categórico (Sí/No)
Valores Únicos: No
Frecuencia:
No: 5434

### Sanitization from Market

Descripción: Indica si el individuo se ha desinfectado al regresar del mercado.
Tipo: Categórico (Sí/No)
Valores Únicos: No
Frecuencia:
No: 5434

### COVID-19

Descripción: Indica si el individuo ha sido diagnosticado con COVID-19.
Tipo: Categórico (Sí/No)
Valores Únicos: Sí, No
Frecuencia:
Sí: 4383
No: 1051

## CONCLUSION
El modelo de Random Forest muestra un rendimiento superior en la mayoría de las métricas clave comparado con el modelo de Regresión Logística:

### Mejor precisión en validación cruzada: 98.37% frente a 97.15%
### ROC AUC: 97.15% frente a 93.23%
### MSE: 2.48% frente a 3.04%
### R2 score: 83.71% frente a 80.09%
### Accuracy: 98.46% frente a 97.03%
### Recall (Clase 0): 97% frente a 87%
### F1-score (Clase 0): 94% frente a 92%
En particular, la mayor precisión en validación cruzada, el mayor ROC AUC, y la menor MSE sugieren que el modelo de Random Forest es más preciso y mejor para distinguir entre clases. 
