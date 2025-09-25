# Projet SCRUM - Détection d’attaques de frelons  

## Index du dossier  

### 1. Contexte et organisation  

Le projet vise à développer un système innovant de détection automatique des attaques de frelons asiatiques et européens sur des ruches d’abeilles. Ce système doit permettre aux apiculteurs de recevoir des alertes en temps réel et de consulter des statistiques précises pour mieux protéger leurs colonies. Le développement s’inscrit dans une démarche agile Scrum pour une livraison rapide et incrémentale de valeur métier.

#### Organisation Scrum : rôles et missions  

- **Product Owner (PO) : Olivier**  
  Responsable de la vision produit et de la priorisation du backlog. Il s’assure que les besoins métier sont bien compris et traduits en User Stories claires, valide les livrables à chaque sprint et pilote la relation avec les parties prenantes.

- **Scrum Master : Romuald**  
  Facilitateur du processus Scrum, il organise les rituels, aide l’équipe à lever les obstacles, veille au respect des bonnes pratiques Scrum et à l’amélioration continue du fonctionnement de l’équipe.

- **Équipe de développement : Kahina (et autres membres)**  
  Responsable de la réalisation technique, elle conçoit, développe, teste et intègre les fonctionnalités. L’équipe est auto-organisée et collabore étroitement avec le PO pour livrer les User Stories définies dans le sprint.

### 2. Product Backlog détaillé 

| Priorité | User Story                                 | Critères d’acceptation clés                                  | Definition of Done spécifique                                    | Story Points | Timebox estimé         |
|----------|--------------------------------------------|--------------------------------------------------------------|-----------------------------------------------------------------|--------------|-----------------------|
| 1        | US1 - Identification Frelon (Asiatique/Européen) | - Précision ≥85% sur jeu test                                 | - Modèle intégré dans pipeline et fonctionnel                    | 8            | 7 à 10 jours          |
|          |                                            | - Classification fiable des 2 types                          | - Validation PO réalisée                                         |              |                       |
|          |                                            |                                                              | - Code review effectué, tests automatisés réussis                |              |                       |
| 1        | US2 - Dashboard Statistiques Quotidiennes  | - Dashboard web responsive avec stats temps réel             | - Données actualisées en temps réel                              | 5            | 4 à 6 jours           |
|          |                                            | - Affichage nombre d’attaques, types frelons, heures         | - Tests fonctionnels complets                                    |              |                       |
|          |                                            |                                                              | - Documentation utilisateur mise à jour                          |              |                       |
| 1        | US3 - Alerte Immédiate (Mail/SMS)           | - Notifications envoyées < 5 min après détection             | - Notifications testées sur au moins 2 canaux                   | 5            | 4 à 6 jours           |
|          |                                            |                                                              | - Tests de latence validés                                       |              |                       |
| 1        | US4 - Alerte Immédiate (Push Mobile)         | - Notifications push fonctionnelles sur Android et iOS       | - Tests sur émulateurs ou appareils réels                       | 5            | 4 à 6 jours           |
|          |                                            | - Latence et fiabilité testées                                | - Documentation mise à jour                                      |              |                       |
| 1        | US5 - Capture Photo Intrus                   | - Photo prise dans les 2 sec après détection                  | - Qualité photo validée par l’équipe                             | 8            | 7 à 10 jours          |
|          |                                            | - Résolution suffisante pour identification humaine          | - Intégration fonctionnelle dans pipeline                        |              |                       |
| 2        | US6 - Filtrage météo (éviter faux positifs) | - Réduction d’au moins 50% des faux positifs météo           | - Tests en conditions réelles et simulées                        | 8            | 7 à 10 jours          |
|          |                                            |                                                              | - Algorithme validé et intégré                                   |              |                       |
| 2        | US7 - Gestion nuage d’abeilles / multiples ruches | - Distinction fiable entre nuage d’abeilles et attaque frelon | - Validation terrain ou simulation                               | 8            | 7 à 10 jours          |
|          |                                            | - Indication de présence de plusieurs ruches                 | - Documentation associée                                         |              |                       |
| 3        | US8 - Triangulation position du Nid          | - Estimation du nid à < 50m de précision sur tests terrain   | - Algorithme de triangulation intégré et testé                  | 13           | 10 à 15 jours         |
|          |                                            |                                                              | - Plans d’atténuation documentés                                |              |                       |
| 3        | US9 - Détection de plusieurs Nids             | - Détection d’au moins 2 nids distincts >80% précision       | - Tests validés en scénario multi-nids                          | 13           | 10 à 15 jours         |
|          |                                            |                                                              | - Rapports et documentation complète                             |              |                       |

---

Chaque User Story doit être affinée et détaillée dans Trello ou l’outil de gestion choisi, avec checklist, pièces jointes, commentaires et responsabilités assignées.  

La Definition of Done garantit la qualité et la complétude avant clôture de la tâche.

### 3. Planning Meeting  
- Compte rendu structuré du Planning Meeting  
- Objectifs, découpage en sprints, rituels Scrum  
- Questions clés et réponses anticipées  

### 4. Sprints Planning  
- Sprint 1 : Infrastructure vidéo et pipeline  
- Sprint 2 : IA de classification  
- Sprint 3 : Alertes et dashboard  
- Sprint 4 : Finalisation MVP  

### 5. Sprint Reviews  
- Sprint reviews hebdomadaires (modèles)  
- Sprint review finale sur 4 semaines (MVP complet)  

### 6. Sprint Retrospectives  
- Modèles concrets de retrospectives par sprint  
- Rétrospective finale synthétique  

### 7. Suivi & Tableaux de bord  
- Description des outils (Trello, Burndown Chart, Velocity)  
- Placeholders pour images d’avancement  
- Guide d’interprétation et communication  

### 8. Bonnes pratiques Scrum complémentaires  
- Priorisation et gestion dynamique du backlog  
- Gestion des dépendances entre User Stories  
- Qualité, tests, plan de gestion des bugs  
- Documentation et formation utilisateur  
- Gestion des risques et imprévus  
- Definition of Ready, règles de communication  

### 9. Mise en scène et présentation  
- Plan détaillé de présentation orale par rôle  
- Discours type et script exemples pour chaque section  
- Conseils pratiques pour l’animation des rituels Scrum  

---

*Ce dossier est conçu pour vous accompagner dans la simulation SCRUM complète, de la planification à la présentation finale.*

