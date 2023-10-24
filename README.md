# master-tesis-data-imputation

# DATA 
## COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University

On March 10, 2023, the Johns Hopkins Coronavirus Resource Center ceased its collecting and reporting of global COVID-19 data. For updated cases, deaths, and vaccine data please visit the following sources:
- Global: [World Health Organization (WHO)](https://www.who.int/)
- U.S.: [U.S. Centers for Disease Control and Prevention (CDC)](https://www.cdc.gov/coronavirus/2019-ncov/index.html)
- Para ver mas informacion: https://github.com/CSSEGISandData/COVID-19
- https://coronavirus.jhu.edu/map.html

License:

1. This data set is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) by the Johns Hopkins University on behalf of its Center for Systems Science in Engineering.  Copyright Johns Hopkins University 2020. 

2. Attribute the data as the "COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University" or "JHU CSSE COVID-19 Data" for short, and the url: https://github.com/CSSEGISandData/COVID-19.  

3. For publications that use the data, please cite the following publication: "Dong E, Du H, Gardner L. An interactive web-based dashboard to track COVID-19 in real time. Lancet Inf Dis. 20(5):533-534. doi: 10.1016/S1473-3099(20)30120-1"

# Data profile
Se realizo dataprofile basado en el curso https://colab.research.google.com/drive/1fMqbta8k59mn_KPgWmqZLLYA7lNDh9Mb?usp=sharing 

# Prueba de prediccion
Se hizo dos pruebas: regresion y clasificacion

## Regresion de un atributo numerico

En base a los datos (**Province_State	Country_Region	Last_Update	Lat	Long_	Confirmed		Incident_Rate	Case_Fatality_Ratio	date**) el objetivo es predecir **Deaths**

Basado en el tutorial: https://colab.research.google.com/github/pycaret/pycaret/blob/master/tutorials/Tutorial%20-%20Regression.ipynb#scrollTo=40ed5152&uniqifier=1

## Prediccion de un campo categorico

En base a los datos (**Deaths	 Province_State	Last_Update	Lat	Long_	Confirmed		Incident_Rate	Case_Fatality_Ratio	date**) el objetivo es predecir **Country_Region**

Basado en el tutorial https://colab.research.google.com/github/pycaret/pycaret/blob/master/tutorials/Tutorial%20-%20Multiclass%20Classification.ipynb#scrollTo=4181de41&uniqifier=1

# GAIN
Basado en https://github.com/jsyoon0823/GAIN

# MIDA
Basado en https://github.com/Harry24k/MIDA-pytorch

# scikit learn impuuter 
Basado en https://scikit-learn.org/stable/modules/impute.html
