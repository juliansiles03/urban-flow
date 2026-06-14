# Urban Flow - Sprint 3

## Objetivo

Profesionalizar la solución desarrollada en los sprints anteriores,
incorporando persistencia en base de datos relacional, uso de ORM,
versionado de datos y preparación para búsquedas avanzadas.

## Introducción y contexto

En los Sprints 1 y 2 se procesaron multas de tránsito e imágenes
asociadas a radares urbanos. En este Sprint 3 se parte de la rama
Sprint_2 y se migra la información procesada hacia una estructura más
robusta, utilizando SQLAlchemy, DVC y bases vectoriales.

## Sprint actual

Sprint_3

## Conclusiones Sprint 3

Durante el Sprint 3 se logró migrar exitosamente la información
procesada en los sprints anteriores hacia una arquitectura basada en
bases de datos relacionales y vectoriales.

Se incorporaron un total de 1547 multas, asociadas a 60 vehículos y
3 radares distintos. Además, se almacenaron 616 evidencias visuales,
lo que representa un 39.82% de las multas registradas. Esto demuestra
que una parte importante de las infracciones cuenta con respaldo visual,
aunque todavía existe un porcentaje considerable de registros sin
evidencia asociada.

El análisis de los datos permitió identificar vehículos con alta
reincidencia. La patente WEFLYN fue la que acumuló la mayor cantidad
de multas registradas, alcanzando un total de 38 infracciones.
También se observó que varias patentes concentran una cantidad
significativa de multas, evidenciando comportamientos recurrentes de
exceso de velocidad dentro del conjunto analizado.

Respecto de los dispositivos de control, los tres radares presentaron
niveles de actividad similares. El radar R01 registró la mayor cantidad
de infracciones con 399 multas, seguido por R02 con 393 y R03 con 384.
Esto indica una distribución relativamente homogénea de los controles
realizados por los radares presentes en el dataset.

Finalmente, la incorporación de SQLAlchemy permitió estructurar la
información en una base de datos relacional, mientras que OpenCLIP y
ChromaDB posibilitaron almacenar vectores de imágenes y realizar
búsquedas por similitud visual. Gracias a esta integración fue posible
recuperar información de vehículos a partir de imágenes de evidencia,
combinando técnicas de visión por computadora, bases vectoriales y
análisis de datos en una misma solución.
