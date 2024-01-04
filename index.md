
# Temps de parole des hommes et femmes à la radio et la télé
![Image de média](https://img.etimg.com/thumb/width-1800,height-900,imgsize-458873,resizemode-75,msid-70322833/industry/media/entertainment/media/tv-and-radio-companies-want-broadcast-policy-to-protect-media-freedom.jpg) 
source:image google
# Sommaire 
1. [Introduction](#introduction)
2. [Choix et recueil du jeu de données](#jeuDeDonnées)
3. [Traitement des données](#traitement)

## Introduction <a name="Introduction"></a>
J'ai choisi de travailler sur la différence de temps accordée aux hommes et aux femmes sur les médias notamment à la radio et à la télé.
Pour faire une visualisation sur le thème de temps de parole des hommes et femmes dans les médias, il a fallu recueillir des open data sur différents sites. Après collecte des données, j'ai décidé de réduire et de synthétiser mes données et de ne travailler que sur la plage qui m'interesse. J'ai donc réduit les données sur une période de 5 ans à savoir entre 2015 et 2019. 


**Les chaînes de télé analysées sont les suivantes:**  Arte, Animaux, BFM TV, Canal+, Canal+ Sport, Chasse et pêche, Chérie 25, Comédie+, D8/C8, Euronews, Eurosport France, France 2, France 24, France 3, France 5, France O, Histoire, I-Télé/CNews, L'Equipe 21, LCI, LCP/Public Sénat, La chaîne Météo, M6, Monte Carlo TMC, NRJ 12, Paris Première, Planète+, TF1, TV Breizh, TV5 Monde, Toute l'Histoire, Téva, Voyage, W9.


**Les chaînes de radio analysées sont les suivantes:** Chérie FM, Europe 1, France Bleu, France Culture, France Info, France Inter, France Musique, Fun Radio, Mouv’, NRJ, Nostalgie, RFM, RMC, RTL, RTL 2, Radio Classique, Radio France Internationale, Rire et Chansons, Skyrock, Sud Radio et Virgin Radio.


Les temps de parole sont estimés par tranches d'une heure, de 5h à minuit pour la radio et de 10h à minuit pour la télévision.

## Choix et recueil du jeu de données
![Image micro](https://previews.123rf.com/images/forestrun/forestrun1902/forestrun190200024/133670236-professional-microphone-in-radio-studio.jpg)
source:image google

Les données sont recueillies en open data sur le site data.gouv
>[Données sur temps de parole des hommes et des femmes à la radio et à la télé](https://www.data.gouv.fr/fr/datasets/temps-de-parole-des-hommes-et-des-femmes-a-la-television-et-a-la-radio/#/resources)



J'ai choisi le jeu de données de temps de parole des hommes et femmes à la radio et à la télé parmi les données proposées. J'ai décidé de reduire la période à 5ans.
Voici un extrait du fichier analysé:


|-------|--------------------|--------------------|----------------------|
| ANNEE | channel_name       |     male_duration  |     female_duration  |
| 2015  | Animaux            |     1 645 238      |        956 988       |
| 2015  | ARTE               |     3 123 603      |     1 231 907        |
| 2015  | BFM TV             |     3 501 573      |     1 773 802        |
| 2015  | Canal+             |     3 339 791      |        916 718       |
| 2015  | Canal+ Sport       |     2 761 056      |        142 649       |
| 2015  | ChÃ©rie 25         |     2 534 101      |     1 509 401        |
| 2015  | ChÃ©rie FM         |        631 373     |        663 166       |
| 2015  | Chasse et pÃªche   |     2 148 307      |        216 361       |
| 2015  | ComÃ©die+          |     1 684 000      |        711 369       |
| 2015  | France Culture     |     3 610 380      |     1 631 197        |
| 2015  | TV5 Monde          |     1 869 065      |        785 390       |
| 2015  | Virgin Radio       |        910 589     |        350 977       |
| 2016  | Animaux            |     1 634 839      |        942 338       |
| 2016  | ARTE               |     3 164 116      |     1 246 289        |
| 2016  | BFM TV             |     3 326 119      |     1 841 251        |
| 2016  | Canal+             |     3 321 179      |        942 185       |
| 2016  | Canal+ Sport       |     2 845 340      |        144 663       |
| 2016  | ChÃ©rie 25         |     2 445 623      |     1 759 206        |
| 2016  | ChÃ©rie FM         |        605 165     |        634 178       |
| 2016  | Chasse et pÃªche   |     2 204 722      |        172 565       |
| 2016  | ComÃ©die+          |     1 768 249      |        705 293       |
| 2016  | D8/C8              |     3 467 974      |     1 228 273        |
| 2016  | Euronews           |     1 714 132      |        768 604       |
| 2016  | Europe 1           |     3 389 069      |     1 741 753        |
| 2016  | France Culture     |     3 785 565      |     1 830 181        |
| 2016  | France Info        |     3 910 029      |     1 688 116        |
| 2016  | LCP/Public SÃ©nat  |     3 777 666      |     1 644 435        |
| 2016  | L'Equipe 21        |     4 729 000      |        519 137       |
| 2016  | M6                 |     2 621 892      |     1 838 931        |
| 2016  | Monte Carlo TMC    |     2 933 446      |     1 220 734        |
| 2016  | MOUV               |        676 694     |        320 761       |
| 2016  | Nostalgie          |        748 343     |        481 719       |
| 2016  | NRJ                |     1 420 215      |        529 194       |
| 2016  | NRJ 12             |     2 821 479      |     1 448 634        |
| 2016  | Paris PremiÃ¨re    |     1 876 543      |        545 368       |
| 2016  | PlanÃ¨te+          |     2 145 703      |        435 923       |
| 2016  | Radio Classique    |     1 130 984      |        642 432       |
| 2016  | RFI                |     3 490 405      |     1 854 570        |
| 2016  | RFM                |        654 968     |        332 059       |
| 2016  | Rire et Chansons   |     3 144 646      |     1 144 369        |
| 2016  | RMC                |     4 642 658      |        950 180       |
| 2017  | Animaux            |     1 550 192      |        937 349       |
| 2017  | ARTE               |     3 001 213      |     1 277 691        |
| 2017  | BFM TV             |     3 299 401      |     1 860 405        |
| 2017  | Canal+             |     3 154 239      |        890 497       |
| 2017  | France 2           |     2 936 590      |     1 681 791        |
| 2017  | I-TÃ©lÃ©/CNews     |     4 110 239      |     1 698 544        |
| 2017  | La chaÃ®ne MÃ©tÃ©o |     2 250 442      |        453 498       |
| 2017  | LCI                |     3 465 760      |     1 646 961        |
| 2017  | LCP/Public SÃ©nat  |     3 584 742      |     1 640 219        |
| 2017  | L'Equipe 21        |     4 438 813      |        652 357       |
| 2017  | M6                 |     2 426 742      |     1 875 444        |
| 2017  | Monte Carlo TMC    |     2 882 344      |     1 240 334        |
| 2018  | Animaux            |     1 475 340      |     1 025 229        |
| 2018  | ARTE               |     3 644 717      |     1 648 909        |
| 2018  | BFM TV             |     4 051 134      |     2 378 788        |
| 2018  | Radio Classique    |     1 594 247      |        910 651       |
| 2018  | RFI                |     6 046 376      |     2 998 556        |
| 2018  | RFM                |     1 155 814      |        617 332       |
| 2018  | Rire et Chansons   |     4 839 996      |     1 719 466        |
| 2018  | RMC                |     7 935 539      |     1 577 283        |
| 2018  | RTL                |     5 837 643      |     2 459 175        |
| 2018  | RTL 2              |     1 015 121      |        806 105       |
| 2018  | Skyrock            |     2 759 366      |        506 528       |
| 2018  | Sud Radio          |     5 739 368      |     2 801 082        |
| 2018  | TF1                |     3 258 465      |     2 014 743        |
| 2018  | Toute l'Histoire   |     2 162 871      |        473 006       |
| 2018  | TV Breizh          |     1 519 168      |        711 319       |
| 2018  | TV5 Monde          |     1 726 992      |        933 227       |
| 2018  | Virgin Radio       |     1 849 363      |        590 290       |
| 2019  | Animaux            |     1 310 231      |        821 350       |
| 2019  | ARTE               |     1 448 996      |        707 776       |
| 2019  | BFM TV             |     1 749 685      |        910 678       |
| 2019  | Canal+             |     1 628 037      |        478 149       |
| 2019  | Canal+ Sport       |     2 507 609      |        135 782       |
| 2019  | ChÃ©rie 25         |     1 340 612      |        888 253       |
| 2019  | ChÃ©rie FM         |        376 524     |        357 088       |
| 2019  | Chasse et pÃªche   |     1 917 493      |        262 611       |
| 2019  | ComÃ©die+          |     1 367 232      |        694 013       |
| 2019  | D8/C8              |     1 526 740      |        648 571       |
| 2019  | Euronews           |     1 488 445      |        826 640       |
| 2019  | Europe 1           |     2 083 347      |     1 410 990        |
| 2019  | Eurosport France   |     2 305 688      |        252 167       |
| 2019  | France 2           |     1 403 641      |        894 336       |
| 2019  | France 24          |     1 341 706      |     1 234 406        |
| 2019  | France 3           |     1 436 585      |        804 822       |
| 2019  | France 5           |     1 544 202      |        917 929       |
| 2019  | France Bleu        |     1 473 454      |        873 362       |
| 2019  | France Culture     |     2 357 351      |     1 257 623        |
| 2019  | France Info        |     2 718 496      |     1 120 455        |
| 2019  | France Inter       |     2 182 146      |     1 141 413        |
| 2019  | France Musique     |        589 819     |        360 779       |
| 2019  | France O           |     1 404 961      |        838 163       |
| 2019  | Fun Radio          |        775 558     |        420 822       |
| 2019  | Histoire           |     1 709 179      |        543 951       |
| 2019  | I-TÃ©lÃ©/CNews     |     1 841 837      |        837 630       |
| 2019  | La chaÃ®ne MÃ©tÃ©o |     2 183 053      |        346 987       |
| 2019  | LCI                |     1 870 422      |        842 139       |
| 2019  | LCP/Public SÃ©nat  |     1 789 019      |        918 346       |
| 2019  | L'Equipe 21        |     2 210 432      |        368 161       |
| 2019  | M6                 |     1 237 199      |        959 699       |
| 2019  | Monte Carlo TMC    |     1 381 865      |        678 938       |
