Proyecto Semana 4


- Este proyecto consistió en crear y construir una base de datos a través del proceso ETL. 

- Los requisitos del proyecto fueron:
      - Extraer los datos de al menos 3 fuentes 
      - Usar al menos 2 métodos de web scraping


Para este proyecto lo que hice fue sacar datos de cada día del mes de Agosto 2022, especificamente la úlitma semana del mes, ya que en las otras semanas habían algunos registros nulos. Los datos fueron de diferentes tópicos, por ejemplo, para cada día había el dato de la película más vendida en Box Office, la foto de la NASA del día, el libro ficción y no ficción más vendido según el New York Times y un dato curioso y una frase del día.


Como métodos de extracción, utilice:
- Beautiful Soup
-Selenium
-API

Las fuentes donde extraí los datos fueron:
- NASA ('https://apod.nasa.gov/apod.rss) {API}
- Box office MOJO (https://www.boxofficemojo.com/date/?ref_=bo_nb_ml_secondarytab) {Beautiful Soup}
- Brainy Quote (https://www.brainyquote.com/quote_of_the_day_) {Selenium}
- New York Times  (https://www.nytimes.com/books/best-sellers/2022/08/28/) {Selenium}


En el folder de data, se podrá encontrar un pptx con la presentación del proyecto y un archivo .ipynb con el código que se utilizó para hacer todo el web scraping. 






