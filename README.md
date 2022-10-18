# Capstone Project - Análisis de Datos
Repositorio del Capstone Project de la asignatura Análisis de Datos, Magíster en Data Science, Universidad del Desarrollo.\
Profesor: Víctor Landaeta
## Integrantes Grupo:
- Fabián Ragnarsson
- Sebastián Gacitúa
- Patricia Calisto
- Bastián Guzmán
- Matthias Clein
## Descripción General del Proyecto
El proyecto busca analizar el nivel de impacto de las descargas de *Aguas Residuales* de las *Centrales Termoeléctricas* en los cuerpos receptores, siendo éstos, ríos, lagos y/o mares.\
Se revisará la cantidad de Centrales en funcionamiento, se hará un mapeo territorial y luego nos centraremos en los parámetros que se miden actualmente en las descargas al mar, dentro de la Zona de Protección Litoral (ZPL).
## Estructura de archivos y carpetas 
El proyecto se presenta siguiendo la estructura sugerida por [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/), destacando en este caso dos carpetas: *data* y *notebooks*.\
### data
La carpeta *data* contiene las subcarpetas *raw* y *processed* las cuales, como su nombre lo indican, almacenan la data cruda y procesada respectivamente. Cabe destacar que por motivo del tamaño de los archivos (>1GB), la subcarpeta *raw* se incluyó en el *.gitignore*.\
### notebooks
En la carpeta *notebooks* se encuentran los siguientes archivos:
- **1_limpieza.ipynb**: Se encarga de cargar y limpiar la data cruda, que corresponde a archivos *.csv* y *.shp*.
- **2_analisis.ipynb**: A partir de la data limpia obtenida en el archivo anterior, analiza la información, enriqueciéndola y aplicando filtros según los parámetros importantes dentro del proyecto.
- **3_reporte.ipynb**: Presenta de manera gráfica los resultados obtenidos e incluye las conclusiones del trabajo.
### references
La carpeta *references* almacena los documentos de referencia de los datos, en este caso el manual explicativo del dataset y los valores de referencia de los límites establecido por variable y zona de descarga.
### output
*output* es la carpeta donde se almacena el resultado final del trabajo en formato HTML.
## Ejecución
Clone este repositorio e instale todas las dependencias presentes en el archivo *requirements.txt*. Luego, como la data procesada se encuentra en el repositorio, sólo es necesario ejecutar las celdas del notebook *3_reporte.ipynb*. Con esto podrá ver e interactuar con los gráficos.
## Gráficos interactivos
La vista previa del notebook *3_reporte.ipynb* en GitHub no permite visualizar los gráficos interactivos, por lo que se sugiere clonar el repositorio y ejecutarlo en local.\
![map](../main/img/mapa.png)
![sunburst_plot](../main/img/sunburst_plot.png)