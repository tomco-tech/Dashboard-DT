# Tableau de bord DT global — V2.4

Widget Grist en lecture seule consolidant :

- `B_EMM`
- `B_Infra_Flux` / `B_Infra & Flux`
- `B_Chantiers_de_conception`

## Fonctions

- filtres intelligents par service utilisateur, communauté, catégorie de périmètre, priorité, statut, état et date cible ;
- KPIs consolidés des périmètres ACMOSS et DT, tous cliquables ;
- treemap des sujets par service ;
- badge bleu `C` lorsqu’un service possède au moins un chantier de conception ;
- pondération renforcée des chantiers de conception dans le calcul de surface de la treemap ;
- section indépendante **Projection des livraisons DT** sur le mois courant et le mois suivant ;
- projection ventilée uniquement selon les trois périmètres consolidés : **Configuration EMM**, **Infra & Flux** et **Chantier de conception** ;
- section indépendante **Sujets à risque ou en retard**, placée à droite de la projection sur les grands écrans ;
- liste consolidée **Sujets concernés** sous forme de cartes ;
- clic sur une carte : mise en évidence croisée ;
- bouton `⤢` sur chaque carte : ouverture d’une fenêtre de détail en lecture seule, refermable avec `⤡`, en cliquant hors de la fenêtre ou avec Échap ;
- résolution des colonnes de référence et récupération de la communauté depuis `REF_Services_Utilisateurs` lorsqu’elle est disponible.

## Installation

1. Publier `index.html`, `README.md` et `.nojekyll` sur GitHub Pages.
2. Ajouter un widget personnalisé dans Grist.
3. Utiliser l’URL GitHub Pages.
4. Accorder `Full document access` pour permettre la lecture des trois tables et des métadonnées de références.

Le widget n’effectue aucune écriture dans Grist.


## Ajustements V2.4

- Badge `C` de la treemap adouci avec un bleu très clair.
- Couleur `Configuration EMM` de la projection remplacée par un vert sauge pâle, avec un texte sombre pour conserver la lisibilité.
