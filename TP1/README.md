\# TP1



\## Etape 1



1. &#x20;une machine virtuelle est un environnement logiciel qui nous permet d'héberger une autre machine (os, des ressources de calculs, stockage et réseau) sur notre machine hôte
2. Isolation, choix des ressources, moins de serveur => moins de maintenance
3. En tant qu'utilisateur, on ne peut pas savoir si on travaille sur une machine virtuelle une fois configurée et connecté cependant la connexion et la configuration est plus complexe.



\## Etape 2



1. un conteneur est un environnement permettant de regrouper des applications et leurs dépendances (librairies, logiciels…). Un conteneur ne contient pas d'os mais doit tourner sur un os définit.
2. Les conteneurs sont hébergés sur un Os hôte contrairement aux VM qui sont dépendent directement de l'hyperviseur (qui peut être sans OS). Une VM a ses propres ressources physiques "simulées" alors que le conteneur exploitent directement les ressources de la machine hôte.
3. Ils permettent d'isole une applications et ses dépendances, c'est plus facilement reproductible qu'une VM notamment car c'est plus léger et fonctionnel.



\## Etape 3



1. Il permet de créer plusieurs conteneurs avec les memes spécifications rapidement.
2. l'image docker est en mode lecture seule par contre le conteneur docker est en mode d'exécution



\## Etape 4



1. Docker Compose permet de lancer plusieurs conteneurs en 1 seule commande
2. Le fichier docker-compose.yml permet d'ordonnancer la creation et le lancement des conteneurs et de l'application.
3. Il y a des limitations de ressources. Il ne peut pas lancer des conteneurs à l'infini. 

