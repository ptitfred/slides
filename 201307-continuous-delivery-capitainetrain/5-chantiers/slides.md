!SLIDE
# Grosses évolutions

Concernent au moins 2 composants

A faire en plusieurs étapes


!SLIDE
# Intégration du code

Dépendances via des APIs (interne ou externe)

* * *

Dépendances via le schéma SQL


!SLIDE
# Déploiement unitaire ?

oui **sauf** pour le modèle SQL

migrations ActiveRecord livrées avec le code

**casse le principe de découplage par les APIs**


!SLIDE
# Du vrai 0-downtime ?

Séparer les modifications de schéma SQL du code

Eviter les opérations bloquantes : expertise SQL

Code jetable

Valable pour les APIs


!SLIDE
# Connaître son système

![](assets/illustrations/schema.png)
