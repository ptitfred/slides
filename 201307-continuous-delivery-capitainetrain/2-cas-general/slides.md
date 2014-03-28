!SLIDE
# Le cas simple

1 seul composant concerné

Du code certes, mais aussi de la configuration

*Déploiement standard*


!SLIDE
# Intégration

Branches _dev_ et _master_

* * *

Intégration continue via Jenkins

Déploiement automatique sur des environnements dédiés


!SLIDE
# Quotidien d'un développeur

### Pull Request

topic-branch → dev

### Release

dev → master


!SLIDE
# Qualité du code

Couverture de test

Pertinence des tests

Respect du codestyle

Du code lisible


!SLIDE
# Revue de code

Fait intervenir un pair

* * *

Contrevisite sur la qualité

S'enquiert des pièges classiques


!SLIDE
# Responsabilisation des développeurs

Pas de Release Manager

**Chacun doit faire avancer ses développements**


!SLIDE
# Points cruciaux

Build rapide & reproductible

Environnements d'intégration proches de la production

Bien identifier les tiers concernés


!SLIDE
# like-prod everywhere

- packages indépendants de la plateforme
- gestion de la configuration rigoureuse
- valable aussi pour les postes de développeurs


!SLIDE
# Préparation d'une MEP

Merge dev → master

```
$ ct release
CHANGELOG koala - Frédéric Menou
*   39b7173  Merge branch 'eucalyptus-service' into 'dev'
|\  
| * 9f72590 Eucalyptus service
|/  
o c8e7dab Merge branch 'ruby-2.0' into 'dev'
Do you want to merge and push? [y/N] 
```

Notification automatique sur le chat interne

!SLIDE
# Déroulement d'une MEP

Déploiement standard ⬄ 1 commande

```
$ ct deploy koala
On build1
  fab -R production koala_deploy:file=koala_201403271611_ba99aac.tar.gz,branch=master

Do you want to deploy? [y/N]
```

Manuel mais routinier

* * *

Notification automatique sur le chat interne


!SLIDE
# Hygiène de vie

- on ne prode pas le vendredi
- on NE prode PAS le vendredi
- on ne prode pas après 18h
- on n'hésite pas à proder plein de petits bouts
