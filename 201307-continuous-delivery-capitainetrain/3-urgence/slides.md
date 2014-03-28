!SLIDE
# Urgences

- Fixes de sécurité
- Bugs critiques
- Rollbacks


!SLIDE
### *Au mieux*

PR → dev → master

* * *

### **Au pire**

- Patcher master
- Backporter dans dev


!SLIDE
# Quelques conseils

- master doit rester iso-prod
- attention aux oublis de report, un **backport est risqué**
- ne faites pas aveuglément confiance à git


!SLIDE
# Cela reste exceptionnel

- 2012 : ~ 35 cas
- 2013 : ~ 20 cas
- 2014 : 4 cas pour l'instant

* * *

Et on peut réagir très vite
