# Projet Image IntroInfo

Info 111: Il est prévu que vous consacriez chacun une vingtaine d’heures de travail intense, dont quatre en séances de TP et le reste en autonomie.

# 1.1. Évaluation du projet: 
Votre travail sera évalué lors de la dernière séance de TP (semaine du 6 décembre) sous la forme d’une présentation composée d’un petit rapport et d’une soutenance orale individuelle (4 minutes) de votre réalisation, suivie de quelques minutes de questions. La présentation devra inclure :
- Une description précise des fonctionnalités implantées ;
- Quelques éléments pour étayer la robustesse de l’implantation (jeux de tests utilisés) ;
- Les difficultés rencontrées ;
- Une discussion sur quelques extraits de code bien choisis.

Elle pourra utilement être complétée par une mini-démonstration. Il est fortement recommandé de travailler en binôme. Cependant, vous devrez démontrer, durant la présentation orale, votre maîtrise de l’ensemble du projet.

# 1.2. Niveaux de difficultés du projet :

Les sections contenant des questions à traiter sont annotées comme suit en fonction de leur difficulté :
- Question facile : « (*) »
- Question moyenne : « (**) »
- Question difficile : « (***) »

Les sections "Aller plus loin" sont facultatives, mais vous donnent des bonus.

Ce projet peut paraître impressionnant. Ne vous fiez pas à votre première impression. D’une part, il est volontairement long afin que chacun puisse s’exprimer en fonction de ses compétences, de son éventuelle expérience préalable et de ses goûts. À vous de choisir un sous-ensemble adapté des questions. Il a été conçu pour qu’un étudiant sans expérience de programmation préalable mais ayant suivi le module avec assiduité puisse facilement avoir au minimum 12. D’autre part, l’expérience que vous accumulerez au cours des premières questions vous fera paraître les questions ultérieures plus simples. Et vous aurez un vrai sentiment d’accomplissement en progressant dans le sujet.

Toutes les parties portent sur des techniques basiques de traitement d’images. Mais bien évidemment, ce n’est qu’un prétexte pour vous faire travailler les notions centrales du cours : tests, tableaux, boucles, fonctions, compilation séparée. Aucune notion de traitement d’images n’est prérequise.

## 1.3. Les différentes parties du projet :

Le projet comporte six parties principales :
- 2 : Traitements basiques d’images binaires
- 3 : Traitements basiques d’images en niveaux de gris
- 4 : Extraction de contours
- 5 : Mise en place d’une bibliothèque de traitement d’images
- 6 : Traitements d’images en couleurs
- 7 : Segmentation en régions homogènes

Remarque : Les premiers exercices sont réalisés dans des fichiers indépendants. Puis, à la fin du projet, on passe à une organisation multi-fichiers dans le but de créer une bibliothèque de traitement d’images. Les exercices de la partie 2 sont conçus de façon progressive pour introduire les notions de base dont nous aurons besoin dans le projet. Les fonctions de la partie 3 sont indispensables pour la suite du projet. L’objectif est d’arriver à implanter la partie 4 (qui dépend de 3) et la partie 7 (qui dépend de 3 et 6). À l’intérieur d’une partie, les questions se suivent (sauf entre les sections 7.1 et 7.2 où une fonction est fournie pour continuer). En dehors de ces dépendances, vous pouvez travailler sur ce projet dans l’ordre que vous souhaitez.

Une archive est fournie sur le web, contenant :
- Une proposition de squelette des fichiers, avec de la documentation et des tests ;
- Des exemples d’images et des résultats de traitements par les différents filtres pour comparer avec les vôtres.

# 1.4. Comment tester vos fonctions et programmes :
Lors des premiers exercices, vous trouverez des tests directement dans les fichiers à remplir. Pour le dernier exercice, une batterie de tests est fournie dans le fichier tests.cpp. À noter qu’une partie seulement des tests est automatique : le nom des images que vous devrez comparer visuellement s’affichera à l’écran.
