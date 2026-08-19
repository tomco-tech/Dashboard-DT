# Tableau de bord DT — EMM v1.2

Widget Grist en lecture seule, rattaché à `B_EMM`.

- filtres compacts par catégorie et service utilisateur ;
- périmètre ACMOSS : indicateurs compacts et répartition des demandes par service sous forme de treemap ;
- périmètre DT : indicateurs compacts, projection du mois en cours et du mois suivant par tranches de 7 jours ;
- axe vertical explicite sur la projection, sans séparation graphique entre les mois ;
- alertes `En cours DT` fondées exclusivement sur `Etat = En retard` ou `Etat = A risque` ;
- message vert lorsqu’aucune alerte DT n’est détectée.

Colonnes principales : `Service Utilisateur`, `Catégorie`, `Prio`, `Statut`, `Cible`, `Etat`, `Description`, `Commentaire`.
