# Investigación sobre Predicción de Rendimiento Académico

## Introducción
El tema del rendimiento académico estudiantil es especialmente importante para el reciente Área de Bienestar del curso. Es por esto que surge la idea de capturar aquellos casos de estudiantes que tengan más posibilidades de reprobar, en base a predicciones sobre su rendimiento académico.

En el presente documento se proponen las siguientes preguntas a responder:
- ¿Cuáles son los **atributos** importantes usados en predecir el desempeño de estudiantes?
- ¿Cuáles son los **métodos** usados actualmente para predecir el desempeño de estudiantes?

Luego de evaluadas distintas respuestas, se tomarán aquellas que vayan más acorde al contexto del curso Programación Avanzada, se propondrá una solución a partir de los datos actuales, y se propondrá un acercamiento distinto a futuro.

Toda la información expuesta fue obtenida a partir de la lectura de papers relacionados.

## Atributos de importancia
A lo largo de los documentos vistos, los atributos que más influencia parecen tener sobre el rendimiento académico, y que son de utilidad para el contexto del curso, son:
- Promedio acumulado (PPA)
- Carrera
- Créditos aprobados
- Créditos tomados el semestre que se cursa IIC2233
- Cursos aprobados del DCC


## Métodos conocidos y candidatos a usar
A partir de la lectura de papers relacionados a distintas técnicas usadas, se encontró que los métodos más efectivos utilizados son **Redes Neuronales**, **Árboles de Decisión** y **Naive Bayes**.


## Aterrizaje de conocimientos: Atributos y métodos posibles
El acceso actual a datos pasados permite obtener únicamente las calificaciones durante los semestres y posiblemente el tiempo en semestres que pasó desde cursar Introducción a la Programación y Programación avanzada (a partir del número de alumno). Sin embargo, al no conocer la carrera de origen de los estudiantes, este último atributo no es de confianza.

Por lo tanto, se debe experimentar usando solo una o dos notas de calificaciones para predecir el promedio final, mediante los distintos métodos propuestos.

## Desafíos a futuro
Una vez se logre conseguir acceso a datos pertinentes, o se consiga una cantidad suficiente de estos, se deberá pasar a una etapa de pruebas, con una esperable mayor precisión en las predicciones.


Por probar:
- Naive Bayes
- Árbol de Decisión