# material-deprivation-côte-divoire
Projet d'analyse multidimentionnelle des données réalisée en première année de ma formation.
# Pauvreté monétaire et privation matérielle en Côte d'Ivoire : analyse factorielle

Projet d'analyse des données, ENSEA (1re année). Outils : SPAD, R.

## Contexte
Étudier le chevauchement entre pauvreté monétaire (dépenses de consommation) et
privation matérielle (biens et équipements du logement).

## Données
EHCVM 2021 (Côte d'Ivoire) : lien vers la page de l'enquête (https://microdata.worldbank.org/index.php/catalog/6273)
*Les données brutes ne sont pas publiées ici (conditions d'utilisation).*

## Méthode
- **ACP** sur les biens et équipements, pour construire un score de conditions de vie
- **ACM** sur les variables du logement, avec classification des ménages en trois groupes
- **AFC** entre le score de conditions de vie et la consommation

## Résultats principaux
- Premier axe de l'ACP : gradient de niveau de vie (24,3 % de l'inertie)
- ACM : trois groupes de ménages (aisés, intermédiaires, en forte privation)
- AFC : l'axe 1 explique environ 90 % de l'inertie ; forte correspondance entre
  conditions de vie et consommation

![Cercle des corrélations (ACP)](COLLER-LA-CAPTURE-ICI)

## Mon rôle
J'ai réalisé l'ensemble des analyses (ACP, ACM, AFC) et produit les graphiques.

## Auteures du rapport
-KOUAKOU Tryphène, 
-N'DRI Ayella
-TUO Fatima 
(rapport rédigé en groupe de trois)

*Rapport complet disponible sur demande. / Full report available on request.*

## English summary
Overlap between monetary poverty and multidimensional material deprivation in Côte
d'Ivoire (EHCVM 2021), using PCA, MCA and correspondence analysis. Households' living
conditions and consumption levels line up strongly along the first factorial axis.
I carried out all the analyses (SPAD, R).
