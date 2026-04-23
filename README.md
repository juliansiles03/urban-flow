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

En cuanto a los horarios, se observa una proporción muy alta de
registros en la hora 00:00. Esto no representa un comportamiento real,
sino que se debe a que las horas inválidas fueron reemplazadas por ese
valor durante el proceso de limpieza. Si se deja de lado ese grupo, el
resto de las infracciones se distribuye de manera bastante pareja entre
distintas horas del día, sin una concentración tan marcada.

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

En resumen, si bien el dataset permite identificar ciertos patrones de
comportamiento en las infracciones, evidencia numerosos problemasen la
calidad de los datos. Es por este motico que considero que no sería una 
base de datos del todo confiable para sacar conclusiones y realizar 
predicciones sin antes realizar una limpieza mas profunda. 
