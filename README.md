## Conseils/Consignes

- Le projet peut être réalisé par 2 au maximum
- Le travail devra être rendu via un repo GIT de votre choix (github ou codefirst)
- Le projet sera réalisé sous forme d'une application en vueJS
- Pensez composant : on découpe la page en composant, chacun ayant UNE responsabilité
- À chaque modification du sujet, pensez à regarder TOUTES les modifications qui peuvent vous donner des idées, indices, solutions etc...

## Ressources
- API des cartes Pokemon : https://api.tcgdex.net/v2/fr/cards
- Manipulation des images : https://tcgdex.dev/assets?ref=assets.tcgdex.net#extension
- MockAPI : https://mockapi.io/projects

## Sujet du TP

1) Mettre en place le routage et les routes de l'application en partant d'un stub devant contenir toutes les routes identifiées
2) Créer un composant `Navbar` qui affichera une liste de liens : un lien Home et un lien pour route existante
3) Au clic sur chaque lien, le H1 de la page devra afficher le libellé du lien cliqué
4) Créer une classe générique `ApiService` permettant de faire des appels de type GET/POST/UPDATE/DELETE qui manipuleront des données au format JSON (cette classe doit fonctionner peu importe l'URL et le verbe utilisés)
5) Créer une classe `CardSercice` permettant de récupérer toutes ou parties des cartes disponibles sur l'API
6) La totalité des cartes sera mémorisée via le `localStorage`. L'écart entre les mises à jour de la collection sera de 4 jours (si la collection a déjà été récupérée aucune requête ne doit être faite)
7) Une liste des cartes sera mise en place et accessible via un lien de la `Navbar`. elle affichera uniquement leurs noms. Référez vous au contenu de l'API pour en déduire le modèle d'une carte
8) Au clic sur le nom, un comoosant affichera le nom et l'image du Pokemon
9) Une description et 2 types pourront être ajoutés pour chaque carte. Ces informations seront mémorisées via une `MockApi` que vous mettrez en place

## Aide

- Un stub/bouchon est une méthode permettant d'intégrer des données factices dans une application. Comme par exemple avec un fichier JSON.
- L'image du pokemon devra être affichée dans une balise img
