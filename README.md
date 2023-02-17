# Movie or Book?, now made with Tableau
![Sauron](Images/Sauron.jpg)

## Introduction.
---
* This project is a continuation to my last project that's called [movie or book](https://github.com/Slivered/Proyecto_ETL) so feel free to check it out before you proceed reading this tableau project.
* In this project the objective is to make a talbeau dashboard expanding the results that i had from my last project.

## Methodology.
---
* I'll be using the clean csv from my last project to make all the graphics needed for my dashboard.
* Additionally I'll be scrapping more information using seleneum to enrich my dashboard with valuable information like images and the most famous quotes of every book.
* Once I have all the data that I wanted, I start the cleaning process, this process is done [here](https://github.com/Slivered/Proyecto_Tableau/blob/main/Notebooks/Scrapping_y_limpieza.ipynb), it's mostly the same as in my last [project](https://github.com/Slivered/Proyecto_ETL) but with the addition of the quote and image scrapping, as well as it's cleaning process.


## [My Tableau](https://public.tableau.com/app/profile/sindri8103/viz/Proyecto_Tableau_16761167849960/BooksvsMovies?publish=yes), and Outcome.
---
* So here is my [Tableau](https://public.tableau.com/app/profile/sindri8103/viz/Proyecto_Tableau_16761167849960/BooksvsMovies?publish=yes), I wanted it to have the feel of a book so I decided to have a paperlike background and use a dark blue to reaseble it's ink.
* As you can see in my Tableau dashboard there is a list of 10 movies/books, these are the best rated in imdb, if you select any of these movies/books the dashboard will change with data according to that specific title.
* Aswell you will see that on one side there is data that doesn't change, those graphs are used to compare every book and movie between them, not individually like in the selector chart that i mentioned before.

## Tools
---
* [Pickle](https://docs.python.org/3/library/pickle.html) is used to store safely a list outside of your notebook, so if your kernel shuts down you won't lose any data.
* [Selenium](https://www.selenium.dev/documentation/webdriver/) is a web scraping tool and it's great for automating your webscraping
* [Fuzzywuzzy](https://pypi.org/project/fuzzywuzzy/) it's an incredible tool used to match strings and keep the most similar string you desire.
* [Tableau](https://www.tableau.com/es-es) is a very powerful and useful visualization software.

## Special thanks.
---
I wanted to thank my teachers [Ana](https://github.com/AnaAGG), Cesar and [Jean-Charles](https://github.com/yamadajc) for all of their support and endless knowledge about all of these tecnologies we see at [ironhack](https://www.ironhack.com/es), be it python, mysql, selenum, tableau, any of these tecnologies is easy to learn thanks to them. Thank you!.