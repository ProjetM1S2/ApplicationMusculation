#<span style="color:orange">Rapport Architecture</span>

###Sujet : MiageCoaching!

>###1.Les technologies utilisées :

* __Les langages utilisés  :__
Nous utiliserons le langage Java pour le développement de notre application. Pour cela nous utiliserons également 
le langage JSP qui va nous permettre de réaliser une application web et dynamique. Tout cela etant gérer par une servlet.


* __Les librairies  :__
Pour la réalisation des graphes, nous utiliserons les librairies JavaScript 
    * [Highcharts] (http://www.highcharts.com/)
    * [amCharts] (http://www.amcharts.com/) 
    
* __La base de données  :__
Nous utiliserons une base de donnée mySQL.

>###2.Les acteurs :
* __Les acteurs  :__
L'utilisateur est un acteur dans notre cas. C'est lui qui va interagir avec l'application et effectué les demandes. 

>###3.Architecture de l'application :

Dans le cadre de ce projet, nous utiliserons une architecture Modèle-Vue-Controlleur (MVC).
Celle ci nous semble être la plus à même afin répondre aux problèmes que peut nous poser l’application. 
La servlet jouera le rôle de contrôleur, elle va permettre de vérifier les demandes de l’utilisateur et de les traiter avec les modèle correspondant. Une fois que le modèle correspondant a effectué le traitement, la vue est chargé d’afficher le résultat à l’utilisateur.
Dans le modèle, il y aura des classes qui se chargeront d’effectuer le traitement des données. Le diagramme des classes plus bas représentent justement les différentes interactions que l’on a entre les classes pour ce projet.
Dans la vue, il y aura essentiellement des fichier jsp. Ces fichier se chargeront d’effectuer l’affichage de manière ergonomique.