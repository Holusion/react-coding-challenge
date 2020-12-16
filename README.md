# React-coding-challenge

Test de développement utilisant React pour créer une application de visualisation simple à partir d'un tableau au format JSON.

Nécessite un ordinateur avec un éditeur de texte et un terminal (au choix) avec nodejs+npm installés.

## Compétences nécessaires

Une connaissance de base du développement web (HTML/CSS/JS) est requise. Une familiarité avec [React](https://reactjs.org) est souhaitable.

## Objectif

Visualiser une liste de "projets" sous la forme d'un tableau avec leur nom et celui de leur propriétaire.

## Ressources

- [create-react-app](https://create-react-app.dev/docs/getting-started)
- [fetch](https://developer.mozilla.org/fr/docs/Web/API/Fetch_API/Using_Fetch)
- [react hooks](https://fr.reactjs.org/docs/hooks-intro.html) (faculatif)


## Partie 1

**Obtenir un environnement de développement fonctionnel**

- Créer et mettre en route un environnement avec "create-react-app".
- Modifier la page d'accueil pour vérifier la mise à jour automatique.
- Copier le fichier [applications.json](https://raw.githubusercontent.com/Holusion/react-coding-challenge/main/public/applications.json) dans le dossier `public/`
- Synchroniser avec un dépôt git en ligne (github ou autre)

### Aide

Utiliser le **getting started** de *create-react-app* et celui de *GitHub*.

Penser à synchroniser régulièrement git au fur et à mesure de l'avancée.

## Partie 2

**Charger et visualiser un fichier json dans l'application**

Visualiser les `id` de projets du fichier [applications.json](https://raw.githubusercontent.com/Holusion/react-coding-challenge/main/public/applications.json) dans une liste.

Obtenir une liste du genre (mise en forme au choix): 
```
alencon
allusion
cmne
egger
handycom
holodemo
holomouseio-lille
les_residences_du_terroir
ory-nbt
placeholder
placeholder_2
st-omer
testflight
xperium
```

Puis formater la liste pour afficher lisiblement le proprietaire (`owner`) de chaque application en face de son nom.



### Aide

Ouvrir le fichier `http://localhost:3000/applications.json` dans un navigateur pour voir sa structure. Utiliser `fetch()`.

Utiliser une combinaison HTML/CSS : tableau, liste, grid, flexbox ...


## Partie 4

Créer des éléments pour permettre à l'utilisateur de trier les applications par `id` ascendant ou descendant.

### Aide

Dans l'idéal, le changement de tri ne demande pas de re-télécharger le fichier `applications.json``


