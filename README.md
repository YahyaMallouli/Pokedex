# Pokedex

Pokedex

--> Description
Le projet Pokedex est une application Android qui permet de rechercher et d'afficher des informations sur les différents Pokémon, tels que leur nom, leur image, leur type, leur attaque, leur défense, leur vitesse et leur description. Le projet utilise l'API PokeAPI pour construire une interface RESTful et accéder à des données détaillées sur les Pokémon.

--> Fonctionnalités
Les fonctionnalités clés de l'application Pokedex incluent :

 -Recherche de Pokémon : L'application permet à l'utilisateur de rechercher des Pokémon par nom ou par numéro de Pokédex.
 -Affichage des informations du Pokémon : Une fois qu'un Pokémon est sélectionné, l'application affiche des informations détaillées sur ce Pokémon, telles que son type, son attaque, sa défense, sa vitesse et sa description.
 -Favoris : L'utilisateur peut ajouter des Pokémon à sa liste de favoris pour les retrouver facilement plus tard.
Technologies utilisées
 -Le projet Pokedex est basé sur le MVVM (Model-View-ViewModel) Architecture, qui permet de séparer la logique de l'interface utilisateur de la logique métier. Les autres technologies et composants utilisés dans le projet comprennent :

Repository Pattern : Ce pattern permet de centraliser l'accès aux données de l'application, en fournissant une couche d'abstraction entre l'interface utilisateur et les sources de données sous-jacentes.
ViewModel : Ce composant permet de stocker et de gérer des données de l'application qui doivent survivre aux changements de configuration, tels que les rotations d'écran.
LiveData : Cette classe permet de stocker et d'observer des données, ce qui permet à l'application de répondre de manière réactive aux changements de données.
ViewBinding : Cette fonctionnalité permet de lier des vues d'interface utilisateur à des variables dans le code Java ou Kotlin, ce qui facilite l'interaction avec les vues.
SwipeRefreshLayout : Ce composant permet de mettre en œuvre le modèle d'interface utilisateur de balayage vers le bas pour rafraîchir, ce qui permet à l'utilisateur de rafraîchir les données affichées à tout moment.
API utilisée
Le projet Pokedex utilise l'API PokeAPI pour accéder aux données détaillées sur les différents Pokémon. PokeAPI est une API RESTful qui fournit des informations détaillées sur les Pokémon, y compris leurs caractéristiques, leurs capacités, leurs mouvements, leurs statistiques et plus encore. Nous avons choisi d'utiliser PokeAPI car c'est l'une des meilleures sources d'informations sur les Pokémon disponibles, avec des données précises et complètes sur les différentes espèces.
