## 4. Planning meeting - Romuald

## Planning des 4 Sprints

**Sprint 1 (Semaine 1) : Infrastructure Robuste**

Sprint Goal : Système de capture vidéo opérationnel toutes météos

Stories sélectionnées : US1

Mise en place :
- Sélection caméra IP66/67 (résistance intempéries)
- Installation boîtier étanche avec chauffage anti-condensation
- Configuration streaming vidéo stable
- Tests de résistance (simulation pluie/neige)

Pipeline de traitement d'images en temps réel

Definition of Done : Caméra fonctionnelle 24h/24 par tous temps, flux vidéo stable, tests météo validés

**Sprint 2 (Semaine 2) : IA de Classification**

Sprint Goal : Modèle de détection et classification des frelons

Stories sélectionnées : US2

- Constitution dataset (500 images frelons asiatiques, 300 européens, 1000 abeilles, 300 Bourdons, 300 Guêpes)
- Annotation des images par experts entomologistes
- Entraînement modèle CNN/YOLO avec classes : abeille, frelon asiatique, frelon européen
- Évaluation précision >85% sur jeu de test
- Optimisation pour inférence temps réel

Definition of Done : Modèle classifiant correctement les 5 catégories, précision validée, intégré au pipeline

**Sprint 3 (Semaine 3) : Alertes et Monitoring**

Sprint Goal : Système d'alerte et dashboard opérationnels

Stories sélectionnées : US3, US4

- Développement API de notifications (SMS, email, push mobile)
- Création dashboard web responsive (statistiques temps réel)
- Base de données des événements de détection
- Graphiques : nombre d'attaques/jour, types de frelons, heures d'activité
- Tests d'intégration alerte-détection

Definition of Done : Notifications fonctionnelles, dashboard accessible, données historiques sauvegardées

**Sprint 4 (Semaine 4) : Finalisation MVP**

Sprint Goal : MVP complet testé et déployé

Stories sélectionnées : US5, US6

- Tests d'endurance système (72h continu)
- Optimisation consommation énergétique
- Module capture photo haute résolution des intrus
- Interface d'administration apiculteur
- Documentation utilisateur et déploiement
- Tests acceptation client (démo finale)

Definition of Done : MVP validé par le client, documentation livrée, système déployé en production

## Outils et Méthodes Scrum

- Outils de suivi : Trello, Sprint, In Progress, Review, Done

Rituels planifiés :
- Daily Scrum : 15min/jour équipe complète
- Sprint Review : Démo client fin de chaque sprint
- Sprint Retrospective : Amélioration continue process équipe

Métriques de suivi :
- Burndown Chart par sprint
- Velocity équipe (story points/sprint)
- Lead time user stories

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
