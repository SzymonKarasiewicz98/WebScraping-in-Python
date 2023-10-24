# WebScraping-in-Python
Celem tego kodu było stworzenie funkcji get_model_pages_urls, która przyjmuje od uzytkownika jedynie nazwe producenta. (car_brand)
Nazwa producenta za pomoca f stringa jest dodawana do URL.
Następnie za pomocą biblioteki BeautifulSoup dostajemy się do strony internetowej i pobieramy interesujące nas informacje
W tym przypadku są to linki odnoszące się do kazdego z modelów aut dla konkretnego producenta (podanego wcześniej przez uzytkownika)
Dane pobierane sa ze strony www.autocentrum.pl
