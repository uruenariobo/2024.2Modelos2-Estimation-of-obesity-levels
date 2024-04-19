# 2024.2Modelos2-Estimation-of-obesity-levels

## Participantes

- Miguel Angel Urueña Riobo
  - Email: miguel.uruena@udea.edu.co
  - Programa: Ingeniería de Sistemas
 
- Eliana Janneth Puerta
  - Email: eliana.puerta@udea.edu.co
  - Programa: Ingeniería de Sistemas
    
- Juan Fernando Lopera Muñoz
  - juan.loperam@udea.edu.co
  - Programa: Ingeniería de Sistemas

# Instrucciones para Reproducción

Este repositorio contiene archivos que forman parte del proyecto de predicción de niveles de obesidad utilizando técnicas de clasificación. A continuación, se detallan las instrucciones para ejecutar los scripts y reproducir los resultados.

## Archivos Disponibles

- **EDA.ipynb**: Este archivo contiene el análisis exploratorio de datos realizado durante el proyecto.
- **Entregable_II_G_DB_1_ElianaPuertaMorales_JuanLoperaMuñoz_MiguelUruenaRiobo.ipynb**: Este archivo contiene la implementación del proyecto, incluyendo el prepocesamiento de los datos y el desarrollo de los 3 modelos predictivos (Random Forest Classifier, Decision Tree Classifier y k-nearest neighbors y se optó por utilizar Stratified KFold como método de validación cruzada).

## Pasos para la Reproducción

## Alternativas para Ejecutar el Proyecto

### 1. Utilizando Google Colab (Sin necesidad de clonar el repositorio)

1. **Abrir en Google Colab**: Haz clic en los siguientes enlaces para abrir los Notebooks en Google Colab:
   - [EDA.ipynb](https://colab.research.google.com/drive/1E08zktRCXRYEY8MsY2TaMiT2aGofvgmI?usp=sharing&authuser=1)
   - [Entregable_II_G_DB_1_ElianaPuertaMorales_JuanLoperaMuñoz_MiguelUruenaRiobo.ipynb](https://colab.research.google.com/drive/14PTfF0AcM4n-vY24eojIwto_z1QgNCww?usp=sharing)

2. **Descargar y descomprimir el dataset**: Ingresar a [DataSet](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition), descargarlo y descomprimirlo para obtener el archivo CSV.
    
2. **Cargar el Dataset en Colab**: Utiliza las funciones de carga de datos desde tu máquina local en el entorno de ejecución de Google Colab y subir el CSV (dataset) previamente descomprimido.

3. **Ejecutar los Notebooks**: Sigue las instrucciones proporcionadas en los Notebooks para ejecutar el código y reproducir los resultados del proyecto.

### 2. Ejecución Local (Clonando el Repositorio y Utilizando Jupyter Notebook)

1. **Clonar el Repositorio**: Clona este repositorio en tu máquina local utilizando el siguiente comando en tu terminal:

```bash
     git clone https://github.com/uruenariobo/2024.2Modelos2-Estimation-of-obesity-levels
```

2. **Download Python 3.11:**
   - Make sure you have Python 3.11 installed on your system. You can download it from the official Python website [here](https://www.python.org/downloads/release/python-3110/).
  
3. **Descargar y descomprimir el dataset**: Ingresar a [DataSet](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition), descargarlo y descomprimirlo para obtener el archivo CSV.
    
4. **Cargar el Dataset en el entorno de Jupyter**: Utiliza las funciones de carga de datos Jupyter para subir el CSV (dataset) previamente descomprimido en el entorno de ejecución que vas a trabajar.

5. **Ejecutar los Notebooks**: Abre Jupyter Notebook en tu entorno de desarrollo preferido y navega hasta la ubicación donde clonaste el repositorio. Abre los archivos `EDA.ipynb` y `Entregable_II_G_DB_1_ElianaPuertaMorales_JuanLoperaMuñoz_MiguelUruenaRiobo.ipynb` en orden y sigue las instrucciones proporcionadas en los notebooks para ejecutar el código.

6. **Exploración de Datos (EDA)**: En el notebook `EDA.ipynb`, encontrarás el análisis exploratorio de datos. Sigue las celdas de código y las explicaciones proporcionadas para comprender los datos y las características del conjunto de datos.

7. **Preprocesamiento de datos e implementación del Modelo**: En el notebook `Entregable_II_G_DB_1_ElianaPuertaMorales_JuanLoperaMuñoz_MiguelUruenaRiobo.ipynb`, se encuentra el preprocesamiento de los datos y la implementación de los modelos predictivos utilizando técnicas de clasificación. Sigue las instrucciones proporcionadas en el notebook para cargar los datos, entrenar los modelos y evaluar sus rendimientos.

8. **Reproducción de Resultados**: Sigue las celdas de código en ambos notebooks para reproducir los resultados del proyecto. Asegúrate de ejecutar todas las celdas en orden para evitar errores.

Con estas instrucciones, deberías poder reproducir los resultados del proyecto de predicción de niveles de obesidad utilizando los scripts proporcionados en este repositorio. Si encuentras algún problema o tienes alguna pregunta, no dudes en contactarnos mediante Email o Github a los autores del proyecto. ¡Gracias por tu interés!

## Dataset

A continuación encuentras el dataset completo: [DataSet](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition).
