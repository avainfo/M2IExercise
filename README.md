# M2IExercise

Instructions :

  1. Télécharger le fichier *\*.tar* sur le lien suivant : [WeTransfer](https://we.tl/t-GfjlsQqqOR)
  2. Executer la commande : *docker load -i [ fichier.tar ]*
  3. Executer la commande : *docker run -d -p 27017:27017 --name MongoDB exercice_mongo:latest*
  4. Trouvé un moyen de :
    4.1  Créer une base de données nommées Spotify
    4.2  Créer une collection nommé spotify
    4.3  importez le fichier.csv dans la base de données
    
TIPS :

  >\> mongosh - ouvre un shell pour interragir avec la base de donnée <br />
  >\> use - utiliser (ou créer si elle existe pas)<br />
  >\> show dbs - afficher les bases de données<br />

API :
  - Recherche par artiste 
  - Filtrage par genre
  - Recherche par année
  - Classement par popularité
  - Filtrage par BPM
  - Filtrage par énergie
  - Recherche par durée
  - Système de comparaison


