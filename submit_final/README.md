# Laboratorio de Implementación I | Workflow final

Estimados,
En esta carpeta encontrarán el notebook con el que pueden correr y simular nuestro submit final en Kaggle.

## Características

- Semilla primigenia: 600167
- N° Experimento: 9101
- Optimización Bayesiana con 100 iteraciones guardadas en el repositorio.
- Ensemble de K = 25 semillas a partir de la semilla primigenia.
- Cantidad de envíos: 2000

Se seleccionó la semilla que presentaba el menor desvío estándar entre las ganancias de las distintas cantidades de envíos (S = 88) y la cantidad de envíos que presentaba el menor desvío estándar entre las semillas utilizadas (S = 23).
Para modificar el código nos basamos en los resultados de algunos experimentos colaborativos, en particular:
- Excluir los campos numero_de_cliente y foto_mes para el modelado.
- Realizar undersampling con training_pct <- 0.5
- Tomar AUC como métrica y GBDT como método.
- Ponderar los años.
- Variables de feature engineering creadas por nosotros en el Experimento #03.

## Autores

Baltazar Villanueva
Fernando Paganini
