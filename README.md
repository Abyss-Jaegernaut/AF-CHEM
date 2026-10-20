
# PhytoTrace – AF-CHEM SOFACO

Projet du module **Atelier du Génie Logiciel** – Institut Ivoirien de Technologie.

## Présentation de la société

**AF-CHEM SOFACO** est une société anonyme ivoirienne au capital de 2 000 000 000 FCFA, spécialisée dans les produits agro-pharmaceutiques (« La référence du phytosanitaire en Côte d'Ivoire »).

- **Historique** : née le 4 novembre 2008 de la fusion de SOFACO (créée en 1961, fabrication industrielle de pesticides) et d'AFCHEM (créée en 2003, distribution de pesticides et d'engrais). Actionnaire majoritaire : groupe SFP (84 %).
- **Siège** : Treichville, Angle Rue des Brasseurs – Zone 3, 30 BP 674 Abidjan 30.
- **Outil industriel** : usine sous agrément UEMOA de formulation, conditionnement et reconditionnement ; usine d'insecticides (tanks d'environ 5 000 L), usine d'herbicides (tanks d'environ 2 500 L), laboratoire d'analyses qualité (chromatographie en phase gazeuse et liquide), service QHSE.
- **Produits** : insecticides, herbicides, fongicides, régulateurs de croissance, traitement de semences, engrais, biosolutions, hygiène publique, appareils de traitement.
- **Présence** : 18 localités en Côte d'Ivoire ; filiales SEAP-CI (San Pedro), AF-CHEM Mali (Bamako), AF-CHEM Burkina Faso (Bobo-Dioulasso).

## Présentation du projet

**PhytoTrace** est une application web responsive qui centralise les formules, les lots de production, le contrôle qualité et les stocks. Son objectif : retrouver en moins de cinq minutes l'historique complet d'un lot, de la matière première au produit fini.

Version 1 (MVP) : authentification par rôle, articles et formules avec versions, lots de production et consommations, résultats du laboratoire et libération des lots, stocks en temps réel (règle FEFO), traçabilité par numéro de lot.

Évolutions possibles : fiches de données de sécurité, alertes, tableau de bord, exports PDF/Excel, QR code.

Technologies prévues : Python / Django (back-end), templates Django + Bootstrap (front-end par défaut, React ou Vue.js possible via Django REST Framework), PostgreSQL.

## Planning

Planning officiel du module, sur quatre mois :

| Phase | Période |
|---|---|
| Analyse et conception (visite entreprise, analyse, conception, maquettes, présentation) | Mois 1 |
| Développement front-end (interface utilisateur, présentation) | Début du mois 2 |
| Développement back-end 1/2 (initialisation, entités, vues et routage) | Fin du mois 2 – début du mois 3 |
| Développement back-end 2/2 (dynamisation, tests, documentation technique) | Mois 3 |
| Présentation, puis correction et prise en compte des remarques | Mois 4 |
| Présentation finale | Fin du mois 4 |

## Organisation du dépôt

```
AFCHEM/
├── README.md
|
├── cadrage/
    └── cahier_des_charges.docx

```

## Liens utiles

- Site de l'entreprise : https://afchemsofaco.com
- Maquette Figma : *à ajouter*
