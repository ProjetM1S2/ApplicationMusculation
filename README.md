
#<span style="color:orange">Rapport projet</span>
 
 
###Sujet : Musclez votre jeu!

>###1.Introduction:

__Musclez votre jeu!__ est une application qui permet à un utilisateur de suivre ses performances dans la pratique d’un sport.

Dès son inscription sur l’application, l’utilisateur rentre ses mensurations. Il a la possibilité de les mettre à jour sinon l’application lui demande chaque semaine.

L’application permet à l’utilisateur de rentrer ses propres exercices (selon ses propres critères). L’utilisateur peut pour chaque jour spécifier les exercices qu’il a fait parmi ses exercices personnalisés ou en rentrant tout simplement les caractéristiques des efforts qu’il a produits. Si l’utilisateur  ne trouve plus d’idées d’exercice, le système pourra également lui en générer en fonction de ses performances et de ses exercices personnalisés.
L’utilisateur rentre un plan d’entraînement qu’il pourra modifier dans le temps.

L’application en fonction des performances et des exercices de l’utilisateur peut également lui générer en programme plus adapté (que l’utilisateur peut modifier).

L’application permet à l’utilisateur de voir les progrès effectués dans le temps ainsi que l’évolution de son physique dans le futur s’il se tient au programme qu’il s’est fixé ou que l’application lui a proposé.


>###2.Cas d’utilisation:
   
* l’utilisateur s’enregistre en fournissant _nom, prénom, login, mail et en créant un mot de passe,  son sexe, date de naissance, taille et poids_.
* L’utilisateur se connecte en fournissant son _login et mot de passe_.
Il a alors accès au Dashboard qui lui propose les fonctionnalités suivantes:
 * __Créer un exercice :__ L’utilisateur propose un exercice portant un titre, une description, des répétitions et un temps… Chaque exercice est spécifique aux choix de l’utilisateur : par exemple il peut avoir un temps mais pas de répétition (ex: footing).
 * __Enregistrer une séance de l’exercice effectué :__ L’utilisateur saisie les données réalisés durant la séance par rapport aux objectifs de l’exercice. Par exemple, il a un objectif de 10 km mais ne cours que 7 km.
 * __Enregistrer d’autres mesures dans le temps :__ L’utilisateur peut renseigner son poids actuel, son poids désiré, son temps de sommeil,...
 * __Visualiser l’évolution de ces progrès à l’aide de graphiques :__ Ces graphiques seront exprimés par rapport à certaines variables dans le temps. Exemple l’évolution du poids dans le temps, les calories dépensées, les objectifs réalisés par rapport à ceux de l’exercice.
 * __L’utilisateur pourra définir un plan d'entraînement :__ pour cela il choisit la série d’exercice qu’il veut effectuer durant un temps donnée, il lui associe un niveau de difficultés.
Le système récupérer le prochain exercice à effectuer par rapport au plan d’entrainement suivie.
 * __Le système génère le plan d'entraînement à effectuer en fonction de l’évolution des performances de l’utilisateur :__ Par exemple le niveau de difficulté peut augmenter.
L’utilisateur ne peut suivre qu’un plan d'entraînement à la fois.
 * __L’utilisateur peut désactiver son compte.__


>###3.les compléments d’informations nécessaires à la réalisation du projet:

* Les statistiques à afficher et les formules mathématique à appliquer.
* Informations sur les différents exercices de musculation.
* Informations sur la sécurité et la bonne pratique des exercices proposés.
* Savoir comment les données mesurés (le sommeil, l’âge, le poids…)  influencent sur les performances de l’utilisateur.

>###4.Les points délicats à traiter:

* Générer des graphes
* Générer des plans d'entraînement automatique en fonction des performances de l’utilisateur
* La création du système d’information
* L’influence des mises à jour des données (poids…) sur les exercices
* Tenir compte des paramètres utilisateurs (âge, sexe  et objectif).

>###5. Prototype :
![prototype](http://img15.hostingpics.net/pics/218583projetM1.jpg)








