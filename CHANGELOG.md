# CHANGELOG

## Día 1 - Ejercicio 01

- Se creó la rama Sprint_3 a partir de Sprint_2.
- Se configuró el repositorio para trabajo versionado.
- Se verificó el acceso a los datasets generados previamente.
- Se actualizó la documentación inicial del Sprint 3.

## Día 2 - Ejercicio 02

- Se creó el directorio /content/remote_dvc para simular un remote DVC.
- Se inicializó DVC dentro del repositorio.
- Se configuró un remote local llamado local_remote.
- Se removió del tracking de Git la carpeta de imágenes de patentes.
- Se migraron las imágenes de patentes a DVC desde urban_flow/data/raw/imgs/urban_flow_plates.
- Se enviaron los datos versionados al remote local de DVC.

## Día 3 - Ejercicio 03

- Se diseñó el modelo lógico del dominio.
- Se definieron las entidades Vehiculo, Multa, Radar y Evidencia.
- Se representaron las relaciones solicitadas entre las entidades.
- Se validaron las columnas necesarias del dataset procesado.

## Día 4 - Ejercicio 04

- Se implementó la función procesar_fila_csv.
- Se mapeó una fila del CSV al modelo lógico definido previamente.
- Se validó la creación de objetos Multa, Vehiculo, Radar y Evidencia.

## Día 5 - Ejercicio 05

- Se diseñó el modelo relacional con SQLAlchemy ORM.
- Se definieron claves primarias para Vehiculo, Multa, Radar y Evidencia.
- Se incorporaron relaciones entre tablas.
- Se sobrescribió el método __repr__ para mejorar la legibilidad.
