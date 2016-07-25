# ShelterAnimalsOutcomes
El objetivo de este proyecto es ayudar a los refugios de animales a predecir el futuro de los animales que llegan a ellos, 
con el objetivo de concentar sus fuerzas en animales especificos que necesitan un poco de ayuda extra para encontrar un hogar.

## Datos
Los datos utilizados en este proyecto provienen de [Kaggle - Shelter Animals Outcomes](https://www.kaggle.com/c/shelter-animal-outcomes/data "Title"),
que a su vez, fueron provistos por el refugio [Austin Animal Center](http://www.austintexas.gov/department/animal-services).

Los archivos proporcionados por el refugio son:
- test.csv
- train.csv

## Resumen
Se realizó una exploración de los datos encontrando que las características de "Tipo de animal", "Edad", "Sexo", y si el animal
es esteril, pueden ser usadas para predecir el futuro de los nuevos animales.

Tambíen se realizó una limpieza de los datos, y se cambiaron las columnas que contenian texto por numeros enteros para trabajar 
con un modelo de svc linear.
