
# Temps de parole des hommes et femmes à la radio et la télé
![Image de média](https://img.etimg.com/thumb/width-1800,height-900,imgsize-458873,resizemode-75,msid-70322833/industry/media/entertainment/media/tv-and-radio-companies-want-broadcast-policy-to-protect-media-freedom.jpg) 
source:image google
# Sommaire 
1. [Introduction](#introduction)
2. [Choix et recueil du jeu de données](#jeuDeDonnées)
3. [Temps de parole des hommes et des femmes par année et par chaîne](#traitement)
4. [Temps de parole total par ]

## 1. Introduction <a name="Introduction"></a>
J'ai choisi de travailler sur la différence de temps accordée aux hommes et aux femmes sur les médias notamment à la radio et à la télé.
Pour faire une visualisation sur le thème de temps de parole des hommes et femmes dans les médias, il a fallu recueillir des open data sur différents sites. Après collecte des données, j'ai décidé de réduire et de synthétiser mes données et de ne travailler que sur la plage qui m'interesse. J'ai donc réduit les données sur une période de 5 ans à savoir entre 2015 et 2019. 


**Les chaînes de télé analysées sont les suivantes:**  Arte, Animaux, BFM TV, Canal+, Canal+ Sport, Chasse et pêche, Chérie 25, Comédie+, D8/C8, Euronews, Eurosport France, France 2, France 24, France 3, France 5, France O, Histoire, I-Télé/CNews, L'Equipe 21, LCI, LCP/Public Sénat, La chaîne Météo, M6, Monte Carlo TMC, NRJ 12, Paris Première, Planète+, TF1, TV Breizh, TV5 Monde, Toute l'Histoire, Téva, Voyage, W9.


**Les chaînes de radio analysées sont les suivantes:** Chérie FM, Europe 1, France Bleu, France Culture, France Info, France Inter, France Musique, Fun Radio, Mouv’, NRJ, Nostalgie, RFM, RMC, RTL, RTL 2, Radio Classique, Radio France Internationale, Rire et Chansons, Skyrock, Sud Radio et Virgin Radio.


Les temps de parole sont estimés en heure.

## 2. Choix et recueil du jeu de données
![Image micro](https://previews.123rf.com/images/forestrun/forestrun1902/forestrun190200024/133670236-professional-microphone-in-radio-studio.jpg)
source:image google

Les données sont recueillies en open data sur le site data.gouv
>[Données sur temps de parole des hommes et des femmes à la radio et à la télé](https://www.data.gouv.fr/fr/datasets/temps-de-parole-des-hommes-et-des-femmes-a-la-television-et-a-la-radio/#/resources)

J'ai choisi le jeu de données de temps de parole des hommes et femmes à la radio et à la télé parmi les données proposées. J'ai décidé de reduire la période à 5ans.
J'ai donc traité ce jeu de données avec Excel puisque la taille dépassait dix millions de lignes. OpenRefine ne pouvait pas traiter les données. 


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
[corpus première visualisation](https://github.com/Odilestar/M2_DEFI_Datavisualisation_2024/blob/main/Corpus_premiereVisualisation.csv)

<div class="flourish-embed flourish-chart" data-src="visualisation/16342816"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Avec cette visualisation, on remarque que pour toutes les chaînes, que ce soit à la télé ou à la radio, les temps de parole des femmes est inférieur à celui des hommes. 



## 4. Visualisation avec Datawrapper

Pour cette visualisation, j'ai décidé d'afficher la différence de temps total par radio et par télé des hommes et des femmes. 
[deuxieme visualisation](https://github.com/Odilestar/M2_DEFI_Datavisualisation_2024/blob/main/Corpus_TV_Radio.csv)

<iframe title="Temps de parole par radio et par télé   " aria-label="Grouped Bars" id="datawrapper-chart-G8VSF" src="https://datawrapper.dwcdn.net/G8VSF/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="951" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();
</script>

## 5. Enrichissement du jeu de données 

J'ai enrichi mon jeu de données avec le nombre de journalistes pour quelques chaînes. L'objectif est de voir combien de femmes et d'hommes sontemployés et voir si le nombre a une incidence sur le temps de parole.


### Visualisation par nombre de journalistes par chaine 
<div class="flourish-embed flourish-chart" data-src="visualisation/16634188"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


Après visualisation, on remarque l'effctif des femmes est plus élevé que celui des hommes. Cependant, le temps de parole des hommes est plus élevé que celui des femmes. 

### Visualisations ratées

<div class="flourish-embed" data-src="story/2158351"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
