# Resumes & Positions Analysis with NLP & Web Scrapping.

>Trabajo Práctico Final para la materia Inteligencia Artificial de la Universidad Nacional de Avellaneda.  
>Profesor: Federico Gabriel D´Angiolo.  
>Autor: Federico Calonge.

### Objetivos.

1.	Análisis de Curriculums Vitae / CVs / Resumes de Candidatos en formato PDF y obtención de Perfiles de Candidatos. 
	* 1.1-Extracción del Corpus (textos de Artículos de Wikipedia) y preprocesamiento del mismo.
	* 1.2-Definimos nuestras Keywords: stadistics, Language, machine_learning, Deep, Python, data.
	* 1.3-Cálculo de palabras más similares a dichas Keywords (mediante word embeddings mediante Word2vect)
	* 1.4-Macheo de estas palabras con los CVs y obtención del perfil de candidato. 

2.	Análisis de Ofertas/Posiciones de Trabajo y obtención de Perfiles de Candidatos. 
	* 2.1-Extracción del Corpus (posiciones de trabajo en Indeed para: ata Scientist, Machine Learning, Data Engineer, Java Programmer. HCM Consultant) y 	preprocesamiento del mismo.
	* 2.2-Definimos nuestra lista de Keywords para Skills, Tools y educación mínima.
	* 2.3-Analizamos los TOP 20 Skills, TOP 20 Tools y educación mínima para el puesto “Data Scientist”.  
	* 2.4-Obtenemos los Top 5 Skills y Top 5 Tools para las demás posiciones. Y utilizaremos estas como una lista de Keywords para
	machear directamente con los CVS y obtener nuestro perfil de candidato. 

>Para mayor detalle ver el Informe en /Informe_Y_Consignas.

### Notebooks.

* Análisis 1 en --> Codigo/CV_Scoring_V1.ipynb
* Análisis 2 en --> Codigo/Job_Positions_Extract&Analysis.ipynb y Codigo/CV_Scoring_V2.ipynb

### Requerimientos TLFinal y cómo ejecutar los Análisis.

Para ambos Análisis se debe tener instalado Anaconda (https://docs.anaconda.com/anaconda/install/linux/)
>
1.	Análisis 1 (CV_Scoring_V1.ipynb):
>
Estando ubicados en el root del proyecto, creamos nuestro entorno virtual (federicio_env) y lo activamos con:
	
    > conda create --name federicio_env

    > conda activate federicio_env
    
Luego instalamos pip con dicho entorno activado:
    
    > conda install pip
    
Nota: se pueden instalar los paquetes necesarios de 2 maneras:
	
* Forma 1 (mediante pip3):
>
    > 1.1. >pip3 install PACKAGE. 
    
    > 1.2. >/home/fedricio/anaconda3/envs/federicio_env/bin/pip3 install PAQUETE_QUE_QUIERA(como gensim) --> Esto es para asegurarnos que realmente corramos el pip3 instalado en nuestro entorno virtual.	

* Forma 2 (mediante conda):
>
    > conda install PACKAGE.

Recomendación: instalar los paquetes con CONDA y lo que no se puedan mediante pip3.
>
Entonces, para instalar los paquetes ejecutamos los siguientes comandos:
	
    > conda install jupyter                       -->(para instalar el jupyter notebook). 

    > conda install gensim

    > pip3 install PyPDF2                         -->(no se puede instalar por conda).

    > conda install nltk

    > conda install pandas

    > conda install spacy

    > conda install matplotlib

    > python -m spacy download en_core_web_sm     -->(para poder ejecutar el paso 7-).
    
Luego nos fijamos que este todo instalado (con nuestro entorno activado):
    
    > pip3 list
    
    > conda list
  
Y por último corremos jupyer notebook (con nuestro entorno activado) y ejecutamos el archivo 'CV_Scoring_V1.ipynb' en nuestro navegador (http://localhost:8888/tree):

    > jupyter-notebook
    
2.	Análisis 2 (Job_Positions_Extract&Analysis.ipynb y CV_Scoring_V2.ipynb):
> FALTA COMPLETAR


### Mejoras

Ver Informe en /Informe_Y_Consignas, sección 5-Mejoras a desarrollar.
