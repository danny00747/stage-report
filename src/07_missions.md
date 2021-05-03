Les missions effectuées
========================

Recruté en tant que stagiaire auprès de BStorm, j’ai eu l’opportunité de découvrir un métier sous toutes ses formes
et de comprendre de manière globale les difficultés que les développeurs et les
designers web pouvaient rencontrer dans l’exercice de la mise en œuvre
d’applications web. 


Pour une meilleure compréhension
des tâches que j’ai pu effectuer, il apparaît approprié de traiter en premier lieu
l’environnement de travail dans lequel j’ai évolué, des outils qui étaient mis à ma disposition, 
puis de traiter de manière synthétique les missions et les tâches que j’ai pu effectuer.


::: tip
Afin de faciliter la compréhension de ce rapport, la présentation des
missions et des tâches effectuées sera volontairement présenter sous
forme synthétique.
:::

## L’environnement de travail

Dès mon arrivée, j’ai été intégré au sein du bureau « open space » de BStorm. Coté
écrans, j’avais à ma disposition l’accès à deux écrans LG pour développer efficacement.


Coté machine, j’ai travaillé sous Windows 10 Home. Pour coder efficacement, j’ai
disposé d’un environnement de développement nommé IntelliJ IDEA [^1], qui est adapté spécialement à la
programmation et dont l’atout majeur est la colorisation syntaxique qui permet de
repérer très vite les erreurs de programmations ou de frappe. 

[^1]: [IntelliJ](https://www.jetbrains.com/fr-fr/idea/)

## Outils utilisés pour les différentes missions

Au cours de mon stage j’ai été amené à utiliser de nombreux outils informatiques :
BitBucket, Redmine, Docker, Swagger et PostgreSQL. Je maitrisais certains d’entre eux avant
de commencer mon stage et j’ai appris à utiliser les autres en fonction de mes besoins. En
outre j’ai utilisé Discord, et Toggl Track pour communiquer mon travail et échanger
avec mon maître de stage qui avait parfois un suivi à faire.

\pagebreak

## Première partie du stage :

### Février - Mars

* **Projet inspiré de Redmine** [^2]

[^2]: [Redmine](https://www.redmine.org/)

\begin{figure}[H]
\centering
\caption{Redmine}
\includegraphics[scale=0.42]{imgs/redmine.png}
\end{figure}


Redmine outil de gestion de projet Open Source très populaire dans le monde du développement informatique. 
Il propose ainsi des fonctionnalités qui facilitent amplement l’encadrement de plusieurs projets. L’outil est adapté à 
toutes sortes de projets, complexes ou simples, grands ou petits et il est aujourd’hui de plus en plus utilisé 
par les entreprises.

Ma première tâche fut de développer une interface graphique inspiré de Redmine pour la gestion d'un ou plusieurs projets 
paramétrables avec des fonctionnalités suivantes : 

- La gestion multi-projets. Possibilité de créer plusieurs projets en parallèle et de les gérer de manière indépendante.
  
- Contrôle flexible des accès des utilisateurs redmine : chaque compte utilisateur dispose d'un ou plusieurs rôle(s) 
  (administrateur, accès restreint, utilisateur). L'administrateur attribue des droits spécifiques à chacun d'eux pour 
  contrôler les accès de chacun.
  
- Un utilisateur peut appartenir à un ou plusieurs projets. À chaque utilisateur sera associé un - ou plusieurs - rôle(s) 
  par projet, les rôles définissant les permissions accordées aux utilisateurs dans un projet. Ainsi, un utilisateur 
  peut avoir des rôles différents selon le projet. Les rôles sont communs à tous les projets et sont très modulables.
  
- Gestion des utilisateurs, des profils et des droits, en fonction de chaque projet.
  
- Les membres du projet peuvent voir un aperçu de qui travaille sur le projet ainsi que son rôle. 
  Chaque tâche possède un fil de discussion permettant d’enrichir les échanges.
  
- Suivre l’évolution de chaque projet grâce à un tableau de synthèse des projets en cours.

## Deuxième partie du stage :

### Mars - Mai

Pour la deuxième partie du stage, ma mission consista à
créer un éditeur de formulaire d'inscription. Ainsi, j’ai créé dans sa totalité (front-end & back-end) une interface permettant à un
utilisateur, créer, modifier et supprimer des informations dans un formulaire lambda. 
:

```{=latex}
\begin{awesomeblock}[gray]{1pt}{\faGrin*[regular]}{gray}   
```

**L’autonomie dans le travail**

Pour réaliser cette interface, le maitre de stage m’a laissé libre
d’organiser mon travail et de mener à bien mes objectifs. J’ai
fortement apprécié son intention, ce qui m’a permis de prendre
conscience que l’autonomie dans le travail est dorénavant l’un des
critères que je rechercherai dans mes futurs emplois.

```{=latex}
\end{awesomeblock}
```

* **Maquette de l'interface à développer**

\begin{figure}[H]
\centering
\caption{mock-up}
\includegraphics[scale=0.27]{imgs/mock-up1.jpeg}
\end{figure}


```{=latex}
\begin{awesomeblock}[white][\abShortLine][\textbf{Les modifications de tous les paramètres concernant la structure d'un 
formulaire que je devais implementer sont les suivantes : }]{5pt}{\faAngular}{red}
```
- Création, Modification (le nom & version) et suppression d'un formulaire

- Alignement des pages, section et question d'un formulaire : pouvoir changer l'ordre d'une page, section, et question d'un formulaire

- Largeur d'une question d'un formulaire : pouvoir changer la largeur d'une question par exemple donner
  une largeur de 50 % ou 75 %

- Modification de Libellés de tous les paramètres d'un formulaire. 

- Modification d'un type de question : pouvoir par exemple changer le champ radio d'une question en champ checkbox. 
```{=latex}
\end{awesomeblock}
```


* **Résultat de mon travail**

\begin{figure}[H]
\centering
\caption{Résultat}
\includegraphics[scale=0.27]{imgs/resultat.jpeg}
\end{figure}




\pagebreak