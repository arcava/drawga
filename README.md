# Drawga

Drawga est une micro-application écrite en AngularJS permettant de formater le contenu d'un export de User Stories (Récits d'Utilisateurs) d'un projet Taiga.

## Utiliser

Vous pouvez utiliser l'application directement sur github à cette adresse : http://github.com/juliensoret/drawga .

## FAQ 

> Comment exporter le fichier .csv nécessaire ?

Dans votre projet Taiga : Partie Administration, puis Projet => Rapports => Rapports des récits utilisateurs.

> Comment est remplie la case "En tant que" ?

Pour le moment, l'application utilise le premier texte placé entre `En tant que` et `je` ou entre `[` et `]`.

## Crédits

* Le code de la directive pour lire le fichier CSV à l'upload vient de [veamospues.wordpress.com](https://veamospues.wordpress.com/2014/01/27/reading-files-with-angularjs/).
* Le motif d'arrière-plan vient de [toptal.com/designers/subtlepatterns](https://www.toptal.com/designers/subtlepatterns/seigaiha/).
