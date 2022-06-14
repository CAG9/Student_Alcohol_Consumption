# Consumo de alcohol en estudiantes
## English version coming soon
## Autores
* ## Cesar Arcos: cesar99ag@gmail.com
* ## Eduardo Ceja: lalitoceja@gmaill.com
## Licencia
GNU General Public License v3.0
## Introducción
El consumo de alcohol ha sido el principal culpable del bajo rendimiento académico pero de hecho, hay más factores que ese  como relaciones familiares, contexto social, interés de los estudiantes, situación económica, entre otros. En este artículo intentaremos ver cuáles son los otros factores que contribuyen al mal desempeño académico de los estudiantes. Como se trata de un análisis exploratorio, llevaremos a cabo métodos de aprendizaje no supervisados como KMeans, agrupamiento jerárquico como también la implementación de visualizaciones de los datos y la información que producimos.
## Ejecutar
Para ejecutar este proyecto primero necesitas clonarlo, una vez clonado para poder abrir la libreta `Analysis.ipynb` tienes que abrirla desde jupyter correrla. <br>
Para ejecutar `app.py` primero hay que estar adentro de la carpeta y en una terminal ejecutar el comando: `streamlit run app.py` o puedes ver los resultados directamente desde el link en la sección de resultados
## Resultados
Puedes Leer el reporte el cual está nombrado como `Reporte.pdf` <br>
Visualizacion Streamlit : https://share.streamlit.io/emacc99/student_alcohol_consumption/main/app.py
## Conclusión
Lo que se puede concluir de este trabajo, es que las tareas de aprendizaje no supervisado no siempre son sencillas ya que al no haber una especie de "respuesta correcta" como etiquetas, se tiene que hacer una análisis más profundo de lo que el grupo está clasificando. Eso sumado con el caso de que nuestros datos no tenían muchos grupos definidos, fue un gran reto extraer información del clustering que se hizo. Este trabajo trata de responder si hay una especie de correlación con el consumo de alcohol con la vida académica tomando en cuenta varios factores extras no solo si toma o no. ya que hay que tener en mente que la correlación no es necesariamente causación. Lo que encontramos demuestra que no hay una correlación clara entre las calificaciones y el consumo de alcohol. Eso no significa que no hayamos aprendido y descubierto cosas acerca de los datos, pero lo más importante son las preguntas que hemos ido haciéndonos acerca de los datos. Estas son las que nos hicimos: ¿Si añadimos todavía más clusters, se empezarían a definir más los grupos? ¿Cómo se podrían limpiar los datos para mejorar la definición de los clusters?. 
## Herramientas de software
- Python 3.8.3
- Numpy 1.18.5
- Pandas 1.0.5
- Matplotlib 3.2.2
- Scikit-learn 0.23.1
- Streamlit 0.69
- Yellowbrick 1.2
- Seaborn 0.10.1



