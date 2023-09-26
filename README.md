# TFM-VIU-Brugada
Autor: Alejandro Hervas Segovia
Director: Flavio Palmieri
Codirectora: Elena Arbelo

Repositorio para el TFM "Desarrollo de algoritmos de machine learning para la clasificación de pacientes con síndrome de Brugada"

## Instrucciones para correr los scripts:
* Se necesitan los documentos almacenados en el mismo directorio que los scripts:
    * dsBiomarkersPlusClinical.xlsx 
    * Biomarkers_12leads.xlsx

Nota: Por motivos de privacidad,  la base de datos está disponible bajo petición al Prof Flavio Palmieri: flavio.palmieri@campusviu.es

* El script llamado <ins>TFM_Brugada_analisis_series.ipynb</ins> contiene el código utilizado para saber el poder predictivo de las variables derivadas de ECG y el código empleado para graficar las series temporales, clasificadas en pacientes sintomáticos y asintomáticos.

* El script llamado <ins>TFM_Brugada_entrenamiento_NeuralNetwork.ipynb</ins> contiene el código utilizado para entrenar la red neuronal con todas las variables derivadas de ECG disponibles, además de los gráficos y métricas para evaluar al modelo.

* El script llamado <ins>TFM_Brugada_entrenamien_NeuralNetwork_mejoresVariables.ipynb</ins> contiene el código utilizado para entrenar la red neuronal con las variables seleccionadas en el desarrollo del trabajo, además de los gráficos y métricas para evaluar al modelo.

* La carpeta <ins>Modelo</ins> contiene el archivo de exportación del mejor modelo entrenado con las variables seleccionadas.