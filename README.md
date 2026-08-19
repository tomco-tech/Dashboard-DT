# Tableau de bord opérationnel — Section EMM v1

Widget Grist en lecture seule, à rattacher à la table `B_EMM`.

## Contenu

- indicateurs : demandes en cours, en retard, à risque ;
- répartition des demandes par service utilisateur ;
- focus DT : En cours DT, Déployé, Terminé ;
- projection des livraisons sur le mois en cours et les cinq mois suivants ;
- alertes nominatives pour les demandes En cours DT en retard ;
- filtres par catégorie et service utilisateur ;
- titre EMM dynamique indiquant explicitement la catégorie sélectionnée.

## Règles de calcul

- **En cours** : statut renseigné différent de `Déployé` et `Terminé`.
- **En retard** : `Etat = En retard`, ou Date Cible dépassée, hors demandes clôturées.
- **À risque** : `Etat = A risque` ou `À risque`.
- **Projection** : lignes `En cours DT`, `Déployé` ou `Terminé` ayant une `Date Cible` / `Cible` dans le mois en cours ou les cinq mois suivants.
- **Alerte DT** : ligne `En cours DT` en retard. Le titre de l’alerte est `Service Utilisateur — Catégorie`.

## Colonnes reconnues

Le widget accepte les libellés visibles ou IDs techniques proches, notamment :

- `Service Utilisateur`
- `Catégorie`
- `Prio`
- `Statut`
- `Etat`
- `Date Cible` ou `Cible`

Les champs texte, choix et références sont résolus automatiquement.

## Installation

1. Publier `index.html` via GitHub Pages.
2. Créer un widget personnalisé Grist rattaché à `B_EMM`.
3. Renseigner l’URL GitHub Pages.
4. Accorder `Full document access` pour permettre la lecture des références et des métadonnées. Le widget ne réalise aucune écriture.
