#  Exercice 1 

##  Tâche 1   
1) Les principaux domaines métiers de l'application sont le Shopping Cart Domain et l'Order Processing Domain.

2) 

3) 
- apps/store-back : Lien Back-end Front-end avec API Rest
- apps/store-front : Front end web
- libs/kernel : Contient l'agrégat Product 
- apps/product-registry-domain-service : Service d'écriture pour le registre des produits
- apps/product-registry-read-service : Service de lecture pour le registre des produits
- libs/bom-platform : Gestion des dépendances
- libs/cqrs-support : Support d'infrastructure pour le CQRS
- libs/sq : Script pour la migration de la base de données

## Tâche 2

1) Les concepts principaux utilisés dans l'application Order Flow sont le CQRS, le Domain-Driven Design (DDD), les events log, les outbox patterns, les communication synchrones et asynchrones ainsi que les projections

2) 
- DDD : Agrégat de Product et les services d'application dans le product-registry-domain-service
- CQRS : les services métier 
- Projection :  