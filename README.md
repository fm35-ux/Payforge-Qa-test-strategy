# 🏦 Stratégie de Test et Recette Agile - Projet PayForge (Application TOMSEN)

## 🎯 Contexte du Projet
Ce projet simule une mission de **Consultante en Test QA** au sein de **PayForge**, une entreprise de la Fintech. 

L'objectif était de définir et de planifier de A à Z la stratégie de test globale pour le lancement de **TOMSEN**, une toute nouvelle application de gestion financière destinée aux particuliers, juste après l'obtention de son agrément auprès de la Banque de France. 

Le défi principal résidait dans l'absence totale de patrimoine de tests existant, nécessitant une conception intégrale de la couverture de qualité dans un cycle Agile de 4 mois.

---

## 📊 Objectifs de Qualité & Contraintes Métier (KPIs)
Le secteur financier impose des exigences de qualité non négociables. Ma stratégie intègre les indicateurs de succès (KPIs) stricts fixés par la Product Owner :
* **Fonctionnalités Critiques :** Taux de validation obligatoire de **100%** avant la mise en production.
* **Fonctionnalités Majeures et Mineures :** Taux de validation standard fixé à **85%**.
* **Gestion des risques de régression :** Planification d'une campagne de non-régression majeure en fin de projet pour sécuriser les fonctionnalités critiques face à l'intégration future d'un module tiers (développé par une autre équipe).

---

## 👤 Mes Missions et Approche QA

### 1. Analyse des exigences et Traçabilité
* Analyse approfondie des spécifications fonctionnelles et des maquettes de l'application.
* Création d'une **Matrice de Traçabilité des Exigences** garantissant une couverture bidirectionnelle stricte : chaque exigence est couverte par au moins un cas de test, et chaque cas de test est justifié par une exigence.

### 2. Chiffrage et Planification budgétaire
* Estimation de la charge de travail (en jours/homme) nécessaire à l'écriture et à l'exécution des campagnes en s'appuyant sur les abaques de l'entreprise pour respecter la deadline des 4 mois.

### 3. Alignement avec les Sprints de Développement (Cycle Agile)
Conception et organisation du cahier de recette pour qu'il s'intègre parfaitement au rythme de livraison de l'équipe de développement (3 Devs, 1 Tech Lead/Scrum Master, 1 PO) :
* **Sprints 1 & 2 :** Authentification et connexion (Périmètre critique)
* **Sprint 3 :** Récupération des données bancaires (Périmètre critique)
* **Sprint 4 :** Consultation des documents et transactions
* **Sprint 5 :** Suivi de consommation / Budget
* **Sprint 6 :** Conseiller virtuel

---

## 🛠️ Outils et Environnement
* **Méthodologie :** Agile / Scrum (6 Sprints de développement)
* **Gestion & Documentation :** Notion
* **Conception des tests :** Matrice Excel de revue des exigences et Cahier de recette par Sprint

---

## 📁 Livrables disponibles dans ce Repository

Les fichiers de conception sont consultables dans le dossier `/livrables` :

---

## 💡 Compétences QA Validées
Ce projet m'a permis de valider des compétences clés indispensables pour une Testeuse Logiciel :
* **Capacité à concevoir une stratégie de test globale** à partir de zéro, en traduisant des contraintes commerciales en critères de qualité mesurables.
* **Maîtrise de la gestion des risques**, en anticipant les impacts techniques d'une intégration d'API tierce via une campagne de non-régression ciblée.
* **Compétences en chiffrage (Abaques)**, permettant d'évaluer le coût et le temps de la QA au sein d'un budget projet.
* **Parfaite synergie avec les équipes de développement**, en calquant l'effort de test sur le découpage des Sprints Scrum.
