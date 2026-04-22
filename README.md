# Urban Flow - Sprint 1

## Objetivo
Analizar los datos de multas por exceso de velocidad y limpiarlos
para poder usarlos sin errores en un sistema nuevo.

## Introducción y contexto
El dataset proviene de un sistema viejo de radares en una zona
de Bélgica que limita con otros países. Como los datos vienen
de sistemas heredados, tienen problemas como formatos incorrectos,
valores faltantes y registros inconsistentes.

En este sprint se busca trabajar sobre esos datos para poder
entenderlos mejor y dejarlos listos para un uso posterior.

## Sprint actual
Sprint_1

## Conclusión

A partir del análisis del dataset se puede observar que existen varias
patentes con niveles similares de reincidencia, lo que indica que las
infracciones no están concentradas en un único infractor, sino
distribuidas entre distintos conductores.

En cuanto a los horarios, se identificó una mayor concentración de
infracciones durante la mañana, especialmente entre las 09:00 y las
10:00. Sin embargo, también se detectó una alta proporción de registros
en la hora 00:00. Esto no representa un comportamiento real, sino que
se debe a que las horas inválidas fueron reemplazadas por ese valor
durante el proceso de limpieza.

Algo similar ocurre con el análisis por mes, donde enero aparece como el
mes con mayor cantidad de infracciones. Esto se debe a que muchas fechas
inválidas fueron reemplazadas por un valor fijo (1932-01-01) durante el
proceso de limpieza, lo que genera una distorsión en la distribución
temporal.

Por otro lado, los gráficos de excesos de velocidad muestran una gran
dispersión en los valores, sin un patrón claro, especialmente en los
registros asociados a datos inválidos. Esto indica que los datos
inconsistentes no siguen una lógica definida y aportan ruido al
análisis.

En general, el dataset permite identificar ciertos patrones de
comportamiento en las infracciones, pero también evidencia problemas
importantes en la calidad de los datos, que deben ser considerados para
evitar interpretaciones erróneas.
