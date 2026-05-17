# 📋 Refonte de l'outil de reporting — Portefeuille crédit

> **Portfolio Project** | Business Analyst & Business Data Analyst Freelance  
> Livrables : Expression des besoins · Spécifications fonctionnelles · Plan de recette UAT  
> Secteur : Banque / Finance

---

## 🎯 Contexte métier

BanqueRégionale SA pilote son portefeuille crédit via des fichiers Excel manuels, mis à jour chaque semaine par les équipes contrôle de gestion et risques. Ce dispositif génère des erreurs, des délais de reporting trop longs (J+5) et une absence de vision consolidée en temps réel.

La DSI mandate un Business Analyst pour cadrer et spécifier la refonte vers un outil Power BI centralisé, connecté au Core Banking System (CBS).

---

## 👥 Parties prenantes

| Rôle | Implication |
|------|-------------|
| Directeur des Risques | Approbateur — pilote NPL ratio et conformité Bâle III |
| DAF / Contrôle de gestion | Recetteur — suit les objectifs budgétaires agences |
| Directeur d'agence | Recetteur — pilote son portefeuille local (RLS) |
| Responsable Conformité | Consulté — reportings réglementaires EBA / ACPR |
| DSI / Chef de projet IT | Responsable technique — développement Power BI |
| Business Data Analyst | Auteur — cadrage, specs, recette |

---

## 📁 Livrables du projet

```
portfolio-ba-refonte-reporting/
│
└── docs/
    ├── 01_expression_besoins.docx
    ├── 02_specifications_fonctionnelles.docx
    └── 03_plan_recette_UAT.docx
```

---

## 📄 Contenu des livrables

### 01 — Expression des besoins métier
- Contexte et enjeux (fiabilité, réactivité, conformité, pilotage)
- Matrice RACI — 7 parties prenantes
- Besoins détaillés par profil utilisateur (4 profils)
- Contraintes techniques, réglementaires et de sécurité
- Périmètre V1 et hors périmètre
- Planning en 5 phases sur 12 semaines

### 02 — Spécifications fonctionnelles
- 10 user stories (format standard : rôle / fonctionnalité / bénéfice)
- Règles de gestion crédit : classification sain / douteux / défaut (RG-CRD-001 à 004)
- Formules de calcul des KPIs : NPL ratio, taux de couverture, taux de réalisation
- Description fonctionnelle des 3 pages du dashboard Power BI
- Architecture de la solution et flux de données CBS → ETL → Power BI Service

### 03 — Plan de recette UAT
- 14 cas de test couvrant les 3 modules du dashboard
- Critères d'acceptation globaux (taux de passage, RLS, performance)
- Matrice de traçabilité : besoin → user story → spécification → cas de test
- Grille de criticité des anomalies (P1 bloquant / P2 majeur / P3 mineur)
- Fiche standardisée de remontée d'anomalie
- Procès-verbal de recette à signer avant Go-live

---

## 🔑 Concepts métier couverts

| Terme | Définition |
|-------|-----------|
| **UAT** | User Acceptance Testing — recette utilisateurs avant mise en production |
| **RACI** | Matrice Responsable / Approbateur / Consulté / Informé |
| **User story** | Expression d'un besoin du point de vue utilisateur |
| **RLS** | Row-Level Security — restriction des données par profil Power BI |
| **NPL Ratio** | Non-Performing Loans — part des crédits douteux et en défaut |
| **Bâle III** | Réglementation bancaire internationale sur les fonds propres et le risque |
| **EBA** | European Banking Authority — autorité de reporting réglementaire européen |
| **CBS** | Core Banking System — système central de gestion bancaire |
| **ETL** | Extract Transform Load — pipeline d'alimentation des données |
| **PV de recette** | Document signé attestant la validation avant Go-live |

---

## 🛠️ Compétences BA démontrées

- Recueil et formalisation des besoins métier multi-parties prenantes
- Rédaction de spécifications fonctionnelles détaillées
- Modélisation des règles de gestion métier
- Élaboration d'un plan de recette UAT complet
- Maîtrise de la traçabilité besoins → specs → tests
- Connaissance du secteur bancaire (réglementation, KPIs crédit)

---

## 👤 Auteur

**Bleze TCHALLA**  
Business Data Analyst Freelance  
Spécialité : Analyse métier · Spécifications fonctionnelles · Power BI · SQL 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profil-blue)](https://linkedin.com/in/bleze-tchalla)

---

*Projet simulé à partir de cas d'usage réels en banque de détail. Données et noms d'entreprises fictifs.*
