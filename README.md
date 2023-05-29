# 🏇 **KAGGLE competition.**

![portada](https://github.com/dapafer/...)

Este proyecto tiene como objetivo predecir el precio de portátiles, en base a sus caractertísticas. Teniendo en cuenta las variables, realizaremos un Análisis Exploratorio de los Datos (EDA), para validar el contenido del dataframe, y realizar las correspondientes transformaciones a los datos. Teniendo el contenido limpio y transformado, procederemos a entrenar los datos, para posteriormente aplicar el modelo, y generar predicciones.

---
## 📌 **Índice.**

- [Contenido.](#cont)
- [Objetivos.](#objs)
- 

---
<a name="cont"/>

###  **Contenido.**

El proyecto cuenta con los siguientes archivos principales:

- `EDA.ipynb`: notebook en el que se ha realizado el análisis de los datos facilitados, y se ha ejecutado la correspondiente transformación de los mismos, para posteriormente ejecutar el entrenamiento.
- `train_pred.ipynb`: notebook donde, teniendo los datos limpios y transformados, se ejecutan el entrenamiento para generar predicciones.
- `Price_pred_1, Price_pred_2`: archivos con las predicciones generadas, para subir a la competeición creada en Kaggle.

---
<a name="objs"/>

### **Objetivos.**

Teniendo el contenido de los datos facilitados ya limpios y transformados, procedemos a:

- Generar las particiones correspondientes para "entrenar" y "testear" con `Train Test Split`.
- Aplicar `Lazy Predict` para ver qué modelo es el más adecuado, teniendo la estructura de datos correspondiente.
- Ejecutar el modelo que puede llegar a funcionar mejor, en este caso `GBR` (Gradient Boosting Regressor).

Para finalizar, subimos las predicciones generadas a la competición creada en Kaggle, para registrar la participación, y competir con los demás compañeros.

---


