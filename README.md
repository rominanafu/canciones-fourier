# canciones-fourier

## Descripción 📑

Los algoritmos que identifican canciones generalmente se basan en el análisis
espectral del sonido. En este proyecto, utilizamos la Transformada Rápida de
Fourier (FFT) para descomponer las señales de audio y obtener su contenido
frecuencial. A partir de esta información, graficamos segmentos de frecuencias
y el espectrograma de cada una de las 10 canciones, lo cual nos permitió realizar
un análisis con el que clasificamos las canciones según su género musical,
diferenciando entre reggaetón e instrumental.

## Canciones 🎶

Cada canción está representada por segmentos de 5 segundos,
con una frecuencia de muestreo de 44,100 Hz. Los datos disponibles representan
las muestras de amplitud de la señal de audio digitalizada en esos segmentos.

## Procedimiento ⚙️

1. Investigación teórica de conceptos relevantes
2. Uso de *Mathematica* para la transformada de Fourier y realizar las gráficas correspondientes
3. Clasificación cualitativa de las canciones con los elementos anteriores

## Resultados 📋

| Canción | Clasificación  |
|---------|----------------|
| 1       | Instrumental   |
| 2       | Reggaetón      |
| 3       | Instrumental   |
| 4       | Instrumental   |
| 5       | Reggaetón      |
| 6       | Reggaetón      |
| 7       | Instrumental   |
| 8       | Instrumental   |
| 9       | Reggaetón      |
| 10      | Instrumental   |

