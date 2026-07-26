# Global Development Dashboard

Tableau de bord interactif analysant l'évolution du développement mondial (émissions de CO2, PIB par habitant, espérance de vie et indice de développement humain) pour 175 pays entre 1998 et 2018, à partir du jeu de données Gapminder.

## Aperçu du dashboard

- **Indicateurs clés (KPI)** — CO2 moyen par habitant, espérance de vie moyenne, PIB moyen par habitant et indice de développement humain moyen, filtrables par année et par continent.
- **Jauges dynamiques** — niveaux de pollution, d'espérance de vie, de PIB et d'IDH, avec seuils et messages contextuels calculés (ex. « Niveau considéré élevé »), et couleurs conditionnelles.
- **Classement Top 10** — pays les plus polluants par habitant d'un continent donné, avec coloration relative à la moyenne continentale.
- **Nuage de points** — espérance de vie vs PIB par habitant, avec lignes de référence mondiales et dégradé de couleur associé à l'espérance de vie.
- **Évolution temporelle** — tendance de l'espérance de vie par continent (1998–2018), avec mise en évidence du continent sélectionné.
- **Carte interactive** — indice de développement humain par pays, avec infobulle détaillant le classement mondial sur plusieurs mesures.
- **Navigation par actions** — filtres année/continent activés par boutons interactifs, sans recours aux filtres standards.

## Compétences techniques mises en pratique

- Champs calculés (logique conditionnelle, seuils dynamiques, classements `RANK`)
- Paramètres et actions de filtrage entre feuilles
- Mise en forme conditionnelle et palettes de couleurs personnalisées
- Conception de tableau de bord (tuiles, alignement, hiérarchie de l'information)

## Fichier

- [`global-development-dashboard.twbx`](./global-development-dashboard.twbx) — classeur Tableau complet (données intégrées)

*Réalisé dans le cadre du cours Visualisation de données (DECI1017).*
