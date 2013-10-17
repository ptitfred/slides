!SLIDE
# Le cas simple

1 seul composant concerné

Du code certes, mais aussi de la configuration

*Déploiement standard*


!SLIDE
# Quotidien d'un développeur

*PullRequest*   topic-branch → dev

**Release**        dev → master


!SLIDE
# Responsabilisation des développeurs

Pas de Release Manager

**Chacun doit faire avancer ses développements**


!SLIDE
# Points cruciaux

Build rapide & reproductible

Environnements d'intégration proches de la production


!SLIDE
# like-prod everywhere

- packages indépendants de la plateforme
- gestion de la configuration rigoureuse
- valable aussi pour les postes de développeurs


!SLIDE
# Déroulement d'une MEP

Déploiement standard ⬄ 1 commande

Scripts *bash + fabric*

Manuel mais routinier

Suivi de la production


!SLIDE
# Hygiène de vie

- on ne prode pas le vendredi
- on NE prode PAS le vendredi
- on ne prode pas après 18h
- on n'hésite pas à proder plein de petits bouts
