# Dashboard Marché de l'Emploi Data — Power BI

![Dashboard Page 1](/images/DashboardPage_1.png)

## Contexte du projet

Ce dashboard a été conçu pour répondre à un besoin concret : **l'information sur le marché de l'emploi data est fragmentée et difficile à exploiter**. À partir d'un jeu de données réel de **offres d'emploi Data Science 2024** (intitulés de postes, salaires, localisations géographiques), ce projet offre une interface analytique unifiée pour explorer les tendances du marché et les niveaux de rémunération.

> Cible : chercheurs d'emploi, reconvertis et professionnels souhaitant se repositionner dans la data.

---

## Compétences techniques démontrées

- **ETL & Transformation de données avec Power Query:**
Nettoyage et structuration du jeu de données brut : gestion des valeurs manquantes, typage des colonnes, création de colonnes calculées.

- **Modélisation & Mesures DAX:**
Élaboration de mesures pour calculer des KPIs clés : `Salaire Médian Annuel`, `Nombre d'Offres`, tendances temporelles.

- **Visualisations avancées:**
Utilisation de graphiques en colonnes, barres et courbes pour comparer les volumes d'offres et analyser les tendances dans le temps.

- **Analyse géospatiale:**
Cartographie de la distribution mondiale des offres d'emploi via des graphiques de type Map.

- **KPIs & Tableaux de données:**
Affichage de métriques clés via des Cards et présentation de données granulaires et triables via des Tables.

- **Design de dashboard:**
Conception d'une interface claire, intuitive et visuellement soignée, combinant types de visualisations courants et moins conventionnels pour maximiser la lisibilité des insights.

- **Interactivité & navigation:**
  - **Slicers** : filtrage dynamique par intitulé de poste
  - **Boutons** : navigation fluide entre les pages du rapport
  - **Drill-Through** : passage contextuel d'une vue synthétique vers une analyse détaillée par poste

---

## Présentation du dashboard

### Page 1 — Vue d'ensemble du marché

![Dashboard page 1](/images/DashboardPage_1.png)

Vue macro du marché de l'emploi data. Cette page centralise les KPIs essentiels : nombre total d'offres, salaires médians, top des intitulés de postes. Elle permet d'obtenir une lecture rapide et globale de l'état du marché.

### Page 2 — Analyse détaillée par intitulé de poste (Drill-Through)

![Dashboard page 2](/images/DashboardPage_2.png)

Page de plongée analytique. Accessible par drill-through depuis la vue principale, elle détaille pour un intitulé de poste donné : les fourchettes salariales, la proportion de postes en télétravail, les principales plateformes de recrutement, et la distribution géographique mondiale des offres.

---

## Conclusion

Ce projet illustre la capacité à transformer des données brutes en outil d'aide à la décision opérationnel avec Power BI. Il met en oeuvre l'ensemble de la chaîne analytique : ingestion et nettoyage des données, modélisation, création de mesures DAX, et restitution via un dashboard interactif, filtrable et navigable.
