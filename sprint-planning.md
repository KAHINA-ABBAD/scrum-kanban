## Sprint 1 : Infrastructure robuste et pipeline vidéo  

**Sprint Goal :**  
Avoir un système de capture vidéo fonctionnel 24h/24 en toutes conditions météo, avec un flux vidéo stable et prêt pour le traitement en temps réel.  

**User Stories sélectionnées :**  
- US1 : En tant qu’apiculteur, je veux une caméra IP66/67 résistante aux intempéries avec un boîtier étanche pour garantir la continuité du flux vidéo.  

**Tâches principales :**  
- Sélection et achat des caméras IP66/67 adaptées  
- Conception et installation du boîtier étanche avec système anti-condensation  
- Mise en place d’un pipeline de streaming vidéo stable (testé sur réseau local)  
- Réalisation de tests de résistance aux conditions météo (pluie, neige, humidité)  

**Definition of Done :**  
- Caméra opérationnelle 24h/24 en conditions réelles  
- Flux vidéo continu, sans interruption ni perte de qualité  
- Tests de résistance validés (>12h de fonctionnement sous conditions simulées)  

**Rituels Scrum :**  
Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective  

---

## Sprint 2 : IA de détection et classification des frelons  

**Sprint Goal :**  
Développer un modèle d’IA capable de détecter et différencier les attaques de frelons asiatiques et européens avec une précision supérieure à 85%.  

**User Stories sélectionnées :**  
- US2 : En tant qu’apiculteur, je veux que le système identifie précisément frelons asiatiques, frelons européens, abeilles, bourdons et guêpes.  

**Tâches principales :**  
- Constitution et annotation d’un dataset représentatif (env. 2 400 images)  
- Entraînement d’un modèle CNN (type YOLO) multi-classes  
- Validation sur jeu de test avec seuil de précision minimum de 85%  
- Optimisation du modèle pour une inférence en temps réel intégrée au pipeline vidéo  

**Definition of Done :**  
- Modèle entraîné avec précision validée sur jeu test  
- Intégration fonctionnelle dans le pipeline de traitement vidéo  
- Tests d’inférence temps réel réalisés avec succès  

**Rituels Scrum :**  
Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective  

---

## Sprint 3 : Mise en place des alertes et du dashboard  

**Sprint Goal :**  
Mettre en place un système d’alertes temps réel et un dashboard web présentant les statistiques quotidiennes des attaques.  

**User Stories sélectionnées :**  
- US3 : En tant qu’apiculteur, je veux recevoir des alertes par SMS, email, et notifications mobiles lors d’attaques détectées.  
- US4 : En tant qu’apiculteur, je veux consulter un dashboard accessible sur mobile et PC avec statistiques des attaques (nombre, type, horaires).  

**Tâches principales :**  
- Développer l’API de notification multi-canal (SMS, mail, push mobile)  
- Concevoir et développer le dashboard web responsive  
- Mettre en place une base de données pour stocker les événements détectés  
- Implémenter graphiques et rapports pour mesures clés  
- Tests d’intégration complète alerte-détection-dashboard  

**Definition of Done :**  
- Notifications fonctionnelles et testées sur différents supports  
- Dashboard accessible et affichant les données en temps réel  
- Données historiques bien sauvegardées et exploitables  

**Rituels Scrum :**  
Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective  

---

## Sprint 4 : Finalisation du MVP et déploiement  

**Sprint Goal :**  
Livrer un MVP complet, testé, documenté, et déployé fonctionnel en production.  

**User Stories sélectionnées :**  
- US5 : En tant qu’apiculteur, je veux que la caméra capture des photos haute résolution des frelons détectés pour identification visuelle.  
- US6 : En tant qu’équipe, nous voulons assurer la stabilité du système, optimiser la consommation énergétique, et obtenir la validation client finale.  

**Tâches principales :**  
- Développement du module capture photo instantanée lors d’attaque détectée  
- Réalisation de tests d’endurance avec fonctionnement continu 72h  
- Optimisation consommation énergétique (caméra, serveur)  
- Création de l’interface d’administration dédiée à l’apiculteur  
- Rédaction de la documentation utilisateur et technique  
- Organisation et réalisation des tests d’acceptation client (démo Méthodique)  

**Definition of Done :**  
- MVP validé par le client selon cahier des charges  
- Documentation complète livrée  
- Système déployé en environnement réel et opérationnel  

**Rituels Scrum :**  
Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective  
