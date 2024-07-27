# CNN-PyTorch
## Preguntas
### Parte 1
¿Por qué creen que es el mal rendimiento de este modelo?

El mal rendimiento de este modelo se debe principalmente a que está hecho de forma bastante simple, este está hecho para fines didácticos y no está optimizado para poder identificar imágenes de forma eficiente, sino que prioriza la rapidez.

¿Qué cosas pueden hacer para mejorarlo?

El principal cambio que se le puede aplicar a dicho modelo es una variación en las capas y neuronas. Es posible también realizar una prueba con diferentes hiperpárametros para poder buscar un resultado más óptimo.

¿Cuáles son las razones para que el modelo sea tan lento?

Este tipo de modelos suelen ser realizados de forma paralela, el hecho de realizarlo de forma serial hace que el modelo sea mucho más lento.

### Parte 2
¿Qué haría para mejorar el rendimiento del modelo?

Comenzaría alterando los hiperparámetros, como el learning rate, el batch size, el número de capas y neuronas, entre otros. También se podría realizar un aumento del tamaño de las imágenes para poder tener un mejor modelo.
También se podría aumentar el número de épocas (aunque, debido a la gráfica, parece que no tendría un mayor impacto).

¿Qué haría para disminuir las posibilidades de overfitting?

Hay varias formas de disminuir el overfitting, una de ellas es aumentar el tamaño del dataset, también se podría realizar un aumento de las imágenes, o bien, se podría realizar un aumento de las capas de dropout.
