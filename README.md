# Tableau de bord DT global — V2

Widget Grist en lecture seule consolidant :

- `B_EMM`
- `B_Infra_Flux` / `B_Infra & Flux`
- `B_Chantiers_de_conception`

## Fonctions

- filtres intelligents par service utilisateur, communauté, priorité, statut, état et date cible ;
- KPIs consolidés des périmètres ACMOSS et DT ;
- treemap des sujets par service ;
- projection des livraisons du mois courant et du mois suivant, ventilée par catégorie ;
- sujets à risque ou en retard ;
- liste consolidée des sujets sous forme de cartes ;
- mise en évidence croisée entre les visualisations, sans modifier les totaux ;
- résolution des colonnes de référence et récupération de la communauté depuis `REF_Services_Utilisateurs` lorsqu’elle est disponible.

## Installation

1. Publier `index.html`, `README.md` et `.nojekyll` sur GitHub Pages.
2. Ajouter un widget personnalisé dans Grist.
3. Utiliser l’URL GitHub Pages.
4. Accorder `Full document access` pour permettre la lecture des trois tables et des métadonnées de références.

Le widget n’effectue aucune écriture dans Grist.
