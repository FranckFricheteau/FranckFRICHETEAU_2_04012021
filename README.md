Projet 3 - Site web ohmyfood

Identité et proposition

Ohmyfood est une entreprise de commande de repas en ligne. Ce concept permet aux utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les restaurants car le menu est préparé à l’avance. 
Gain de temps pour consulter la carte des restaurants !
L’objectif est de proposer aux clients des menus de restaurants gastronomiques.

Identité graphique 

Les Polices du site pour logo et titres en Shrikhand. Le texte est en Roboto. 
La charte graphique est #9356DC pour la couleur Primaire, #FF79DA pour le Secondaire et #99E2D0 pour le Tertiaire.

Enjeux

Les objectifs s'articulent sur 2 phases: 

Phase 1 : développer un site proposant le menu de 4 restaurants parisiens.
Phase 2 : Permettre la réservation en ligne et la composition de menus.

Fonctionnement

Technologies :

Un développement uniquement en CSS, pas de JavaScript.
Framework interdit, l’utilisation du SASS est un plus.(fichier oh_my_food.sass)
Pas de de code CSS appliqué via un attribut style dans une balise HTML.

Compatibilité

Le site est développé en utilisant l’approche mobile-first(consiste à concevoir un site en mettant la priorité sur la version mobile et en adaptant progressivement le web design pour les écrans + larges). 
Seules les maquettes mobiles sont réalisées. 
Le site s’adapte également sur tablette et desktop mais ces supports ne sont pas prioritaires, leur mise en page est forcément libre.
L’ensemble du site est responsive sur mobile, tablette et desktop.
Les pages passent la validation W3C en HTML et CSS sans erreur. 
Le site est parfaitement compatible avec les dernières versions desktop de Firefox et de Chrome.

Contenu des pages

Pages d’accueil (x1) :

La localisation des restaurants s’affiche correctement avec la possibilité de choisir sa localisation pour trouver des restaurants proches d’un certain lieu. ( bouton Explorer nos restaurants avec un scroll qui dirige vers la section restaurants).
Une courte présentation de l’entreprise est présente (Nom du restaurant + localisation)
Présence d’une section contenant les 4 menus sous formes de cartes. 
Au clic sur la carte, l’utilisateur est redirigé vers la page de menu du site.

Pages de menu (x4) :

Présence de 4 pages contenant chacune le menu d’un restaurant.

Header :

Le Header est présent sur toutes les pages du site. (header = logo du site)
Sur la page d’accueil, il contient le logo du site. (ohmyfood)
Sur les pages de menu, il contient également un bouton de retour vers la page d’accueil.

Footer :

Le footer est identique sur toutes les pages. (accueil + 4 pages de menus)
Au clic sur « contact », un renvoi vers une adresse mail est effectué. (envoi sur mon adresse gmail)

Effets graphiques et animations

Les effets accessibles au clic et au survol sont visibles sur la maquette. 
Ils utilisent uniquement les animations et transitions CSS sans JavaScript ni librairie.(voir code css et sass)

Boutons :

Au survol, la couleur de fond sur les boutons principaux s’éclaircit légèrement. L’ombre portée est plus visible. 
Les visiteurs peuvent sauvegarder leur menu préférés. 
Un bouton j’aime en forme de cœur est présent sur les 4 vignettes des restaurants. 
Au clic, il se remplit progressivement et apparaît au survol sur desktop au lieu du clic.

Page d’accueil :

Un « loading spinner » apparaît pendant entre 1 et 3 secondes lorsque le visiteur arrive sur la page d’accueil, couvre l’intégralité de l’écran et utilise des animations CSS. 
Le design de ce loader est cohérente avec la charte graphique du site.(voir css et sass)

Pages de menu :
A l’arrivée sur la page, les plats apparaissent progressivement avec un léger décalage dans le temps. 
Ils apparaissent un par un.
Le visiteur peut ajouter des plats qu’il souhaite à sa commande en cliquant dessus en faisant apparaître une petite coche à droite du plat. 
Elle coulisse de la droite vers la gauche avec l’effet apparaissant sur desktop au survol au lieu du clic. 
Lorsque l’intitulé du plat est trop long, il est rogné avec des points de suspension.







