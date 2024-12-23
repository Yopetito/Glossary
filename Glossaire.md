# GLOSSAIRE

- [Général](#général) (9 / 17)
- [Front-end](#front-end) (9 / 17)
- [UX / UI](#ux-ui) (3 / 8)
- [POO] (#Programmation orienté objet POO) (8 / 17)
- [Architecture](#architecture) (0 / 7)
- [Modélisation / Base de données](#modélisation---base-de-données) (8 / 17)
- [Symfony](#symfony) (0 / 10)
- [Sécurité](#sécurité) (0 / 10)
- [RGPD](#rgpd) (9 / 10)
- [SEO](#seo) (0 / 13)
- [Gestion de projets / DevOps](#gestion-de-projets---devops) (0 / 16)
- [English](#english) (6 / 8)

TOTAL = 54 / 150

## Général 9 / 17
1.	Quel est l’environnement à installer pour exécuter un script PHP ? Citer 2 exemples de logiciels permettant ce contexte
Laragon, WAMP. ()

2.	Qu’est-ce qu’un algorithme ?  
    Suite d'instructions.

3.	Qu’est-ce qu’une variable ? Par quel symbole est préfixée une variable en PHP ?
    espace de mémoire qui sert a stocker donnée, valeur, et peut changer au cours de l'algorithme.
    en php: $nomDeLaVariable

4.	Qu’est-ce que la portée d’une variable ?
    l'endroit ou cette variable peut etre utilisé.

5.	Qu’est-ce qu’une constante ? Quelle est la différence avec une variable ?
    valeur nommée qui peut pas etre modifié. Var : conteneur dynamique, const: donnée fixe.

6.	Qu’est-ce qu’une superglobale, combien en existent-ils et donner un exemple d’utilisation 
variable native a php, permettent d'acceder a toutes les informations pouvant etre transmises par le clien au serveur. sont du type tableau.
9 superglobales
$_GET = données envoyée via une requete http get (url) ex: $_GET['id] recupere une variable trnasmise par URL sous forme ?id=valeur

7.	Quels sont les différents types (primitifs) que l’on peut associer à une variable en PHP ? Les citer et en donner des exemples (ne pas oublier le type d’une variable sans valeur)
Boolean: true, false
entier : nombre entiers
string : chaine de char
float: nombres decimaux
objet : objet (instance d'une class)
array: tableau
sans valeur: $var; = NULL par defaut

8.	Existe-t-il plusieurs types de tableaux en PHP, si oui lesquels ?
tableaux indexé, tableaux associatif.
//tableau multidimensionnel un tableau avec des tableau. 

9.	Quelles sont les différentes structures de contrôles qu’il existe en algorithmie ? Donner un exemple pour chacune d’entre elles

10.	Quelle est la fonction PHP permettant de demander la longueur d’une chaîne de caractères ?
strlen();

11.	Qu’est-ce qu’une session ? Quelle fonction permet de démarrer une session en PHP ? Donner un exemple d’utilisation en PHP
12.	Qu’est-ce qu’un cookie ? Donner un exemple d’utilisation en PHP
13.	Quelle est la différence entre les instructions « require » et « include » en PHP
14.	Comment effectuer une redirection en PHP ?
15.	Définir la partie « front-end » et « back-end » d’une application
16.	Définir le contrôle de version ? Qu’est-ce que Git ?
17.	Qu’est-ce qu’un CMS ? Citer au moins 2 exemples





## Front-end 9 / 17
18.	Définir HTML
(HyperText Markup Language) langage de balisage standard utilisé pour créer et structurer le contenu des pages web

19.	Définir CSS
    (Cascading Style Sheets) langage utilisé pour définir le style et la présentation des documents HTML.

20.	Définir Javascript
    langage de programmation orienté objet, utilisé principalement pour ajouter des fonctionnalités dynamiques et interactives aux pages web

21.	Définir JSON. Dans quel contexte ce format est-il utilisé ? 
22.	Peut-on interpréter du Javascript côté serveur ? Si oui, comment ?

23.	Qu’est-ce qu’un sélecteur CSS ?
élément utilisé pour cibler un ou plusieurs éléments HTML sur une page web, afin d’appliquer des styles spécifiques à ces éléments

24.	Quelle balise HTML permet de créer un lien hypertexte ?
<a href="lien">text a afficher</a>

25.	Qu’est-ce qu’une requête AJAX ?

26.	Quel sélecteur CSS permet de sélectionner tous les éléments d’une classe spécifique ? D’un identifiant spécifique ?
. pour les classe, # pour les ID

27.	Définir le responsive design
conception de sites web qui permet aux pages de s'ajuster automatiquement en fonction de la taille et des caractéristiques de l'écran sur lequel elles sont affichées

28.	Qu’est-ce que le templating ?
concevoir une structure fixe, afin de l'appliquer dans d'autre fichiers, et separé des données dynamiques.

29.	Qu’est-ce qu’une fonction anonyme en Javascript ?
30.	Quelle méthode JavaScript est utilisée pour ajouter un élément à la fin d'un tableau ?

31.	Qu’est-ce qu’un « media query » ?
fonctionnalité de CSS qui permet d'appliquer des règles de style spécifiques en fonction des caractéristiques du périphérique de l'utilisateur, telles que la largeur de l'écran, la hauteur, la résolution, l'orientation

32.	Qu’est-ce qu’un pseudo élément en CSS ?
33.	Qu’est-ce que Bootstrap ? Donner d’autres exemples équivalent
34.	Quand un formulaire HTML est créé, quelles sont les 2 méthodes qui peuvent lui être associées ? Donner la différence entre ces 2 méthodes




## UX UI 3 / 8
35.	Quelle est la différence entre UX Design et UI Design ?
UX concerne l'expérience globale de l'utilisateur, UI concerne la création de l'interface graphique et de l'esthétique

36.	Qu’est-ce qu’un wireframe ? 
37.	Qu’est-ce qu’un prototype ? 
38.	Qu’est-ce que la hiérarchie visuelle en UI Design ?

39.	Qu’est-ce que l’accessibilité en UX Design ? 
    concevoir des produits numériques de manière à ce qu'ils soient accessibles et utilisables par tous, y compris les personnes en situation de handicap

40.	Qu’est-ce qu’une grille de mise en page ?
41.	Qu’est-ce que la notion d’affordance en UX Design ?

42.	Qu’est-ce qu’un « mobile first design » ?
    Concevoir d'abord un site web pour appareils mobiles, puis adapter la conception pour des grands ecrans.

## Programmation orientée objet (POO) 8 / 17
43.	Donner une définition de la programmation orientée objet 
    approche de conception qui utilise des objets et des classes pour organiser le code de manière structurée

44.	Qu’est-ce qu’une classe ? Comment la déclare-t-on ?
    Une classe est une modèle qui définit les attributs (propriétés) et les méthodes (comportements) d'un objet

45.	Qu’est-ce qu’un objet ?
    Un objet est une instance d'une classe. Il contient des valeurs spécifiques pour les attributs et peut appeler des méthodes définies dans la classe.

46.	Définir la notion de propriété / attribut / méthode
    attribut = variables associé a une Class qui dévrivent l'état de l'objet créé a partir de cette class (ex: class voiture : 2 attributs marque, couleur)
    méthode = fonctions qui agi sur le comportement d'un objet. elle peuvent agir sur les propriétés d'un objet.
    !!! a retenir: attribut = état d'un objet, méthode = comportement d'un objet !!!
    
47.	Qu’est-ce que la visibilité d’une propriété ou d’une méthode ? Citer les différents types de visibilité
    règles d'accès à ces éléments à partir d'autres parties du programme
    Public, protected, privé. (protected utilisé lors d'héritage)

48.	Quelle est la méthode spécifique utilisée pour créer un nouvel objet à partir d’une classe ?
    New ($var = new Class)

49.	Qu’est-ce que l’encapsulation ?
    Protege les données d'un objet en limitant l'accès direct à ces données

50.	Que signifie « étendre une classe » ? Quelle est le concept clé mis en œuvre ? Donner un exemple
    voir héritage > utilisé des fonctionnalités d'une autre classe tout en permettant de les ajouter, modifier ou personnaliser
    Class Personne (avec attributs nom, prenom) > 2 class enfants > auteurs et réalisateurs les deux class ont pour attributs nom prenom.

51.	Définir l’opérateur de résolution de portée
52.	Définir une méthode / propriété statique
53.	Définir le polymorphisme en POO
54.	Définir une méthode / classe abstraite ?
55.	Définir le chaînage de méthodes
56.	Qu’est-ce que la méthode __toString() ? Existe-t-il d’autres méthodes « magiques »
57.	Qu’est-ce qu’un « autoload » ?
58.	Comment appelle-t-on en français les « getters » et les « setters » ?
59.	Qu’est-ce que la sérialisation en PHP ? 

## Architecture  0 / 7
60.	Qu’est-ce que l’architecture client / serveur ? Grâce à quel type de requête peut-on interroger le serveur. Définir l’acronyme de ce type de requête. Si on ajoute un « S » à cet acronyme, expliquer la différence
61.	Donner la définition d’un design pattern. Citer au moins 3 exemples de design pattern
62.	Qu’est-ce que l’architecture MVC ?
63.	Quel est le rôle de chaque couche du design pattern MVC : Model, View, Controller ?
64.	Quels sont les avantages de l’architecture MVC ?
65.	Existe-t-il des variantes à l’architecture MVC ?
66.	Qu’est-ce qu’une API ? Définir l’architecture REST

## Modélisation - Base de données 8 / 17
67.	Qu’est-ce que la modélisation de données ? Définir la méthode Merise
créer une représentation abstraite et organisée des données d'une organisation ou d'un système pour en comprendre la structure et les relations.
methode de conception qui repose sur une approche structuée.

68.	Quelles sont les 3 étapes principales de la méthode Merise ? 
a.	Analyse, conception et réalisation<<<<<<<<<<<<<<<
b.	Planification, exécution et contrôle
c.	Création, modification et suppression

69.	Qu’est-ce qu’un modèle conceptuel de données (MCD) en Merise ?
représentation simplifiée des données d’un système d'information. Il décrit les entités et leurs relations

70.	Qu’est-ce qu’un modèle logique de données (MLD) en Merise ?
version plus détaillée et précise du MCD. Il décrit comment les données seront organisées dans une base de données

71.	Donner la définition des mots suivants :
a.	Entité
représente un objet du système d'information généralement une chose ou une personne dont on veut stocker des informations
b.	Relation
lien ou une association entre deux entités
c.	Cardinalité
nombre d'occurrences d'une entité pouvant être associées à une autre entité (1,1 1,n)
d.	Clé primaire / clé étrangère
primeaire: permet d'identifier de manière unique chaque instance de cette entité
etrangere: fait référence à la clé primaire d'une autre table

73.	Que devient une relation de type « Many To Many » dans le modèle logique de données ?
74.	Qu’est-ce qu’une base de données ?
données qui sont stockées, on peut les modifier et manipuler.

76.	Définir les notions suivantes : 
a.	SQL
b.	MySQL
c.	SGBD (donner 2 exemples de SGBD)

78.	Dans une base de données, les données sont stockées dans des ___. Celles-ci sont constituées de lignes appelées ___ et de colonnes appelées ___.
tables, enregistrements, attributs

79.	Quelle est la différence entre une base de données relationnelle et non relationnelle ?
80.	Qu’est-ce qu’une jointure dans une base de données ? En existe-t-il plusieurs ? Si oui lesquelles ?
81.	A quoi sert une vue dans une base de données ?
82.	Qu’est-ce que l’intégrité référentielle dans une base de données ?
83.	Quelles sont les fonctions d’agrégation en SQL ?
84.	Qu’est-ce qu’un CRUD dans le contexte d’une base de données ?
85.	Quelles sont les clauses qui permettent de :
a.	Insérer un nouvel enregistrement dans une table
b.	Modifier un enregistrement dans une table
c.	Supprimer un enregistrement dans une table
d.	Supprimer la base de données
e.	Filtrer les résultats d’une requête SQL
f.	Trier les résultats d’une requête SELECT
g.	Regrouper les résultats d'une requête SELECT en fonction d'une colonne spécifique
h.	Concaténer 2 chaînes de caractères 
86.	Comment se connecter à une base de données en PHP ? Quelle est la classe native utilisée ?

## Symfony 0 / 10
84.	Qu’est-ce que Symfony ?
85.	Sur quel langage de programmation et design pattern repose Symfony ? 
86.	Quelle est la dernière version en date de Symfony ?
87.	Qu’est-ce qu’un bundle ? 
88.	Quel est le moteur de template utilisé par défaut dans Symfony ?
89.	Qu’est-ce qu’un ORM ? Quel est son utilité et comment s’appelle-t-il au sein de Symfony ?
90.	Qu’est-ce que l’injection de dépendances ? Quel est l’outil utilisé dans ce contexte et quel fichier contient l’intégralité des dépendances du projet ?
91.	Que permet le bundle Maker au sein de Symfony ? 
92.	Quel est le langage de requêtage exploité au sein d’un projet Symfony ?
93.	Quel est le composant qui garantit l’authentification et l’autorisation des utilisateurs ?

## Sécurité 0 / 10
94.	Qu’est-ce que l’injection SQL ? Comment s’en prémunir ?
95.	Qu’est-ce que la faille XSS ? Comment s’en prémunir ?
96.	Qu’est-ce que la faille CSRF ? Comment s’en prémunir ?
97.	Définir l’attaque par force brute et l’attaque par dictionnaire
98.	Existe-t-il d’autres failles de sécurité ? Citer celles-ci et expliquer simplement leur comportement
99.	A quoi servent l’authentification et l’autorisation dans un contexte d’application web ?
100. Définir la notion de hachage d’un mot de passe et citer des algorithmes de hachage
101. Qu’est-ce qu’une politique de mots de passe forts ?
102. Qu’est-ce que l’hameçonnage ?
103. Définir la « validation des entrées »

## RGPD 9 / 10
104. Qu’est-ce que le RGPD ?
     Règlement Général sur la Protection des Données 

105. Quel est son objectif principal ?
    Sert a renforcer la protection des données personnelles des citoyens de l'Union Européenne et de réguler leur traitement au sein de l'UE, mais aussi par des entreprises en dehors de l'UE qui traitent les données de citoyens européens.

106. Quelle est la date d’entrée en vigueur du RGPD ?
    25 mai 2018

107. Quelles sont les sanctions possibles en cas de non-respect du RGPD ?
    4% de leur chiffre d'affaires annuel mondial ou 20 millions d'euros (le plus élevé)

108. En France, quel est l’autorité administrative qui s’occupe de faire appliquer le RGPD ?
    CNIL

109. Quel est le consentement valide selon le RPGD ?
    libre et éclairé

110. Qu’est-ce qu’une politique de confidentialité ?
    document qui explique comment l'entreprise/site web collecte, utilise, protège, et partage les données personnelles de ses utilisateurs ou clients. 

111. Quelle est la durée de conservation maximale des données personnelles selon le RGPD ?

112. Quels sont les droits des utilisateurs selon le RGPD ?
droits d'accès
droit de rectification
droit a l'oubli
droit a la portabilité
droit d'opposition
droit a la non-soumission a des décisions automatisées
droit a la notification en cas de violation de connées

113. Qu’est-ce que le principe de minimisation des données selon le RGPD ?
    Demandé les informations au clients/utilisateurs nécessaires.

## SEO 0 / 13
114.	Qu’est-ce que le SEO ? 
115.	Quel est l’objectif principal du SEO ?
116.	Existe-t-il plusieurs types de référencement ? Lesquels ?
117.	Qu’est-ce que la densité de mots-clés en SEO ?
118.	Qu’est-ce qu’une balise « alt » ?
119.	Qu’est-ce que la balise « meta description » ?
120.	Qu’est-ce que le « nofollow » en SEO ?
121.	Quelle est l'importance du contenu de qualité pour le référencement d'un site web ?
122.	Pourquoi est-il important d'utiliser des balises de titre (h1, h2, h3, etc.) de manière structurée ?
123.	Quelle est la recommandation pour les URL d'un site web bien référencé ?
124.	Qu'est-ce que le maillage interne et pourquoi est-il important pour le référencement ?
125.	Qu'est-ce que l'optimisation des images pour le référencement ?
126.	Qu'est-ce qu'un plan de site (sitemap) et pourquoi est-il important pour le référencement ?

## Gestion de projets - DevOps 0 / 16
127.	Qu’est-ce que la gestion de projet ?	
128.	Qu’est-ce qu’une méthode Agile de gestion de projet ? 
129.	Expliquer la méthode MoSCoW en quelques lignes et citer ses avantages
130.	A quoi sert la méthodologie MVP ? Citer les caractéristiques clés
131.	Qu’est-ce que la planification itérative ?
132.	Citer 3 méthodes Agiles dans le cadre d’un projet informatique
133.	Qu’est-ce qu’une réunion de revue de projet ?
134.	Qu’est-ce qu’un livrable dans un projet ? 
135.	Quels sont les 3 piliers SCRUM ? Définir chacun d’entre eux
136.	Qu’est-ce que le DevOps et quel est son objectif principal ?
137.	Qu’est-ce que l’intégration continue ? 
138.	Qu’est-ce que Docker ? Et en quoi est-il utile dans le cadre du DevOps ?
139.	Qu’est-ce qu’un test unitaire ? 
140.	Quelle est l'unité de code testée lors d'un test unitaire ?
141.	Quelles sont les caractéristiques d'un bon test unitaire ?
142.	Qu'est-ce qu'une assertion dans un test unitaire ?
 
## English 6 / 8
1)	What does JavaScript enable you to do on a website ?
a.	Add interactive behavior and dynamic content <<<<<<<<<<<<
b.	Define the layout and design of web pages
c.	Handle server-side operations

2)	Which programming language is primarily used for server-side web development ?
a.	PHP <<<<<<<<<<<<
b.	JavaScript
c.	HTML

3)	What is the purpose of a web browser ?
a.	To render and display web pages <<<<<<<<<<<<<<<
b.	To execute serve-side code
c.	To manage databases

4)	What is the difference between GET and POST methods in HTTP ?
a.	GET retrieves data from a server, while POST submits data to a server <<<<<<<<<<<<<<<<
b.	GET submits data to a server, while POST retrieves data from a server
c.	GET and POST methods are interchangeable

5)	What is the purpose of version control systems (e.g., Git) in web development ?
a.	To track changes and manage collaborative development <<<<<<<<<<<<<<<<
b.	To optimize website loading speed
c.	To handle server-side scripting

6)	What is the purpose of a framework in web development ?
a.	To provide a structured environment for building web applications <<<<<<<<<<<<<<<<
b.	To handle network protocols and data transfer
c.	To create visual designs and layouts for websites

7)	What does NoSQL stand for ?
a.	Not Only SQL 
b.	Non-Structured Query Language
c.	New Object-Oriented Language

8)	Which of the following is a characteristic of NoSQL databases ?
a.	Strict schema enforcement
b.	Support for complex transactions
c.	Scalability and flexible data models
