# tp_SpringBoot-Swager

#  Introduction :

Cette application est une démonstration de la gestion des étudiants dans une filière, construite avec Spring Boot et Swagger.
Elle permet de gérer les étudiants qui peuvent être admis dans une filière, et les utilisateurs de l'application peuvent avoir plusieurs rôles.

#  Technologies Utilisées :

L'application repose sur plusieurs technologies essentielles pour son développement et son fonctionnement :

Spring Boot : 
Notre framework principal pour la création rapide et simplifiée d'applications Java basées sur Spring. Spring Boot offre une configuration automatique pour faciliter le développement.

JPQL (Java Persistence Query Language) :
Nous utilisons JPQL pour formuler des requêtes complexes qui interagissent avec des bases de données relationnelles dans un environnement Java. Il nous permet de récupérer des données de la base de données de manière orientée objet.

Swagger : Swagger est notre outil de documentation d'API de prédilection. Il génère automatiquement une documentation à partir de notre code source d'API. Les développeurs peuvent ainsi explorer les endpoints, les paramètres acceptés, les réponses renvoyées et d'autres détails de l'API de manière conviviale.

Postman : Pour le test et la validation de nos API, nous utilisons Postman, un outil populaire qui permet de créer, tester et automatiser des requêtes HTTP vers notre API. Cela garantit que notre API fonctionne correctement et renvoie les réponses attendues.

#  Generation de la base de donnees :

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/c467c4fe-e6a6-4162-a1bd-6bb1616dc3b9)

#  API CRUD : 

## Au niveau de POSTMAN :

-Test de l'entitée Filiere :

*Création : POST

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/177d6c04-0dfa-419b-859d-78458c7dbe77)

*Suppression de la filiere "id=2": DELETE

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/b214e59d-74a1-4d8a-ae8c-9e8201a22522)

*Affichage de la liste des filieres : GET

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/46cdd51e-ecab-4b7b-a1ea-79fd65397613)

*Modification de la filiere "id=3": PUT

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/07200db2-22db-484c-836e-6c8f2bed33e7)


-Test de l'entitée Role :

*Création : POST

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/d0b0faa1-4b5e-4b2e-a873-1f78e20d6741)

*Suppression du role "id=5": DELETE

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/72e96702-f208-41d5-8052-21f7d91a8d12)

*Affichage de la liste des roles : GET

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/7a04a770-7a77-4ffe-8389-4b1a538c90e4)

*Modification du role "id=1": PUT

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/5d9837ac-dcd2-47f8-8a15-f768e31454f6)

-Test de l'entitée Student :

*Création : POST

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/df3b846c-c25b-4b87-beb7-639d434e841f)

*Suppression de l'etudiant "id=3": DELETE

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/a27f1327-a19f-4836-8596-0f35827cc002)

*Affichage de la liste des etudiants : GET

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/693da478-2522-4c59-89e2-751a8cdcff57)

*Modification de l'etudiant ayant "id=1": PUT

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/7e857ff8-e2d5-4dc8-9fcc-765b5792f452)

-Test du filtrage d'etudiant par filiere :

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/8ea4a924-7446-47dd-966d-02fcbf9e53f9)

## Au niveau de SWAGER :

-Test pour Filiere :

-GET :

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/571fd6a3-14fc-47d2-bb40-9a46fa519cd2)

-DELETE :

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/b5220ca2-e00e-40e7-8ee1-67d9418020e0)

-POST :

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/66b3149d-f2e2-4478-9b84-f6c67ded577e)

![image](https://github.com/ghita-baghdad/tp_SpringBoot-Swager/assets/147449053/e4e459f0-c24b-4bc9-99e0-c3d8ec4d93a3)

# Conclusion :

Cette application de gestion des étudiants basée sur Spring Boot, JPQL, Swagger et Postman est conçue pour simplifier la gestion des étudiants dans le contexte d'une filière éducative.
Elle offre une manière efficace d'interagir avec les données des étudiants et des utilisateurs, tout en facilitant l'exploration de l'API grâce à Swagger.






















