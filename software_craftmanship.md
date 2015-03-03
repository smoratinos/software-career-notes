# Artisant du Logiciel

Peu importe le poste occupé, du développeur à l'administrateur système en passant par le testeur.
Peu importe les langages utilisés, du Java au Bash.

Un Artisant du logiciel doit s'intéresser à toutes les phases que traverse un logiciel (analyse, conception, validation et déploiement).
Il doit sans cesse se remettre en question et puiser des idées dans différents domaines.

Il est indispensable de se familiariser avec les différentes méthodes de gestion de projet IT, ainsi qu'avec plusieurs paradigmes de programmation.
Il est aussi intéressant d'aborder plusieurs type d'application (web, embarqué, )


## Objectifs

Elever le niveau du développement professionnel, pour satisfaire le client.

## Principes

Il faut des processus et des outils, mais nous devons privilégier les individus et leurs interactions.
Pour celà, il est indispensable d'avoir une communauté de professionnels.

Il faut de la documentation, mais nous devons privilégier les logiciels opérationnels.
Pour celà, il est indispensable d'avoir des logiciels bien conçus.

Il faut de la négociation contractuelle, mais nous devons privilégier la collaboration avec les clients.
Pour celà, il est indispensable d'avoir des partenariats productifs.

Il faut avoir un plan, mais nous devons privilégier l'adaptation aux changements.
Pour celà, il est indispensable d'ajouter constamment de la valeur.

[Manifeste pour le développement Agile de logiciels](http://www.agilemanifesto.org/iso/fr/)

[Manifeste pour l'Artisanat Logiciel](http://manifesto.softwarecraftsmanship.org/#/fr-fr)

## Cycle de vie d'une logiciel

### Besoins

Spécification Fontionnelles

doc expression besoin plus ou moins détaillé

user stories expression d'un besoin orienté métier

première estimation

### Conception

Spécification Technique

archi

analyse

affinage estimation

doc

### Implementation

#### Code
Le code doit être clair, le reste est secondaire.

Data Structure

Algorithms

Thread, Sequence


#### Test
Les doivent être complet : 
 * validation des tests d'acceptance
 * limite du test (attention aux boucles et aux récurrences)
 * cas d'erreur, vérification des entrées

Types de tests : 
 * unitaire
 * integration
 * fonctionnel
 * performance & montée en charge

#### doc


#### revue code


#### version control system

### Test de l'ensemble du système

Il faut impérativement effectuer une validation du produit dans le contexte client, en cas réel.

Cette validation assure que l'ensemble du produit fonctionne sur la plateforme cible, et qu'il s'intègre bien dans l'existant.

### Deploiement

sys, ops

infra

microservices

HA, proxy, conteneur

### Maintenance

refactoring

debugueur


## Concept

### Performance et Montée en charge

"The Scale Cube"

TODO : diagramme

#### Threads et Locks

#### Programmation fonctionelle

#### Séparation Identity/State

#### Actors

#### Communicating Sequential Process

#### Data Parallelism

#### Lambda Architecture

#### Fork/Join

#### Dataflow

#### Reactive Programming

#### Functional Reactive Programming

#### Grid Computing

#### Tuple Spaces


### Sécurité

### Disponibilité et Résistance

L'intégration est le 1er risque. Tous les appels externes peuvent nuire au système.

Circuit Breaker

Use Timeouts

Use Decoupling Middleware

Handshaking

Test Harness

Bulkheads

### Evolutivité

SOA
