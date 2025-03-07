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

Vous êtes libres d'installer une libraire de style ou composants si vous sentez plus à l'aise avec ou que vous voulez aller plus loin : 

 - [Tailwind](https://tailwindcss.com/docs/installation/using-vite) 
 - [ShadCn](https://ui.shadcn.com/docs/installation/vite) 
 - [Material UI](https://mui.com/material-ui/getting-started/) 
 - [Semantic UI](https://react.semantic-ui.com/usage) 
 - [Chakra UI](https://chakra-ui.com/docs/get-started/installation) 
 - [Boostrap](https://react-bootstrap.netlify.app/docs/getting-started/introduction) 

## Doc :

-   [React.JS](https://react.dev/)
-   [Vite.JS](https://vite.dev/guide/)
-   [<table>](https://developer.mozilla.org/fr/docs/Web/HTML/Element/table)
