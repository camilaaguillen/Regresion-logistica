# Regresion-logistica

En este proyecto trabajé con un conjunto de datos financieros para predecir si habría ganancia positiva o no. Primero importé los datos y creé una variable binaria llamada target, que vale 1 si la ganancia es mayor a cero y 0 en caso contrario.

Después revisé cómo estaban distribuidas las clases y dividí los datos en entrenamiento y prueba, manteniendo el balance de clases para que ambas particiones fueran representativas. Entrené un modelo de regresión logística usando inicialmente un subconjunto de variables y validación cruzada para medir la exactitud promedio, y luego ajusté un modelo final con todas las variables de entrenamiento.

Con este modelo generé probabilidades para los datos de prueba y evalué su desempeño usando matrices de confusión y métricas como exactitud, sensibilidad y especificidad bajo distintos umbrales. Además, tracé la curva ROC y calculé el AUC para ver qué tan bien el modelo discrimina entre ganancias y no ganancias.

Finalmente, los coeficientes del modelo permitieron identificar qué variables aumentan o disminuyen el log-odds de obtener ganancia, y los resultados muestran cómo ajustar el umbral afecta la sensibilidad y la especificidad según la estrategia que se quiera seguir.


- [Reporte en formato ipynb](./jupiter21.ipynb)
- [Reporte en formato html](./html21.html)
- [Base de datos](./datos21.csv)
