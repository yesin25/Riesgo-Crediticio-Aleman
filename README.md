# Riesgo-Crediticio-Aleman
# Primer análisis
Análisis predictivo de datos crediticios alemanes para determinar el riesgo crediticio de una cuenta determinada,cuya variable objetivo es Risk.
# Paso 1 Análisis descriptivo
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/2d7c081c-4fb2-4c35-a61b-04dcac190732)
# Paso 2 Imputación de la data
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/d8d26a59-4a4b-4520-80a8-5cc655110f1b)
# Paso 3 Ordenamiento de variables cuantitativas y cualitativas
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/cb1ef146-07e5-4694-aa7f-2e0b2b3deffe)
# Paso 4 Recodificación de variables categóricas
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/5286ff7d-6abc-4759-be33-2d5e27f95b1a)
# Paso 5 Correlación de variables por rangos de spearman
Se quitará en el modelo la variable correlacionada por el filtro, Credit_amount 
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/7ffb0e4a-3a4a-426a-b2c3-44e133dd71fe)
# Paso 6 Convirtiendo a factor
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/b76412c8-a821-477d-baaa-487d04a5a5e0)
# Paso 7 modelo 1 y cálculo de indicadores Gini 39.34 y KS 29.86
Usando funciones.r
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/294b12b5-0309-469b-8bc9-6dd2337b3603)
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/ce70d1cb-a4b1-4f2f-9e44-2381778beab2)
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/4ecda592-978b-4c6c-90d8-983231a848e5)
# Paso 8 modelo 2 y cálculo de indicadores Gini 39.16 y KS 29.52
Se removió la variable Job
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/d70977aa-b0cb-467f-bd5a-e30b814cc995)
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/80f729ae-3d70-4ecd-b308-f99786a0915b)
# SegundO análisis
# Paso 9 Categorizando variables por arboles sin imputar
Se usa funciones2.r para generar los pdf y se requiere como imput data_train_2 que es la misma de train inicial sin imputar, luego se recodificará creando una variable data_train_2_f
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/15a9cf84-0074-4339-bc4a-2b958a8fc0aa)
# Paso 10 modelo 3 y cálculo de indicadores Gini 55.18 y KS 42.43
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/a9a7c1f3-bdfa-494e-8742-1f426682ae77)
![image](https://github.com/yesin25/Riesgo-Crediticio-Aleman/assets/47453948/3599f73e-0923-4c6e-9ac7-3a73540d2fb3)
