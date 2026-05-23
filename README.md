# Urban Flow - Sprint 2

## Objetivo

Aplicar técnicas de procesamiento de imágenes y OCR para relacionar
patentes detectadas con multas del dataset.

## Introducción y contexto

En este sprint se trabajó con imágenes asociadas a infracciones de
tránsito. Las imágenes fueron clasificadas, procesadas y analizadas
utilizando técnicas de visión por computadora.

A partir de transformaciones como escala de grises, suavizado Gaussian
Blur y detección de bordes con Canny, se buscó mejorar la calidad de
las imágenes para posteriormente aplicar OCR sobre las patentes.

Finalmente, las patentes detectadas fueron comparadas con el dataset de
multas utilizando un criterio de similitud del 80% o superior, con el
objetivo de identificar coincidencias válidas entre imágenes y datos.

## Sprint actual

Sprint_2

## Conclusión

A partir del procesamiento realizado se pudo observar que trabajar con
imágenes reales presenta múltiples dificultades, principalmente por la
calidad visual de algunas capturas y las limitaciones del OCR.

Si bien varias patentes pudieron detectarse correctamente, también se
obtuvieron casos donde el texto extraído contenía caracteres erróneos,
patentes incompletas o incluso palabras que no correspondían a una
matrícula vehicular. Esto demuestra que los modelos de OCR funcionan de
forma aceptable en imágenes claras, pero pueden deteriorar mucho su
precisión cuando existen problemas de iluminación, resolución o ruido.

Por otro lado, las transformaciones aplicadas sobre las imágenes
permitieron mejorar parcialmente los resultados de detección. El uso de
escala de grises, suavizado y detección de bordes ayudó a resaltar
ciertas zonas importantes de las imágenes antes de aplicar OCR.

Además, el uso de un criterio de similitud permitió tolerar pequeños
errores de reconocimiento y relacionar correctamente varias imágenes con
las multas originales del dataset.

En conclusión, el trabajo permitió integrar procesamiento de imágenes,
OCR y análisis de datos en un mismo flujo de trabajo, mostrando tanto
las posibilidades como las limitaciones de automatizar validaciones
visuales sobre datos reales.
