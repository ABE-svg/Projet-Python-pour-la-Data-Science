# Projet python pour la datascience - ENSAE - 2A

**_Auteurs: ABE Kevin, DEMGNE Lisa, Oscar_**

## Sujet:
Les accidents de la circulation routière constituent l'une des préoccupations majeures des autorités francaises depuis des années. De l’après guerre à nos jours, environ 700 000 personnes ont été tuées sur les routes de France (OSNIR). Un ensemble de politiques ont été mises sur pieds pour lutter contre ce fléau. Par exemple, le permis à point est instauré en 1992 dans le but de pénaliser la mauvaise conduite. En 2001, Le Conseil national de la sécurité routière (CNSR) voit le jour. Il rassemble les principaux acteurs de la sécurité routière, avec leurs compétences et sensibilités respectives, afin qu’ils puissent débattre, échanger et réfléchir pour formuler des propositions concrètes à l’attention du Gouvernement pour inverser la courbe de la mortalité routière. L'ensemble de mesures mises en place par le CNSR ont entrainé une baisse de la mortalité de 51% sur la période 2002-2012 et de 11% sur la période 2012-2019. Il faut noter que les données statistiques nationales de sécurité routière sont collectées, mises en forme, interprétées et diffusées par L'Observatoire national interministériel de la sécurité routière (ONISR) ce qui assure un suivi continu de l'évolution de la courbe de mortalité dû aux accidents de la circulation routière.
La France a signé les déclarations européennes de La Valette en 2017 et de Stockholm en 2020. Ainsi, elle s’est engagée à long terme dans la « vision zéro » (zéro décès et zéro blessé grave à l'horizon 2050) et a repris à son compte l’objectif en sécurité routière de l’ONU de réduire de moitié la mortalité routière et le nombre de blessés graves pour la décennie d’action en cours (d’ici 2030, en prenant comme année référence 2019, avant la pandémie).
Ce projet a pour objectif d'analyser les données des accidents corporels de la circulation routière établies par l'ONISR, et de  déterminer les facteurs pouvant influencer la gravité d'un accident.

## Intérêt
Un Etat des lieux de l'accidentologie pour une année donnée renseigne les forces de l'ordre sur l'éfficacité ou non des mesures en place pour limiter les accidents routiers. De plus, l'identification des facteurs à risque peut aider à l'optimisation des patrouilles de polices ainsi que la circonscription des points de sensibilisation.

## Statistiques descriptives
Pour le description des données, nous utiliserons essentiellement des méthodes d'analyse descriptive univariée et bivariée.

## Modélisation
Nous avons utiliser un modèle de régression logistique multivarié ( étant donné que la variable cible qui est ici le niveau de gravité de l'accident a plus de deux catégories). Ce modèle nous permet d'identifier les facteurs déterminant du niveau de gravité d'un accident, et aussi d'estimer la probabilité de la gravité de l'accident en fonction des variables explicatives.

## Sources des données

- [Base de données annuelles des accidents corporels de la circulation routière](https://www.data.gouv.fr/fr/datasets/bases-de-donnees-annuelles-des-accidents-corporels-de-la-circulation-routiere-annees-de-2005-a-2023/?reuses_page=1#/resources)
- [Code officiel géographique](https://www.insee.fr/fr/metadonnees/source/operation/s2085/bases-donnees-ligne): où nous avons pris les données sur les codes INSEE des départements et leur noms.

Liens de téléchargement des bases de données annuelles sur les accidents corporels de la circulation routière en 2023:
- [Base des usagers](https://www.data.gouv.fr/fr/datasets/r/68848e2a-28dd-4efc-9d5f-d512f7dbe66f)
- [Base des véhicules](https://www.data.gouv.fr/fr/datasets/r/146a42f5-19f0-4b3e-a887-5cd8fbef057b)
- [Base des lieux](https://www.data.gouv.fr/fr/datasets/r/8bef19bf-a5e4-46b3-b5f9-a145da4686bc)
- [Base des caractéristiques des accidents](https://www.data.gouv.fr/fr/datasets/r/104dbb32-704f-4e99-a71e-43563cb604f2)

## Références

[regression lasso](https://www.ibm.com/fr-fr/topics/lasso-regression)


ajouter les références, décrire les packages qui sont utilisés, et la procédure pour parcourir le projet