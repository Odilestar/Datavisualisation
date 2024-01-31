# Temps de parole des hommes et femmes à la radio et la télé
![Image_logos](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQjXVAE9ssxRB3PbJYX8jGSG4ZeyUoBozKdwEYQB1A0bVj0A9oXzMpT40tiHP2yjQh7pcA&usqp=CAU)
>[Source](https://www.google.com/search?q=m%C3%A9dias&tbm=isch&ved=2ahUKEwjyornnqIeEAxXcXqQEHcVdB7oQ2-cCegQIABAA&oq=m%C3%A9dias&gs_lcp=CgNpbWcQAzIECCMQJzIECCMQJzIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEOgoIABCABBCKBRBDOggIABCABBCxAzoNCAAQgAQQigUQQxCxA1DmD1jmIGC0ImgCcAB4AIABWogBsQSSAQE5mAEAoAEBqgELZ3dzLXdpei1pbWfAAQE&sclient=img&ei=jhO6ZfKjM9y9kdUPxbud0As&bih=559&biw=1280&client=firefox-b-d&hl=fr#imgrc=o1UY94mD_WrOSM&imgdii=cLPVhX1szwgWUM)


# Sommaire 
1. [Introduction](#introduction)
2. [Choix et recueil du jeu de données](#jeuDeDonnées)
3. [Temps de parole des hommes et des femmes par année et par chaîne](#premièreVisuallisation)
4. [Temps de parole total des hommes et femmes à la radio et la télé par année](#deuxièmeVisulaisation)
5. [Visualisation en fonction du nombre de journalistes par chaîne](#troisièmeVisualisation)
6. [Bloopers](#visualisationsRates)

## 1. Introduction <a name="Introduction"></a>
J'ai choisi de travailler sur la différence de temps accordée aux hommes et aux femmes sur les médias notamment à la radio et à la télé.
Pour faire une visualisation sur le thème de temps de parole des hommes et femmes dans les médias, il a fallu recueillir des open data sur différents sites. Après collecte des données, j'ai décidé de réduire et de synthétiser mes données et de ne travailler que sur la plage qui m'interesse. J'ai donc réduit les données sur une période de 5 ans à savoir entre 2015 et 2019. 


**Les chaînes de télé analysées sont les suivantes:**  Arte, Animaux, BFM TV, Canal+, Canal+ Sport, Chasse et pêche, Chérie 25, Comédie+, D8/C8, Euronews, Eurosport France, France 2, France 24, France 3, France 5, France O, Histoire, I-Télé/CNews, L'Equipe 21, LCI, LCP/Public Sénat, La chaîne Météo, M6, Monte Carlo TMC, NRJ 12, Paris Première, Planète+, TF1, TV Breizh, TV5 Monde, Toute l'Histoire, Téva, Voyage, W9.


**Les chaînes de radio analysées sont les suivantes:** Chérie FM, Europe 1, France Bleu, France Culture, France Info, France Inter, France Musique, Fun Radio, Mouv’, NRJ, Nostalgie, RFM, RMC, RTL, RTL 2, Radio Classique, Radio France Internationale, Rire et Chansons, Skyrock, Sud Radio et Virgin Radio.

Les temps de parole sont estimés en heure.

## 2. Choix et recueil du jeu de données
![image_micro](https://www.shutterstock.com/image-photo/microphone-radio-studio-260nw-554468578.jpg)
>[Source](https://www.google.com/search?q=studio+radio+mic+live&tbm=isch&ved=2ahUKEwi7qvLfqIeEAxW7TaQEHZ9GBxEQ2-cCegQIABAA&oq=studio+radio+mic+live&gs_lcp=CgNpbWcQAzoECCMQJzoHCAAQgAQQEzoICAAQCBAeEBM6BAgAEB46BggAEAgQHlC5D1iyF2CcGmgAcAB4AIABRIgB2AKSAQE2mAEAoAEBqgELZ3dzLXdpei1pbWfAAQE&sclient=img&ei=fhO6ZbvzPLubkdUPn42diAE&bih=559&biw=1280&client=firefox-b-d&hl=fr#imgrc=2DgB8sl22J3JIM)

Les données sont recueillies en open data sur le site data.gouv
>[Données sur temps de parole des hommes et des femmes à la radio et à la télé](https://www.data.gouv.fr/fr/datasets/temps-de-parole-des-hommes-et-des-femmes-a-la-television-et-a-la-radio/#/resources)

![Voici le fichier de départ](https://we.tl/t-K6lzQzZH5h)
**Dans ce fichier se trouve les données de base et les traitements apportés. Chaque feuille constitue un traitement qui a permis à déduire les corpus de visualisation**

J'ai choisi le jeu de données de temps de parole des hommes et femmes à la radio et à la télé parmi les données proposées. J'ai décidé de reduire la période à 5ans.
J'ai donc traité ce jeu de données avec Excel puisque la taille dépassait dix millions de lignes. OpenRefine ne pouvait pas traiter les données. J'ai utilisé la formule NB.SI.ENS pour sortir les années de 2015 à 2019. Ensuite j'ai fait une autre formule pour calculer le nombre total des heures par chaîne. Je précise que les temps sont estimés en heure et sont énoncé par jour, de 1975 à 2019. J'ai donc transformé les temps journaliers en mensuel puis en année. J'ai fait le traitement avec Excel au vu de la taille du corpus.


### Voici un extrait du fichier traité:

| ANNEE | channel_name       |     male_duration  |     female_duration  |
|-------|--------------------|--------------------|----------------------|
| 2015  | Animaux            |     1 645 238      |        956 988       |
| 2015  | ARTE               |     3 123 603      |     1 231 907        |
| 2015  | BFM TV             |     3 501 573      |     1 773 802        |
| 2015  | Canal+             |     3 339 791      |        916 718       |
| 2015  | Canal+ Sport       |     2 761 056      |        142 649       |
| 2016  | Animaux            |     1 634 839      |        942 338       |
| 2016  | ARTE               |     3 164 116      |     1 246 289        |
| 2016  | BFM TV             |     3 326 119      |     1 841 251        |
| 2016  | Canal+             |     3 321 179      |        942 185       |
| 2016  | Canal+ Sport       |     2 845 340      |        144 663       |
| 2017  | Animaux            |     1 550 192      |        937 349       |
| 2017  | ARTE               |     3 001 213      |     1 277 691        |
| 2017  | BFM TV             |     3 299 401      |     1 860 405        |
| 2017  | Canal+             |     3 154 239      |        890 497       |
| 2017  | France 2           |     2 936 590      |     1 681 791        |
| 2018  | Animaux            |     1 475 340      |     1 025 229        |
| 2018  | ARTE               |     3 644 717      |     1 648 909        |
| 2018  | BFM TV             |     4 051 134      |     2 378 788        |
| 2018  | Radio Classique    |     1 594 247      |        910 651       |
| 2018  | RFI                |     6 046 376      |     2 998 556        |
| 2019  | Animaux            |     1 310 231      |        821 350       |
| 2019  | ARTE               |     1 448 996      |        707 776       |
| 2019  | BFM TV             |     1 749 685      |        910 678       |
| 2019  | Canal+             |     1 628 037      |        478 149       |
| 2019  | Canal+ Sport       |     2 507 609      |        135 782       |

> Tableau généré avec [Tables Generator](https://www.tablesgenerator.com)

## 3. Temps de parole des hommes et des femmes par année et par chaîne

Pour cette première visualisation, j'ai utilisé Flourish pour visualiser pour chaque chaîne de télé et de radio le temps de parole des hommes et des femmes. 
Voici le fichier de cette visualisation 
>[corpus première visualisation.csv](https://github.com/Odilestar/M2_DEFI_Datavisualisation_2024/blob/main/Corpus_premiereVisualisation.csv)

<div class="flourish-embed flourish-chart" data-src="visualisation/16342816"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Avec cette visualisation, on remarque que pour toutes les chaînes, que ce soit à la télé ou à la radio, les temps de parole des femmes est inférieur à celui des hommes. 



## 4. Temps de parole total des hommes et femmes à la radio et la télé par année

Pour cette visualisation, j'ai décidé d'afficher la différence de temps total par radio et par télé des hommes et des femmes. 
>[deuxieme visualisation.csv](https://github.com/Odilestar/M2_DEFI_Datavisualisation_2024/blob/main/Corpus_TV_Radio.csv)

<iframe title="Temps de parole par radio et par télé   " aria-label="Grouped Bars" id="datawrapper-chart-G8VSF" src="https://datawrapper.dwcdn.net/G8VSF/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="951" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();
</script>

## 5. Visualisation en fonction du nombre de journalistes par chaîne et par temps de parole des femmmes et des hommes

### visualisation par temps de parole pour 6 chaînes
>[troisièmeVisualisation](https://github.com/Odilestar/M2_DEFI_Datavisualisation_2024/blob/main/temps_six_chaines.csv) 
 Pour cette visualisation l'objectif est de comparer le temps des hommes et des femmes en fonction de l'effectif par chaîne. C'est-à-dire que l'on veut savoir si le temps de parole des hommes est supérieur à celui des femmes pour une chaîne parce que l'effectif des hommes de cette chaîne est supérieur à celui des femmes. 

<div class="flourish-embed flourish-chart" data-src="visualisation/16640160"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Visualisation par effectif masculin ou féminin par chaîne
>[quatrièmeVisualisation.csv](https://github.com/Odilestar/M2_DEFI_Datavisualisation_2024/blob/main/Journalistes_chaine.csv)

Pour avoir ce fichier, j'ai utilisé une requête wikidata pour avoir la liste des journlaistes par chaîne et leur genre. Pour ressortir l'effectif des hommes et femmes pour quelques chaînes. (TF1, RTL, ARTE, RMC, M6, France Info)
J'ai enrichi mon jeu de données avec le nombre de journalistes pour quelques chaînes. L'objectif est de voir combien de femmes et d'hommes sontemployés et voir si le nombre a une incidence sur le temps de parole. 
Je me suis posé la question de savoir si le temps de parole des femmes est moins que celui des hommes en fonction de l'effectif des journalistes par chaîne.

<div class="flourish-embed flourish-chart" data-src="visualisation/16641215"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Après visualisation, on remarque l'effctif des femmes est plus élevé que celui des hommes. Cependant, le temps de parole des hommes est plus élevé que celui des femmes. 


## 6. Bloopers

<div class="flourish-embed" data-src="story/2158351"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<div class="flourish-embed flourish-chart" data-src="visualisation/16634188"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
