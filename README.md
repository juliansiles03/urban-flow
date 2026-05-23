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
