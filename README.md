npx @angular/cli@latest new frontend 

Maven, c’est l’outil qui construit et gère le backend Java. Il télécharge les bibliothèques nécessaires (Spring, le pilote MySQL, etc.), compile le code et lance les tests. Le projet généré inclura mvnw, le Maven Wrapper : tu pourras utiliser Maven même sans l’installer séparément.

JPA est une spécification Java qui permet de manipuler les données sous forme d’objets et de les relier aux tables de la base. Spring Data JPA facilite ce travail ; Hibernate, inclus par défaut, s’occupe généralement de l’implémentation.