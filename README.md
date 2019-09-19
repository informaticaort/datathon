# Datathon!
Repositorio para archivos relacionados a la experiencia Datathon

## 00 - Primeros pasos en Python

### Objetivos
1. Presentar el entorno de trabajo: Jupyter Notebook, corriendo sobre Python.
2. Mediante la introducción de algunos elementos nativos de Python, brindar ejemplos de programación basados en datos básicos, pudiendo relacionar los diferentes conceptos lógicos. 
3. Introducir la lógica de los iteradores y mecanismos de excepción.

### Secciones
Elementos y métodos asociados 
 * Listas 
 * Tuplas 
 * Diccionarios 
 
Temas transversales
* Indexación
* Funciones *built-in*
* Iteradores (loops y listas por comprensión)
* Excepciones (condiciones validadas con booleanos)


## 01 - Análisis exploratorio de datos (EDA)

### Objetivos
1. Presentar las principales librerías de Python para análisis exploratorio de datos y recursos visuales (Pandas, NumPy, SciPy, Seaborn).
2. Introducir y familiarizarse con la lectura y la exploración de datasets, permitiendo identificar límites y potencial de los datos así como su adecuación para el análisis.

### Datasets
Datos abiertos del GCBA. Ministerio de Salud. Instituto de Trasplantes de la Ciudad de Buenos Aires. Los descargamos de [aquí](https://data.buenosaires.gob.ar/dataset/manifestaciones-a-la-donacion-para-trasplantes).

**Manifestaciones a la donación para trasplantes**
Información correspondiente a la Campaña de Promoción “Hoy también elegís ser donante de órganos” organizada por el Instituto de Trasplante de la Ciudad de Buenos Aires en el marco de la jornada electoral **PASO 2017** dando cumplimiento a la Ley 2508/07. Se realizó en 62 establecimientos autorizados por la Justicia Electoral de la Ciudad de Buenos Aires.

1. *Manifestaciones a la donación para trasplantes*: personas que decidieron sobre la donación de órganos y tejidos en la CABA durante las Elecciones PASO 2017.

2. *Establecimentos - Elecciones 2017*: ubicación de los establecimientos autorizados para las Elecciones Legislativas de Octubre 2017.

## 02 - Complemento Pyplot - Pandas
Un Notebook en el cual encontrarás cómo utilizar Pyplot para graficar, y alguna otra funcionalidad de Pandas

## Ejercicios de Práctica!!
En la carpeta "prácticas" vas a encontrar ejercicios para completar con lo aprendido en los encuentros!

## Otras opciones para ejecutar Notebooks sin depender de una instalación de Python en tu PC 

[Jupyter Notebook Online](https://jupyter.org/try) -> Eligiendo la opción de Classic Notebook con IPython

[Google Colaboratory](https://colab.research.google.com)

Para cargar archivos (por ejemplo datasets, archivos .csv) desde Colab, escribimos estas dos líneas

`url = 'https://raw.githubusercontent.com/informaticaort/extra-datathon/master/datasets/titanic.csv'`
`df1 = pd.read_csv(url,error_bad_lines=False)`

## Material de referencia y consulta
* [Descarga Python](https://campus.almagro.ort.edu.ar/musicaydatos/descargar/repositorioarchivo/1081804/)
* [Artículos del Campus Virtual ORT sobre Python](https://campus.almagro.ort.edu.ar/musicaydatos/articulos/1078892/categoria/116651/1)
* [Más documentación de Python](https://campus.almagro.ort.edu.ar/musicaydatos/articulos/1078892/categoria/115929/1)
* [Curso en Google Drive de Python](https://drive.google.com/open?id=1bEgTN_cSBBns8K9kF5v9tmKJhh9D9Ets)
* [Web Oficial de Python](https://www.python.org/)
* [Web Oficial de Python Argentina](https://www.python.org.ar/)
* [Web Oficial de Pandas](https://pandas.pydata.org/)
* [Web Oficial de Jupyter](https://jupyter.org/)
* [Kaggle (Repositorio de Datasets)](https://kaggle.com/)
* [Stack Overflow (nunca falla...)](https://stackoverflow.com/)
