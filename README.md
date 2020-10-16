# TP3_Partie3

## Comment tester
Dans cette dernière partie, je suis parti sur la base du projet spring-boot-sample-data-jpa-standalone, j'ai utilisé hsqldb pour la problématique de gestion de 
données. La partie Rest se trouve dans le package sample.data.jpa.web, la partie JPA dans le package sample.data.jpa.domain.  
L'aspect pour les log se retrouve dans le package sample.data.jpa.monitor. 
Les deux ressources qui ont été rendues disponibles sont celles liées aux utilisateurs et aux cartes. Il est possible:
1. de rechercher un utilisateur ou une carte par un id (méthode GET)
2. de créer un utilisateur ou une carte en mettant dans le body JSON correspondant à l'objet qu'on souhaite créé (méthode POST)
3. de supprimer une ressource grâce à son id (méthode DELETE)


Pour tester il faudra lancer dans un terminal les fichiers run-hsqldb-server.sh et show-hsqldb.sh. Lancer ensuite le server grâce à la classe src/main/java/sample/data/jpa/SampleDataJpaApplication.java. Lancer POSTMAN pour effectuer les requêtes.
