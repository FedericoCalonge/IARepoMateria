# Resumes & Positions Analysis with NLP & Web Scrapping.

>Trabajo Práctico Final para la materia Inteligencia Artificial de la Universidad Nacional de Avellaneda.  
>Profesor: Federico Gabriel D´Angiolo.  
>Autor: Federico Calonge.

### Objetivos

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

>Para mayor detalle ver ver el Informe en /Inorme_Y_Consignas.

### Requerimientos

Ver imports en los Notebooks: pandas, nltk, gensim, spacy, PyPDF2, matplotlib, selenium.

### Notebooks

>Análisis 1 en --> Codigo/CV_Scoring_V1.ipynb
>Análisis 2 en --> Codigo/Job_Positions_Extract&Analysis.ipynb y Codigo/CV_Scoring_V2.ipynb

### Mejoras

Ver Informe en /Inorme_Y_Consignas, sección 5-Mejoras a desarrollar.