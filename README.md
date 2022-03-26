# Projet Vue.js 2 - ForEach B2

C'est le moment de mettre en pratique vos connaissances avec Vue.js et de mettre en applications les différentes fonctionnalités qui ont été étudiées en créant une app!

## Quel est le projet (spécifications) ? 

Le but est de proposer une expérience utilisateur à partir d'une API de votre choix. En voici quelques-unes, mais libre à vous d'en utiliser une autre (à condition qu'elle rentre dans le cadre du projet) ou même de flex vos compétences backend en la créant vous-mêmes.

- [PokéAPI](https://pokeapi.co/)
- [LoL's CDragon API](https://www.communitydragon.org/documentation)
- [Rick & Morty API](https://rickandmortyapi.com/documentation)
- [Studio Ghibli API](https://ghibliapi.herokuapp.com/)
- [CocktailDB API](https://www.thecocktaildb.com/api.php)

Ou créez une API locale simplement avec [JSON server](https://github.com/typicode/json-server) ou encore votre propre code backend (Node, Java...).

Ces différentes APIs représentent principalement des données, à vous de proposer une solution frontend en Vue.js pour permettre à l'utilisateur de naviguer dans ces données.

## Comment le projet est-il evalué ?

L'évaluation des compétences se fera sur les axes suivants:

1. Maitrise des concepts de base de Vue.js
    - Rendu déclaratif (`template`) et directives (`v-`)
    - Communication entre composants (`props`/`events`)
    - Utilisation des options (`computed`, `methods`...)
    - Réutilisation du code (`slots`, `mixins`...)
2. Utilisation des plugins
    - Navigation avec le routeur (`vue-router`)
    - State global avec le store (`vuex`)
    - Autres (`vuetify`, `vue-i18n`...)
3. Intéragir avec les APIs
    - Réaliser des appels (`axios`, `fetch`)
    - Gérer l'asynchronicité (`.then`, `async/await`)
    - Gérer les erreurs (`try/catch`, `.catch`)
4. Organisation du projet et developer experience
    - Organiser les différentes composantes du projet (dossiers, nommage...)
    - Analyse statique du code, lintage et formattage (`eslint`, `prettier`...)
    - Documentation (comment démarrer...)
5. Tester son code
    - Ecrire des tests pertinents sur des composants.
    - Mocker correctement les éléments hors du scope d'un test.

Pour vous donner quelques pistes:

- Utilisez le routeur pour la navigation.
- Enregistrez des favoris dans un store.
- Utilisez une librairie de composants (UI).
- Proposez plusieurs langues.

## Ce qui est attendu

Ecrivez le code et faites évoluer le projet comme vous le feriez en entreprise, c'est à dire:

- Allez-y progressivement, et faites des commits régulier, en regroupant les développements. Préférez des conventions et évitez les commits `WIP`.
- Définissez les règles de votre projet en amont et respectez les (lintage, formattage, hiérarchie...) en vous aidant des outils adaptés.
- Il n'y a jamais de solution absolue en développement, mais si une solution que vous avez trouvée vous parait peu claire, vous pouvez commenter et expliquer ce qui l'a motivée (communiquez sur votre code).
- Utilisez au maximum le framework et tirez avantage de l'efficacité qu'il vous offre.
- N'hésitez pas à vous appuyer sur des librairies externes si vous en ressentez le besoin (comme pour travailler avec des datetimes avec [date-fns](https://date-fns.org/)).
- Essayez de vous appuyer sur la documentation du framework et des outils pour répondre à vos questions (pas la doc de StackOverflow 😡)

> **Enfin, avant tout, amusez-vous :)**

## Note concernant les dates limites de rendu:

- Les points 1 à 3 seront évalués jusqu'au 18 février 2022 (inclus) à minuit.
- Le point 4 et 5 seront évalués jusqu'au 15 avril 2022 (inclus) à minuit.
