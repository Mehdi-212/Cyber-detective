# Cyber-detective

Ce projet est basé sur du webscrapping.

il se décliner en plusieurs étapes:
-Récupérer les infos sur les livres : titre, prix, rating, disponibilités des livres et les liens vers les images de couverture des libres via un scrapper, dans mon cas j'ai utilisées Selenium pour scrapper les informations.

Les informations des livres sur les 50 pages web issues du scrapper sont intégrées dans une base de données et dans un fichier csv.

il faillait collecter tous les tweets via l’API de tweeter liés à ces livres depuis le 01/06/2022. 

La quantité de tweet liés à chaque livre sera entre 700 et 1000. 
Les livres à analyser seront : 
-the Art of War
-The song of Achille
-Batman : the Dark Night Return
-The Picture of Dorian Gray
-The Book Thief

Il fallait faire plusieurs visualisations sous plusieurs forme: 

-une analyse nuage de mots
-la fréquence des bigrammes et trigrammes

Il y a 3 bonus nous permettant d'améliorer notre analyse.

Bonus 1 : Automatiser la récupération des données sur les livres ( automisation du navigateur): on doit voir le scrapper scroller les pages lors de la récupération des données.

Bonus 2 : Code le scrapper du site https://books.toscrape.com/ en POO.

Bonus 3 : Faire une analyse de sentiments des livres sur Twitter.
