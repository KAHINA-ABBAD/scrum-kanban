# Planning Meeting - Projet Détection Attaques Frelons  
**Date :** [Date du meeting]  
**Présents :** [Noms des participants]  
**Durée :** [Durée estimée]  

---

## Objectifs du projet  
- Développer un système complet de détection automatique d’attaques de frelons asiatiques et européens.  
- Fournir des alertes en temps réel et un dashboard de suivi des attaques.  
- Finaliser un MVP opérationnel et déployable en conditions réelles.  

---

## Organisation des Sprints  

### Sprint 1 : Infrastructure vidéo  
- Objectif principal : Installation caméra IP66/67 résistante aux intempéries, pipeline vidéo stable.  
- US1 sélectionnée, tâches détaillées et tests météo planifiés.  

### Sprint 2 : IA de classification  
- Objectif principal : Modèle IA différenciant frelons asiatiques, européens, abeilles, bourdons, guêpes.  
- US2 sélectionnée, constitution dataset, annotation par experts, entraînement CNN, précision ≥ 85%.  

### Sprint 3 : Alertes et dashboard  
- Objectif principal : Notifications (SMS, email, push), dashboard web responsive affichant statistiques d’attaques.  
- US3, US4 sélectionnées, développement API, base de données, modules graphiques.  

### Sprint 4 : Finalisation MVP  
- Objectif principal : MVP complet avec photos haute résolution des intrus, tests 72h, déploiement et documentation.  
- US5, US6 sélectionnées, tests d’endurance, optimisation, interface apiculteur, validation client.  

---

## Rituels Scrum  
- Sprint Planning : Lundi 9h30-10h30  
- Daily Scrum : 15 min chaque jour à 9h30  
- Sprint Review : Dernier jour du sprint
- Sprint Retrospective : Après Review  

---

## Outils & Métriques  
- Gestion de tâches : Trello avec colonnes Backlog, Sprint, In Progress, Review, Done  
- Suivi : Burndown Chart, velocity équipe (story points par sprint), lead time des user stories  

---

## Questions et points à clarifier  
- Disponibilité des experts entomologistes pour annotation dataset  
- Ressources pour tests météo en conditions réelles versus simulation  
- Priorisation des fonctionnalités secondaires (nombre de nids, triangulation)  
- Modalités de recette client (livraison progressive ou démo finale)  

---

## Prochaines étapes  
- Finalisation des User Stories et estimations story points  
- Lancement Sprint 1 dès validation du backlog  
- Mise en place des outils de suivi et communication  

```markdown
# Diagramme de Gantt - Exemple

| Tâche                | Début      | Fin        | Semaine 1 | Semaine 2 | Semaine 3 | Semaine 4 |
|----------------------|------------|------------|-----------|-----------|-----------|-----------|
| Analyse des besoins  | 01/07/2024 | 05/07/2024 | █████     |           |           |           |
| Conception           | 06/07/2024 | 12/07/2024 |     █████ |           |           |           |
| Développement        | 13/07/2024 | 19/07/2024 |           | █████     |           |           |
| Tests                | 20/07/2024 | 26/07/2024 |           |     █████ |           |           |
| Livraison            | 22/09/2025 | 26/09/2025 |           |           |           |███████████|

    Légende : █ = période d'activité_
```

---

*Fin du Planning Meeting*  

