# Adne_Text
Trabajo de procesamiento del lenguaje natural. Realizado por Antonio Bajo Gómez-Madurga y Javier Gallego Fernández


Para el proyecto se han creado dos environments debido a los conflictos e incompatibilidades entre distintas librerías. 
El primer environment hay tres notebooks en los que se realiza un análisis de los datos efectuando distintas técnicas y algoritmos, el notebook es "Primer_Analisis". Posteriormente se han realizado dos notebooks más en el que se realizan modelos para la clasificación de noticias según su categoría. El primer modelo es una Regresión Logística bastante sencilla y previamente se han preprocesado los datos y se ha hecho uso de TF-IDF: Para el segundo modelo se utiliza una red LTSM variando algunos parámetros. 

El segundo environment tiene únicamente un notebook, junto con un modelo entrenado y un csv de salida con los resúmenes que se han generado para entrenar el modelo. Se ha utilizado un modelo preentrenado para generar resúmenes de las noticias y con esos resúmenes se ha podido hacer fine-tuning para poder generar resúmenes de manera más personalizada sobre nuestras noticias, o tipo de noticias.

Para lanzar cada environment se deberá crear uno con el fichero requirements.txt que está para cada environment en su respectiva carpeta. 
Una vez creado con dichos ficheros, los notebooks deberían correr perfectamente. 
