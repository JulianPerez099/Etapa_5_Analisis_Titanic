# Etapa_5_Analisis_Titanic

El modelo inicial de árbol de decisiones demostró una precisión notable, con 827 predicciones
correctas, representando un 92,817% de exactitud en sus pronósticos. No obstante, se identificaron 29
falsos positivos y 35 falsos negativos, evidenciando errores en la clasificación de ciertos casos como
positivos o negativos.
Después de concluir el proceso de análisis de datos, se evaluaron los resultados iniciales y se
determinó que, aunque el modelo mostraba un rendimiento generalmente bueno, aún existía margen de
mejora. Para optimizar el modelo, se implementaron las siguientes modificaciones:
✓ Eliminación de filas con valores faltantes en las columnas "Age" y "Cabin" para gestionar de
manera más efectiva los datos incompletos.
✓ Establecimiento de reglas para asignar etiquetas basadas en condiciones específicas, capturando
patrones relacionados con género, tarifa, edad y la presencia de familiares, influyendo en la
probabilidad de supervivencia.
Posterior a estas modificaciones, se observó una mejora significativa en el análisis de datos. La
métrica de precisión aumentó a 94,054%, el error general disminuyó a 5,946%, y el coeficiente de
Cohen's kappa aumentó a 0,866%, indicando una contribución positiva de las modificaciones al
rendimiento del modelo.
En el análisis técnico de la matriz de confusión, se evidenció que el modelo acertó en predecir
correctamente la supervivencia de 56 pasajeros y la no supervivencia de 118. A pesar de ello, se
cometieron 7 errores de falsos positivos y 4 de falsos negativos. Comparando con los resultados iniciales,
se destaca una reducción en el número de falsos positivos y negativos, indicando una mejora en la
capacidad del modelo para prever correctamente la supervivencia de los pasajeros.
