# data-chomage

Ce dépot contient les données nettoyées concernant le chomage en France pendant les années 2016 à 2019.

La structure du dépot suit le modèle suivant:

- `raw_data`: données brutes
- `clean_data`: données nettoyées
- `notebooks`: jupyter notebooks ayant servi au nettoyage ainsi qu'à l'analyse des données

## Données brutes

Les données brutes concernent trois aspects:

- informations sur les communes en 2014 en France (issu de [data.gouv.fr](https://www.data.gouv.fr/fr/datasets/r/908643e9-a25f-4420-a99a-39a10fe80c0f))
- informations sur les EPCI (composition, nature, nom) issu du site de l'[INSEE](https://www.insee.fr/fr/information/2510634)
- données de chomage par EPCI issues de [Pole Emploi](https://www.pole-emploi.org/statistiques-analyses/en-savoir/accedez-a-nos-donnees/demandeurs-demploi-par-epci.html?type=article)

## Données nettoyées

Les données de chomage ont été nettoyées. On retrouve les dossiers suivants:

- `anciennete`: contient les informations de chomage par ancienneté pour toutes les catégories
- `categorie`: contient les informations de chomage par catégorie
- `categorie_a`: contient les informations de chomage par age, sexe pour la catégorie A
- `categorie_abc`: contient les informations de chomage par age, sexe pour les catégories ABC agrégées

Les données sont disponibles avec un jeu de données par année.
