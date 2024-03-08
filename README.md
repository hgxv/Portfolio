# Portfolio

1. [Projet d'introduction au scrapping](#projet-dintroduction-au-scrapping)
2. [Organisateur de tournoi d'échecs en MVC](#organisateur-de-tournoi-déchecs-en-mvc)
3. [Projet Front - Carrousel style Netflix](#projet-front---carrousel-style-netflix)
4. [Projet Algo - programmation dynamique](#projet-algo---programmation-dynamique)
5. [Premier projet Django - Appli réseau social minimaliste](#premier-projet-django---appli-réseau-social-minimaliste)
6. [Première API Django REST - Système de gestion de projet et de ticket](#première-api-django-rest---système-de-gestion-de-projet-et-de-ticket)
7. [Flask - Debugging et Testing](#flask---debugging-et-testing)
8. [Système CRM - Django REST](#système-crm---django-rest)
9. [Django - Devops et architecture modulaire](#django---devops-et-architecture-modulaire)

# Projet d'introduction au scrapping

Ce projet est le premier de la formation Openclassroom. Il s'agit d'un petit script qui va lire le site http://books.toscrape.com/
et va récupérer toutes les catégories disponibles sur le site, puis créer un fichier csv contenant les données de chacun des livres
présents dans celle-ci.
Il va également récupérer les images associées au livre et les stocker dans un dossier à part, en nommant le fichier avec
un identifiant unique.

https://github.com/hgxv/Projet_2_OC

# Organisateur de tournoi d'échecs en MVC

C'est un projet en console qui permet à l'utilisateur de créer des profils de joueurs, afin d'organiser des tournois.

Le coeur de ce projet est l'algorithme de pairage qui suit le système suisse :
- Au premier tour, les joueurs sont classés selon leur elo
- Lors des rounds suivants, les joueurs ayant le plus de points s'affrontent
- Deux joueurs ne peuvent s'affronter qu'une seule fois

Les tournois sont modulables, on peut choisir le nombre de joueurs, ainsi que le nombre de tours joués.

https://github.com/hgxv/4_OC_MVC_ChessTournament

# Projet Front - Carrousel style Netflix

Pour ce projet, il est nécessaire de lancer l'API fournie par Openclassroom, qui génère une base de données
contenant une liste de films et ses caractéristiques.
Il présente des carrousels contenant les films les mieux notées sur imdb par catégories.

https://github.com/hgxv/Projet6

# Projet Algo - programmation dynamique

Pour ce projet, le script lis un fichier .csv contenant une liste d'actions, leur valeur actuelle, et le revenu après 2 ans.
L'algorithme donne la combinaison la plus rentable d'action à acheter pour un montant donné, où chaque action ne peut
être achetée qu'une seule fois.

https://github.com/hgxv/Projet-7-algo

# Premier projet Django - Appli réseau social minimaliste

Pour ce projet, on a deux types de postes :
- Les reviews
- Les demandes de review

On peut poster une review en réponse à une demande, ou poster une review simplement.
![Accueil du site](/images/9.PNG)

https://github.com/hgxv/Projet_9_OC

# Première API Django REST - Système de gestion de projet et de ticket

Pour cette première API, il est question d'avoir un système sécurisé avec un Java Web Token, qui respecte les RGPD et les
normes de sécurité OWASP.
![Demo API](/images/10_Rest.PNG)

https://github.com/hgxv/10_API_Rest

# Flask - Debugging et Testing

Pour ce projet, il est question de reprendre [ce repo](https://github.com/OpenClassrooms-Student-Center/Python_Testing) et de corriger les différents bugs issued.
Il y a également une implémentation de tests et de fonctionnalités. Le projet est configuré pour suivre les performances avec Locust.
![Demo API](/images/11_show.PNG)
![Demo API](/images/11_locust.PNG)

https://github.com/hgxv/11_Debug

# Système CRM - Django REST
C'est un projet pour une entreprise d'évenementiel. Il doit donc pouvoir 
Pour ce projet, j'utilise une base de données Postgres reliée à une API Django REST. Il est axé sur la sécurité avec le principe
de moindre permission.
Il y a plusieurs profils utilisateurs selon leur rôle dans l'entreprise :
- Vendeur
- Support clientèle
- Management
Chacun de ces profils dispose de permissions qui leur sont propres.

Voici une représentation de la base de données :
![Demo API](/images/12_bdd.PNG)

# Django - Devops et architecture modulaire

Ce projet est un fork de [ce repo](https://github.com/OpenClassrooms-Student-Center/Python-OC-Lettings-FR).
Il est décomposé en 5 parties distinctes :

- Refonte de l'architecture modulaire dans le repository GitHub
- Réduction de diverses dettes techniques sur le projet
- Ajout d'un pipeline CI/CD ainsi que son déploiement
- Surveillance de l’application et suivi des erreurs via Sentry
- Création de la documentation technique de l’application avec Read The Docs et Sphinx.

![Demo API](/images/13_show.PNG)
