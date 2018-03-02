# scrapper-airbnb-reviews

##Instalación

1- Bajar e instalar con pip las siguientes librerías de Python

BeautifulSoup
selenium
webdriver
docx

2- Bajar el wevdriver de Chrome que usa Selenium

##Ejecución

1- El archivo "airbnb_scrapper.py" primero usa selenium (una librería de testing) para abrir cada link de Airbnb.
Guarda los archivos html de donde se extraen las reviews (se puede comentar esta parte para que no los guarde)
Guarda el .json de las reviews. 

2- El archivo "airbnb_reviews_json_parser_to_docx.py" parsea el .json y guarda algunos campos en un docx (o en un txt).
Se pueden filtrar distintos campos del .json de las reviews modificando el array (data["reviews"][i]["comments"])
