# osic-pulmonary-fibrosis-progression

> OSIC Pulmonary Fibrosis Progression: Predict lung function decline competition.

https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression/overview

## Primeros pasos

Para descargar los datos de la competición de kaggle y descomprimir los archivos necesarios para la ejecucción de los ipynb:

``` shell
$ ./get_data.sh
```

## Contenido

- 01train_vs_test_csv -> Análisis datos train & test
- 02casos_hops_uci_gob -> Análisis datos casos COVID19 España
- 03imagenes-dicom -> Análisis imágenes
- 04pulmonary-dicom-preprocessing -> Análisis imágenes extendido
- 05modelo-final -> Modelo multicapa + Combinado CNN
- src/csv -> Archivos casos COVID-19 España
- osic-pulmonary-fibrosis-progression -> archivos competición (sin imágenes)