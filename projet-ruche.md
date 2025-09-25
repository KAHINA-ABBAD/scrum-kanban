# Mise en scène Scrum : Détection d’attaque de frelons sur ruches

## 1. Contexte du projet - Oliver

Objectif du projet :
- (Exemple à compléter – surveillance et protection de ruches avec IA/capteurs)

Problématique à résoudre :
- (Ex : Attaques fréquentes de frelons asiatiques sur les ruches, difficulté d’intervention rapide...)

## 2. Organisation Scrum du projet - Olivier

Product Owner :
- Olivier, rôle, missions

Scrum Master :
- Romuald, rôle, missions

Equipe de développement :
- Kahina, rôles (IA, dashboard, alertes, capteurs...)

## 3. Backlog Produit (User Stories) - Olivier

'#' |	User Story	                                                           | Critères d’acceptation | Priorité | Notes |
----|------------------------------------------------------------------------|------------------------|----------|-------|
  1 |	En tant qu’apiculteur, je veux une alerte en cas d’attaque de frelon...|	                      |          |       |  2 |		                                                                     |                        |          |       |

## 4. Planning meeting - Romuald
Gant, gestion des sprint, etc...

## 4. Sprint Planning - Romuald

Sprint courant :
- (Ex : durée, objectifs principaux, user stories sélectionnées)
Tâches à réaliser :

## 4. Sprint Backlog

## 5. Daily Scrum - Kahina

Avancement :
- (Checklist à remplir : fait, en cours, blocage)
Obstacles rencontrés :

## 6. Sprint Review - Kahina / Romuald

Livrables présentés :
- (Ex : prototype IA, dashboard, journal des attaques...)
- Feedback utilisateur (apiculteur) :

## 7. Rétrospective Sprint - Romuald

Ce qui a bien fonctionné :

Ce qui doit être amélioré :

## 8. Suivi & Tableaux - Romuald

Tableau Kanban (à dessiner ou intégrer)

Dashboard de suivi des attaques (captures ou schémas)

## 9. Cas Spéciaux - Oliver / Kahina

Scénarios d’attaque simultanée / multiples ruches :

Gestion des alertes et du reporting :








PBI --> User Stories --> Story Points x timebox --> Ingénieur avec 2 ans d'experience

NPriorité 1
US1 - Identification Frelon (Asiatique / Européen)
En tant qu’apiculteur, je veux que le système détecte et différencie précisément les frelons asiatiques et européens pour mieux cibler les interventions.
Critères d’acceptation :

Modèle IA capable de classifier avec une précision ≥85% sur jeu de test.

Résultats validés sur un dataset équilibré.
Story Points : 8
Timebox estimé : 7 à 10 jours

US2 - Dashboard Statistiques Quotidiennes
En tant qu’apiculteur, je veux consulter un tableau de bord indiquant le nombre d’attaques par jour, type de frelons, et heures d’activité.
Critères d’acceptation :

Dashboard web responsive fonctionnel.

Statistiques agrégées mises à jour en temps réel.
Story Points : 5
Timebox estimé : 4 à 6 jours

US3 - Alerte Immédiate (Mail / SMS)
En tant qu’apiculteur, je veux recevoir des alertes immédiates par mail et SMS dès qu’une attaque est détectée.
Critères d’acceptation :

Notifications envoyées dans les 5 minutes suivant la détection.

Tests sur plusieurs canaux (mail, SMS) validés.
Story Points : 5
Timebox estimé : 4 à 6 jours

US4 - Alerte Immédiate (Push Mobile)
En tant qu’apiculteur équipé d’un smartphone, je veux recevoir des notifications push pour être alerté en temps réel.
Critères d’acceptation :

Notifications push fonctionnelles sur Android et iOS (simulées si nécessaire).

Test de latence et fiabilité.
Story Points : 5
Timebox estimé : 4 à 6 jours

US5 - Capture Photo Intrus
En tant qu’apiculteur, je veux que la caméra capture automatiquement une photo haute résolution de l’intrus détecté.
Critères d’acceptation :

Photo prise dans les 2 secondes après détection.

Qualité suffisante pour identification humaine.
Story Points : 8
Timebox estimé : 7 à 10 jours

Priorité 2
US6 - Filtrage météo (éviter faux positifs pluie/vent/feuilles)
En tant qu’équipe technique, je veux que le système filtre les fausses détections causées par la pluie, le vent ou des feuilles afin d’améliorer la qualité des alertes.
Critères d’acceptation :

Réduction des faux positifs météo d’au moins 50% validation terrain.
Story Points : 8
Timebox estimé : 7 à 10 jours

US7 - Gestion nuage d’abeilles / dédoublement de ruche
En tant qu’apiculteur, je veux que le système distingue un nuage d’abeilles normal d’une attaque réelle et identifie s’il y a plusieurs ruches proches.
Critères d’acceptation :

Classification fiable entre nuage d’abeilles et attaque frelons.

Indication de présence de plusieurs ruches.
Story Points : 8
Timebox estimé : 7 à 10 jours

Priorité 3
US8 - Triangulation position du Nid
En tant qu’apiculteur, je veux localiser géographiquement le nid de départ grâce à la triangulation des trajectoires des frelons détectés.
Critères d’acceptation :

Estimation du nid à une distance raisonnable (<50m) sur tests terrain.
Story Points : 13
Timebox estimé : 10 à 15 jours

US9 - Détection de plusieurs Nids
En tant qu’apiculteur, je veux que le système identifie la présence de plusieurs nids dans la zone surveillée pour mieux organiser la défense.
Critères d’acceptation :

Système détectant au moins 2 nids distincts avec un taux de précision >80%.
Story Points : 13
Timebox estimé : 10 à 15 jours