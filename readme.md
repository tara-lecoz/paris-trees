## Contexte du projet 

Paris, l'une des capitales les plus boisées d'Europe, s'engage à planter 170 000 arbres supplémentaires d'ici 2026.

Le défi : optimiser les tournées d'entretien des arbres pour réduire l'empreinte carbone et maximiser l'efficacité des services municipaux.

Notre mission : en tant que data scientist, participez au challenge "Végétalisons la ville" et analysez un jeu de données complet pour développer des itinéraires optimisés pour les équipes d'entretien.

Notre contribution permettra à Paris de devenir une ville plus verte et plus intelligente.

## Présentation des données utilisées & Traitement de l'analyse des données

Pour effectuer ce travail nous avions à notre disposition un dataset contenant les données suivantes : 

* id
* type_emplacement
* domanialite
* arrondissement
* lieu
* id_emplacement
* libelle_francais
* genre
* espece
* circonference_cm
* hauteur_m
* geo_point_2d_a
* geo_point_2d_b

Ainsi que d'autres variables qui ont été supprimées. Nous avons décidé de garder uniquement ces variables parce qu'il s'agit de celles qui ont le moins de données manquantes. 

Une fois le data set nettoyé et les données importantes pour nous conservée nous avons procédé avec une analyse descritive de la donnée. Dans cette analyse nous regardons d'abord ce qui constitue le dataset en terme de données, les différentes corrélations, les valeurs maximales, minimales, les moyennes etc. 

Le manque de données quantitative dans le dataset rend l'analyse des corrélations compliqué car nous ne pouvons pas forcément former des hypothèses. Ce dataset présente une réeelle difficulté quant à son contenu car il ne nous permet pas d'effectuer une analyse complète. Nous avons tenté d'observer les différentes corrélation entre les hauteurs, les circonférences et les genres / types d'arbres mais nous n'avons pas pu remarquer de corrélation distinctes. La même chose peut être dites par rapport à la localisation des arbres et leur type.

Une analyse plus détailée peut être retrouvée dans le jupyter notebook. 

## Conclusion sur le challenge

Le contexte du projet manquait d'information donc nous n'avons pas pu identifier les critères necessaires qui permettrait de déterminer quelle est la meilleure route possible. Il aurait été intéressant d'avoir à notre disposition un planning de routes, les différents traitements nécessaires pour les arbres ainsi qu'un critère d'importance pour les arbres. Cela nous aurait permis de terminer une route précise en fonction des plannings et des priorités. Ainsi qu'en fonction des différents traitements, arrosages nécessaires pour les différents types d'arbres. 