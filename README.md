#  Analyse des performances et de la satisfaction des transports urbains  
**Chicago & Philadelphia — Power BI | Python | Data Analytics**

---

##  Contexte du projet

Dans un contexte d’augmentation continue des volumes de données liées aux transports urbains, les agences de transport de **Chicago** et **Philadelphia** souhaitent disposer d’un **outil de pilotage décisionnel** permettant de mieux comprendre et analyser la fréquentation des réseaux de transport.

L’objectif principal est de fournir une **vision claire, comparative et évolutive** du *ridership* (fréquentation), afin de :

- Suivre l’évolution temporelle de la fréquentation,
- Comparer les performances entre les deux villes,
- Analyser les données par **mode de transport** et par **route**,
- Identifier des tendances, des écarts et des comportements significatifs,
- Faciliter la **prise de décision stratégique**.

Ce projet s’inscrit dans une démarche **Business Intelligence complète**, allant de la collecte et transformation des données jusqu’à leur visualisation avancée dans **Power BI**.

---

##  Objectifs du projet

- Intégrer des **sources de données hétérogènes** (RDF, CSV, Excel)
- Mettre en place un **processus ETL** automatisé avec Python
- Réaliser une **exploration et un nettoyage des données (EDA)**
- Concevoir un **modèle de données en étoile (Star Schema)**
- Créer **deux dashboards Power BI professionnels**
- Définir et calculer des **indicateurs de performance (KPIs)** pertinents

---

##  Stack technique

###  Data Processing & Analytics
- **Python**
  - `pandas`
  - `pathlib`
  - `xml.etree`
  

###  Business Intelligence
- **Power BI Desktop**
  - Power Query (ETL)
  - Modélisation des données (Star Schema)
  - DAX (mesures avancées)

###  Outils collaboratifs
- GitHub
- Jira
- Confluence

---

##  Sources de données

###  Chicago
- Ridership quotidien par **route** (format RDF converti en CSV)
- Ridership quotidien global par **mode de transport** (Bus / Rail)

###  Philadelphia
- Average Daily Ridership par **mode**
- Average Daily Ridership par **route**

---

##  Pipeline de traitement des données

1. Conversion des fichiers **RDF vers CSV** à l’aide de Python  
2. **Exploration des données (EDA)** pour identifier valeurs manquantes et incohérences  
3. **Nettoyage et standardisation** des données  
4. **Filtrage temporel** : conservation des données de **2019 à 2025**  
5. Harmonisation des noms de colonnes et des formats  
6. Création des **tables de faits**  
7. Création des **tables de dimensions**  
8. Chargement et modélisation dans **Power BI**  
9. Création des dashboards interactifs

---

##  Modèle de données

###  Tables de faits
- **Fact_Ridership_Mode**  
  → Analyse comparative de la fréquentation par **mode de transport**

- **Fact_Ridership_Route**  
  → Analyse comparative de la fréquentation par **route**

###  Tables de dimensions
- **Dim_Date**
- **Dim_City**
- **Dim_Mode**
- **Dim_Route**

La modélisation suit un **schéma en étoile**, garantissant :
- De meilleures performances
- Une lecture simplifiée des données
- Une facilité d’évolution du modèle

---

##  Dashboards Power BI

###  Dashboard 1 — Comparaison par Mode
- KPIs :  
  - Ridership total  
  - Évolution MoM (Month over Month)  
  - Évolution YoY (Year over Year)
- Comparaison **Chicago vs Philadelphia**
- Répartition **Bus / Rail**
- Analyse de l’évolution temporelle

###  Dashboard 2 — Comparaison par Route
- **Top 10 routes** par ridership
- Classement et analyse de la volatilité
- Répartition par ville
- Analyse temporelle par route

---

##  Livrables

- Notebook Python (EDA & nettoyage des données)
- Scripts Python de conversion **RDF → CSV**
- Fichier Power BI **(.pbix)**
- Dashboards interactifs
- Documentation complète (**README + Confluence**)

---

##  Conclusion

Ce projet permet de démontrer une **maîtrise complète de la chaîne décisionnelle BI**, depuis la gestion de données complexes jusqu’à la création de tableaux de bord analytiques à forte valeur métier, facilitant la prise de décision pour les acteurs du transport urbain.

