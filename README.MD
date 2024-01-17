# PROYECTO INDIVIDUAL N2 
# SINIESTROS VIALES EN CIUDAD DE BUENOS AIRES
![](foto_portada.jpg) 
## Introduccion : 
Este proyecto consiste en asumir el rol de un Data Science y Data Analyst y en base a la base de datos del gobierno de la Ciudad de Buenos Aires realizar un analisis de los siniestros viales para poder entregar informacion que permita a las autoridades locales tomar medidas para reducir la cantidad de victimas fatales. Para eso vamos a utilizar los archivos disponibles en su pagina oficial y realizarles un proceso de EDA , ETL y finalmente la creacion de un dash board en power bi. 
## Tecnologias utilizadas 
- Python 
- Pandas 
- Numpy 
- Seaborn 
- Matplotlib 
- Power bi 
## Archivo necesario para ejecutar el dash boar en Power Bi
1.  [Archivo .pbix(Power Bi)](pi02.pbix)
2.  [Data Set final ](merged_clean.csv)
## Resolucion: 
### 1. [EDA](EDA.ipynb): 
Realice el proceso EDA  (Exploratory Data Analysis) en el DataSet  con el objetivo de identificar relaciones , insights , tendencias y/o patrones , tal que , sirvan para el proceso de ETL y la creacion del Data Set final. Todo el proceso esta comentado y registrado en el archivo EDA.ipynb.
### 1.1. [ETL](ETL.ipynb): 
En este paso se realizo el proceso de ETL para la obtencion del Data Set final y Data Sets especiales para le proceso EDA. Todo el proceso esta debidamente comentado en el archivo ETL.ipynb. 
### 2. [Creacion del Dash Board](pi02.pbix):
Para este paso se utilizo el Data set final llamado merged_clean.csv. Se crearon 5 Paginas dentro de la presentacion de Power Bi con el siguiente objetivo: 
1. Es un menu para navegar entre las otras  paginas. 
2. Es el Dash Board principal donde se pueden realizar todo tipo de consultas al Data Set y configurar con los filtros creados. 
3. La tercera pagina es el KPIs 1 : 
* Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.
Definimos a la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico. Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000
4. La cuarta pagina es el KIps 2 : 
* Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.
Definimos a la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100
5. La quinta pagina es el KPIs 3 : 
* Reducir en un 25% la cantidad de victimas menores de 25 años en CABA , respecto al año anterior. Su fórmula para medir la evolución de los accidentes mortales con víctimas menores a 25 años es: (Número de accidentes mortales con víctimas <= 25 años del año anterior - poblacion total ) / (poblacion total ) * 100 
### 2.1 Estetica del Dash Board : 
Para este paso se consulto el libro de marca de la Ciudad de Buenos Aires y se respeto su gama de colores y tipografias. 
## Contacto : 
- [Portafolio Web](https://alejodiezgomez.github.io/)
- [Linkedin](https://www.linkedin.com/in/alejo-gabriel-diez-gomez-402b93254/)
- [alejo10gomezz@gmail.com]()



