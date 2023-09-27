# Exercice : Création d'une mini-galerie d'art avec Bootstrap

**Objectif :** Utilisez uniquement Bootstrap pour créer une galerie d'art numérique responsive et visuellement attrayante.

## Étapes :

### 1. Préparation et structure en HTML

- **Document et Bootstrap** :
  - Créez un nouveau fichier HTML appelé `galerie-bootstrap.html`.
  - Intégrez Bootstrap à votre projet en utilisant le CDN.
  
- **Éléments de base avec Bootstrap** :
  - Utilisez la classe `.display-4` pour le titre principal de votre galerie.
  - Pour le conteneur principal de votre galerie, utilisez la classe `.container-fluid`.

### 2. Collection d'œuvres avec Bootstrap

- **Cartes d'œuvres** :
  - Utilisez le composant `Card` de Bootstrap pour chaque œuvre. 
  - Dans ces cartes, ajoutez un titre avec la classe `.card-title` et une description avec la classe `.card-text`.
  
- **Grille de mise en page** :
  - Utilisez les classes `.row` et `.col-*` pour organiser les cartes de manière responsive. Par exemple, `.col-md-4` pour avoir trois colonnes sur un écran de taille moyenne.

### 3. Navigation avec Bootstrap

- **Barre de navigation** :
  - Utilisez le composant `Navbar` de Bootstrap avec les classes `.navbar`, `.navbar-expand-lg`, et `.navbar-light` pour créer une barre de navigation claire et responsive.
  - Elle contiendra les liens suivants :
    - Un logo représentant la galerie
    - Oeuvres d'art : Renvoyant à la page principale
    - Contact : Renvoyant vers un formulaire de contact (ne doit pas être implémentée)
    - Une zone permettant de faire une recherche sur le oeuvre (ne doit pas être implémentée)
  
- **Liens de Navigation** :
  - Utilisez le composant `Nav` de Bootstrap avec les classes `.nav` et `.nav-item` pour les liens de navigation individuels.

### 4. Stylisation et espacement avec Bootstrap

- **Stylisation générale** :
  - Utilisez les classes `.bg-light` ou `.bg-dark` pour changer l'arrière-plan de la galerie ou des composants individuels.
  
- **Stylisation des cartes** :
  - Utilisez les classes d'utilité comme `.mt-*`, `.mb-*`, `.ml-*`, et `.mr-*` pour gérer les marges autour des cartes.
  - Utilisez les classes `.text-center`, `.text-left`, ou `.text-right` pour aligner le texte dans les cartes.
  
- **Stylisation de la barre de navigation** :
  - Utilisez les classes `.navbar-light` ou `.navbar-dark` pour le style de votre barre de navigation.

## Conseils :

- N'utilisez pas de CSS supplémentaire pour cet exercice; tout doit être réalisé avec les classes Bootstrap. Si, dans des projets futurs, vous avez besoin d'ajouter du CSS personnalisé, assurez-vous de le faire dans un fichier CSS séparé, sans modifier le fichier Bootstrap original.
- Parcourez la documentation de Bootstrap pour vous familiariser avec les différentes classes et composants disponibles.
- Assurez-vous de tester votre galerie sur différents appareils et navigateurs pour confirmer sa responsivité.
- [Avantages et Inconvénients de l'Utilisation de CSS Pur et de Bootstrap](pro_cons.md)
