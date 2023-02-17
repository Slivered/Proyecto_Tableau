# Movie or Book?, now made with Tableau
![Sauron](Images/Eye.jpg)

## Introduction.
---
* This project is a continuation to my last project that's called [movie or book](https://github.com/Slivered/Proyecto_ETL) so feel free to check it out before you proceed reading this tableau project.
* In this project the objective is to make a talbeau dashboard expanding the results that i had from my last project.

## Methodology.
---
* Ill be using the clean csv from my last project to make all the graphics needed for my dashboard.
* Additionally ill be scrapping more information using seleneum to enrich my dashboard with valuable information like images and the most famouse quotes of every book.
* Once i have all the data that i wanted i start the cleaning process, this process is done [here](https://github.com/Slivered/Proyecto_Tableau/blob/main/Notebooks/Scrapping_y_limpieza.ipynb), it's mostly the same as in my last [project](https://github.com/Slivered/Proyecto_ETL) but with the addition of the quote and image scrapping, as well as it's cleaning process.

## Outcome.
---
So here is my [Tableau](https://public.tableau.com/app/profile/sindri8103/viz/Proyecto_Tableau_16761167849960/BooksvsMovies?publish=yes) i wanted it to have the feel of a book so i decided to have a paperlike background and use a dark blue to reaseble it's ink.

## Tools
* [Pickle](https://docs.python.org/3/library/pickle.html) is used to store safely a list outside of your notebook, so if your kernel shuts down you won't lose any data.
* [Selenium](https://www.selenium.dev/documentation/webdriver/) is a web scraping tool and it's great for automating your webscraping
* [Fuzzywuzzy](https://pypi.org/project/fuzzywuzzy/) it's an incredible tool used to match strings and keep the most similar string you desire.
* [Tableau](https://www.tableau.com/es-es) is a very powerful and useful visualization software.
