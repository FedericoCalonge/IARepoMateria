# IARepoMateria
>
Repo de la materia Inteligencia Artificial - Universidad Nacional de Avellaneda
>
>Trabajos Prácticos para la materia Inteligencia Artificial de la Universidad Nacional de Avellaneda.
>Profesor: Federico Gabriel D´Angiolo.
>Autor: Federico Calonge.

### Resumen Contenido:
>
* TL1: Manipulación y Visualización de datos aplicados a dataset COVID-19 & Regresión Lineal aplicado a sobre dataset de Presiones. 
* TL2: Regresión Lineal Multivariable & Regresión de Ridge aplicados a dataset de Propiedades en Boston y dataset de Articulos de Machine Learning. 
* TL3: KNN & Clasificador Bayesiano aplicados a dataset animales zoologico.
* TL4: Redes Neuronales aplicadas a predicción de artículos de moda (dataset de imagenes).
* TLFinal: NLP Aplicado a Job Positions y CVs de Candidatos

### Requerimientos TLFinal y cómo ejecutar los programas.
>
* CV_Scoring_V1.ipynb:
>
Estando ubicados en el root del proyecto, creamos nuestro entorno virtual (federicio_env) y lo activamos con:
	> conda create --name federicio_env
	>
	> conda activate federicio_env
	>
Luego, parados en el entorno instalamos pip:
	>conda install pip
	>
Se pueden instalar los paquetes necesarios de 2 maneras:
	>
	>Forma 1 (mediante pip3):
	>1.1 --> pip3 install PACKAGE. 
	>1.2 --> /home/fedricio/anaconda3/envs/federicio_env/bin/pip3 install PAQUETE_QUE_QUIERA(como gensim)
	--> Para asegurarnos que realmente corramos el pip3 instalado en nuestro entorno virtual.	
	>
	> Forma 2 (mediante conda):
	> conda install PACKAGE.
	>
	> Recomendación: instalar con CONDA y lo que no se pueda mediante pip3.
	>
Entonces, la instalación de paquetes sera ejecutando:
	> conda install jupyter -->(para instalar el jupyter notebook). 
	> conda install gensim
	> pip3 install PyPDF2   -->(no se puede instalar por conda).
	> conda install nltk
	> conda install pandas
	> conda install spacy
	> conda install matplotlib
	> python -m spacy download en_core_web_sm     --> (para poder ejecutar el paso 7-).
	>
Por último nos fijamos que este todo instalado (con nuestro entorno activado):
	> pip3 list
	> conda list
	>
* Job_Positions_Extract&Analysis.ipynb y CV_Scoring_V2.ipynb:
>
	-<FaltaCOMPLETAR
