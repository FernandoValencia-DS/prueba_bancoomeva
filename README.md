# Prueba Técnica Identificación de operaciones inusuales o sospechosas.

Candidato: Fernando Jose Valencia Marin

## Contexto del Problema
El banco necesita mejorar su sistema de monitoreo transaccional para identificar posibles actividades relacionadas con lavado de activos o financiamiento del terrorismo. Actualmente existen muchas alertas falsas positivas, baja capacidad de detectar nuevas tipologías y tiempos lentos de análisis manual.

## Resultados
Se entrenaron 2 modelo, el modelo principal **CatBoost** y un modelo base **Regresión logística**. El modelo **CatBoost** demostró una mejora significativa al modelo de **Regresión logística**, especialmente reduciendo hasta la mitad el número de falsos positivos, cumpliendo con el objetivo planteado.
