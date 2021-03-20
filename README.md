# AprendizajeProfundo

## Performance obtenido 

Balanced accuracy: 0.848
Loss: 0.648

## Reporte

Probé el modelo modificando los hiperparametros hidden layers, epochs, dropout, 
batch size y freez embeddings. 

Epochs: Al comienzo, aumente a 4 los epoch y con esto aumentó el balanced accuracy pero su curva tiende a aplanarse y por lo que creo que no mejorará significativamente probando con más. 

Hidden layers: Me dio un poco mejor resultado con menos nodos. 

Dropout: Si aumentaba o disminuía el dropout me daba más bajo el balanced accuracy por lo que decidí dejarlo en 0.3. 

Batch size: Disminuyendo el batch size mejoró un poco el modelo. 

Freez embeddings y Batch size: Por ultimo probe no hacer freez embeddings y bajar un poco más el batch size. Con estos cambios el balance accuracy paso de 0.417 a 0.848 y loss de 2.782 a 0.648. Deje de probar porque tardo mas de 4hs.
