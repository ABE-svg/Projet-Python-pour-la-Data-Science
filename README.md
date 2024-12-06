# Projet python pour la datascience - ENSAE - 2A

**_ Auteurs: ABE Kevin, DEMGNE Lisa, Oscar _**

## Sujet:
Un accident de la route ou accident de la circulation est entendu comme une collision non voulue, non prévue et mal anticipée d'au moins un engin roulant avec une chose, un animal ou une personne sur une voie publique ou privée ouverte à la circulation.Ils constituent un véritable fléau mondial, causant chaque année des milliers de morts et de blessés. Ces tragédies bouleversent des vies et ont un impact considérable sur la société. En France, la lutte contre ce phénomène est prise en charge au niveau national par la délégation à la sécurité routière, qui se sert des éclairages fourni par un document d'information édité annuellement par l'ONISR(Observatoire National Interministériel de la Sécurité Routière) faisant la synthèse des principales données de l'accidentologie.
Nous nous intéresserons dans le cadre de ce projet à la description de l'accidentologie en France en 2023, ainsi qu'a la prédiction du niveau de gravité d'un accident. Ainsi, ce projet se donne de renseigner sur la fréquence des accidents, le profil des victimes, les caractéristiques des véhicules impliqués, les conditions météorologiques,... et ainsi que les facteurs succeptibles d'influencer le niveau de gravité d'un accident.

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



