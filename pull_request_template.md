## Description
🎫 [Nom de la tâche](lien sur asana)

### Décrivez brièvement ce que cette PR implique
- Pourquoi on fait cette tâche, quels sont les résultats attendus ?
- Qui sont les interlocuteurs clés dans le cadre de cette tâche ?
- Quelles fonctionnalités ou problèmes sont résolus ?
- Quelles sont les URLs ou écrans impacté(e)s ?

### Comment vérifier le comportement ?
Donner des exemples de pages précis ou de comportements à reproduire pour valider la fonctionnalité.

### Process & vérifications déjà effectuées
- [ ] J'ai factorisé mon code, de manière à avoir le moins de LoC possible
- [ ] J'ai vérifié manuellement la PR
- [ ] La modification impacte le backend
  - [ ] J'ai vérifié les interactions avec le cache
  - [ ] Le temps de réponse du backend est cohérent avec le volume de page vue attendu
- [ ] La modification impacte des pages publiques
  - [ ] J'ai fait les vérifications SEO - [📚 Manuel](https://www.notion.so/brakson/Template-Checklist-MEP-Recettages-181b3526b6fb8035bb5cc5d9910d9ad9?v=fed687df60bb44329025e96e53937984&source=copy_link)
  - [ ] Mes modifications sont indexables
  - [ ] Les méta données _( meta title, description, og:... )_ ont étées vérifiées et validées
  - [ ] Les données structurées sont à jour
  - [ ] Les assets appelés sur ma page ont étés optimisés
- [ ] J'estime avoir besoin d'une relecture de code
- [ ] Les interlocuteurs clés sont au courant de l'avancement de cette PR et du calendrier de déploiement
