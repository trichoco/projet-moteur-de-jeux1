# Projet Moteur de Jeux

Notre projet consiste à développer un moteur de jeux en 3D avec l'API OpenGL, et un jeu l'accompagnant conçu avec cet outil.
Le concept résiderait davantage dans la modélisation 3D du jeu que dans l'édition de son gameplay.
 
  ## Objectifs

  Le projet dans sa quasi-globalité est une découverte totale. Même si notre interêt commun pour le média numérique des jeux vidéos est ce qui est a orienté notre choix,
  la manière de parvenir à notre objectif est encore ponctuée de quelques zones d'ombre.
  ### Description du moteur de jeux
  
  Même si la notion de moteur de jeux est une sorte de "boîte noire" sur certains aspects, elle n'en reste pas moins appréhensible et réalisable.
     L'un des objectifs du projet serait d'ouvrir cette "boite noire" pour en explorer les mécanismes.
     Le second serait de pallier le principal défaut que l'on peut entendre sur l'utilisation des moteurs de jeux lors du développement de jeux vidéos :
     ils ne seraient pas spécifiques (et donc pas optimisés pour développer un jeu vidéo).
     Bien entendu, nous n'avons ni l'ambition ni la prétention de concurrencer de tels logiciels.
     Notre modeste objectif est de créer un outil adapté au concept de jeu que l'on souhaite réaliser.
### Langages et API utilisées
La bibliothèque OpenGl est associé au langage C++.
     Bien que la totalité du groupe, au cours de sa formation dans l'enseignement secondaire (ou autrement pour les plus intrépides), ait pu programmer avec des langages apparentés
     au C++ (C, Csharp, Java, etc), on peut affirmer qu'il est une terre que l'on ne peut qualifier de conquise.
     Réaliser un tel projet nous permettrait de gagner en polyvalence en développant dans un langage que nous ne maitrisons pas.
### Modélisation 3D et mathématiques accociées
Le concept de notre jeu vidéo est orienté autour d'un environnement 3D qui se génère aléatoirement et sur une surface gigantesque (autrement appelé génération procédurale du terrain).
     Des jeux tels que YLANDS, Equilinox ou No Man's Sky sont totalement orientés sur ce principe.
     Mais la modélisation qu'elle soit 2D ou 3D est un domaine qui ne nous est pas familier en pratique.
     De ce que l'on peut trouver en survolant sa definition c'est qu'il est lié à de nombreuses notions d'arithmétiques.
     On peut donc supposer que nous approfondirons des concepts que nous avons déjà aborder (ou non) dans un domaine qui nous est étranger.

### Travail de Groupe 
Programmer à plusieurs est un exercice que la plupart d'entre nous ont déjà vécu. Mais pas tous. C'est un moyen d'apprendre (ou de perfectionner) sa coordination et sa façon de coder pour rendre l'expérience de chacun la plus profitable possible. Ajoutons à cela que l'aspect communication sera renforcé par l'usage de GiHub et Discord qui permettront à chacun de faire évoluer le projet quand il le souhaite et de le communiquer ensuite aux autres. 
## Démarches 
Le projet n'ayant pas encore debuté, les étapes avancées de sa construction sont encore floues : aucun de nous cinq n'a encore eu l'occasion de réaliser quelque chose de semblable. La première chose à faire est donc la suivante : se documenter. 
### Documentation et Information 
Cette démarche a déjà été partiellement entreprise. 
Les principales ressources trouvées (si ce n'est la totalité) sont éléctroniques. La Bibliothèque Universitaire nous a fournit deux ouvrages éléctroniques concernant la programmation avec OpenGL :

- OpenGL Build high performance graphics
- OpenGL Came Development By Example

Le reste s'apprendra surement à l'aide de tutoriels et l'articles disponibles sur Internet. En s'informant, nous en apprendrions davantages sur les aspects techniques de notre projet.

### Définition concrète en UML
La seconde étape de ce projet consisterait a concevoir le projet sous la forme de diagramme de classes, d'objets, de séquences ou de cas d'utilisation pour mieux en cerner les enjeux. Le but étant de définir, avec le plus de précisions possibles l'étendue de nos attentes vis à vis de ce projet. Etant encore vagues, les démarches suivantes s'eclairciraient lorsque nous aborderons cette étape munis d'une documentation et de connaissances suffisantes. 

### Idée abstraite du processus de développement
Le processus de conception, tel qu'on se le représente maintenant est le suivant:
- Mise en place de l'environnement de programmation et des fonctions de bases permettant le rendu de primitives
- Définition de functions permettant le rendu de modèles 3D d'après des primitives.
- Réalisation de la génération procédurale du terrain
- Gestion des entrées utilisateurs et de la caméra 
- Écriture de scripts de shaders pour le rendu graphique
- Conception du moteur physique et de la détection des collisions
- Ajouts des personnages et d'éléments de gameplay
- Embellisement des graphismes et optimisation des performances
