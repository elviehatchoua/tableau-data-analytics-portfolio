# HR Workforce Equity Dashboard

Tableau de bord des ressources humaines analysant l'équité de genre au sein des employés actifs d'une entreprise, à des fins de suivi de la diversité et de l'équité salariale.

## Aperçu du dashboard

- **Effectifs globaux** — total des employés, répartition hommes/femmes, distribution des embauches annuelles par genre.
- **Indicateurs moyens** — âge moyen, ancienneté moyenne, salaire moyen et satisfaction moyenne, globalement et par genre (calculés en date du 31 décembre 2018).
- **Distribution démographique** — répartition de l'âge des employés par genre, et effectifs par département selon le genre.
- **Top 5 séniorité par département** — pour chaque département, les 5 employés les plus seniors avec identifiant, genre, nom, poste, salaire et années d'expérience.
- **Diversité** — distribution des employés selon la race et le genre.
- **Équité salariale** — analyse du lien entre salaire et années d'expérience, par département et par genre.
- **Contrôle interactif** — sélection du département.

## Compétences techniques mises en pratique

- Conception de tableau de bord à partir de critères d'affaires RH (simulation d'un mandat réel)
- Champs calculés temporels (âge et ancienneté à une date de référence fixe)
- Analyse comparative multi-dimensionnelle (genre, race, département)
- Visualisation de distributions et de relations entre variables (salaire vs expérience)

## Fichier

- [`hr-workforce-equity-dashboard.twb`](./hr-workforce-equity-dashboard.twb) — classeur Tableau (structure du dashboard ; les données sources `HRDataset.csv` ne sont pas incluses)

*Réalisé dans le cadre du cours Visualisation de données (DECI1017).*
