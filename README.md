# Analyse von Netflix Originals anhand Daten von Wikipedia

Dieses Projekt analysiert die Netflix-Originals-Serien und -Filme anhand von öffentlich zugänglichen Daten aus Wikipedia:

### Netflix Originals Serien:
[Netflix-Originals-Series](https://en.wikipedia.org/wiki/List_of_Netflix_original_programming)

### Netflix Originals Filme:
[Netflix-Originals-Movies-LIST](https://en.wikipedia.org/wiki/Lists_of_Netflix_original_films)

[2015-2017](https://en.wikipedia.org/wiki/List_of_Netflix_original_films_(2015%E2%80%932017))
[2018](https://en.wikipedia.org/wiki/List_of_Netflix_original_films_(2018))
[2019](https://en.wikipedia.org/wiki/List_of_Netflix_original_films_(2019))
[2020](https://en.wikipedia.org/wiki/List_of_Netflix_original_films_(2020))
[2021](https://en.wikipedia.org/wiki/List_of_Netflix_original_films_(2021))
[2022](https://en.wikipedia.org/wiki/List_of_Netflix_original_films_(2022))
[2023](https://en.wikipedia.org/wiki/List_of_Netflix_original_films_(2023))
[2024](https://en.wikipedia.org/wiki/List_of_Netflix_original_films_(2024))


Es umfasst 3 Teile: 
    1. Web-Scraping der Daten, 
    2. die Bereinigung von Daten
    3. Analysen bzw. Einsichten zur Anzahl der Veröffentlichungen, Genres, Laufzeiten und Verlängerungen.
        3.1 Einsicht: In welchen Genres wurden die meisten Filme und Serien produziert?
        3.2 Einsicht: Wie viele Originals wurden pro Jahr veröffentlicht?
        3.3 Einsicht: Wie ist die durchschnittliche Laufzeit pro Original Kategorie?
        3.4 Einsicht: Wie viele Serien wurden für das Jahr 2025 verlängert?


## Projektstruktur

    - `netflix-originals-analysis/
        - netflix-originals-analyzing.ipynb     - Jupyter Notebook mit Code & Analysen
        - netflix-originals-analyzing.html      - Code und Analysen als HTML
        - netflix_series.csv                    - Rohdaten der Serien
        - netflix_movies.csv                    - Rohdaten der Filme
        - netflix_series_clean.csv              - Bereinigte Daten der Serien
        - netflix_movies_clean.csv              - Bereinigte Daten der Filme

## Technologien
    - Python - Programmiersprache
    - Pandas - Webscraping der Wikipedia-Seite (pandas.read_html) und zur Datenverarbeitung und Bereinigung
    - NumPy - Datenmanipulation
    - Regular Expressions - Bereinigung von Texten
    - Matplotlib - Visualisierung der Analysen mit Diagrammen
    - Jupyter Notebook - Interaktive Umgebung


### Voraussetzung
    1. Python herunterladen 

    2. Jupyter Notebook herunterladen

    pip install notebook

    3. Erforderlichen Pakete herunterladen:

    pip install pandas numpy matplotlib

    Alternativ kannst du dir den Code und die Analysen über den File netflix-originals-analyzing.html anschauen 