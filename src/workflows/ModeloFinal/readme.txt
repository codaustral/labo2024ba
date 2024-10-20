El modelo final es un ensamble de los siguientes modelos:

1.	KA-0005 https://github.com/labo-imp/labo2024ba/commit/62c6a0eb8875359b5feac7767146f0f87f55d28f
2.	KA-0009 https://github.com/labo-imp/labo2024ba/commit/3b7d43c842bc00335b1e5c50b35a86ee72ed38bf
3.	KA_0010 https://github.com/labo-imp/labo2024ba/commit/ffa7cd1d880ebba06308eb6052d253ec83a87ce7
4.	KA-0011 https://github.com/labo-imp/labo2024ba/commit/61bf3b1e92c9a4842cb2ee843073b5cf9ff44dcf
5.	KA-0012 https://github.com/labo-imp/labo2024ba/commit/9ac2449adf0662c09a78f6c728247c5f508d1ae2
6.	KA-0013 https://github.com/labo-imp/labo2024ba/commit/fc4860655906d915f522218035196f66856adc54
7.	KA_0014 https://github.com/labo-imp/labo2024ba/commit/57795b1ba55e0e39d5e79c428b36feed29160c6a

Pasos para replicar el resultado del modelo final:
1. Ejecutar los 7 script
2. Bajar los archivos resultantes de la corrida de cada script que contienen la predicción que se sube a Kaggle: expw_KA-XXXX_KA-XXXX_XX_XXX_sXXXXXX_XXXXX.csv  
3. Ordenar por número de cliente cada archivo
4. Consolidar en un excel los siete modelos
5. Agregar las columnas para realizar la votación. Ver archivo excel votacion_ensamble.xlsx en este repositorio
6. Crear archivo .csv con los resultados de la votación, con las columnas numero_de_cliente y Predicted
7. Comprimir archivo
8. Realizar submmit manual a Kaggle

Archivo enviado a Kaggle manualmente: KA-00ENSAMBLE_7.7z
