# US Flights Performance Dashboard

Analyse et tableau de bord de performance sur près de 8 millions de vols aériens commerciaux aux États-Unis (2010-2011), à partir d'un jeu de données brut nécessitant nettoyage et préparation.

## Aperçu du projet

- **Préparation des données** — reconstruction de la date de vol, scission des champs ville/état pour l'origine et la destination, correction des formats, création de nouvelles variables via champs calculés.
- **Analyse exploratoire** — série de visualisations ciblées répondant à des questions d'affaires précises :
  - Explication de la baisse d'environ 300 000 vols entre 2010 et 2011
  - Identification des journées avec chute marquée du trafic aérien et mise en contexte (événements survenus aux États-Unis)
  - Compagnie aérienne exploitant le plus de vols hebdomadaires
  - Comparaison des retards moyens au départ par état pour chaque compagnie (dont JetBlue)
  - Aéroports les plus achalandés, incluant le hub principal de Delta
  - Variation mensuelle (%) de l'achalandage par compagnie par rapport à l'année précédente
- **Tableau de bord de performance** — indicateurs clés de performance (KPI) comparant automatiquement la période actuelle à la période équivalente de l'année précédente, avec mise à jour dynamique des dates de comparaison.

## Compétences techniques mises en pratique

- Nettoyage et structuration de données volumineuses (~8M lignes) directement dans Tableau
- Champs calculés (extraction de dates, découpage de chaînes, agrégations conditionnelles, comparaisons période sur période)
- Sélection de graphiques adaptés au contexte analytique
- Conception de tableau de bord orienté KPI pour un contexte opérationnel (compagnie aérienne)

## Fichier

- [`us-flights-performance-dashboard.twbx`](./us-flights-performance-dashboard.twbx) — classeur Tableau complet

*Réalisé dans le cadre du cours Visualisation de données (DECI1017).*
