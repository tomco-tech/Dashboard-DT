# Tableau de bord DT global — V2.1

Widget Grist en lecture seule consolidant :

- `B_EMM`
- `B_Infra_Flux` / `B_Infra & Flux`
- `B_Chantiers_de_conception`

## Fonctions

- filtres intelligents par service utilisateur, communauté, catégorie de périmètre, priorité, statut, état et date cible ;
- filtre de périmètre proposant `EMM`, `Infra & Flux` et `Chantiers de conception` ;
- KPIs consolidés des périmètres ACMOSS et DT, tous cliquables ;
- treemap des sujets par service ;
- projection des livraisons du mois courant et du mois suivant, ventilée par catégorie ;
- sujets à risque ou en retard ;
- liste consolidée des sujets sous forme de cartes ;
- lorsqu’une visualisation est sélectionnée, la section **Sujets concernés** affiche uniquement les cartes correspondantes, tandis que les autres visualisations utilisent la mise en évidence croisée ;
- résolution des colonnes de référence et récupération de la communauté depuis `REF_Services_Utilisateurs` lorsqu’elle est disponible.

## Installation

1. Publier `index.html`, `README.md` et `.nojekyll` sur GitHub Pages.
2. Ajouter un widget personnalisé dans Grist.
3. Utiliser l’URL GitHub Pages.
4. Accorder `Full document access` pour permettre la lecture des trois tables et des métadonnées de références.

Le widget n’effectue aucune écriture dans Grist.
