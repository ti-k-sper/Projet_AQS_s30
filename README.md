# Challenge Projet Libre

Réalisez un « site web » en partant de votre propre expérience, vos idées, en utilisant les technologies vues en cours : HTML5(ou Bootstrap), CSS( ou SASS), js, jquery, php mysql, MVC.

Suivez les instructions fournies pas les formateurs : 
- tpdevwebwebmobile.pdf (ressource/...)

----

## Étape 1 - Cahier des charges:

Suite au premier rendez-vous avec le client, récupération des images, catalogue des formations, ainsi que de la CGV.  
Proposition de différents menus, visualition de la page acceuil.  
Ci-dessous, les points validés et à effectuer : 

- Nom de domaine : "localhost:8081" - "www.AllierQualiteSante.fr"
- Nom du site (nom a donné au client suite recherche web) : "Allier Qualité Santé - AQS"
- Couleurs (charte graphique du client) : 
  - <span style="background : #760089; color : white">Violet (#760089)  </span>,  
  - <span style="background : #7DB344; color : white">Vert (#7DB344)  </span>, 
  - <span style="background : #D2A4D3; color : white">Mauve (#D2A4D3)  </span>,
  - <span style="background : #30A9F1; color : white">Bleu (#30A9F1)  </span>.
- Logo et/ou bannière (provenant le client) :
  - ![Logo](/ressource/logo_banniere_AQS_resize_moitie.jpg)
- Nombre de pages :
  - 10 pages (peut-être plus).
- Nom des pages et URL : 
  - Accueil : '/', 'Site#index', 'accueil',
  - Catégories : '/categories', 'Categories#all', 'categories',
  - Formations : '/formations/[i:id]-[*:slug]', 'Formations#show', 'formations',
  - Connexion : '/connexion', 'User#login', 'connexion',
  - Inscription : '/inscription', 'User#subscribe', 'inscription',
  - Profil : '/profil', 'User#show', 'profil',
  - Déconnexion : '/deconnexion', 'User#logout', 'deconnexion',
  - Contact : '/contact', 'Site#contact', 'contact',
  - Admin : '/admin', 'Admin#index', 'admin',
  - Validation compte : '/validation', 'User#userValidate', 'validation'.
- Futures fonctionnalités : 
  - Visualisation de la formation avec possibilité de faire la demande d'inscription directement,
  - Pour l'utilisateur : 
    - Via la page profil, voir sous forme de dashboard, sa propre évolution durant sa formation avec les points validés
    et les points à améliorer (commentaire mis par le formateur (client)), comme un genre de rapport,
    - Modifier ses coordonnées,
    - Contacter le formateur (client) sans passer par la page 'contact',
    - Un calendrier.
  - Pour le client (formateur) : 
    - Via la page admin, voir sous forme de dashboard, un calendrier, le nombre d'aprenant, un accés aux différents profils,
    - Gestion des données, ajouter, modifier les formations,
    - Mise à jour des nouvelles périodes de formations,
    - Pouvoir accéder aux profils des aprenants pour ainsi valider, donner des commentaires sur leur formation en cours,
    - Contacter sans passer par la page 'contact', l'aprenant,
    - Un calendrier, contenant les périodes de formations avec le nombre d'apprenants, en cliquant dessus pouvoir voir la liste.

## Étape 2 :

- Maquette :
  - Accès au site : 
  ![Acceuil site](/ressource/maquette/accueilaccessite.png)