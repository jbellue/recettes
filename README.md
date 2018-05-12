###### For the gritty technical mumbo-jumbo, [click here](#technical-mumbo-jumbo)

# Notre liste de recettes

## Ajouter une recette

* Copier le contenu d'une recette (par example, [la recette de Yassa](https://raw.githubusercontent.com/jbellue/recettes/new_recipes/content/Sal%C3%A9/Plat/Poulet%20yassa.md)).
* Aller sur le lien <https://github.com/jbellue/recettes/tree/master/content>
* Créer un nouveau fichier (le bouton `create new file`), et entrer un nom de fichier: `salé/quiches/quiche-aux-lardons.md`, `sucré/tartes/tarte-aux-lardons.md`, etc.)
* en bas de la page, cliquer `Create a new branch for this commit and start a pull request.`
* Coller la recette et l'éditer (github permet de prévisualiser les changements en direct)
* La syntaxe pour les recettes est disponible [ici](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links)
* Dans les méta-données (en haut, entre les lignes de `+++++`), les mots-clés suivant sont disponibles:
  * auteur
  * "quantité" (les guillemets sont nécessaires), par example "un bol"
  * personnes
  * tempsTotal
  * "tempsDePréparation" (les guillemets sont nécessaires)
  * tempsDeCuisson
  * tempsAutre (par example, "3 heures de marinade")
  * source (pour mettre un lien)
* Soumettre un requête d'intégration du nouveau fichier (`create pull request`)

Quand la recette sera acceptée, le site sera automatiquement mis à jour

## Technical mumbo-jumbo

* Site is generated with Hugo, because it's neat.
* Theme has been butchered from <https://github.com/jgreely/hugo-theme-recipe>
* CircleCi automatically tests the generated code and deploys <https://jbellue.github.io/recettes>
