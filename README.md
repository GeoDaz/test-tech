# React + Vite

-   pour lancer le projet `npm install` puis `npm run dev`

## Préambule :

Désactiver toute IA dans l'éditeur
Aucun style n'est demandé

## Consigne :

Récupérer les données présentes dans public/dataset.json au moyen d'une requete fetch.
Les données sont typées de la façon suivante : {"id": number, "label": string, "amount": number, "tva"?: number, "removable": bool }
Vous devez faire un tableau HTML affichant ces données avec les entêtes suivantes : Libellé, Montant, TVA, Action
La colonne "TVA" ne doit être affichée que si au moins un élément du tableau à de la TVA 0 inclus.
La colonne "Action" ne doit être affichée que si au moins un élément est "removable"
Si l'élément est supprimable placer un bouton de suppression dans la colonne action
Si le bouton est cliqué, il faut que la ligne entière soit signalée comme en train de charger.
Puis mettre un timer de 2 secondes au bout du quel l'élément est supprimé du tableau.

## Doc :

-   [React.JS](https://react.dev/)
-   [Vite.JS](https://vite.dev/guide/)
-   [<table>](https://developer.mozilla.org/fr/docs/Web/HTML/Element/table)
