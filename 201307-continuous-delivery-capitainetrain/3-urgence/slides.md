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
