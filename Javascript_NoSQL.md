NoSQL

La modélisation de données peut se faire directement au niveau du code, comment ? C’est assez simple puisqu’il suffit d’utiliser le format JSON (JavaScript Object Notation) pour stocker toutes les variables (membres) d’un objet. JSON permet de modéliser de façon intuitive et recursive toutes les données relatives à un objet et de les regrouper au sein d’une variable qui pourra être manipulée directement dans le code.

Une fois vos données au format JSON cela devient très simple de les stocker au niveau d’une base NoSQL, pourquoi? Car les bases de données NoSQL utilisent généralement le format BSON qui constitue en fait une version binaire du format JSON, il est donc très facile de passer d’un de ces formats à l’autre.

En bref, cela signifie qu’on peut se permettre de penser la modélisation de données directement au moment de l’écriture du programme. On peut aussi maintenant stocker des données dans une base sans même avoir connaissance de la structure de données, ce qui était impossible avec des bases relationnelles. Si des données sont au format JSON alors elle peuvent être facilement stockées dans une base NoSQL comme mongoDB ou couchDB.

Le gain de temps se fait donc à la création de la base de données en économisant la réflexion de la modélisation de la base, mais aussi à chaque modification de la nature des données où cette reflexion n’est plus nécessaire.

Conclusion

En fait la réflexion sur le modèle de données à toujours lieu, simplement elle se fait plus naturellement et au moment de coder, ce qui était déjà le cas avec les bases de données relationnelles. Mais celles-ci apportaient surtout des contraintes et de la rigidité, ce qui nécessitait une réflexion plus importante, consommatrice de temps.

En résumé, l’utilisation de Javascript et de son format de données JSON d’un côté et des bases de type NoSQL au format BSON de l’autre permettra dans un avenir proche de considérer la modélisation de données comme une discipline faisant partie du passé de la jeune histoire de l’informatique.
